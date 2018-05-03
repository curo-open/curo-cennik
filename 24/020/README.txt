                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────┐
│ Názov a hodnota │ Popis          │
├─────────────────┼────────────────┤
│ IDK = 0         │ NASTAVENIA IDK │
└─────────────────┴────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 20 │          2.87 │ IDK+cena │ p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          1.86 │ IDK+cena │ p|vekMedzi(20, 28) │
│ vek od 28 do 46 │          1.95 │ IDK+cena │ p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          1.97 │ IDK+cena │ p|vekMedzi(46, 52) │
│ vek od 52 do 54 │          2.14 │ IDK+cena │ p|vekMedzi(52, 54) │
│ vek od 54 do 58 │          2.52 │ IDK+cena │ p|vekMedzi(54, 58) │
│ vek od 58 do 62 │           2.7 │ IDK+cena │ p|vekMedzi(58, 62) │
│ vek od 62 do 65 │          2.88 │ IDK+cena │ p|vekMedzi(62, 65) │
│ vek od 65 do 69 │          3.05 │ IDK+cena │ p|vekMedzi(65, 69) │
│ vek od 69 do 73 │           3.3 │ IDK+cena │ p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          3.63 │ IDK+cena │ p|vekMedzi(73, 88) │
│ vek od 88+      │          3.59 │ IDK+cena │ p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.020072 │ vv.bodyCelkom*cena        │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['BE','CU','EU']                    │
│        0.013278 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│          0.0078 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│          0.0193 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && vv.typ!='SVaLZ'                              │
│        0.048972 │ vv.pocet*180*cena         │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.018257 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│           0.044 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│          0.0193 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│        0.048972 │ vv.pocet*390*cena         │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│              10 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             4.2 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702zv']                                         │
│               4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a']                                          │
│               6 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

