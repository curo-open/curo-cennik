                                                                         ==============
                                                                         Cenník chirurg
                                                                         ==============

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
│             454 │ vv.pocet*cena             │ Výkon 8502                                    │ vv.kod in ['8502'] && vv.kod in ['8502']                     │
│             340 │ vv.pocet*cena             │ Výkon 8537                                    │ vv.kod in ['8537'] && vv.kod in ['8537']                     │
│             355 │ vv.pocet*cena             │ Výkon 8538                                    │ vv.kod in ['8538'] && vv.kod in ['8538']                     │
│             380 │ vv.pocet*cena             │ Výkon 8539                                    │ vv.kod in ['8539'] && vv.kod in ['8539']                     │
│             364 │ vv.pocet*cena             │ Výkon 8540                                    │ vv.kod in ['8540'] && vv.kod in ['8540']                     │
│              95 │ vv.pocet*cena             │ Výkon 8547                                    │ vv.kod in ['8547'] && vv.kod in ['8547']                     │
│             584 │ vv.pocet*cena             │ Výkon 8564                                    │ vv.kod in ['8564'] && vv.kod in ['8564']                     │
│             456 │ vv.pocet*cena             │ Výkon 8565                                    │ vv.kod in ['8565'] && vv.kod in ['8565']                     │
│             471 │ vv.pocet*cena             │ Výkon 8567                                    │ vv.kod in ['8567'] && vv.kod in ['8567']                     │
│             324 │ vv.pocet*cena             │ Výkon 8572                                    │ vv.kod in ['8572'] && vv.kod in ['8572']                     │
│              75 │ vv.pocet*cena             │ Výkon 8573                                    │ vv.kod in ['8573'] && vv.kod in ['8573']                     │
│             564 │ vv.pocet*cena             │ Výkon 8577                                    │ vv.kod in ['8577'] && vv.kod in ['8577']                     │
│             210 │ vv.pocet*cena             │ Výkon 8586                                    │ vv.kod in ['8586'] && vv.kod in ['8586']                     │
│             212 │ vv.pocet*cena             │ Výkon 8587                                    │ vv.kod in ['8587'] && vv.kod in ['8587']                     │
│             297 │ vv.pocet*cena             │ Výkon 8909                                    │ vv.kod in ['8909'] && vv.kod in ['8909']                     │
│             214 │ vv.pocet*cena             │ Výkon 8929                                    │ vv.kod in ['8929'] && vv.kod in ['8929']                     │
│             224 │ vv.pocet*cena             │ Výkon 9254                                    │ vv.kod in ['9254'] && vv.kod in ['9254']                     │
│             321 │ vv.pocet*cena             │ Výkon 9255                                    │ vv.kod in ['9255'] && vv.kod in ['9255']                     │
│             124 │ vv.pocet*cena             │ Výkon 9300                                    │ vv.kod in ['9300'] && vv.kod in ['9300']                     │
│             252 │ vv.pocet*cena             │ Výkon 9302                                    │ vv.kod in ['9302'] && vv.kod in ['9302']                     │
│             251 │ vv.pocet*cena             │ Výkon 9303                                    │ vv.kod in ['9303'] && vv.kod in ['9303']                     │
│             256 │ vv.pocet*cena             │ Výkon 9306                                    │ vv.kod in ['9306'] && vv.kod in ['9306']                     │
│             299 │ vv.pocet*cena             │ Výkon 9310                                    │ vv.kod in ['9310'] && vv.kod in ['9310']                     │
│             375 │ vv.pocet*cena             │ Výkon 8501A                                   │ vv.kod in ['8501A'] && vv.kod in ['8501A']                   │
│             630 │ vv.pocet*cena             │ Výkon 8501B                                   │ vv.kod in ['8501B'] && vv.kod in ['8501B']                   │
│             564 │ vv.pocet*cena             │ Výkon 8501C                                   │ vv.kod in ['8501C'] && vv.kod in ['8501C']                   │
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

