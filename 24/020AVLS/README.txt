                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬────────────────────────────┐
│ Názov a hodnota   │ Popis                      │
├───────────────────┼────────────────────────────┤
│ IDK = 0           │ NASTAVENIA IDK             │
│ CB = 0.022089     │ Cena bodu                  │
│ CBSVALZ = 0.00819 │ Cena bodu SVaLZ            │
│ CBEUNK = 0.022973 │ Cena bodu Nekapitovany(EU) │
│ _4571a = 4.4      │ 4571a                      │
└───────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 20 │          3.39 │ IDK+cena │ p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          2.19 │ IDK+cena │ p|vekMedzi(20, 28) │
│ vek od 28 do 46 │           2.3 │ IDK+cena │ p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          2.32 │ IDK+cena │ p|vekMedzi(46, 52) │
│ vek od 52 do 54 │          2.53 │ IDK+cena │ p|vekMedzi(52, 54) │
│ vek od 54 do 58 │          2.97 │ IDK+cena │ p|vekMedzi(54, 58) │
│ vek od 58 do 62 │          3.19 │ IDK+cena │ p|vekMedzi(58, 62) │
│ vek od 62 do 65 │           3.4 │ IDK+cena │ p|vekMedzi(62, 65) │
│ vek od 65 do 69 │           3.6 │ IDK+cena │ p|vekMedzi(65, 69) │
│ vek od 69 do 73 │          3.89 │ IDK+cena │ p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          4.29 │ IDK+cena │ p|vekMedzi(73, 88) │
│ vek od 88+      │          4.23 │ IDK+cena │ p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│                 │ _4571a                    │ Pripočitateľné položky                        │ vv.kod=='4571a'                                              │
│            4.79 │ vv.pocet*cena             │ Nekapitovaný - Vykon 4                        │ !p.kapitacia && vv.kod in ['4']                              │
│            6.38 │ vv.pocet*cena             │ Nekapitovaný - Vykon 8                        │ !p.kapitacia && vv.kod in ['8']                              │
│         0.00819 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│        0.022973 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│                 │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│                 │ vv.bodyCelkom*CBEUNK      │ Výkon 70                                      │ vv.kod in ['70']                                             │
│             4.4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A']                                          │
│            4.45 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702Z']                                   │
│            0.05 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.048972 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│            0.05 │ vv.bodyCelkom*cena        │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│              16 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│           0.025 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│               5 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│             4.5 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│               9 │ vv.pocet*cena             │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
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
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

