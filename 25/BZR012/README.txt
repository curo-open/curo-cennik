                                                                        ===============
                                                                        Cenník urologia
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬─────────────────────┐
│ Názov a hodnota       │ Popis               │
├───────────────────────┼─────────────────────┤
│ IPP1 = 1.46           │ IPP1                │
│ IPP2 = 2.35           │ IPP2                │
│ IPP3 = 3.98           │ IPP3                │
│ IPP4 = 6.98           │ IPP4                │
│ IPPD = 0              │ IPPD                │
│ LIMIT = 0             │ Limit               │
│ CB = 0.03466          │ Cena bodu           │
│ CBSVALZ = 0.009159    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG │
└───────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Plánovanie terapeutických postupov            │ vv.kod in ['10']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│               5 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 252                                     │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Zhodnotenie výsledkov                         │ vv.kod in ['15b']                                            │
│           0.026 │ vv.bodyCelkom*cena        │ Zhodnotenie RTG dokumentácie                  │ vv.kod in ['15d']                                            │
│             150 │ vv.pocet*cena             │ Výkon 5153C                                   │ vv.kod in ['5153C']                                          │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5330','5331','5332','5300','5301','5302','5303', │
│                 │                           │                                               │ '5304','5307','5307a','5312','5315','5316','5796','5799']    │
│            0.08 │ vv.bodyCelkom*cena        │ Výkon - Vyšetrenie na včasné rozpoznanie ocho │ vv.kod in ['158','158A','158B','158C','158D','159c']         │
│                 │                           │ renia na rakovinu                             │                                                              │
│              94 │ vv.pocet*cena             │ Výkon 4L03003, 4L03004                        │ vv.kod in ['4L03003','4L03004']                              │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             500 │ 60                                                                                                        │                           │
│             310 │ 62                                                                                                        │                           │
│             250 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             390 │ 158                                                                                                       │                           │
│            1000 │ 5302                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             390 │ 158A                                                                                                      │                           │
│             390 │ 158B                                                                                                      │                           │
│             390 │ 158C                                                                                                      │                           │
│             390 │ 158D                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

