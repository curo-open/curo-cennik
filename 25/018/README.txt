                                                                    =======================
                                                                    Cenník dermatovenerolog
                                                                    =======================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IPP1 = 0.9      │ IPP1                  │
│ IPP2 = 1.16     │ IPP2                  │
│ IPP3 = 1.96     │ IPP3                  │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0202 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            2.98 │ vv.pocet*cena             │ Výkon 250x                                    │ vv.kod in ['250x']                                           │
│        0.011618 │ vv.bodyCelkom*cena        │ Výkon 509a;512;513;514a;516;518;522;523a;530; │ vv.kod in ['509a','512','513','514a','516','518','522','523a │
│                 │                           │ 531                                           │ ','530','531']                                               │
│        0.007635 │ vv.bodyCelkom*cena        │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│        0.011618 │ vv.bodyCelkom*cena        │ Výkon 532;533a;540;541;542                    │ vv.kod in ['532','533a','540','541','542']                   │
│           0.041 │ vv.bodyCelkom*cena        │ Výkon 760sp;760sn;760pp;760pn;763pp;763pn;763 │ vv.kod in ['760sp','760sn','760pp','760pn','763pp','763pn',' │
│                 │                           │ sp;763sn                                      │ 763sp','763sn']                                              │
│           0.022 │ vv.bodyCelkom*cena        │ Výkon 765p                                    │ vv.kod in ['765p']                                           │
│           0.022 │ vv.bodyCelkom*cena        │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│                 │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│                 │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│                 │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│        0.007635 │ vv.bodyCelkom*cena        │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│           0.022 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│           0.041 │ vv.bodyCelkom*cena        │ Preventívne vykony                            │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

