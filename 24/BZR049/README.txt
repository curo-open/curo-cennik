                                                                       ==================
                                                                       Cenník kardiologia
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────────┐
│ Názov a hodnota    │ Popis               │
├────────────────────┼─────────────────────┤
│ CB = 0.040975      │ Cena bodu           │
│ CBSVALZ = 0.009724 │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0     │ Cena bodu SVaLZ USG │
│ AGTC = 4.8         │ AGTC                │
│ PP50 = 10          │ PP50                │
│ LIMIT = 2235       │ Limit               │
└────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkony 60,62,63                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Výkon 15b - zhodnotenie odberov               │ vv.kod in ['15b']                                            │
│          0.0193 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 252                                     │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ Echokardiografia                              │ vv.kod in ['5744','5745','5746','5746b','5754']              │
│            null │ vv.bodyCelkom*CBSVALZ     │ EKG                                           │ vv.kod in ['5702']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Ergometria                                    │ vv.kod in ['5708']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Ekg holter                                    │ vv.kod in ['5712','5713','5714']                             │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│        0.024504 │ vv.bodyCelkom*cena        │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│        0.024504 │ vv.bodyCelkom*cena        │ Výkony                                        │ vv.kod in ['1']                                              │
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
│              50 │ 70                                                                                                        │                           │
│             190 │ 1b                                                                                                        │                           │
│            1200 │ 1c                                                                                                        │                           │
│             250 │ 11a                                                                                                       │                           │
│              50 │ 15d                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

