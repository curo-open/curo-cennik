                                                                      ===================
                                                                      Cenník algeziologia
                                                                      ===================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬─────────────────────┐
│ Názov a hodnota      │ Popis               │
├──────────────────────┼─────────────────────┤
│ LIMIT = 0            │ Limit               │
│ CB = 0.0391          │ Cena bodu           │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ USG │
│ IPP4 = 2.49          │ IPP4                │
│ IPP5 = 0.73          │ IPP5                │
│ IPP6 = 0.57          │ IPP6                │
│ IPP7 = 1.06          │ IPP7                │
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
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 654                                     │ vv.kod in ['654']                                            │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│           0.015 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkon 5330,5531,5332                          │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5302','5303','5304','5307','5307a' │
│                 │                           │                                               │ ,'5312','5315','5316']                                       │
│            null │ vv.bodyCelkom*CB          │ Epidurálna anestézia                          │ vv.kod in ['89']                                             │
│            null │ vv.bodyCelkom*CB          │ Blokáda periférneho nervu                     │ vv.kod in ['91']                                             │
│            null │ vv.bodyCelkom*CB          │ Selektívna blokáda pod USG                    │ vv.kod in ['95b']                                            │
│            null │ vv.bodyCelkom*CB          │ Aplikácia náplasti Qutenza                    │ vv.kod in ['410']                                            │
│            null │ vv.bodyCelkom*CB          │ Intraartikulárna injekcia                     │ vv.kod in ['255']                                            │
│            null │ vv.bodyCelkom*CB          │ Obstreky bolestivých bodov                    │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Infúzia                                       │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ TENS                                          │ vv.kod in ['562']                                            │
│            null │ vv.bodyCelkom*CB          │ Bankovanie                                    │ vv.kod in ['568']                                            │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│           0.055 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5330','5331','5332'] && vv.typ!='SVaLZ'          │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5793','5794','5795'] && vv.typ!='SVaLZ'          │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             500 │ 60                                                                                                        │                           │
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

