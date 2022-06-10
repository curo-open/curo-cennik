                                                                    ========================
                                                                    Cenník VLD Bez zdruzenia
                                                                    ========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota    │ Popis                                             │
├────────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0            │ IDK                                               │
│ KPS = 1            │ KPS                                               │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?                             │
│ CB = 0.03          │ Cena bodu                                         │
│ CBSVALZ = 0.007303 │ Cena bodu SVaLZ                                   │
│ CBEUNK = 0.03      │ Cena bodu Nekapitovany(EU)                        │
│ AGTC = 4.8         │ AGTC                                              │
│ PP50 = 10          │ PP50                                              │
│ FOB = 2            │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ EDU = 2            │ EDU k výkonom H0003, H0004                        │
└────────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek do 19       │          3.52 │ IDK+cena │ p.kapitacia && p|vekMedzi(19, 20) │
│ vek od 20 do 28 │           2.8 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 28) │
│ vek od 29 do 39 │           2.6 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 39) │
│ vek od 40 do 44 │          2.64 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 44) │
│ vek od 45 do 49 │          2.69 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 49) │
│ vek od 50 do 54 │          3.12 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 54) │
│ vek od 55 do 59 │          3.24 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 59) │
│ vek od 60 do 64 │          3.62 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 64) │
│ vek od 65 do 69 │          4.32 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 69) │
│ vek od 70 do 74 │          4.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 74) │
│ vek od 75 do 79 │          4.62 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 79) │
│ vek od 80 do 84 │          5.06 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 84) │
│ vek od 85+      │          5.15 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ'                 │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ=='SVaLZ'      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│        0.021995 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│        0.021995 │ vv.bodyCelkom*cena        │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│           0.065 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.008105 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│         0.00861 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│        0.021999 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku - vyhodnotenie       │ vv.kod in ['5716']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│            0.03 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│            null │ vv.bodyCelkom*CBSVALZ     │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│               5 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│               6 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              12 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              12 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Vyšetrenie pacienta s COVID 19                │ vv.kod in ['62a']                                            │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│               6 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            0.06 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
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

