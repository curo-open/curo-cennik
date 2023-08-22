                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota    │ Popis                                             │
├────────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0            │ IDK                                               │
│ KPS = 1            │ KPS                                               │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?                             │
│ CB = 0.0318        │ Cena bodu                                         │
│ CBSVALZ = 0.009574 │ Cena bodu SVaLZ                                   │
│ CBEU = 0.0339      │ Cena bodu Nekapitovany(EU)                        │
│ FOB = 2            │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ AGTC = 4.8         │ AGTC                                              │
│ PP50 = 10          │ PP50                                              │
│ EDU = 2            │ EDU                                               │
└────────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          4.05 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 29 │          3.22 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 40 │          3.02 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 45 │          3.04 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 50 │          3.07 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 55 │          3.53 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 60 │          4.05 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 65 │          4.51 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 70 │          4.88 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 75 │          5.55 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 80 │          6.22 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 85 │          6.99 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │           7.3 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│            null │ vv.bodyCelkom*CB          │ Výkon 10                                      │ vv.kod in ['10']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│          0.0318 │ vv.bodyCelkom*cena        │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│            0.08 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│        0.021999 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku - vyhodnotenie       │ vv.kod in ['5716']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b','252c']                                    │
│           0.041 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza in ['Z25.1'] && vv.kod in ['252b','252c','252s'] │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│          0.0339 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│            5.75 │ vv.pocet*cena             │ Vyšetrenie C – reaktívneho proteínu           │ vv.kod in ['4571a','4571A']                                  │
│        0.007303 │ vv.bodyCelkom*cena        │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│            6.78 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              15 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              15 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│            5.65 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b','60B']                                      │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│            6.78 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│               2 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D','250d']                                    │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             180 │ 10                                                                                                        │                           │
│             285 │ 25                                                                                                        │                           │
│             500 │ 26                                                                                                        │                           │
│             620 │ 60                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
│             550 │ 5702                                                                                                      │                           │
│             750 │ 5715                                                                                                      │                           │
│             240 │ 5716                                                                                                      │                           │
│             550 │ 5702P                                                                                                     │                           │
│              70 │ 252b                                                                                                      │                           │
│              70 │ 252c                                                                                                      │                           │
│              70 │ 252s                                                                                                      │                           │
│             500 │ 5702c                                                                                                     │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

