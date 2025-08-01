                                                                       ==================
                                                                       Cenník kardiologia
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬─────────────────────┐
│ Názov a hodnota      │ Popis               │
├──────────────────────┼─────────────────────┤
│ CB = 0.0391          │ Cena bodu           │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ USG │
│ IPP1 = 1.98          │ IPP1                │
│ IPP2 = 0.36          │ IPP2                │
│ IPP3 = 0.28          │ IPP3                │
│ AGTC = 4.8           │ AGTC                │
│ PP50 = 10            │ PP50                │
│ OPT = 10             │ Optimus             │
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
│          0.0435 │ vv.bodyCelkom*cena        │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│          0.0295 │ vv.bodyCelkom*cena        │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Výkon 15b - zhodnotenie odberov               │ vv.kod in ['15b']                                            │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            8.95 │ vv.pocet*cena             │ Výkon 3860                                    │ vv.kod in ['3860']                                           │
│            6.06 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│         0.01107 │ vv.bodyCelkom*cena        │ Echokardiografia                              │ vv.kod in ['5744','5745','5746','5746b','5754']              │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon 5727                                    │ vv.kod in ['5727']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5702                                    │ vv.kod in ['5702']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Ergometria                                    │ vv.kod in ['5708']                                           │
│          0.0158 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│            null │ vv.bodyCelkom*CB          │ EKG                                           │ vv.kod in ['603a','15c']                                     │
│            null │ vv.bodyCelkom*CBSVALZ     │ Ekg holter                                    │ vv.kod in ['5712','5713','5714','5715']                      │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
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
│             480 │ 60r                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
│             150 │ 15d                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
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

