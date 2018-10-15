                                                                  ===========================
                                                                  Cenník klinicka psychologia
                                                                  ===========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IPP1 = 0.9      │ IPP1                  │
│ IPP2 = 1.16     │ IPP2                  │
│ IPP3 = 1.96     │ IPP3                  │
│ LIMIT = 75900   │ Limit                 │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0238 │ vv.pocet*420*cena         │ Výkon 60;62;63                                │ vv.kod in ['60'] && EL_POBOCKA                               │
│          0.0238 │ vv.pocet*270*cena         │ Výkon 60;62;63                                │ vv.kod in ['62'] && EL_POBOCKA                               │
│          0.0238 │ vv.pocet*210*cena         │ Výkon 60;62;63                                │ vv.kod in ['63'] && EL_POBOCKA                               │
│          0.0237 │ vv.pocet*420*cena         │ Výkon 60;62;63                                │ vv.kod in ['60']                                             │
│          0.0237 │ vv.pocet*270*cena         │ Výkon 60;62;63                                │ vv.kod in ['62']                                             │
│          0.0237 │ vv.pocet*210*cena         │ Výkon 60;62;63                                │ vv.kod in ['63']                                             │
│                 │ IPP1                      │ Pripočitateľné položky                        │ vv.kod=='IPP1'                                               │
│                 │ IPP2                      │ Pripočitateľné položky                        │ vv.kod=='IPP2'                                               │
│                 │ IPP3                      │ Pripočitateľné položky                        │ vv.kod=='IPP3'                                               │
│          0.0238 │ vv.bodyCelkom*cena        │ Výkony - Bezdomovec, Cudzinec, EU             │ EL_POBOCKA && p.typ in ['BE','CU','EU']                      │
│          0.0237 │ vv.bodyCelkom*cena        │ Výkony - Bezdomovec, Cudzinec, EU             │ p.typ in ['BE','CU','EU']                                    │
│          0.0238 │ vv.bodyCelkom*cena        │ Výkony                                        │ EL_POBOCKA                                                   │
│          0.0237 │ vv.bodyCelkom*cena        │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

