                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────┐
│ Názov a hodnota │ Popis          │
├─────────────────┼────────────────┤
│ IDK = 0.01      │ NASTAVENIA IDK │
└─────────────────┴────────────────┘


  CENY ZA PACIENTA
┌─────────────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                       │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────────────────┼───────────────┼──────────┼────────────────────┤
│ do 1 roku                   │             6 │ IDK+cena │ p|vekMedzi(0, 1)   │
│ od 1 do dovršenia 2 rokov   │           6.4 │ IDK+cena │ p|vekMedzi(1, 2)   │
│ od 2 do dovršenia 7 rokov   │          4.25 │ IDK+cena │ p|vekMedzi(2, 7)   │
│ od 7 do dovršenia 19 rokov  │          2.87 │ IDK+cena │ p|vekMedzi(7, 19)  │
│ od 19 do dovršenia 27 rokov │          1.86 │ IDK+cena │ p|vekMedzi(19, 27) │
│ od 27 do dovršenia 28 rokov │          1.95 │ IDK+cena │ p|vekMedzi(27, 28) │
└─────────────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.020072 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|has('jeNeodkladna')                     │
│          0.0078 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaZL                                   │
│          0.0193 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaZL                                  │
│        0.048972 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143', '143a', '144', '145', '145a', '146', '146a │
│                 │                           │                                               │ ', '146b', '146c', '148', '148a', '148b', '148c', '149', '14 │
│                 │                           │                                               │ 9a', '149b', '149c', '149d', '149f', '159b', '950', '953', ' │
│                 │                           │                                               │ 159a', '159x', '159z']                                       │
│        0.048972 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['160']                                            │
│           0.041 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142']                                            │
│           0.044 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.044 │ vv.bodyCelkom*cena        │ Glykemia                                      │ vv.kod in ['3671']                                           │
│          0.0193 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25', '26', '29', '30']                           │
│               4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a']                                          │
│              10 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             4.2 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702ZV']                                         │
│               6 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

