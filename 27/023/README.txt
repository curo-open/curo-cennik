                                                                       =================
                                                                       Cenník radiologia
                                                                       =================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────┬─────────────────┐
│ Názov a hodnota  │ Popis           │
├──────────────────┼─────────────────┤
│ LIMIT = 0        │ Limit           │
│ CB = 0.007838    │ Cena bodu       │
│ CBSVALZ = 0.0073 │ Cena bodu SVALZ │
│ CBEU = 0.007838  │ Cena bodu EU    │
│ X03501 = 32      │ X03501          │
│ X03853 = 20.5    │ X03853          │
└──────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon                                         │ vv.kod in ['65']                                             │
│          0.0055 │ vv.bodyCelkom*cena        │ Denzitometria                                 │ vv.kod in ['5331']                                           │
│          0.0096 │ vv.bodyCelkom*cena        │ Mamografia                                    │ vv.kod in ['5092','5092a']                                   │
│          0.0117 │ vv.bodyCelkom*cena        │ RTG                                           │ vv.kod in ['5010','5011','5012','5015','5016','5020','5021', │
│                 │                           │                                               │ '5022','5023','5024','5025','5030','5031','5032','5033','503 │
│                 │                           │                                               │ 5','5050','5051','5052','5053','5056','5060','5061','5062',' │
│                 │                           │                                               │ 5065','5070','5071','5072','5075','5076','5077','5080','5081 │
│                 │                           │                                               │ ','5082','5083','5090','5095','5051R']                       │
│          0.0081 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5300','5301','5302','5303','5306','5307','5308', │
│                 │                           │                                               │ '5309','5310','5312','5315','5316','5742','5743','5739','573 │
│                 │                           │                                               │ 8','5153a']                                                  │
│              30 │ vv.pocet*cena             │ Skríningová mamografia                        │ vv.kod in ['1301','1301a','1301b','1301c','1301d','1301e']   │
│            null │ X03501                    │ Pripočitateľné položky  - Bioptická ihla      │ vv.kod=='X03501'                                             │
│            null │ X03853                    │ Pripočitateľné položky  - Bioptická ihla      │ vv.kod=='X03853'                                             │
│            null │ vv.bodyCelkom*CBEU        │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ vv.typ!='SVaLZ'                                              │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             200 │ 65                                                                                                        │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

