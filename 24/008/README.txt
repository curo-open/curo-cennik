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
│        0.020072 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
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
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Preventivný výkon 142 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["142"]')             │ p.vekTyzdnov >= 0 || p.vekTyzdnov < 4                │
│ leného rozpǎtia (1-4 tyždne)    │            │                                                      │                                                      │
│ Preventivný výkon 143 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["143"]')             │ p.vekTyzdnov >= 2 || p.vekTyzdnov < 5                │
│ leného rozpǎtia (2-5 tyždne)    │            │                                                      │                                                      │
│ Preventivný výkon 143a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["143a"]')            │ p.vekTyzdnov >= 5 || p.vekTyzdnov < 8                │
│ oleného rozpǎtia (5-8 tyždne)   │            │                                                      │                                                      │
│ Preventivný výkon 144 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["144"]')             │ p.vekTyzdnov >= 8 || p.vekTyzdnov < 11               │
│ leného rozpǎtia (8-11 tyždne)   │            │                                                      │                                                      │
│ Preventivný výkon 145 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["145"]')             │ p.vekMesiacov >= 3 || p.vekMesiacov < 5              │
│ leného rozpǎtia (3-5 mesiacov)  │            │                                                      │                                                      │
│ Preventivný výkon 145a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["145a"]')            │ p.vekMesiacov >= 5 || p.vekMesiacov < 7              │
│ oleného rozpǎtia (5-7 mesiacov) │            │                                                      │                                                      │
│                                 │            │                                                      │                                                      │
│ Preventivný výkon 146 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["146"]')             │ p.vekMesiacov >= 7 || p.vekMesiacov < 9              │
│ leného rozpǎtia (7-9 mesiacov)  │            │                                                      │                                                      │
│ Preventivný výkon 146a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146a"]')            │ p.vekMesiacov >= 9 || p.vekMesiacov < 11             │
│ oleného rozpǎtia (9-11 mesiacov │            │                                                      │                                                      │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 146b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146b"]')            │ p.vekMesiacov >= 11 || p.vekMesiacov < 13            │
│ oleného rozpǎtia (11-13 mesiaco │            │                                                      │                                                      │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 146c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146c"]')            │ p.vekMesiacov >= 13 || p.vekMesiacov < 24            │
│ oleného rozpǎtia (13-24 mesiaco │            │                                                      │                                                      │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["148"]')             │ p.vekMesiacov >= 25 || p.vekMesiacov < 48            │
│ leného rozpǎtia (25-48 mesiacov │            │                                                      │                                                      │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 148a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148a"]')            │ p.vekMesiacov >= 49 || p.vekMesiacov < 60            │
│ oleného rozpǎtia (49-60 mesiaco │            │                                                      │                                                      │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148b"]')            │ p.vekMesiacov >= 61 || p.vekMesiacov < 84            │
│ oleného rozpǎtia (61-84 mesiaco │            │                                                      │                                                      │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148c"]')            │ p.vekMesiacov >= 97 || p.vekMesiacov < 120           │
│ oleného rozpǎtia (97-120 mesiac │            │                                                      │                                                      │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["149"]')             │ p.vekMesiacov >= 121 || p.vekMesiacov < 144          │
│ leného rozpǎtia (121-144 mesiac │            │                                                      │                                                      │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149a"]')            │ p.vekMesiacov >= 145 || p.vekMesiacov < 168          │
│ oleného rozpǎtia (145-168 mesia │            │                                                      │                                                      │
│ cov)                            │            │                                                      │                                                      │
│ Preventivný výkon 149b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149b"]')            │ p.vekMesiacov >= 169 || p.vekMesiacov < 192          │
│ oleného rozpǎtia (169-192 mesia │            │                                                      │                                                      │
│ cov)                            │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

