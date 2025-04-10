                                                                     ======================
                                                                     Cenník gastroenterolog
                                                                     ======================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬──────────────────────────────┐
│ Názov a hodnota │ Popis                        │
├─────────────────┼──────────────────────────────┤
│ CB = 0.045      │ Cena bodu                    │
│ CBP = 0.07      │ Cena bodu preventívne výkony │
│ CBSVALZ = 0.015 │ Cena bodu SVaLZ              │
└─────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│            null │ vv.bodyCelkom*CB          │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CB          │ Výkon ŠAS                                     │ vv.kod in ['740','741','746','756','761','763','763a','765'] │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5330,5531,5332                          │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316']                                              │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760SP','760SN','760PP','760PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763SP','763SN','763PP','763PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763p','763m']                                    │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763P','763M']                                    │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.kod in ['15d']                                            │
│           0.022 │ vv.bodyCelkom*cena        │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             200 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│            2426 │ 761                                                                                                       │                           │
│            3000 │ 763                                                                                                       │                           │
│            1500 │ 760sp                                                                                                     │                           │
│            1500 │ 760sn                                                                                                     │                           │
│            1500 │ 760pp                                                                                                     │                           │
│            1500 │ 760pn                                                                                                     │                           │
│            3000 │ 763sp                                                                                                     │                           │
│            3000 │ 763sn                                                                                                     │                           │
│            3000 │ 763pp                                                                                                     │                           │
│            3000 │ 763pn                                                                                                     │                           │
│            3000 │ 763p                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1000 │ 68a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│            0.95 │ 62328                                                                                                     │ liek                      │
│            1.15 │ 62329                                                                                                     │ liek                      │
│           133.1 │ 02578                                                                                                     │ liek                      │
│         2012.24 │ 0358b                                                                                                     │ liek                      │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Výkony 760*, 763* sú vykázané p │     0      │ vv.kod in ['760sp','760sn','760pp','760pn','763sp',' │ vv.diagnoza in ['Z12.1']                             │
│ od zlou diagnózou               │            │ 763sn','763pp','763pn','763p']                       │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

