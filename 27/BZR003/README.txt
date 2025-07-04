                                                                 =============================
                                                                 Cenník pneumologia a ftizeolo
                                                                 =============================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬─────────────────────┐
│ Názov a hodnota      │ Popis               │
├──────────────────────┼─────────────────────┤
│ LIMIT = 0            │ Limit               │
│ CB = 0.0391          │ Cena bodu           │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ USG │
│ IPP4 = 5.83          │ IPP4                │
│ IPP5 = 4.24          │ IPP5                │
│ IPP6 = 3.18          │ IPP6                │
└──────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│          0.0435 │ vv.bodyCelkom*cena        │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│            0.15 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│            null │ vv.bodyCelkom*CB          │ Výkon 5765                                    │ vv.kod in ['5765']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 5766                                    │ vv.kod in ['5766']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 5770                                    │ vv.kod in ['5770']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 5779                                    │ vv.kod in ['5779']                                           │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            8.95 │ vv.pocet*cena             │ Výkon 3860                                    │ vv.kod in ['3860']                                           │
│          0.0158 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test                   │ vv.kod in ['629b']                                           │
│            6.06 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5330','5331','5332']                             │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5766','5769','5770','5771']                      │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│           0.022 │ vv.bodyCelkom*cena        │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

