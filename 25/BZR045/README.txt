                                                                      ===================
                                                                      Cenník reumatologia
                                                                      ===================

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
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│               5 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5302','5303','5304','5307','5307a' │
│                 │                           │                                               │ ,'5312','5315','5316']                                       │
│        0.005311 │ vv.bodyCelkom*cena        │ Osteodenzitometria                            │ vv.kod in ['5330','5331','5332']                             │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d','15D']                                      │
│            null │ vv.bodyCelkom*CB          │ Výkon 1A02072                                 │ vv.kod in ['1A02072']                                        │
│            null │ vv.bodyCelkom*CB          │ Výkon 1A03057                                 │ vv.kod in ['1A03057']                                        │
│            null │ vv.bodyCelkom*CB          │ Výkon 1B08098                                 │ vv.kod in ['1B08098']                                        │
│            null │ vv.bodyCelkom*CB          │ Výkon 1B08082                                 │ vv.kod in ['1B08082']                                        │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
│        0.005311 │ vv.bodyCelkom*cena        │ Výkony - Bezdomovec, Cudzinec, EU             │ vv.kod in ['5330','5331','5332'] && p.typ in ['BE','CU','EU' │
│                 │                           │                                               │ ]                                                            │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkony - Bezdomovec, Cudzinec, EU             │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316'] && p.typ in ['BE','CU','EU']                 │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ vv.typ!='SVaLZ' && p.typ in ['BE','CU','EU']                 │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkony - Bezdomovec, Cudzinec, EU             │ vv.typ=='SVaLZ' && p.typ in ['BE','CU','EU']                 │
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
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1300 │ 1A02072                                                                                                   │                           │
│             150 │ 15d                                                                                                       │                           │
│             320 │ 1A03057                                                                                                   │                           │
│             300 │ 1B08098                                                                                                   │                           │
│             300 │ 1B08082                                                                                                   │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

