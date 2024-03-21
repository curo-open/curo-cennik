                                                                          ===========
                                                                          Cenník VLDD
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────────────────┐
│ Názov a hodnota    │ Popis                       │
├────────────────────┼─────────────────────────────┤
│ IDK = NaN          │ NASTAVENIA IDK              │
│ CB = 0             │ Cena bodu Kapitovany SK/EU  │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ             │
│ CBEUNK = 0         │ Cena bodu Nekapitovany      │
│ AGTC = 4.8         │ AGTC                        │
│ PP50 = 10          │ PP50                        │
└────────────────────┴─────────────────────────────┘


  CENY ZA PACIENTA
┌──────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                │ Premenná cena │ Vzorec   │ Podmienka          │
├──────────────────────┼───────────────┼──────────┼────────────────────┤
│ vek do 1 roku života │         10.74 │ IDK+cena │ p|vekDo (1)        │
│ vek od 1 do 2        │         11.22 │ IDK+cena │ p|vekMedzi(1, 2)   │
│ vek od 2 do 7        │           7.4 │ IDK+cena │ p|vekMedzi(2, 7)   │
│ vek od 7 do 19       │          4.49 │ IDK+cena │ p|vekMedzi(7, 19)  │
│ vek od 19 do 26      │          2.89 │ IDK+cena │ p|vekMedzi(19, 26) │
└──────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b,11a,70                               │ vv.kod in ['1b','11a','70']                                  │
│            0.78 │ vv.bodyCelkom*cena        │ Výkon 1                                       │ !p.kapitacia && vv.kod in ['1']                              │
│            2.88 │ vv.pocet*cena             │ Výkon 4                                       │ !p.kapitacia && vv.kod in ['4']                              │
│            3.85 │ vv.pocet*cena             │ Výkon 8                                       │ !p.kapitacia && vv.kod in ['8']                              │
│            1.15 │ vv.pocet*cena             │ Výkon 250                                     │ !p.kapitacia && vv.kod in ['250']                            │
│            8.63 │ vv.pocet*cena             │ Výkon 4                                       │ vv.kod in ['4']                                              │
│           12.26 │ vv.pocet*cena             │ Výkon 8                                       │ vv.kod in ['8']                                              │
│           0.079 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252a','252b']                                    │
│        0.110198 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['142']                                            │
│           0.079 │ vv.bodyCelkom*cena        │ Preventívne výkony                            │ vv.kod in ['143','143a','144','145','145a','146','146a','146 │
│                 │                           │                                               │ b','146c','148','148a','148b','148c','149','149a','149b','14 │
│                 │                           │                                               │ 9c','149d','149f','160','950','953']                         │
│           0.079 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.079 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│            5.98 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            5.98 │ vv.pocet*cena             │ EKG (5702,5702ZV)                             │ vv.kod in ['5702ZV','5702']                                  │
│            5.65 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
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

