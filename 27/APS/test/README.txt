Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────┐
│ Názov a hodnota │ Popis │
└─────────────────┴───────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 4                                 │ d.typDoprava=="APOS" && vv.kod in ['4']                      │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 5                                 │ d.typDoprava=="APOS" && vv.kod in ['5']                      │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 6                                 │ d.typDoprava=="APOS" && vv.kod in ['6']                      │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 8                                 │ d.typDoprava=="APOS" && vv.kod in ['8']                      │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 15c                               │ d.typDoprava=="APOS" && vv.kod in ['15c']                    │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 64                                │ d.typDoprava=="APOS" && vv.kod in ['64']                     │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 71                                │ d.typDoprava=="APOS" && vv.kod in ['71']                     │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 252                               │ d.typDoprava=="APOS" && vv.kod in ['252']                    │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 253                               │ d.typDoprava=="APOS" && vv.kod in ['253']                    │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 603a                              │ d.typDoprava=="APOS" && vv.kod in ['603a']                   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 3525                              │ d.typDoprava=="APOS" && vv.kod in ['3525']                   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 3635a                             │ d.typDoprava=="APOS" && vv.kod in ['3635a']                  │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon APS - 4571a                             │ d.typDoprava=="APOS" && vv.kod in ['4571a']                  │
│              20 │ vv.pocet*cena             │ Výkon APS - 62a                               │ d.typDoprava=="APOS" && vv.kod in ['62a']                    │
│           0.027 │ vv.bodyCelkom*cena        │ Výkony APS                                    │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

