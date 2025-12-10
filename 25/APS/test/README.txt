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
│             0.5 │ vv.pocet*cena             │ DOPRAVA:  do 60 km APSD                       │ d.typDoprava=="APSD" && vv.kod in ['doprava'] && vv.pocet <  │
│                 │                           │                                               │ 60                                                           │
│            0.25 │ vv.pocet*cena             │ DOPRAVA:  + 60 km LSPR                        │ d.typDoprava=="LSPR" && vv.kod in ['doprava'] && vv.pocet <  │
│                 │                           │                                               │ 60                                                           │
│            null │ vv.pocet*CBD              │ DOPRAVA:  do 60 km                            │ vv.kod in ['doprava'] && vv.pocet < 60                       │
│            null │ vv.pocet*CBD60plus        │ DOPRAVA:  + 60 km                             │ vv.kod in ['doprava'] && vv.pocet >= 60                      │
│             4.8 │ vv.pocet*cena             │ Výkon APS - 4                                 │ d.typDoprava=="APOS" && vv.kod in ['4']                      │
│             8.4 │ vv.pocet*cena             │ Výkon APS - 5                                 │ d.typDoprava=="APOS" && vv.kod in ['5']                      │
│             9.6 │ vv.pocet*cena             │ Výkon APS - 6                                 │ d.typDoprava=="APOS" && vv.kod in ['6']                      │
│               6 │ vv.pocet*cena             │ Výkon APS - 8                                 │ d.typDoprava=="APOS" && vv.kod in ['8']                      │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 15c                               │ d.typDoprava=="APOS" && vv.kod in ['15c']                    │
│              12 │ vv.pocet*cena             │ Výkon APS - 26                                │ d.typDoprava=="APOS" && vv.kod in ['26']                     │
│            21.6 │ vv.pocet*cena             │ Výkon APS - 29                                │ d.typDoprava=="APOS" && vv.kod in ['29']                     │
│            10.8 │ vv.pocet*cena             │ Výkon APS - 30                                │ d.typDoprava=="APOS" && vv.kod in ['30']                     │
│            1.68 │ vv.pocet*cena             │ Výkon APS - 64                                │ d.typDoprava=="APOS" && vv.kod in ['64']                     │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 67                                │ d.typDoprava=="APOS" && vv.kod in ['67']                     │
│            0.84 │ vv.pocet*cena             │ Výkon APS - 71                                │ d.typDoprava=="APOS" && vv.kod in ['71']                     │
│            1.08 │ vv.pocet*cena             │ Výkon APS - 71b                               │ d.typDoprava=="APOS" && vv.kod in ['71b']                    │
│            1.68 │ vv.pocet*cena             │ Výkon APS - 200                               │ d.typDoprava=="APOS" && vv.kod in ['200']                    │
│             9.6 │ vv.pocet*cena             │ Výkon APS - 201                               │ d.typDoprava=="APOS" && vv.kod in ['201']                    │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 204                               │ d.typDoprava=="APOS" && vv.kod in ['204']                    │
│            1.68 │ vv.pocet*cena             │ Výkon APS - 206                               │ d.typDoprava=="APOS" && vv.kod in ['206']                    │
│            2.88 │ vv.pocet*cena             │ Výkon APS - 207                               │ d.typDoprava=="APOS" && vv.kod in ['207']                    │
│             1.8 │ vv.pocet*cena             │ Výkon APS - 210                               │ d.typDoprava=="APOS" && vv.kod in ['210']                    │
│            4.32 │ vv.pocet*cena             │ Výkon APS - 212                               │ d.typDoprava=="APOS" && vv.kod in ['212']                    │
│            1.92 │ vv.pocet*cena             │ Výkon APS - 250a                              │ d.typDoprava=="APOS" && vv.kod in ['250a']                   │
│             3.6 │ vv.pocet*cena             │ Výkon APS - 250b                              │ d.typDoprava=="APOS" && vv.kod in ['250b']                   │
│            1.68 │ vv.pocet*cena             │ Výkon APS - 252                               │ d.typDoprava=="APOS" && vv.kod in ['252']                    │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 253                               │ d.typDoprava=="APOS" && vv.kod in ['253']                    │
│            1.44 │ vv.pocet*cena             │ Výkon APS - 258                               │ d.typDoprava=="APOS" && vv.kod in ['258']                    │
│             3.6 │ vv.pocet*cena             │ Výkon APS - 260a                              │ d.typDoprava=="APOS" && vv.kod in ['260a']                   │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 267                               │ d.typDoprava=="APOS" && vv.kod in ['267']                    │
│             4.8 │ vv.pocet*cena             │ Výkon APS - 271                               │ d.typDoprava=="APOS" && vv.kod in ['271']                    │
│             3.6 │ vv.pocet*cena             │ Výkon APS - 320                               │ d.typDoprava=="APOS" && vv.kod in ['320']                    │
│             8.4 │ vv.pocet*cena             │ Výkon APS - 321                               │ d.typDoprava=="APOS" && vv.kod in ['321']                    │
│             4.8 │ vv.pocet*cena             │ Výkon APS - 322                               │ d.typDoprava=="APOS" && vv.kod in ['322']                    │
│              12 │ vv.pocet*cena             │ Výkon APS - 323                               │ d.typDoprava=="APOS" && vv.kod in ['323']                    │
│            5.28 │ vv.pocet*cena             │ Výkon APS - 330                               │ d.typDoprava=="APOS" && vv.kod in ['330']                    │
│            0.72 │ vv.pocet*cena             │ Výkon APS - 332                               │ d.typDoprava=="APOS" && vv.kod in ['332']                    │
│            3.84 │ vv.pocet*cena             │ Výkon APS - 363                               │ d.typDoprava=="APOS" && vv.kod in ['363']                    │
│             3.6 │ vv.pocet*cena             │ Výkon APS - 603a                              │ d.typDoprava=="APOS" && vv.kod in ['603a']                   │
│            0.72 │ vv.pocet*cena             │ Výkon APS - 1275                              │ d.typDoprava=="APOS" && vv.kod in ['1275']                   │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 1402                              │ d.typDoprava=="APOS" && vv.kod in ['1402']                   │
│             2.4 │ vv.pocet*cena             │ Výkon APS - 2000                              │ d.typDoprava=="APOS" && vv.kod in ['2000']                   │
│            4.08 │ vv.pocet*cena             │ Výkon APS - 2003                              │ d.typDoprava=="APOS" && vv.kod in ['2003']                   │
│               6 │ vv.pocet*cena             │ Výkon APS - 2011                              │ d.typDoprava=="APOS" && vv.kod in ['2011']                   │
│             3.6 │ vv.pocet*cena             │ Výkon APS - 2011a                             │ d.typDoprava=="APOS" && vv.kod in ['2011a']                  │
│             1.2 │ vv.pocet*cena             │ Výkon APS - 3525                              │ d.typDoprava=="APOS" && vv.kod in ['3525']                   │
│            0.84 │ vv.pocet*cena             │ Výkon APS - 3526                              │ d.typDoprava=="APOS" && vv.kod in ['3526']                   │
│            1.44 │ vv.pocet*cena             │ Výkon APS - 3635a                             │ d.typDoprava=="APOS" && vv.kod in ['3635a']                  │
│            5.75 │ vv.pocet*cena             │ Výkon APS - 4571a                             │ d.typDoprava=="APOS" && vv.kod in ['4571a']                  │
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

