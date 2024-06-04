                                                                     ======================
                                                                     Cenník gastroenterolog
                                                                     ======================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬──────────────────────────────┐
│ Názov a hodnota       │ Popis                        │
├───────────────────────┼──────────────────────────────┤
│ IPP1 = 2.44           │ IPP1                         │
│ IPP2 = 3.92           │ IPP2                         │
│ IPP3 = 6.64           │ IPP3                         │
│ IPP4 = 6.64           │ IPP4                         │
│ IPPD = 5              │ IPPD                         │
│ LIMIT = 0             │ Limit                        │
│ EL_POBOCKA = 1        │ Používa el. pobočku ?        │
│ CB = 0.03466          │ Cena bodu                    │
│ CBP = 0.049           │ Cena bodu preventívne výkony │
│ CBSVALZ = 0.009159    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG          │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│           0.026 │ vv.bodyCelkom*cena        │ Prev. KS                                      │ vv.kod in ['765p']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon ŠAS                                     │ vv.kod in ['740','741','746','756','761','763','763a','765', │
│                 │                           │                                               │ '765p']                                                      │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763P','763M']                                    │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760SP','760SN','760PP','760PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763SP','763SN','763PP','763PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763p','763m']                                    │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│               5 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│            null │ vv.bodyCelkom*CB          │ Povrchová anestézia                           │ vv.kod in ['401']                                            │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5330','5331','5332','5300','5301','5303','5304', │
│                 │                           │                                               │ '5307','5307a','5312','5315','5316']                         │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│           15.54 │ vv.pocet*cena             │ Výkon 8899 - Stacionár                        │ vv.kod in ['8899']                                           │
│             435 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9104'] || vv.k in ['9104'] || vv.k25 in ['9104'] │
│             400 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9105'] || vv.k in ['9105'] || vv.k25 in ['9105'] │
│             228 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['8586'] || vv.k in ['8586'] || vv.k25 in ['8586'] │
│             454 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['8502'] || vv.k in ['8502'] || vv.k25 in ['8502'] │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ' && p.typ in ['BE','CU','EU']                 │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
│          0.0238 │ vv.bodyCelkom*cena        │ Výkony                                        │ 1                                                            │
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
│              40 │ 70                                                                                                        │                           │
│             100 │ 401                                                                                                       │                           │
│            3000 │ 763P                                                                                                      │                           │
│            3000 │ 763M                                                                                                      │                           │
│            1500 │ 760SP                                                                                                     │                           │
│            1500 │ 760SN                                                                                                     │                           │
│            1500 │ 760PP                                                                                                     │                           │
│            1500 │ 760PN                                                                                                     │                           │
│            3000 │ 763SP                                                                                                     │                           │
│            3000 │ 763SN                                                                                                     │                           │
│            3000 │ 763PP                                                                                                     │                           │
│            3000 │ 763PN                                                                                                     │                           │
│            3000 │ 763m                                                                                                      │                           │
│            3000 │ 763p                                                                                                      │                           │
│             946 │ 765p                                                                                                      │                           │
│            1500 │ 760sp                                                                                                     │                           │
│            1500 │ 760sn                                                                                                     │                           │
│            1500 │ 760pp                                                                                                     │                           │
│            1500 │ 760pn                                                                                                     │                           │
│            3000 │ 763sp                                                                                                     │                           │
│            3000 │ 763sn                                                                                                     │                           │
│            3000 │ 763pp                                                                                                     │                           │
│            3000 │ 763pn                                                                                                     │                           │
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
│ od zlou diagnózou               │            │ 763sn','763pp','763pn','763p','765p']                │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

