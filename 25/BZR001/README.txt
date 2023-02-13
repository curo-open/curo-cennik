                                                                   =========================
                                                                   Cenník vnútorné lekárstvo
                                                                   =========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬───────────────────────┐
│ Názov a hodnota       │ Popis                 │
├───────────────────────┼───────────────────────┤
│ IPP1 = 1.19           │ IPP1                  │
│ IPP2 = 2.9            │ IPP2                  │
│ IPP3 = 4.9            │ IPP3                  │
│ IPP4 = 4.9            │ IPP4                  │
│ LIMIT = 75900         │ Limit                 │
│ EL_POBOCKA = 1        │ Používa el. pobočku ? │
│ CB = 0.0318           │ Cena bodu             │
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
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            2.98 │ vv.pocet*cena             │ Výkon 250x                                    │ vv.kod in ['250x']                                           │
│           0.035 │ vv.bodyCelkom*cena        │ Elektronická komunikácia                      │ vv.kod in ['11a','1b','70','1c']                             │
│        0.011618 │ vv.bodyCelkom*cena        │ Výkon 509a;512;513;514a;516;518;522;523a;530; │ vv.kod in ['509a','512','513','514a','516','518','522','523a │
│                 │                           │ 531                                           │ ','530','531']                                               │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5330','5331','5332','5300','5301','5303','5304', │
│                 │                           │                                               │ '5307','5307a','5312','5315','5316','5799']                  │
│        0.011618 │ vv.bodyCelkom*cena        │ Výkon 532;533a;540;541;542                    │ vv.kod in ['532','533a','540','541','542']                   │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 765p                                    │ vv.kod in ['765p']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 60;62;63                                │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 60;62;63                                │ vv.kod in ['62']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 60;62;63                                │ vv.kod in ['63']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 654                                     │ vv.kod in ['654']                                            │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon 5702, 5715, 5716                        │ vv.kod in ['5702','5715','5716']                             │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
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

