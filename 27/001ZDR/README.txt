                                                                   =========================
                                                                   Cenník vnútorné lekárstvo
                                                                   =========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬──────────────────────────────┐
│ Názov a hodnota   │ Popis                        │
├───────────────────┼──────────────────────────────┤
│ CB = 0.0323       │ Cena bodu                    │
│ CBO = 0.0365      │ Cena bodu ostatné ŠAS výkony │
│ CBSVALZ = 0.01031 │ Cena bodu SVaLZ              │
│ CBUSG = 0.0088    │ Cena bodu USG                │
│ NCB = 0           │ Navysena cena bodu           │
│ IPP4 = 5.83       │ IPP4                         │
│ IPP5 = 4.24       │ IPP5                         │
│ IPP6 = 3.18       │ IPP6                         │
│ AGTC = 4.8        │ AGTC                         │
│ LIMIT = 0         │ Limit                        │
└───────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon 1a                                      │ vv.kod in ['1a']                                             │
│        0.007303 │ vv.bodyCelkom*cena        │ Výkon 509a;512;513;514a;516;518;522;523a;530; │ vv.kod in ['509a','512','513','514a','516','518','522','523a │
│                 │                           │ 531                                           │ ','530','531']                                               │
│        0.007303 │ vv.bodyCelkom*cena        │ Výkon 532;533a;540;541;542                    │ vv.kod in ['532','533a','540','541','542']                   │
│           0.035 │ vv.bodyCelkom*cena        │ Elektronická komunikácia                      │ vv.kod in ['11a','1b','70','1c']                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon `60,`62,`63                             │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon `60r                                    │ vv.kod in ['60r']                                            │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon `65,`66,`67                             │ vv.kod in ['65','66','67']                                   │
│            64.5 │ vv.pocet*cena             │ Výkon 760sp;760sn;760pp;760pn                 │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│             129 │ vv.pocet*cena             │ Výkon 763p                                    │ vv.kod in ['763p']                                           │
│             129 │ vv.pocet*cena             │ Výkon 763sp;763sn;763pp;763pn                 │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│               5 │ vv.pocet*cena             │ Výkon Y0018                                   │ vv.kod in ['Y0018']                                          │
│            4.56 │ vv.pocet*cena             │ Výkon Y0023                                   │ vv.kod in ['Y0023']                                          │
│         0.01107 │ vv.bodyCelkom*cena        │ Výkon 5153a;5153b;5333                        │ vv.kod in ['5153a','5153b','5333']                           │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkon 5330;5331;5332                          │ vv.kod in ['5330','5331','5332']                             │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkony 5727                                   │ vv.kod in ['5727']                                           │
│         0.01275 │ vv.bodyCelkom*cena        │ Výkon 5793;5794;5795                          │ vv.kod in ['5793','5794','5795']                             │
│            6.06 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            8.95 │ vv.bodyCelkom*cena        │ Stanovenie hodnoty NT-proBNP                  │ vv.kod in ['3860']                                           │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
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
│            3292 │ 741                                                                                                       │                           │
│             480 │ 60r                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             900 │ 62b                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

