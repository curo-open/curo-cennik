                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬─────────────────────────────────┐
│ Názov a hodnota   │ Popis                           │
├───────────────────┼─────────────────────────────────┤
│ IDK = 0           │ NASTAVENIA IDK                  │
│ VCB1 = 0.55       │ Vypočítaná cena bodu. výkon 1   │
│ VCB4 = 1.42       │ Vypočítaná cena bodu. výkon 4   │
│ VCB8 = 2.8        │ Vypočítaná cena bodu. výkon 8   │
│ VCB250 = 0.55     │ Vypočítaná cena bodu. výkon 250 │
│ VCB10 = 0         │ Vypočítaná cena bodu. výkon 10  │
│ PPH1 = 10         │ PPH1                            │
│ PPH2 = 6.5        │ PPH2                            │
│ PREDOP = 18.4     │ PREDOP                          │
│ _4571a = 5.65     │ 4571a                           │
│ CHRSTAR = 10      │ CHRSTAR                         │
│ CHRST = 10        │ CHRST                           │
│ TELEKON = 1.3     │ TELEKON                         │
│ HYPVS = 8         │ HYPVS                           │
│ HYPKON = 5        │ HYPKON                          │
│ HYPSTA = 4        │ HYPSTA                          │
│ SKOR01 = 0        │ SKOR01                          │
│ SKOR02 = 0        │ SKOR02                          │
│ SKOR03 = 0        │ SKOR03                          │
│ SKOR04 = 0        │ SKOR04                          │
│ CB = 0.025402     │ Cena bodu                       │
│ CBSVALZ = 0.0086  │ Cena bodu SVaLZ                 │
│ CBEUNK = 0.022973 │ Cena bodu Nekapitovany(EU)      │
│ AGTC = 4.8        │ AGTC                            │
│ PP50 = 10         │ PP50                            │
│ 5702D = 10        │ 5702D                           │
│ _3635A = 2.26     │ 3635A                           │
│ _3634 = 4.5       │ 3634                            │
│ EDU = 2           │ EDU k výkonu 10                 │
└───────────────────┴─────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          4.51 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          3.01 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 28) │
│ vek od 28 do 46 │          3.17 │ IDK+cena │ p.kapitacia && p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          3.19 │ IDK+cena │ p.kapitacia && p|vekMedzi(46, 52) │
│ vek od 52 do 54 │          3.46 │ IDK+cena │ p.kapitacia && p|vekMedzi(52, 54) │
│ vek od 54 do 58 │          4.15 │ IDK+cena │ p.kapitacia && p|vekMedzi(54, 58) │
│ vek od 58 do 62 │          4.46 │ IDK+cena │ p.kapitacia && p|vekMedzi(58, 62) │
│ vek od 62 do 65 │          5.08 │ IDK+cena │ p.kapitacia && p|vekMedzi(62, 65) │
│ vek od 65 do 69 │          5.35 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 69) │
│ vek od 69 do 73 │          5.79 │ IDK+cena │ p.kapitacia && p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          6.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(73, 88) │
│ vek od 88+      │          6.89 │ IDK+cena │ p.kapitacia && p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ PPH1                      │ Pripočitateľné položky                        │ vv.kod=='PPH1'                                               │
│            null │ PPH2                      │ Pripočitateľné položky                        │ vv.kod=='PPH2'                                               │
│            null │ PREDOP                    │ Pripočitateľné položky                        │ vv.kod=='PREDOP'                                             │
│            null │ _4571a                    │ Pripočitateľné položky                        │ vv.kod in ['4571a','4571A']                                  │
│            null │ CHRST                     │ Pripočitateľné položky                        │ vv.kod=='CHRST'                                              │
│            null │ TELEKON                   │ Pripočitateľné položky                        │ vv.kod=='TELEKON'                                            │
│            null │ HYPVS                     │ Pripočitateľné položky                        │ vv.kod=='HYPVS'                                              │
│            null │ HYPKON                    │ Pripočitateľné položky                        │ vv.kod=='HYPKON'                                             │
│            null │ HYPSTA                    │ Pripočitateľné položky                        │ vv.kod=='HYPSTA'                                             │
│            null │ SKOR01                    │ Pripočitateľné položky                        │ vv.kod=='SKOR01'                                             │
│            null │ SKOR02                    │ Pripočitateľné položky                        │ vv.kod=='SKOR02'                                             │
│            null │ SKOR03                    │ Pripočitateľné položky                        │ vv.kod=='SKOR03'                                             │
│            null │ SKOR04                    │ Pripočitateľné položky                        │ vv.kod=='SKOR04'                                             │
│            null │ SKOR05                    │ Pripočitateľné položky                        │ vv.kod=='SKOR05'                                             │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ _3635A                    │ Pripočitateľné položky                        │ vv.kod=='3635A'                                              │
│            null │ _3634                     │ Pripočitateľné položky                        │ vv.kod=='3634'                                               │
│            6.95 │ vv.pocet*cena             │ Nekapitovaný - Vykon 4                        │ !p.kapitacia && vv.kod in ['4']                              │
│            5.21 │ vv.pocet*cena             │ Nekapitovaný - Vykon 8                        │ !p.kapitacia && vv.kod in ['8']                              │
│            1.39 │ vv.pocet*cena             │ Nekapitovaný - Vykon 1                        │ !p.kapitacia && vv.kod in ['1']                              │
│            1.39 │ vv.pocet*cena             │ Nekapitovaný - Vykon 250                      │ !p.kapitacia && vv.kod in ['250']                            │
│         0.00819 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│        0.022973 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.pocet*VCB4             │ Vykon 4                                       │ vv.kod in ['4']                                              │
│            null │ vv.pocet*VCB8             │ Vykon 8                                       │ vv.kod in ['8']                                              │
│            null │ vv.pocet*VCB250           │ Vykon 250                                     │ vv.kod in ['250']                                            │
│            17.5 │ vv.pocet*10               │ Vykon 10                                      │ vv.kod in ['10']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.079 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.079 │ vv.bodyCelkom*cena        │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│           18.08 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            5.98 │ vv.pocet*cena             │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│            5.98 │ vv.pocet*cena             │ EKG (5702)+65                                 │ p|vekMedzi(65) && vv.kod in ['5702']                         │
│            4.78 │ vv.pocet*cena             │ EKG (5702)                                    │ vv.kod in ['5702']                                           │
│              10 │ vv.pocet*cena             │ EKG (5702D)                                   │ vv.kod in ['5702D']                                          │
│            6.24 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│             7.2 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            19.8 │ vv.pocet*cena             │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│              16 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│        0.022089 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
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

