                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬────────────────────────────┐
│ Názov a hodnota    │ Popis                      │
├────────────────────┼────────────────────────────┤
│ IDK = 1.2          │ IDK                        │
│ KPS = 1            │ KPS                        │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?      │
│ CB = 0.026         │ Cena bodu                  │
│ CBSVALZ = 0.007303 │ Cena bodu SVaLZ            │
│ CBEUNK = 0.026     │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8         │ AGTC                       │
│ PP50 = 10          │ PP50                       │
└────────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          3.98 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 29 │          3.16 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 40 │          2.94 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 45 │          2.98 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 50 │          3.04 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 55 │          3.53 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 60 │          3.66 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 65 │          4.09 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 70 │          4.88 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 75 │          5.05 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 80 │          5.22 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 85 │          5.72 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │          5.82 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│        0.021995 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 70                                      │ vv.kod in ['70']                                             │
│        0.021995 │ vv.bodyCelkom*cena        │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│         0.07345 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.008105 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.008105 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku - vyhodnotenie       │ vv.kod in ['5716']                                           │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.041 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza in ['Z25.1'] && vv.kod in ['252b','252c','252s'] │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│             4.4 │ vv.pocet*cena             │ Vyšetrenie C – reaktívneho proteínu           │ vv.kod in ['4571a','4571A']                                  │
│        0.007303 │ vv.bodyCelkom*cena        │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│               6 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              12 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              12 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b','60B']                                      │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│             4.5 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D','250d']                                    │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             180 │ 10                                                                                                        │                           │
│             285 │ 25                                                                                                        │                           │
│             500 │ 26                                                                                                        │                           │
│             350 │ 60                                                                                                        │                           │
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

