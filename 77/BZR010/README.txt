                                                                        ================
                                                                        Cenník chirurgia
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬─────────────────┐
│ Názov a hodnota │ Popis           │
├─────────────────┼─────────────────┤
│ LIMIT = 0       │ Limit           │
│ CB = 0.045      │ Cena bodu       │
│ CBSVALZ = 0.015 │ Cena bodu SVaLZ │
│ IPP4 = 2.49     │ IPP4            │
│ IPP5 = 0.73     │ IPP5            │
│ IPP6 = 0.65     │ IPP7            │
└─────────────────┴─────────────────┘


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
│            null │ vv.bodyCelkom*CB          │ Výkon 15d                                     │ vv.kod in ['15d']                                            │
│            null │ vv.bodyCelkom*CB          │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5302                                    │ vv.kod in ['5302']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5330,5531,5332                          │ vv.kod in ['5330','5331','5332']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon SVALZ USG                               │ vv.kod in ['5300','5301','5303','5304','5307','5307a','5312' │
│                 │                           │                                               │ ,'5315','5316','5799']                                       │
│            null │ vv.bodyCelkom*CB          │ Odstránenie sutury alebo stehov z veľkej rany │ vv.kod in ['2007']                                           │
│            null │ vv.bodyCelkom*CB          │ Cirkulárny obväz hlavy, drieku                │ vv.kod in ['204']                                            │
│            null │ vv.bodyCelkom*CB          │ Ošetrenie malej rany hojacej sa per secundam  │ vv.kod in ['2018']                                           │
│            null │ vv.bodyCelkom*CB          │ Ošetrenie veľkej rany hojacej sa per secundam │ vv.kod in ['2018a']                                          │
│            null │ vv.bodyCelkom*CB          │ Príplatok za nekrektómie na ruke a nohe       │ vv.kod in ['2019']                                           │
│            null │ vv.bodyCelkom*CB          │ Príplatok za nekrektómie na trupe             │ vv.kod in ['2019c']                                          │
│            null │ vv.bodyCelkom*CB          │ Zavedenie jedného alebo viacerých drénov do r │ vv.kod in ['2030']                                           │
│                 │                           │ any                                           │                                                              │
│            null │ vv.bodyCelkom*CB          │ Zavedenie centrálneho cievneho katétra vrátan │ vv.kod in ['260']                                            │
│                 │                           │ e fixácie katétra a preväzu                   │                                                              │
│            null │ vv.bodyCelkom*CB          │ Zavedenie katétra do periférnej cievy         │ vv.kod in ['260a']                                           │
│            null │ vv.bodyCelkom*CB          │ Zhodnotenie výsledkov                         │ vv.kod in ['15b']                                            │
│            null │ vv.bodyCelkom*CB          │ Punkcia cysty, ganglia, serómu, hygrómu, hema │ vv.kod in ['303a']                                           │
│                 │                           │ tómu alebo abscesu                            │                                                              │
│            null │ vv.bodyCelkom*CB          │ Otvorenie abscesu ležiaceho povrchovo pod kož │ vv.kod in ['2141']                                           │
│                 │                           │ ou, sliznicou alebo excízia furunkla          │                                                              │
│            null │ vv.bodyCelkom*CB          │ Otvorenie hlboko ležiaceho abscesu            │ vv.kod in ['2145']                                           │
│            null │ vv.bodyCelkom*CB          │ Zavedenie jedného alebo viacerých drénov do r │ vv.kod in ['2030']                                           │
│                 │                           │ any                                           │                                                              │
│            null │ vv.bodyCelkom*CB          │ Intrakutánna, subkutánna, submukózna, subkonj │ vv.kod in ['252']                                            │
│                 │                           │ uktiválna alebo intramuskulárna injekcia.     │                                                              │
│            null │ vv.bodyCelkom*CB          │ Injekcia intravenózna                         │ vv.kod in ['253']                                            │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia v trvaní od 10 do 30 min │ vv.kod in ['271']                                            │
│                 │                           │ út                                            │                                                              │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia v trvaní viac ako 30 min │ vv.kod in ['272']                                            │
│                 │                           │ út                                            │                                                              │
│            null │ vv.bodyCelkom*CB          │ Odber krvi                                    │ vv.kod in ['250b']                                           │
│            null │ vv.bodyCelkom*CB          │ Stanovenie sedimentačnej rýchlosti krviniek   │ vv.kod in ['3592']                                           │
│            null │ vv.bodyCelkom*CB          │ Infiltračná anestézia                         │ vv.kod in ['407']                                            │
│            null │ vv.bodyCelkom*CB          │ Odber a odoslanie biologického materiálu      │ vv.kod in ['299d']                                           │
│            null │ IPP4                      │ Pripočitateľné položky                        │ vv.kod=='IPP4'                                               │
│            null │ IPP5                      │ Pripočitateľné položky                        │ vv.kod=='IPP5'                                               │
│            null │ IPP6                      │ Pripočitateľné položky                        │ vv.kod=='IPP6'                                               │
│            null │ vv.bodyCelkom*CB          │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│          0.0055 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5330','5331','5332'] && vv.typ!='SVaLZ'          │
│        0.012075 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ vv.kod in ['5793','5794','5795'] && vv.typ!='SVaLZ'          │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
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
│             150 │ 15d                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             480 │ 60r                                                                                                       │                           │
│            1300 │ 1A02072                                                                                                   │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

