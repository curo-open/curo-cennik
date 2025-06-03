                                                                       =================
                                                                       Cenník imunologia
                                                                       =================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬──────────────────────┐
│ Názov a hodnota      │ Popis                │
├──────────────────────┼──────────────────────┤
│ CB = 0.0391          │ Vypočitaná cena bodu │
│ CBSVALZ = 0.01031    │ Cena bodu SVaLZ      │
│ CBSVALZUSG = 0.01107 │ Cena bodu SVaLZ USG  │
│ IPP1 = 3.71          │ IPP1                 │
│ IPP2 = 3.18          │ IPP2                 │
│ IPP3 = 2.12          │ IPP3                 │
│ LIMIT = 0            │ Limit                │
└──────────────────────┴──────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Plánovanie terapeutických postupov            │ vv.kod in ['10']                                             │
│            null │ vv.bodyCelkom*CB          │ Edukácia k spirometrii                        │ vv.kod in ['10e']                                            │
│            null │ vv.bodyCelkom*CB          │ Zhodnotenie výsledkov                         │ vv.kod in ['15b']                                            │
│            null │ vv.bodyCelkom*CB          │ Interpretácia imunologického profilu          │ vv.kod in ['15f']                                            │
│          0.0435 │ vv.bodyCelkom*cena        │ Výkon 60,62,63                                │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkon 65,66,67                                │ vv.kod in ['65','66','67']                                   │
│           0.035 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Sledovanie pacienta                           │ vv.kod in ['40']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 252                                     │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia do 30min                 │ vv.kod in ['271']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia viac ako 30min           │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 350-Prick testy                         │ vv.kod in ['350']                                            │
│            8.95 │ vv.pocet*cena             │ Výkon 3860                                    │ vv.kod in ['3860']                                           │
│            10.2 │ vv.pocet*cena             │ Výkon 629b                                    │ vv.kod in ['629b']                                           │
│            6.06 │ vv.pocet*cena             │ Výkon H0007                                   │ vv.kod in ['H0007']                                          │
│            6.98 │ vv.pocet*cena             │ Výkon H0008                                   │ vv.kod in ['H0008']                                          │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon 5766                                    │ vv.kod in ['5766']                                           │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon 5769                                    │ vv.kod in ['5769']                                           │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon 5770                                    │ vv.kod in ['5770']                                           │
│         0.02463 │ vv.bodyCelkom*cena        │ Výkon 5771                                    │ vv.kod in ['5771']                                           │
│          0.0435 │ vv.bodyCelkom*cena        │ ŠAS                                           │ vv.kod in ['60','62','63'] && p.typ in ['EU']                │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ ŠAS                                           │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkon                                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CB          │  Iné ako SVALZ                                │ !vv.jeSVaZL                                                  │
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

