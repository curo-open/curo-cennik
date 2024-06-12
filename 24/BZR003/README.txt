                                                                 =============================
                                                                 Cenník pneumologia a ftizeolo
                                                                 =============================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────┐
│ Názov a hodnota    │ Popis           │
├────────────────────┼─────────────────┤
│ LIMIT = 240000     │ Limit           │
│ CB = 0.0338        │ Cena bodu       │
│ CBV = 0.026432     │ Cena bodu vv=60 │
│ CBSVALZ = 0.009724 │ Cena bodu SVaLZ │
└────────────────────┴─────────────────┘


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
│          0.0193 │ vv.bodyCelkom*cena        │ Zhodnotenie RTG dokumentácie                  │ vv.kod in ['15D']                                            │
│            null │ vv.bodyCelkom*CB          │ Interpretácia imunologického profilu          │ vv.kod in ['15f']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkony 60,62,63                               │ vv.kod in ['60','62','63']                                   │
│            null │ vv.bodyCelkom*CB          │ Výkony 65,66,67                               │ vv.kod in ['65','66','67']                                   │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['70','1b','1c','11a']                             │
│            null │ vv.bodyCelkom*CB          │ Odber venóznej krvi                           │ vv.kod in ['250a','250b']                                    │
│            null │ vv.bodyCelkom*CB          │ Sledovanie pacienta                           │ vv.kod in ['40']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 252                                     │ vv.kod in ['252']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia do 30min                 │ vv.kod in ['271']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia viac ako 30min           │ vv.kod in ['272']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 350-Prick testy                         │ vv.kod in ['350']                                            │
│         0.01892 │ vv.bodyCelkom*cena        │ Výkon 5766                                    │ vv.kod in ['5766']                                           │
│         0.01892 │ vv.bodyCelkom*cena        │ Výkon 5769                                    │ vv.kod in ['5769']                                           │
│         0.01892 │ vv.bodyCelkom*cena        │ Výkon 5770                                    │ vv.kod in ['5770']                                           │
│         0.01892 │ vv.bodyCelkom*cena        │ Výkon 5771                                    │ vv.kod in ['5771']                                           │
│         0.01892 │ vv.bodyCelkom*cena        │ Výkon 5772                                    │ vv.kod in ['5772']                                           │
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
│             220 │ 65                                                                                                        │                           │
│             350 │ 66                                                                                                        │                           │
│             220 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             900 │ 5766                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1200 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Výkon 250X nie je akceptovaný v │     0      │ p.vek >= 0                                           │ d.vv|ma('!(kod in ["250X"])')                        │
│ o Dôvere, použite 250a alebo 25 │            │                                                      │                                                      │
│ 0b                              │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

