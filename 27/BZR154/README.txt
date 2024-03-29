                                                                 =============================
                                                                 Cenník pediatrická gastroente
                                                                 =============================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬─────────────────┐
│ Názov a hodnota   │ Popis           │
├───────────────────┼─────────────────┤
│ LIMIT = 2235      │ Limit           │
│ CB = 0.0355       │ Cena bodu       │
│ CBSVALZ = 0.00973 │ Cena bodu SVaLZ │
│ IPP4 = 5.5        │ IPP4            │
│ IPP5 = 4          │ IPP5            │
│ IPP6 = 3          │ IPP6            │
└───────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0385 │ vv.bodyCelkom*cena        │ Výkony 60,62,63                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkony 65,66,67                               │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│            null │ vv.bodyCelkom*CB          │ Výkon ŠAS                                     │ vv.kod in ['732','735','736','737']                          │
│          0.1035 │ vv.bodyCelkom*cena        │ Výkon ŠAS                                     │ vv.kod in ['740','741','745','745A','745B','746','755','756' │
│                 │                           │                                               │ ,'760','761','762','763','763A']                             │
│          0.1035 │ vv.bodyCelkom*cena        │ Výkon ŠAS                                     │ vv.kod in ['360','361','363','364','365','366','367']        │
│          0.0226 │ vv.bodyCelkom*cena        │ Výkon ŠAS                                     │ vv.kod in ['5793','5794','5795']                             │
│           0.015 │ vv.bodyCelkom*cena        │ Výkon 4571a                                   │ vv.kod in ['4571a']                                          │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            null │ vv.bodyCelkom*CB          │ Plánovanie terapeutických postupov            │ vv.kod in ['10']                                             │
│           0.055 │ vv.bodyCelkom*cena        │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│           0.055 │ vv.bodyCelkom*cena        │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│         0.01044 │ vv.bodyCelkom*cena        │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5316']                             │
│            null │ vv.bodyCelkom*cena        │ Výkon 15b - Zhodnotenie výsledkov             │ vv.kod in ['15b']                                            │
│            null │ vv.bodyCelkom*CB          │ Infúzia                                       │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a','299b']                                    │
│            null │ vv.bodyCelkom*CB          │ Injekcia                                      │ vv.kod in ['253']                                            │
│            null │ vv.bodyCelkom*CB          │ Anestézia                                     │ vv.kod in ['81']                                             │
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
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             900 │ 62b                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             150 │ 15d                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

