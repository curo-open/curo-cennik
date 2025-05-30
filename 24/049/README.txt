                                                                       ==================
                                                                       Cenník kardiologia
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬──────────────────────┐
│ Názov a hodnota    │ Popis                │
├────────────────────┼──────────────────────┤
│ CB = 0.0338        │ Cena bodu            │
│ CBO = 0.037151     │ Cena bodu 60, 62, 63 │
│ CBSVALZ = 0.009724 │ Cena bodu SVaLZ      │
│ CBSVALZUSG = 0     │ Cena bodu SVaLZ USG  │
│ AGTC = 4.8         │ AGTC                 │
│ PP50 = 10          │ PP50                 │
│ POHOS = 30         │ POHOS                │
│ LIMIT = 2235       │ Limit                │
└────────────────────┴──────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBO         │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│          0.0027 │ vv.bodyCelkom*cena        │ telemedicína                                  │ vv.kod in ['1b','11a','70']                                  │
│          0.0338 │ vv.bodyCelkom*cena        │ Výkon 15b - vyhodnotenie odberov              │ vv.kod in ['15b']                                            │
│          0.0338 │ vv.bodyCelkom*cena        │ Výkon 65;66                                   │ vv.kod in ['65','66']                                        │
│          0.0338 │ vv.bodyCelkom*cena        │ Výkon 250a,b - odbery                         │ vv.kod in ['250a','250b']                                    │
│          0.0318 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['603a','15c']                                     │
│        0.009724 │ vv.bodyCelkom*cena        │ Výkon 5702                                    │ vv.kod in ['5702']                                           │
│        0.009724 │ vv.bodyCelkom*cena        │ Ergometria                                    │ vv.kod in ['5708']                                           │
│        0.009724 │ vv.bodyCelkom*cena        │ EKG holter                                    │ vv.kod in ['5712','5713','5714']                             │
│        0.009724 │ vv.bodyCelkom*cena        │ Echokardiografia                              │ vv.kod in ['5744','5745','5746','5746b','5754']              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ POHOS                     │ Pripočitateľné položky                        │ vv.kod=='POHOS'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             500 │ 60                                                                                                        │                           │
│             310 │ 62                                                                                                        │                           │
│             250 │ 63                                                                                                        │                           │
│            2000 │ 5712                                                                                                      │                           │
│             450 │ 5713                                                                                                      │                           │
│             190 │ 1b                                                                                                        │                           │
│             160 │ 252b                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

