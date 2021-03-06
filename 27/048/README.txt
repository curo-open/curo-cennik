                                                                     ======================
                                                                     Cenník gastroenterolog
                                                                     ======================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────┬──────────────────────────────┐
│ Názov a hodnota  │ Popis                        │
├──────────────────┼──────────────────────────────┤
│ CB = 0.0285      │ Cena bodu                    │
│ CBP = 0.0455     │ Cena bodu preventívne výkony │
│ CBSVALZ = 0.0082 │ Cena bodu SVaLZ              │
│ LIMIT = 0        │ Limit                        │
└──────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            9.41 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['60']                                             │
│            6.05 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['62']                                             │
│             4.7 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['63']                                             │
│            9.41 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['60r']                                            │
│            3.36 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['65'] && p|vekMedzi(0, 5)                         │
│          0.0224 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['65']                                             │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760SP','760SN','760PP','760PN']                  │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763SP','763SN','763PP','763PN']                  │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│                 │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│           0.045 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['763p']                                           │
│             254 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['8586']                                           │
│          378.23 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9104']                                           │
│             297 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9105']                                           │
│        0.006666 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['15d']                                            │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkon 5330,5331,5332                          │ vv.kod in ['5330','5331','5332']                             │
│        0.012083 │ vv.bodyCelkom*cena        │ Výkon 5793,5794,5795                          │ vv.kod in ['5793','5794','5795']                             │
│           14.99 │ vv.pocet*cena             │ Výkon 8899 - Stacionár                        │ vv.kod in ['8899']                                           │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│                 │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.kod in ['5300','5301','5702']                             │
│           0.022 │ vv.bodyCelkom*cena        │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│                 │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│                 │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
│               0 │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│            1500 │ 760sp                                                                                                     │                           │
│            1500 │ 760sn                                                                                                     │                           │
│            1500 │ 760pp                                                                                                     │                           │
│            1500 │ 760pn                                                                                                     │                           │
│            3000 │ 763sp                                                                                                     │                           │
│            3000 │ 763sn                                                                                                     │                           │
│            3000 │ 763pp                                                                                                     │                           │
│            3000 │ 763pn                                                                                                     │                           │
│            3000 │ 763p                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1000 │ 68a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│            0.95 │ 62328                                                                                                     │ liek                      │
│            1.15 │ 62329                                                                                                     │ liek                      │
│           133.1 │ 02578                                                                                                     │ liek                      │
│         2012.24 │ 0358b                                                                                                     │ liek                      │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Výkony 760*, 763* sú vykázané p │     0      │ vv.kod in ['760sp','760sn','760pp','760pn','763sp',' │ vv.diagnoza in ['Z12.1']                             │
│ od zlou diagnózou               │            │ 763sn','763pp','763pn','763p']                       │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

