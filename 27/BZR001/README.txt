                                                                   =========================
                                                                   Cenník vnútorné lekárstvo
                                                                   =========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬─────────────────────┐
│ Názov a hodnota      │ Popis               │
├──────────────────────┼─────────────────────┤
│ CB = 0.039           │ Cena bodu           │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ USG │
│ IPP1 = 0.57          │ IPP1                │
│ IPP2 = 0.36          │ IPP2                │
│ IPP3 = 0.28          │ IPP3                │
│ IPP4 = 5.83          │ IPP4                │
│ IPP5 = 4.24          │ IPP5                │
│ IPP6 = 3.18          │ IPP6                │
│ AGTC = 4.8           │ AGTC                │
│ PP50 = 10            │ PP50                │
│ LIMIT = 0            │ Limit               │
└──────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0488 │ vv.bodyCelkom*cena        │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 60a                                     │ vv.kod in ['60a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a','299b']                                    │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 1a                                      │ vv.kod in ['1a']                                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Zhodnotenie vyšetrení a zdrav.dokumentácie    │ vv.kod in ['5700']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ EKG                                           │ vv.kod in ['5702']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 654                                     │ vv.kod in ['654']                                            │
│            6.06 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│            8.95 │ vv.pocet*cena             │ Výkon 3860                                    │ vv.kod in ['3860']                                           │
│          0.0158 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252l                          │ vv.kod in ['252l']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test                   │ vv.kod in ['629b']                                           │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│            3292 │ 741                                                                                                       │                           │
│             480 │ 60r                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
│             150 │ 15d                                                                                                       │                           │
│             380 │ 4571a                                                                                                     │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

