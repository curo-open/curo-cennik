                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota    │ Popis                                             │
├────────────────────┼───────────────────────────────────────────────────┤
│ IDK = 1.11         │ IDK                                               │
│ KPS = 1            │ KPS                                               │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?                             │
│ CB = 0.0318        │ Cena bodu                                         │
│ CBSVALZ = 0.009574 │ Cena bodu SVaLZ                                   │
│ CBEUNK = 0.035     │ Cena bodu Nekapitovany(EU)                        │
│ CBSVALZEU = 0.01   │ Cena bodu SVaLZ Nekapitovany(EU)                  │
│ FOB = 2            │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ AGTC = 4.8         │ AGTC                                              │
│ PP50 = 10          │ PP50                                              │
│ EDU = 2            │ EDU k výkonom H0003, H0004                        │
└────────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌───────────────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis                     │ Premenná cena │ Vzorec   │ Podmienka                         │
├───────────────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ od 18 do 19 rokov vrátane │          4.83 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ od 20 do 28 rokov vrátane │          3.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ od 29 do 39 rokov vrátane │           3.5 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ od 40 do 44 rokov vrátane │          3.52 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ od 45 do 49 rokov vrátane │          3.56 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ od 50 do 54 rokov vrátane │          4.09 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ od 55 do 59 rokov vrátane │          4.69 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ od 60 do 64 rokov vrátane │          5.23 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ od 65 do 69 rokov vrátane │           5.7 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ od 70 do 74 rokov vrátane │          6.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ od 75 do 79 rokov vrátane │          7.26 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ od 80 do 84 rokov vrátane │          8.15 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ od 85+                    │          8.18 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└───────────────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 1                                       │ vv.kod in ['1']                                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 4                                       │ !p.kapitacia && vv.kod in ['4']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 8                                       │ !p.kapitacia && vv.kod in ['8']                              │
│            null │ vv.bodyCelkom*CB          │ Komunikácia v cudziom jazyku                  │ vv.kod in ['79a']                                            │
│            null │ vv.bodyCelkom*CB          │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│           17.33 │ vv.pocet*cena             │ Predoperačné vyšetrenie (výkon 60b)           │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│          0.0073 │ vv.bodyCelkom*cena        │ Výkon 5301                                    │ vv.kod in ['5301']                                           │
│            8.98 │ vv.pocet*cena             │ Stanovenie hodnoty D-diméru                   │ vv.kod in ['3860']                                           │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│        0.021999 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku - vyhodnotenie       │ vv.kod in ['5716']                                           │
│           0.084 │ vv.bodyCelkom*cena        │ Očkovanie - 252a,252b,252c                    │ !p.kapitacia && vv.kod in ['252a','252b','252c']             │
│           0.035 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│            11.6 │ vv.pocet*cena             │ Stanovenie hodnoty troponínu                  │ vv.kod in ['4485']                                           │
│           19.78 │ vv.pocet*cena             │ Stanovenie hodnoty NT-proBNP                  │ vv.kod in ['44418']                                          │
│            5.75 │ vv.pocet*cena             │ Vyšetrenie C – reaktívneho proteínu           │ vv.kod in ['4571a','4571A']                                  │
│            null │ vv.bodyCelkom*CBSVALZ     │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│            6.78 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              15 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              15 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│            5.65 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│            6.78 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│               2 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ vv.bodyCelkom*CB          │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZEU   │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['EU'] && vv.typ=='SVaLZ'           │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ vv.bodyCelkom*CBSVALZEU   │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ=='SVaLZ'      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ!='SVaLZ'      │
│            null │ vv.bodyCelkom*0           │ SVALZ výkon                                   │ p.kapitacia && vv.jeSVaZL                                    │
│            null │ vv.bodyCelkom*0           │ iné ako SVALZ                                 │ p.kapitacia && !vv.jeSVaZL                                   │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             180 │ 10                                                                                                        │                           │
│             285 │ 25                                                                                                        │                           │
│             285 │ 25                                                                                                        │                           │
│             500 │ 26                                                                                                        │                           │
│             500 │ 26                                                                                                        │                           │
│             620 │ 60                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
│             600 │ 5301                                                                                                      │                           │
│             550 │ 5702                                                                                                      │                           │
│             750 │ 5715                                                                                                      │                           │
│             240 │ 5716                                                                                                      │                           │
│             550 │ 5702P                                                                                                     │                           │
│              70 │ 252a                                                                                                      │                           │
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

