                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────┐
│ Názov a hodnota │ Popis             │
├─────────────────┼───────────────────┤
│ IDK = 0.01      │ NASTAVENIA IDK    │
│ VCB8 = 2.98     │ VCB pre výkon 8   │
│ VCB4 = 2.23     │ VCB pre výkon 4   │
│ VCB1 = 0.59     │ VCB pre výkon 1   │
│ VCB250 = 0.88   │ VCB pre výkon 250 │
│ AGTC = 4.8      │ AGTC              │
│ PP50 = 10       │ PP50              │
│ PP05 = 10       │ PP05              │
└─────────────────┴───────────────────┘


  CENY ZA PACIENTA
┌─────────────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                       │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────────────────┼───────────────┼──────────┼────────────────────┤
│ do  1 roku                  │          9.14 │ IDK+cena │ p|vekMedzi(0, 1)   │
│ od  1 do dovršenia 2 rokov  │          9.55 │ IDK+cena │ p|vekMedzi(1, 2)   │
│ od  2 do dovršenia 7 rokov  │           6.3 │ IDK+cena │ p|vekMedzi(2, 7)   │
│ od  7 do dovršenia 19 rokov │          3.89 │ IDK+cena │ p|vekMedzi(7, 19)  │
│ od 19 do dovršenia 27 rokov │           2.5 │ IDK+cena │ p|vekMedzi(19, 27) │
│ od 27 do dovršenia 28 rokov │          2.61 │ IDK+cena │ p|vekMedzi(27, 28) │
└─────────────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.020072 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│          0.0078 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaZL                                   │
│          0.0193 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaZL                                  │
│           0.065 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143', '143a', '144', '145', '145a', '146', '146a │
│                 │                           │                                               │ ', '146b', '146c', '148', '148a', '148b', '148c', '149', '14 │
│                 │                           │                                               │ 9a', '149b', '149c', '149d', '149f', '159b', '950', '953', ' │
│                 │                           │                                               │ 159a', '159x', '159z','160']                                 │
│           0.092 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│            0.05 │ vv.bodyCelkom*cena        │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67']                                             │
│                 │                           │ nie do 5 roku života                          │                                                              │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','11a','70']                                  │
│           0.044 │ vv.bodyCelkom*cena        │ Glykemia                                      │ vv.kod in ['3671']                                           │
│          0.0193 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25', '26', '29', '30']                           │
│               5 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a']                                          │
│              10 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             4.2 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702ZV']                                         │
│           10.22 │ vv.pocet*cena             │ Vykon 8                                       │ !p.kapitacia && vv.kod in ['8']                              │
│            7.19 │ vv.pocet*cena             │ Vykon 4                                       │ !p.kapitacia && vv.kod in ['4']                              │
│            6.54 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│            null │ vv.pocet*VCB8             │ Vykon 8                                       │ vv.kod in ['8']                                              │
│            null │ vv.pocet*VCB4             │ Vykon 4                                       │ vv.kod in ['4']                                              │
│            null │ vv.pocet*VCB1             │ Vykon 1                                       │ vv.kod in ['1']                                              │
│            null │ vv.pocet*VCB250           │ Vykon 250                                     │ vv.kod in ['250']                                            │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ PP05                      │ Pripočitateľné položky                        │ vv.kod=='PP05'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
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
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Preventivný výkon 142 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["142"]')             │ pacient.vekDni|vTyzdnoch >= 0 || pacient.vekDni|vTyz │
│ leného rozpǎtia (1-4 tyždne)    │            │                                                      │ dnoch < 4                                            │
│ Preventivný výkon 143 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["143"]')             │ pacient.vekDni|vTyzdnoch >= 2 || pacient.vekDni|vTyz │
│ leného rozpǎtia (2-5 tyždne)    │            │                                                      │ dnoch < 5                                            │
│ Preventivný výkon 143a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["143a"]')            │ pacient.vekDni|vTyzdnoch >= 5 || pacient.vekDni|vTyz │
│ oleného rozpǎtia (5-8 tyždne)   │            │                                                      │ dnoch < 8                                            │
│ Preventivný výkon 144 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["144"]')             │ pacient.vekDni|vTyzdnoch >= 8 || pacient.vekDni|vTyz │
│ leného rozpǎtia (8-11 tyždne)   │            │                                                      │ dnoch < 11                                           │
│ Preventivný výkon 145 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["145"]')             │ pacient.vekDni|vMesiacoch >= 3 || pacient.vekDni|vMe │
│ leného rozpǎtia (3-5 mesiacov)  │            │                                                      │ siacoch < 5                                          │
│ Preventivný výkon 145a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["145a"]')            │ pacient.vekDni|vMesiacoch >= 5 || pacient.vekDni|vMe │
│ oleného rozpǎtia (5-7 mesiacov) │            │                                                      │ siacoch < 7                                          │
│ Preventivný výkon 146 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["146"]')             │ pacient.vekDni|vMesiacoch >= 7 || pacient.vekDni|vMe │
│ leného rozpǎtia (7-9 mesiacov)  │            │                                                      │ siacoch < 9                                          │
│ Preventivný výkon 146a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146a"]')            │ pacient.vekDni|vMesiacoch >= 9 || pacient.vekDni|vMe │
│ oleného rozpǎtia (9-11 mesiacov │            │                                                      │ siacoch < 11                                         │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 146b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146b"]')            │ pacient.vekDni|vMesiacoch >= 11 || pacient.vekDni|vM │
│ oleného rozpǎtia (11-13 mesiaco │            │                                                      │ esiacoch < 13                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 146c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146c"]')            │ pacient.vekDni|vMesiacoch >= 13 || pacient.vekDni|vM │
│ oleného rozpǎtia (13-24 mesiaco │            │                                                      │ esiacoch < 24                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["148"]')             │ pacient.vekDni|vMesiacoch >= 25 || pacient.vekDni|vM │
│ leného rozpǎtia (25-48 mesiacov │            │                                                      │ esiacoch < 48                                        │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 148a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148a"]')            │ pacient.vekDni|vMesiacoch >= 49 || pacient.vekDni|vM │
│ oleného rozpǎtia (49-60 mesiaco │            │                                                      │ esiacoch < 60                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148b"]')            │ pacient.vekDni|vMesiacoch >= 61 || pacient.vekDni|vM │
│ oleného rozpǎtia (61-84 mesiaco │            │                                                      │ esiacoch < 84                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148c"]')            │ pacient.vekDni|vMesiacoch >= 97 || pacient.vekDni|vM │
│ oleného rozpǎtia (97-120 mesiac │            │                                                      │ esiacoch < 120                                       │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["149"]')             │ pacient.vekDni|vMesiacoch >= 121 || pacient.vekDni|v │
│ leného rozpǎtia (121-144 mesiac │            │                                                      │ Mesiacoch < 144                                      │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149a"]')            │ pacient.vekDni|vMesiacoch >= 145 || pacient.vekDni|v │
│ oleného rozpǎtia (145-168 mesia │            │                                                      │ Mesiacoch < 168                                      │
│ cov)                            │            │                                                      │                                                      │
│ Preventivný výkon 149b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149b"]')            │ pacient.vekDni|vMesiacoch >= 169 || pacient.vekDni|v │
│ oleného rozpǎtia (169-192 mesia │            │                                                      │ Mesiacoch < 192                                      │
│ cov)                            │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

