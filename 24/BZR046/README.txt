                                                                      ===================
                                                                      Cenník algeziologia
                                                                      ===================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────┐
│ Názov a hodnota    │ Popis           │
├────────────────────┼─────────────────┤
│ IPP1 = 1.08        │ IPP1            │
│ LIMIT = 2235       │ Limit           │
│ CB = 0.037971      │ Cena bodu       │
│ CBSVALZ = 0.009724 │ Cena bodu SVaLZ │
└────────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0193 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.kod in ['62','63']                                        │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.kod in ['65','66','67']                                   │
│           0.027 │ vv.bodyCelkom*cena        │ Elektronická komunikácia                      │ vv.kod in ['11a','1b','70','1c']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316']                                              │
│            null │ vv.bodyCelkom*CB          │ Epidurálna anestézia                          │ vv.kod in ['89']                                             │
│            null │ vv.bodyCelkom*CB          │ Blokáda periférneho nervu                     │ vv.kod in ['91']                                             │
│            null │ vv.bodyCelkom*CB          │ Selektívna blokáda pod USG                    │ vv.kod in ['95b']                                            │
│            null │ vv.bodyCelkom*CB          │ Aplikácia náplasti Qutenza                    │ vv.kod in ['410']                                            │
│            null │ vv.bodyCelkom*CB          │ Intraartikulárna injekcia                     │ vv.kod in ['255']                                            │
│            null │ vv.bodyCelkom*CB          │ Obstreky bolestivých bodov                    │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Infúzia                                       │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ TENS                                          │ vv.kod in ['562']                                            │
│            null │ vv.bodyCelkom*CB          │ Bankovanie                                    │ vv.kod in ['568']                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             650 │ 60                                                                                                        │                           │
│             310 │ 62                                                                                                        │                           │
│             250 │ 63                                                                                                        │                           │
│               0 │ 65                                                                                                        │                           │
│               0 │ 66                                                                                                        │                           │
│               0 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             600 │ 79                                                                                                        │                           │
│            5766 │ 89                                                                                                        │                           │
│            2878 │ 91                                                                                                        │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             150 │ 15d                                                                                                       │                           │
│            5156 │ 95b                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

