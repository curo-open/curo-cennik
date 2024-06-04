                                                                   =========================
                                                                   Cenník vnútorné lekárstvo
                                                                   =========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬───────────────────────┐
│ Názov a hodnota       │ Popis                 │
├───────────────────────┼───────────────────────┤
│ IPP1 = 2.44           │ IPP1                  │
│ IPP2 = 3.92           │ IPP2                  │
│ IPP3 = 6.64           │ IPP3                  │
│ IPP4 = 6.64           │ IPP4                  │
│ LIMIT = 75900         │ Limit                 │
│ EL_POBOCKA = 1        │ Používa el. pobočku ? │
│ CB = 0.03466          │ Cena bodu             │
│ CBSVALZ = 0.009159    │ Cena bodu SVaLZ       │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG   │
│ AGTC = 4.8            │ AGTC                  │
│ PP50 = 10             │ PP50                  │
└───────────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 60a                                     │ vv.kod in ['60a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│            null │ vv.bodyCelkom*CB          │ Zhodnotenie výsledkov                         │ vv.kod in ['15b']                                            │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│               5 │ vv.pocet*cena             │ Výkon 250x                                    │ vv.kod in ['250x']                                           │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a','299b']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ Zhodnotenie vyšetrení a zdrav.dokumentácie    │ vv.kod in ['5700']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ EKG                                           │ vv.kod in ['5702']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon 5715, 5716                              │ vv.kod in ['5715','5716']                                    │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             160 │ 1                                                                                                         │                           │
│             620 │ 60                                                                                                        │                           │
│             400 │ 62                                                                                                        │                           │
│             310 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│            1700 │ 5715                                                                                                      │                           │
│             400 │ 5716                                                                                                      │                           │
│             150 │ 15d                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

