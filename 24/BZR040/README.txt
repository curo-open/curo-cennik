                                                                       =================
                                                                       Cenník imunologia
                                                                       =================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────┐
│ Názov a hodnota    │ Popis           │
├────────────────────┼─────────────────┤
│ LIMIT = 240000     │ Limit           │
│ CB = 0.029626      │ Cena bodu       │
│ CBV = 0.026432     │ Cena bodu vv=60 │
│ CBSVALZ = 0.008605 │ Cena bodu SVaLZ │
└────────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBV         │ Výkon 60                                      │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 62,63                                   │ vv.kod in ['62','63']                                        │
│           0.027 │ vv.bodyCelkom*cena        │ Elektronická komunikácia                      │ vv.kod in ['70','1b','1c','11a']                             │
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
│             450 │ 60                                                                                                        │                           │
│             290 │ 62                                                                                                        │                           │
│             230 │ 63                                                                                                        │                           │
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
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Výkon 250X nie je akceptovaný v │     0      │ p.vek >= 0                                           │ d.vv|ma('!(kod in ["250X"])')                        │
│ o Dôvere, použite 250a alebo 25 │            │                                                      │                                                      │
│ 0b                              │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘
