                                                                 =============================
                                                                 Cenník pneumologia a ftizeolo
                                                                 =============================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬──────────────────────┐
│ Názov a hodnota │ Popis                │
├─────────────────┼──────────────────────┤
│ CB = 0          │ Vypočitaná cena bodu │
│ CBSVALZ = 0     │ Cena bodu SVaLZ      │
│ CBSVALZUSG = 0  │ Cena bodu SVaLZ USG  │
│ LIMIT = 0       │ Limit                │
└─────────────────┴──────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*cena        │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│            null │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*cena        │ Výkon Ine SVALZ                               │ vv.kod in ['5766','5769','5770','5771']                      │
│            null │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*cena        │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
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
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

