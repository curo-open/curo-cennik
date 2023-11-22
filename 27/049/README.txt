                                                                       ==================
                                                                       Cenník kardiologia
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬──────────────────────────────┐
│ Názov a hodnota      │ Popis                        │
├──────────────────────┼──────────────────────────────┤
│ CB = 0.0335          │ Cena bodu                    │
│ CBO = 0.0305         │ Cena bodu ostatné ŠAS výkony │
│ CBSVALZ = 0.00973    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.01044 │ Cena bodu SVaLZ USG          │
│ NCB = 0.005          │ Navysena cena bodu           │
│ IPP1 = 0             │ IPP1                         │
│ IPP2 = 0             │ IPP2                         │
│ IPP3 = 0             │ IPP3                         │
│ AGTC = 4.8           │ AGTC                         │
│ PP50 = 10            │ PP50                         │
│ OPT = 10             │ Optimus                      │
│ LIMIT = 0            │ Limit                        │
└──────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0305 │ vv.bodyCelkom*(cena+NCB)  │ Výkon 250a, 250b - odbery                     │ vv.kod in ['250a','250b']                                    │
│          0.0305 │ vv.bodyCelkom*(cena+NCB)  │ Výkon 15b - zhodnotenie odberov               │ vv.kod in ['15b']                                            │
│          0.0335 │ vv.bodyCelkom*(cena+NCB)  │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│          0.0226 │ vv.bodyCelkom*(cena+NCB)  │ Izometrický zátažový tes                      │ vv.kod in ['5727']                                           │
│         0.01044 │ vv.bodyCelkom*(cena+NCB)  │ Echokardiografia                              │ vv.kod in ['5744','5745','5746','5746b','5754']              │
│         0.00973 │ vv.bodyCelkom*(cena+NCB)  │ Ergometria                                    │ vv.kod in ['5708']                                           │
│          0.0305 │ vv.bodyCelkom*(cena+NCB)  │ EKG                                           │ vv.kod in ['603a','15c']                                     │
│         0.00973 │ vv.bodyCelkom*(cena+NCB)  │ Ekg holter                                    │ vv.kod in ['5712','5713','5714']                             │
│              50 │ vv.pocet*cena             │ Výkon 4F00010                                 │ vv.kod in ['4F00010']                                        │
│              70 │ vv.pocet*cena             │ Výkon 607A                                    │ vv.kod in ['607A']                                           │
│          0.0305 │ vv.bodyCelkom*(cena+NCB)  │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*(cena+NCB)  │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            8.95 │ vv.pocet*cena             │ Stanovenie D-diméru                           │ vv.kod in ['3860']                                           │
│            5.88 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.78 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│            10.2 │ vv.pocet*cena             │ Prístrojový antigénový test                   │ vv.kod in ['629b']                                           │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

