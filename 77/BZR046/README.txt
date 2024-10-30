                                                                      ===================
                                                                      Cenník algeziologia
                                                                      ===================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬─────────────────┐
│ Názov a hodnota │ Popis           │
├─────────────────┼─────────────────┤
│ LIMIT = 0       │ Limit           │
│ CB = 0.045      │ Cena bodu       │
│ CBSVALZ = 0.015 │ Cena bodu SVaLZ │
│ IPP4 = 2.49     │ IPP4            │
│ IPP5 = 0.73     │ IPP5            │
│ IPP6 = 0.65     │ IPP7            │
└─────────────────┴─────────────────┘


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
│            null │ vv.bodyCelkom*CB          │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5330,5531,5332                          │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316','5799']                                       │
│            null │ vv.bodyCelkom*CB          │ Epidurálna anestézia                          │ vv.kod in ['89']                                             │
│            null │ vv.bodyCelkom*CB          │ Blokáda periférneho nervu                     │ vv.kod in ['91']                                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Selektívna blokáda pod USG                    │ vv.kod in ['95b']                                            │
│            null │ vv.bodyCelkom*CB          │ Aplikácia náplasti Qutenza                    │ vv.kod in ['410']                                            │
│            null │ vv.bodyCelkom*CB          │ Intraartikulárna injekcia                     │ vv.kod in ['255']                                            │
│            null │ vv.bodyCelkom*CB          │ Obstreky bolestivých bodov                    │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Infúzia                                       │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ TENS                                          │ vv.kod in ['562']                                            │
│            null │ vv.bodyCelkom*CB          │ Bankovanie                                    │ vv.kod in ['568']                                            │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5330','5331','5332'] && vv.typ!='SVaLZ'          │
│        0.012075 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5793','5794','5795'] && vv.typ!='SVaLZ'          │
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
│             150 │ 15d                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             480 │ 60r                                                                                                       │                           │
│            1300 │ 1A02072                                                                                                   │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

