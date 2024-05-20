                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬────────────────────────────┐
│ Názov a hodnota    │ Popis                      │
├────────────────────┼────────────────────────────┤
│ IDK = 0            │ NASTAVENIA IDK             │
│ CB = 0.025402      │ Cena bodu                  │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ            │
│ CBEU = 0.028704    │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8         │ AGTC                       │
│ PP50 = 10          │ PP50                       │
└────────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 19 │          4.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 19) │
│ vek od 19 do 27 │          3.16 │ IDK+cena │ p.kapitacia && p|vekMedzi(19, 27) │
│ vek od 27 do 45 │          3.33 │ IDK+cena │ p.kapitacia && p|vekMedzi(27, 45) │
│ vek od 45 do 51 │          3.35 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 51) │
│ vek od 51 do 53 │          3.56 │ IDK+cena │ p.kapitacia && p|vekMedzi(51, 53) │
│ vek od 53 do 57 │          3.92 │ IDK+cena │ p.kapitacia && p|vekMedzi(53, 57) │
│ vek od 57 do 61 │          4.38 │ IDK+cena │ p.kapitacia && p|vekMedzi(57, 61) │
│ vek od 61 do 64 │          5.11 │ IDK+cena │ p.kapitacia && p|vekMedzi(61, 64) │
│ vek od 64 do 68 │          5.89 │ IDK+cena │ p.kapitacia && p|vekMedzi(64, 68) │
│ vek od 68 do 72 │          6.36 │ IDK+cena │ p.kapitacia && p|vekMedzi(68, 72) │
│ vek od 72 do 87 │          7.12 │ IDK+cena │ p.kapitacia && p|vekMedzi(72, 87) │
│ vek od 87+      │          7.07 │ IDK+cena │ p|vekMedzi(87)                    │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - neodkladná starostlivosť - SVA │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│                 │                           │ LZ                                            │                                                              │
│        0.025959 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná - iné ako SVALZ     │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.084 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│           0.084 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│          0.0375 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│           0.057 │ vv.bodyCelkom*cena        │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│           18.08 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│          0.0078 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            5.98 │ vv.pocet*cena             │ EKG (5702Z,5702ZV)                            │ vv.kod in ['5702Z','5702']                                   │
│            5.65 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│              20 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný -  EU - SVALZ                    │ !p.kapitacia && p.typ in ['EU'] && vv.typ=='SVaLZ'           │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - EU -  iné ako SVALZ            │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
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

