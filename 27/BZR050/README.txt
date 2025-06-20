                                                                       =================
                                                                       Cenník diabetolog
                                                                       =================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬──────────────────────────────┐
│ Názov a hodnota      │ Popis                        │
├──────────────────────┼──────────────────────────────┤
│ CB = 0.0391          │ Cena bodu                    │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.01107 │ Cena bodu USG                │
│ CBP = 0.0455         │ Cena bodu preventívne výkony │
│ IPP1 = 3.71          │ IPP1                         │
│ IPP2 = 3.18          │ IPP2                         │
│ IPP3 = 2.12          │ IPP3                         │
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
│          0.0435 │ vv.bodyCelkom*cena        │ Výkony 60,62,63                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkony 65,66,67                               │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['70','1b','1c','11a']                             │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Odber kapilárnej krvi                         │ vv.kod in ['258']                                            │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 1B06025, 1B05011,1B05012,1B05013,1B0501 │ vv.kod in ['1B06025','1B05011','1B05012','1B05013','1B05014' │
│                 │                           │ 4                                             │ ]                                                            │
│          0.0391 │ vv.bodyCelkom*cena        │ Výkon 1A02009,1A02012,1A03007                 │ vv.kod in ['1A02007','1A02009','1A02012','1A3007']           │
│            5.82 │ vv.pocet*cena             │ Výkon H0006                                   │ vv.kod in ['H0006']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 15b - zhodnotenie odberov               │ vv.kod in ['15b']                                            │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5330','5331','5332']                             │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5793','5794','5795']                             │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ USG                                           │ vv.kod in ['5734','5735','5736','5737','5738','5739','5740', │
│                 │                           │                                               │ '5741','5742','5743']                                        │
│         0.01107 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5153a','5333']                                   │
│          0.0158 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod==['4571a']                                            │
│         0.01107 │ vv.bodyCelkom*cena        │ Výkon 4587a                                   │ vv.kod==['4587a']                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ EKG                                           │ vv.kod in ['5702','5702a','15c']                             │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
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
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1200 │ 1B06025                                                                                                   │                           │
│             180 │ 1A02007                                                                                                   │                           │
│            1000 │ 1A02009                                                                                                   │                           │
│           12000 │ 1A02012                                                                                                   │                           │
│            1200 │ 1A03007                                                                                                   │                           │
│             420 │ 1B05011                                                                                                   │                           │
│             420 │ 1B05012                                                                                                   │                           │
│             270 │ 1B05013                                                                                                   │                           │
│             270 │ 1B05014                                                                                                   │                           │
│             180 │ 10c                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
│             380 │ 4571a                                                                                                     │                           │
│             500 │ 4587a                                                                                                     │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

