                                                                  ===========================
                                                                  Cenník pediatrická gastroen
                                                                  ===========================

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
│             407 │ vv.pocet*cena             │ Výkon 9104                                    │ vv.kod in ['9104'] || vv.k in ['9104'] || vv.k24 in ['9104'] │
│             357 │ vv.pocet*cena             │ Výkon 9105                                    │ vv.kod in ['9105'] || vv.k in ['9105'] || vv.k24 in ['9105'] │
│             273 │ vv.pocet*cena             │ Výkon 9100                                    │ vv.kod in ['9100'] || vv.k in ['9100'] || vv.k24 in ['9100'] │
│             229 │ vv.pocet*cena             │ Výkon 8502                                    │ vv.kod in ['8502'] || vv.k in ['8502'] || vv.k24 in ['8502'] │
│             432 │ vv.pocet*cena             │ Výkon 9101                                    │ vv.kod in ['9101'] || vv.k in ['9101'] || vv.k24 in ['9101'] │
│             382 │ vv.pocet*cena             │ Výkon 9103                                    │ vv.kod in ['9103'] || vv.k in ['9103'] || vv.k24 in ['9103'] │
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

