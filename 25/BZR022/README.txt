                                                                          ===========
                                                                          Cenník VLDD
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────────────────┐
│ Názov a hodnota    │ Popis                       │
├────────────────────┼─────────────────────────────┤
│ IDK = 0.65         │ NASTAVENIA IDK              │
│ CB = 0.0318        │ Cena bodu Kapitovany SK/EU  │
│ CBSVALZ = 0.009574 │ Cena bodu SVaLZ             │
│ CBEUNK = 0.0339    │ Cena bodu Nekapitovany      │
│ AGTC = 4.8         │ AGTC                        │
│ PP50 = 10          │ PP50                        │
└────────────────────┴─────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                   │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────────────┼───────────────┼──────────┼────────────────────┤
│ vek do 1 roku života    │         10.51 │ IDK+cena │ p|vekDo (1)        │
│ vek od 1 do 2 vrátane   │         10.42 │ IDK+cena │ p|vekMedzi(1, 3)   │
│ vek od 3 do 5 vrátane   │          7.21 │ IDK+cena │ p|vekMedzi(3, 6)   │
│ vek od 6 do 9 vrátane   │          5.21 │ IDK+cena │ p|vekMedzi(6, 10)  │
│ vek od 10 do 14 vrátane │          4.77 │ IDK+cena │ p|vekMedzi(10, 15) │
│ vek od 15 do 17 vrátane │           4.5 │ IDK+cena │ p|vekMedzi(15, 18) │
│ vek od 18 do 19 vrátane │          4.05 │ IDK+cena │ p|vekMedzi(18, 20) │
│ vek od 20 do 28 vrátane │          3.22 │ IDK+cena │ p|vekMedzi(20, 29) │
└─────────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b,11a,70                               │ vv.kod in ['1b','11a','70']                                  │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
│          0.0339 │ vv.bodyCelkom*cena        │ Výkon 25,26                                   │ vv.kod in ['25','26']                                        │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 60                                      │ vv.kod in ['60']                                             │
│              16 │ vv.pocet*cena             │ Výkon 60b                                     │ vv.kod in ['60b']                                            │
│              20 │ vv.pocet*cena             │ Výkon 62a                                     │ vv.kod in ['62a']                                            │
│           0.029 │ vv.bodyCelkom*cena        │ Výkon 67                                      │ vv.kod in ['67']                                             │
│            0.08 │ vv.bodyCelkom*cena        │ Výkon 950,951,952,953                         │ vv.kod in ['950','951','952','953']                          │
│           0.079 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252a','252b','252c']                             │
│         0.11187 │ vv.bodyCelkom*cena        │ 1.preventívna prehliadka u VLDD               │ vv.kod in ['142']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ Preventívne výkony                            │ vv.kod in ['143','143a','144','145','145a','146','146a','146 │
│                 │                           │                                               │ b','146c','148','148a','148b','148c','149','149a','149b','14 │
│                 │                           │                                               │ 9c','149d','149f']                                           │
│           0.079 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.079 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Základná preventívna prehliadka               │ vv.kod in ['160']                                            │
│            5.98 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            5.98 │ vv.pocet*cena             │ EKG (5702,5702ZV)                             │ vv.kod in ['5702ZV','5702']                                  │
│            5.75 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│               2 │ vv.pocet*cena             │ Delegovaný odber 250D                         │ vv.kod in ['250D']                                           │
│            6.22 │ vv.pocet*cena             │ Výkon H0002                                   │ vv.kod in ['H0002']                                          │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             620 │ 60                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             350 │ 142                                                                                                       │                           │
│             390 │ 160                                                                                                       │                           │
│             390 │ 950                                                                                                       │                           │
│             250 │ 951                                                                                                       │                           │
│              60 │ 952                                                                                                       │                           │
│             110 │ 953                                                                                                       │                           │
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

