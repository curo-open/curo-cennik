                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬──────────────────────┐
│ Názov a hodnota │ Popis                │
├─────────────────┼──────────────────────┤
│ IDK = 0         │ NASTAVENIA IDK       │
│ ZCV = 1         │ Zvýhodnená cena bodu │
│ PPH1 = 10       │ PPH1                 │
│ PPH2 = 6.5      │ PPH2                 │
│ PREDOP = 12.9   │ PREDOP               │
│ 4571a = 4       │ 4571a                │
└─────────────────┴──────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 20 │          3.22 │ IDK+cena │ p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          2.13 │ IDK+cena │ p|vekMedzi(20, 28) │
│ vek od 28 do 46 │          2.24 │ IDK+cena │ p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          2.26 │ IDK+cena │ p|vekMedzi(46, 52) │
│ vek od 52 do 54 │           2.4 │ IDK+cena │ p|vekMedzi(52, 54) │
│ vek od 54 do 58 │           2.6 │ IDK+cena │ p|vekMedzi(54, 58) │
│ vek od 58 do 62 │          2.84 │ IDK+cena │ p|vekMedzi(58, 62) │
│ vek od 62 do 65 │          3.14 │ IDK+cena │ p|vekMedzi(62, 65) │
│ vek od 65 do 69 │          3.33 │ IDK+cena │ p|vekMedzi(65, 69) │
│ vek od 69 do 73 │          3.59 │ IDK+cena │ p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          4.03 │ IDK+cena │ p|vekMedzi(73, 88) │
│ vek od 88+      │             4 │ IDK+cena │ p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            4.79 │ vv.bodyCelkom*cena        │ Nekapitovaný - Vykon 4                        │ !p.kapitacia && vv.kod in ['4']                              │
│            6.38 │ vv.bodyCelkom*cena        │ Nekapitovaný - Vykon 8                        │ !p.kapitacia && vv.kod in ['8']                              │
│         0.00819 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│            0.52 │ vv.pocet*cena             │ Vykon 1                                       │ ZCV && vv.kod in ['1']                                       │
│            1.95 │ vv.pocet*cena             │ Vykon 4                                       │ ZCV && vv.kod in ['4']                                       │
│             2.6 │ vv.pocet*cena             │ Vykon 8                                       │ ZCV && vv.kod in ['8']                                       │
│            0.52 │ vv.pocet*cena             │ Vykon 250                                     │ ZCV && vv.kod in ['250']                                     │
│            0.29 │ vv.pocet*cena             │ Vykon 1                                       │ vv.kod in ['1']                                              │
│            1.08 │ vv.pocet*cena             │ Vykon 4                                       │ vv.kod in ['4']                                              │
│            1.44 │ vv.pocet*cena             │ Vykon 8                                       │ vv.kod in ['8']                                              │
│            0.29 │ vv.pocet*cena             │ Vykon 250                                     │ vv.kod in ['250']                                            │
│        0.048972 │ vv.pocet*180*cena         │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.048972 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│        0.048972 │ vv.pocet*390*cena         │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│            10.5 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│               8 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│        0.022089 │ vv.bodyCelkom*cena        │ Návštevná služba                              │                                                              │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

