                                                                       ==================
                                                                       Cenník kardiologia
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────────┬─────────────────────┐
│ Názov a hodnota     │ Popis               │
├─────────────────────┼─────────────────────┤
│ CB = 0.045          │ Cena bodu           │
│ CBSVALZ = 0.015     │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.0088 │ Cena bodu SVaLZ USG │
│ IPP1 = 0.57         │ IPP1                │
│ IPP2 = 0.36         │ IPP2                │
│ IPP3 = 0.28         │ IPP3                │
│ AGTC = 4.8          │ AGTC                │
│ PP50 = 10           │ PP50                │
│ LIMIT = 0           │ Limit               │
└─────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 1a                                      │ vv.kod in ['1a']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 509a;512;513;514a;516;518;522;523a;530; │ vv.kod in ['509a','512','513','514a','516','518','522','523a │
│                 │                           │ 531                                           │ ','530','531']                                               │
│            null │ vv.bodyCelkom*CB          │ Výkon 532;533a;540;541;542                    │ vv.kod in ['532','533a','540','541','542']                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5330,5531,5332                          │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316','5799']                                       │
│            null │ vv.bodyCelkom*CB          │ Výkon 654                                     │ vv.kod in ['654']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon Y0018                                   │ vv.kod in ['Y0018']                                          │
│            null │ vv.bodyCelkom*CB          │ Výkon Y0023                                   │ vv.kod in ['Y0023']                                          │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5793;5794;5795                          │ vv.kod in ['5793','5794','5795']                             │
│            null │ vv.bodyCelkom*CB          │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

