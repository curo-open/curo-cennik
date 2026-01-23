                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IDK = 1.3       │ IDK                   │
│ KPS = 1         │ KPS                   │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
│ AGTC = 4.8      │ AGTC                  │
│ PP50 = 10       │ PP50                  │
│ PP05 = 10       │ PP05                  │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────────────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis                     │ Premenná cena │ Vzorec   │ Podmienka                         │
├───────────────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ do  1 roku                │         12.53 │ IDK+cena │ p.kapitacia && p|vekMedzi(0, 1)   │
│ od  1 do 2 rokov vratane  │         12.41 │ IDK+cena │ p.kapitacia && p|vekMedzi(1, 3)   │
│ od  3 do 5 rokov vratane  │          8.59 │ IDK+cena │ p.kapitacia && p|vekMedzi(3, 6)   │
│ od  6 do 9 rokov vratane  │          6.21 │ IDK+cena │ p.kapitacia && p|vekMedzi(6, 10)  │
│ od 10 do 14 rokov vratane │          5.69 │ IDK+cena │ p.kapitacia && p|vekMedzi(10, 15) │
│ od 15 do 17 rokov vratane │          5.37 │ IDK+cena │ p.kapitacia && p|vekMedzi(15, 18) │
│ od 18 do 18 rokov vratane │          4.83 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 19) │
│ od 19 do 19 rokov vratane │          4.83 │ IDK+cena │ p.kapitacia && p|vekMedzi(19, 20) │
│ od 20 do 25 rokov vratane │          3.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 26) │
└───────────────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│           0.035 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143', '143a', '144', '145', '145a', '146', '146a │
│                 │                           │                                               │ ', '146b', '146c', '148', '148a', '148b', '148c', '149', '14 │
│                 │                           │                                               │ 9a', '149b', '149c', '149d', '159b', '950', '951','952','953 │
│                 │                           │                                               │ ']                                                           │
│        0.018257 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['1']                                              │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['160']                                            │
│          0.1175 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142']                                            │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252a','252b','252c','252C']                      │
│          0.0318 │ vv.bodyCelkom*cena        │ Rozbor a plánovanie cielených terapeutických  │ vv.kod in ['10']                                             │
│                 │                           │ postupov v na ovplyvnenie                     │                                                              │
│                 │                           │ chronických ochorení                          │                                                              │
│           0.027 │ vv.bodyCelkom*cena        │ Telekomunikácia                               │ vv.kod in ['1b','70','11a']                                  │
│          0.0318 │ vv.bodyCelkom*cena        │ Komplexné vyšetrenie pri prevzatí do starostl │ vv.kod in ['60']                                             │
│                 │                           │ ivosti                                        │                                                              │
│           0.029 │ vv.bodyCelkom*cena        │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67']                                             │
│                 │                           │ nie do 5 roku života                          │                                                              │
│           0.035 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25','26']                                        │
│            5.75 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│           17.33 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a','62b']                                      │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│               2 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250D']                                           │
│              10 │ vv.pocet*cena             │ Intenzifikovaná zdravotná starostlivosť pre r │ vv.kod in ['H0002']                                          │
│                 │                           │ izikových poistencov s obezitou               │                                                              │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ PP05                      │ Pripočitateľné položky                        │ vv.kod=='PP05'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            0.01 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaLZ                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaLZ                                  │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             620 │ 60                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│              70 │ 252a                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
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

