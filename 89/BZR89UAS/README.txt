                                                                       ==================
                                                                       Cenník specialista
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬──────────────────────────────┐
│ Názov a hodnota       │ Popis                        │
├───────────────────────┼──────────────────────────────┤
│ IPP1 = 2.48           │ IPP1                         │
│ IPP2 = 3.98           │ IPP2                         │
│ IPP3 = 6.74           │ IPP3                         │
│ IPP4 = 6.71           │ IPP4                         │
│ IPPD = 5              │ IPPD                         │
│ LIMIT = 0             │ Limit                        │
│ EL_POBOCKA = 1        │ Používa el. pobočku ?        │
│ CB = 0.03553          │ Cena bodu                    │
│ CBP = 0.041           │ Cena bodu preventívne výkony │
│ CBSVALZ = 0.009159    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG          │
│ CBEU = 0.007303       │ Cena bodu EU                 │
│ CB50XX = 0.015336     │ Cena bodu 50XX               │
│ PACS = 0.93           │ PACS                         │
│ X03501 = 32           │ X03501                       │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│           11.82 │ vv.pocet*cena             │ Výkon 60U                                     │ vv.kod in ['60U','60u']                                      │
│             7.6 │ vv.pocet*cena             │ Výkon 62U                                     │ vv.kod in ['62U','62u']                                      │
│            5.91 │ vv.pocet*cena             │ Výkon 63U                                     │ vv.kod in ['63U','63u']                                      │
│        0.005311 │ vv.bodyCelkom*cena        │ Denzitometria                                 │ vv.kod in ['5331']                                           │
│            null │ vv.bodyCelkom*CB          │ Mamografia                                    │ vv.kod in ['5092','5092a']                                   │
│            null │ vv.bodyCelkom*CB          │ RTG                                           │ vv.kod in ['5010','5011','5012','5015','5016','5020','5021', │
│                 │                           │                                               │ '5022','5023','5024','5025','5030','5031','5032','5033','503 │
│                 │                           │                                               │ 5','5050','5051','5052','5053','5056','5060','5061','5062',' │
│                 │                           │                                               │ 5065','5070','5071','5072','5075','5076','5077','5080','5081 │
│                 │                           │                                               │ ','5082','5083','5090','5095','5051R']                       │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ USG                                           │ vv.kod in ['5300','5301','5302','5303','5306','5307','5308', │
│                 │                           │                                               │ '5309','5310','5312','5315','5316','5742','5743','5739','573 │
│                 │                           │                                               │ 8','5153a']                                                  │
│            null │ PACS                      │ Pripočitateľné položky  - PACS                │ vv.kod=='PACS'                                               │
│            null │ X03501                    │ Pripočitateľné položky  - Bioptická ihla      │ vv.kod=='X03501'                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Elektronická komunikácia                      │ vv.kod in ['11a','1b','70','1c']                             │
│           0.026 │ vv.bodyCelkom*cena        │ Prev. KS                                      │ vv.kod in ['765p']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon ŠAS                                     │ vv.kod in ['740','741','746','756','761','763','763a','765'] │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763P','763M']                                    │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760SP','760SN','760PP','760PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763SP','763SN','763PP','763PN']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763p','763m']                                    │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['760sp','760sn','760pp','760pn']                  │
│            null │ vv.bodyCelkom*CBP         │ Prev. KS                                      │ vv.kod in ['763sp','763sn','763pp','763pn']                  │
│               5 │ vv.pocet*cena             │ ŠAS                                           │ vv.kod in ['250x']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZUSG  │ Výkon SVALZ USG                               │ vv.kod in ['5330','5331','5332','5300','5301','5303','5304', │
│                 │                           │                                               │ '5307','5307a','5312','5315','5316']                         │
│           0.026 │ vv.bodyCelkom*cena        │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│           15.54 │ vv.pocet*cena             │ Výkon 8899 - Stacionár                        │ vv.kod in ['8899']                                           │
│             428 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9104']                                           │
│             393 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['9105']                                           │
│             224 │ vv.pocet*cena             │ JZS                                           │ vv.kod in ['8586']                                           │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ' && p.typ in ['BE','CU','EU']                 │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
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
│              40 │ 70                                                                                                        │                           │
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

