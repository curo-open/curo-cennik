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
│ vek od 18 do 19 │          2.95 │ IDK+cena │ p|vekMedzi(18, 19) │
│ vek od 19 do 27 │          1.95 │ IDK+cena │ p|vekMedzi(19, 27) │
│ vek od 27 do 45 │          2.05 │ IDK+cena │ p|vekMedzi(27, 45) │
│ vek od 45 do 51 │          2.07 │ IDK+cena │ p|vekMedzi(45, 51) │
│ vek od 51 do 53 │          2.21 │ IDK+cena │ p|vekMedzi(51, 53) │
│ vek od 53 do 57 │          2.38 │ IDK+cena │ p|vekMedzi(53, 57) │
│ vek od 57 do 61 │          2.59 │ IDK+cena │ p|vekMedzi(57, 61) │
│ vek od 61 do 64 │          2.88 │ IDK+cena │ p|vekMedzi(61, 64) │
│ vek od 64 do 68 │          3.05 │ IDK+cena │ p|vekMedzi(64, 68) │
│ vek od 68 do 72 │          3.29 │ IDK+cena │ p|vekMedzi(68, 72) │
│ vek od 72 do 87 │           3.7 │ IDK+cena │ p|vekMedzi(72, 87) │
│ vek od 87+      │          3.66 │ IDK+cena │ p|vekMedzi(87)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.022089 │ vv.bodyCelkom*cena        │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['BE','CU']                         │
│        0.022973 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│         0.00819 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│        0.022089 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && vv.typ!='SVaLZ'                              │
│         0.04851 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│         0.04851 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│        0.022089 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│        0.048972 │ vv.bodyCelkom*cena        │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│          0.0078 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            4.41 │ vv.pocet*cena             │ EKG (5702Z,5702ZV)                            │ vv.kod in ['5702ZV','5702Z']                                 │
│             4.4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│              16 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│        0.022089 │ vv.bodyCelkom*cena        │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             390 │ 160                                                                                                       │                           │
│             180 │ 159a                                                                                                      │                           │
│             180 │ 159b                                                                                                      │                           │
│             180 │ 159x                                                                                                      │                           │
│             180 │ 159z                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

