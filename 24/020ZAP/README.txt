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
│ AGTC = 4.8        │ AGTC                       │
└───────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 19 │          3.62 │ IDK+cena │ p|vekMedzi(18, 19) │
│ vek od 19 do 27 │          2.44 │ IDK+cena │ p|vekMedzi(19, 27) │
│ vek od 27 do 45 │          2.57 │ IDK+cena │ p|vekMedzi(27, 45) │
│ vek od 45 do 51 │          2.59 │ IDK+cena │ p|vekMedzi(45, 51) │
│ vek od 51 do 53 │          2.75 │ IDK+cena │ p|vekMedzi(51, 53) │
│ vek od 53 do 57 │          2.81 │ IDK+cena │ p|vekMedzi(53, 57) │
│ vek od 57 do 61 │          3.07 │ IDK+cena │ p|vekMedzi(57, 61) │
│ vek od 61 do 64 │          3.39 │ IDK+cena │ p|vekMedzi(61, 64) │
│ vek od 64 do 68 │           3.6 │ IDK+cena │ p|vekMedzi(64, 68) │
│ vek od 68 do 72 │          3.88 │ IDK+cena │ p|vekMedzi(68, 72) │
│ vek od 72 do 87 │          4.35 │ IDK+cena │ p|vekMedzi(72, 87) │
│ vek od 87+      │          4.32 │ IDK+cena │ p|vekMedzi(87)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│                 │ vv.bodyCelkom*CB          │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['BE','CU']                         │
│                 │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│                 │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│                 │ vv.bodyCelkom*CB          │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && vv.typ!='SVaLZ'                              │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│                 │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.057 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│        0.048972 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│           0.025 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│           0.057 │ vv.bodyCelkom*cena        │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│          0.0078 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            4.45 │ vv.pocet*cena             │ EKG (5702Z,5702ZV)                            │ vv.kod in ['5702ZV','5702Z']                                 │
│             4.4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│              16 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│                 │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│                 │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
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

