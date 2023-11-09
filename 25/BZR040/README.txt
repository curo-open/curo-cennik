                                                                       =================
                                                                       Cenník imunologia
                                                                       =================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬─────────────────────┐
│ Názov a hodnota       │ Popis               │
├───────────────────────┼─────────────────────┤
│ IPP1 = 1.34           │ IPP1                │
│ IPP2 = 2.9            │ IPP2                │
│ IPP3 = 4.9            │ IPP3                │
│ IPP4 = 7.9            │ IPP4                │
│ IPPD = 5              │ IPPD                │
│ LIMIT = 0             │ Limit               │
│ CB = 0.0318           │ Cena bodu           │
│ CBSVALZ = 0.009159    │ Cena bodu SVaLZ     │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG │
└───────────────────────┴─────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Plánovanie terapeutických postupov            │ vv.kod in ['10']                                             │
│            null │ vv.bodyCelkom*CB          │ Zhodnotenie výsledkov                         │ vv.kod in ['15b']                                            │
│            null │ vv.bodyCelkom*CB          │ Interpretácia imunologického profilu          │ vv.kod in ['15f']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkony 60,62,63                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkony 65,66,67                               │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70','1c']                             │
│               5 │ vv.pocet*cena             │ Odber venóznej krvi                           │ vv.kod in ['250x']                                           │
│            null │ vv.bodyCelkom*CB          │ Odber biol.materiálu                          │ vv.kod in ['299a']                                           │
│            null │ vv.bodyCelkom*CB          │ Sledovanie pacienta                           │ vv.kod in ['40']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 252                                     │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia do 30min                 │ vv.kod in ['271']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia viac ako 30min           │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 350-Prick testy                         │ vv.kod in ['350']                                            │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta pri pandémii COVI │ vv.kod in ['62a','62b']                                      │
│                 │                           │ D-19                                          │                                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ vv.kod in ['1A02060','1A02077','1A03044','1A01033','40']     │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkony                                        │ vv.kod in ['4H00001','4H00004','4H00005']                    │
│            null │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│            null │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│            null │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPPD                      │ Pripočitateľné položky                        │ vv.kod=='IPPD'                                               │
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
│             200 │ 40                                                                                                        │                           │
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             210 │ 15d                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│            1640 │ 4H00001                                                                                                   │                           │
│            2400 │ 4H00004                                                                                                   │                           │
│            1750 │ 4H00005                                                                                                   │                           │
│             525 │ 1A01033                                                                                                   │                           │
│             340 │ 1A02060                                                                                                   │                           │
│             900 │ 1A02077                                                                                                   │                           │
│             260 │ 1A03044                                                                                                   │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Výkon 250a,b nie je akceptovaný │     0      │ p.vek >= 0                                           │ !d.vv|ma('kod in ["250a","250b"]')                   │
│ vo VšZP, použite 250X           │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

