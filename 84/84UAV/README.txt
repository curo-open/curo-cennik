                                                                          ============
                                                                          Cenník UAVLD
                                                                          ============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota    │ Popis                                             │
├────────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0.96         │ IDK                                               │
│ KPS = 1            │ KPS                                               │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?                             │
│ CB = 0.0339        │ Cena bodu                                         │
│ CBSVALZ = 0.009574 │ Cena bodu SVaLZ                                   │
│ CBEUNK = 0.0339    │ Cena bodu Nekapitovany(EU)                        │
│ FOB = 2            │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ AGTC = 4.8         │ AGTC                                              │
│ PP50 = 10          │ PP50                                              │
│ EDU = 2            │ EDU                                               │
└────────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│             5.1 │ vv.pocet*cena             │ UAO - KPU                                     │ vv.kod in ['KPU']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Preventívna prehliadka                  │ vv.kod in ['160U']                                           │
│        0.009574 │ vv.bodyCelkom*cena        │ UAO - EKG pri preventívnej prehliadke         │ vv.kod in ['5702PU']                                         │
│        0.009574 │ vv.bodyCelkom*cena        │ UAO - EKG                                     │ vv.kod in ['5702U']                                          │
│        0.021999 │ vv.bodyCelkom*cena        │ UAO - Celodenné snímanie tlaku                │ vv.kod in ['5715U']                                          │
│        0.016597 │ vv.bodyCelkom*cena        │ UAO - Celodenné snímanie tlaku - vyhodnotenie │ vv.kod in ['5716U']                                          │
│              15 │ vv.pocet*cena             │ UAO - Inicialne I10/E78 (H0003)               │ vv.kod in ['H0003U']                                         │
│              15 │ vv.pocet*cena             │ UAO - Kontrolne I10/E78 (H0004)               │ vv.kod in ['H0004U']                                         │
│               6 │ vv.pocet*cena             │ UAO - Akutne I10                              │ vv.kod in ['H0005U']                                         │
│            5.65 │ vv.pocet*cena             │ UAO - Stratifikacia CMP                       │ vv.kod in ['H0006U']                                         │
│             5.2 │ vv.pocet*cena             │ UAO - Kvantitatívne vyšetrenie INR POCT       │ vv.kod in ['H0007U']                                         │
│            6.78 │ vv.pocet*cena             │ UAO - Stanovenie ABI oscilometricky           │ vv.kod in ['H0008U']                                         │
│              12 │ vv.pocet*cena             │ UAO - TOKS pozitívny                          │ vv.kod in ['159AU']                                          │
│              12 │ vv.pocet*cena             │ UAO - TOKS negatívny                          │ vv.kod in ['159ZU']                                          │
│            3.02 │ vv.pocet*cena             │ UAO - TOKS znehodnotený                       │ vv.kod in ['159XU']                                          │
│          0.0318 │ vv.bodyCelkom*cena        │ UAO - Komplexné vyšetrenie                    │ vv.kod in ['60U']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Očkovanie                               │ vv.kod in ['252BU']                                          │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Očkovanie                               │ vv.kod in ['252CU']                                          │
│          0.0318 │ vv.bodyCelkom*cena        │ UAO - Výkon 10                                │ vv.kod in ['10U']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 11a                               │ vv.kod in ['11AU']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 1b                                │ vv.kod in ['1BU']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 70                                │ vv.kod in ['70U']                                            │
│          0.0339 │ vv.bodyCelkom*cena        │ UAO - Návštevná služba                        │ vv.kod in ['25U']                                            │
│          0.0339 │ vv.bodyCelkom*cena        │ UAO - Návštevná služba                        │ vv.kod in ['26U']                                            │
│            5.75 │ vv.pocet*cena             │ UAO - Vyšetrenie C – reaktívneho proteínu     │ vv.kod in ['4571AU']                                         │
│              16 │ vv.pocet*cena             │ UAO - Komplexné predoperačné vyšetrenie       │ vv.kod in ['60BU']                                           │
│               2 │ vv.pocet*cena             │ UAO - Delegovaný odber krvi                   │ vv.kod in ['250DU']                                          │
│              20 │ vv.pocet*cena             │ UAO - Cielené vyšetrenie pacienta s respiračn │ vv.kod in ['62AU']                                           │
│                 │                           │ ým syndrómom pri pandémii COVID-19            │                                                              │
│            6.78 │ vv.pocet*cena             │ UAO - Výkon 163                               │ vv.kod in ['163U']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│              10 │ vv.pocet*cena             │ Očkovanie COVID19                             │ vv.kod in ['252L']                                           │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
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
│          0.0339 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│            5.75 │ vv.pocet*cena             │ Vyšetrenie C – reaktívneho proteínu           │ vv.kod in ['4571a','4571A']                                  │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│            4.78 │ vv.pocet*cena             │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│            6.78 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              15 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              15 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│            5.65 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b','60B']                                      │
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
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaLZ                                   │
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaLZ                                  │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
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

