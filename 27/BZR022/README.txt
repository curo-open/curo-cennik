                                                                          ===========
                                                                          Cenník VLDD
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬─────────────────────────────┐
│ Názov a hodnota   │ Popis                       │
├───────────────────┼─────────────────────────────┤
│ IDK = NaN         │ NASTAVENIA IDK              │
│ CB = 0.00339      │ Cena bodu Kapitovany SK/EU  │
│ CBSVALZ = 0.00973 │ Cena bodu SVaLZ             │
│ CBEUNK = 0.0339   │ Cena bodu Nekapitovany      │
│ AGTC = 4.8        │ AGTC                        │
│ PP50 = 10         │ PP50                        │
└───────────────────┴─────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                   │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────────────┼───────────────┼──────────┼────────────────────┤
│ vek do 1 roku života    │          9.48 │ IDK+cena │ p|vekDo (1)        │
│ vek od 1 do 2 vrátane   │          7.45 │ IDK+cena │ p|vekMedzi(1, 3)   │
│ vek od 3 do 5 vrátane   │          7.18 │ IDK+cena │ p|vekMedzi(3, 6)   │
│ vek od 6 do 14 vrátane  │          4.96 │ IDK+cena │ p|vekMedzi(6, 15)  │
│ vek od 15 do 18 vrátane │          3.13 │ IDK+cena │ p|vekMedzi(15, 19) │
│ vek od 19 do 28 vrátane │          3.07 │ IDK+cena │ p|vekMedzi(19, 29) │
└─────────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b,11a,70                               │ vv.kod in ['1b','11a','70']                                  │
│           13.56 │ vv.pocet*cena             │ Výkon 10                                      │ vv.kod in ['10']                                             │
│          0.0339 │ vv.bodyCelkom*cena        │ Výkon 4,5,6,30                                │ vv.kod in ['4','5','6','30']                                 │
│          0.0339 │ vv.bodyCelkom*cena        │ Výkon 40,41                                   │ vv.kod in ['40','41']                                        │
│           0.079 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252a']                                           │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│            0.12 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['142']                                            │
│           0.079 │ vv.bodyCelkom*cena        │ Preventívne výkony                            │ vv.kod in ['143','143a','144','145','145a','146','146a','146 │
│                 │                           │                                               │ b','146c','148','148a','148b','148c','149','149a','149b','14 │
│                 │                           │                                               │ 9c','149d','149f','60','950','953']                          │
│           0.087 │ vv.bodyCelkom*cena        │ Preventívne výkony                            │ vv.kod in ['143','143a','144','145','145a','146','146a','146 │
│                 │                           │                                               │ b','146c','148']                                             │
│           0.079 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.079 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│           0.079 │ vv.bodyCelkom*cena        │ Výkon 951,952                                 │ vv.kod in ['951','952']                                      │
│          0.0339 │ vv.bodyCelkom*cena        │ Výkon 25,26,29                                │ vv.kod in ['25','26','29']                                   │
│           28.83 │ vv.pocet*cena             │ Výkon 160                                     │ vv.kod in ['160']                                            │
│            5.09 │ vv.pocet*cena             │ Výkon 60                                      │ vv.kod in ['60']                                             │
│              17 │ vv.pocet*cena             │ Výkon 60b                                     │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Výkon 62a                                     │ vv.kod in ['62a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 63                                      │ vv.kod in ['63']                                             │
│            4.63 │ vv.pocet*cena             │ Výkon 67                                      │ vv.kod in ['67']                                             │
│            4.97 │ vv.pocet*cena             │ Výkon 1544a                                   │ vv.kod in ['1544a']                                          │
│         0.00973 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│            5.36 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702Z']                                          │
│           0.015 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571a']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│            1.19 │ vv.pocet*cena             │ Delegovaný odber 250D                         │ vv.kod in ['250D']                                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
│             180 │ 950953                                                                                                    │                           │
│             180 │ 159a                                                                                                      │                           │
│             180 │ 159b                                                                                                      │                           │
│             180 │ 159x                                                                                                      │                           │
│             180 │ 159z                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

