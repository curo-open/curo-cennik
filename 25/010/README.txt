                                                                         ==============
                                                                         Cenník chirurg
                                                                         ==============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬──────────────────────────────┐
│ Názov a hodnota       │ Popis                        │
├───────────────────────┼──────────────────────────────┤
│ IPP1 = 1.8            │ IPP1                         │
│ IPP2 = 2.9            │ IPP2                         │
│ IPP3 = 4.9            │ IPP3                         │
│ IPP4 = 4.9            │ IPP4                         │
│ IPPD = 5              │ IPPD                         │
│ LIMIT = 75900         │ Limit                        │
│ EL_POBOCKA = 1        │ Používa el. pobočku ?        │
│ CB = 0.0268           │ Cena bodu                    │
│ CBP = 0.041           │ Cena bodu preventívne výkony │
│ CBE = 0.026           │ Cena bodu el. výkony         │
│ CBSVALZ = 0.008105    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.008473 │ Cena bodu SVaLZ USG          │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            2.98 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│                 │ vv.bodyCelkom*CBE         │ ŠAS el. výkony                                │ vv.kod in ['1b','1c','70','11a']                             │
│                 │ vv.bodyCelkom*CBE         │ ŠAS                                           │ vv.kod in ['15d']                                            │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│                 │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│                 │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│                 │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│                 │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│                 │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
│                 │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│                 │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│                 │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│                 │ vv.bodyCelkom*CB          │ Výkon 1                                       │                                                              │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             160 │ 1                                                                                                         │                           │
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1000 │ 68a                                                                                                       │                           │
│             150 │ 15d                                                                                                       │                           │
│            1500 │ 760SP                                                                                                     │                           │
│            1500 │ 760SN                                                                                                     │                           │
│            1500 │ 760PP                                                                                                     │                           │
│            1500 │ 760PN                                                                                                     │                           │
│            3000 │ 763SP                                                                                                     │                           │
│            3000 │ 763SN                                                                                                     │                           │
│            3000 │ 763PP                                                                                                     │                           │
│            3000 │ 763PN                                                                                                     │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

