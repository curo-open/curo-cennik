                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬────────────────────────────┐
│ Názov a hodnota    │ Popis                      │
├────────────────────┼────────────────────────────┤
│ IDK = 0            │ IDK                        │
│ KPS = 1            │ KPS                        │
│ EL_POBOCKA = 1     │ Používa el. pobočku ?      │
│ CB = 0.020995      │ Cena bodu                  │
│ CBSVALZ = 0.007303 │ Cena bodu SVaLZ            │
│ CBEUNK = 0.020995  │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8         │ AGTC                       │
│ PP50 = 10          │ PP50                       │
└────────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          3.02 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 29 │          2.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 40 │          2.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 45 │          2.51 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 50 │          2.56 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 55 │          2.63 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 60 │          2.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 65 │          2.87 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 70 │          2.98 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 75 │           3.1 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 80 │          3.21 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 85 │          3.55 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │          3.62 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│                 │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│                 │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│                 │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ!='SVaLZ'      │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│                 │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            3.78 │ vv.pocet*cena             │ Výkon 10                                      │ vv.kod in ['10']                                             │
│            7.35 │ vv.pocet*cena             │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│           0.046 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ KPS && EL_POBOCKA && vv.kod in ['160']                       │
│           0.045 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ KPS && vv.kod in ['160']                                     │
│           0.042 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ EL_POBOCKA && vv.kod in ['160']                              │
│           0.041 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.008105 │ vv.pocet*550*cena         │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.008105 │ vv.pocet*550*cena         │ EKG                                           │ vv.kod in ['5702']                                           │
│        0.016597 │ vv.pocet*750*cena         │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.pocet*240*cena         │ Celodenné snímanie tlaku - vyhodnotenie       │ vv.kod in ['5716']                                           │
│           0.041 │ vv.pocet*70*cena          │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.041 │ vv.pocet*70*cena          │ Očkovanie proti chrípke                       │ vv.diagnoza in ['Z25.1'] && vv.kod in ['252b','252c','252s'] │
│        0.020995 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│        0.007303 │ vv.pocet*500*cena         │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              12 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              12 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│             4.5 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│                 │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│                 │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│                 │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             180 │ 10                                                                                                        │                           │
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

