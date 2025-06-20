                                                                    =======================
                                                                    Cenník dermatovenerolog
                                                                    =======================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬─────────────────────────────────────────────────────────┐
│ Názov a hodnota      │ Popis                                                   │
├──────────────────────┼─────────────────────────────────────────────────────────┤
│ CB = 0.0391          │ Cena bodu                                               │
│ CBE = 0.035          │ Cena bodu el. výkony                                    │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ                                         │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ - ULTRAZVUK – USG a FUNKČNÁ DIAGNOSTIKA │
│ IPP1 = 3.71          │ IPP1                                                    │
│ IPP2 = 3.18          │ IPP2                                                    │
│ IPP3 = 2.12          │ IPP3                                                    │
│ NCB = 0              │ Navysena cena bodu                                      │
└──────────────────────┴─────────────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│            null │ IPP7                      │ Pripočitateľné položky                        │ vv.kod=='IPP7'                                               │
│            2.98 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│          0.0435 │ vv.bodyCelkom*cena        │ Výkon 60,62,63,                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│          0.0415 │ vv.bodyCelkom*cena        │ Výkon 2018,2018a,2100                         │ vv.kod in ['2018','2018a','2100']                            │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','11a','70']                                  │
│          0.0158 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 1                                       │ vv.kod in ['1']                                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Vykony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              80 │ 1                                                                                                         │                           │
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             480 │ 60r                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
│             380 │ 4571a                                                                                                     │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

