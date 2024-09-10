                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota    │ Popis                                             │
├────────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0            │ NASTAVENIA IDK                                    │
│ CB = 0             │ Cena bodu                                         │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ                                   │
│ CBEU = 0.028704    │ Cena bodu Nekapitovany(EU)                        │
│ _4571a = 5         │ 4571a                                             │
│ AGTC = 4.8         │ AGTC                                              │
│ PP50 = 10          │ PP50                                              │
│ FOB = 2            │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ EDU = 2            │ EDU k výkonom  H0004                              │
└────────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 19 │          4.71 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 19) │
│ vek od 19 do 27 │          3.03 │ IDK+cena │ p.kapitacia && p|vekMedzi(19, 27) │
│ vek od 27 do 45 │          3.16 │ IDK+cena │ p.kapitacia && p|vekMedzi(27, 45) │
│ vek od 45 do 51 │          3.34 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 51) │
│ vek od 51 do 53 │          3.63 │ IDK+cena │ p.kapitacia && p|vekMedzi(51, 53) │
│ vek od 53 do 57 │          4.36 │ IDK+cena │ p.kapitacia && p|vekMedzi(53, 57) │
│ vek od 57 do 61 │          4.68 │ IDK+cena │ p.kapitacia && p|vekMedzi(57, 61) │
│ vek od 61 do 64 │          4.99 │ IDK+cena │ p.kapitacia && p|vekMedzi(61, 64) │
│ vek od 64 do 68 │          5.73 │ IDK+cena │ p.kapitacia && p|vekMedzi(64, 68) │
│ vek od 68 do 72 │           6.2 │ IDK+cena │ p.kapitacia && p|vekMedzi(68, 72) │
│ vek od 72 do 87 │          6.83 │ IDK+cena │ p.kapitacia && p|vekMedzi(72, 87) │
│ vek od 87+      │          6.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(87)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ _4571a                    │ Pripočitateľné položky                        │ vv.kod in ['4571a','4571A']                                  │
│            4.79 │ vv.pocet*cena             │ Nekapitovaný - Vykon 4                        │ !p.kapitacia && vv.kod in ['4']                              │
│            6.38 │ vv.pocet*cena             │ Nekapitovaný - Vykon 8                        │ !p.kapitacia && vv.kod in ['8']                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && p.typ in ['EU'] && vv.typ=='SVaLZ'           │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│        0.025959 │ vv.bodyCelkom*cena        │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            5.65 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│            5.98 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702Z']                                   │
│           0.084 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.084 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│           18.08 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│          0.0375 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│           0.084 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│           0.065 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│              12 │ vv.pocet*cena             │ Starostlivosť o poistenca s artériovou hypert │ vv.kod in ['H0003','H0004']                                  │
│                 │                           │ enziou, dyslipidémiou a/alebo obezitou        │                                                              │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│               6 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            16.5 │ vv.pocet*cena             │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
│        0.025959 │ vv.bodyCelkom*cena        │ Neodkladná starostlivosť                      │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
│             180 │ 159a                                                                                                      │                           │
│             180 │ 159b                                                                                                      │                           │
│             180 │ 159x                                                                                                      │                           │
│             180 │ 159z                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             390 │ 160R                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

