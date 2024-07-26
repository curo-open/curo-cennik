                                                                          ===========
                                                                          Cenník VLDD
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────────────────┐
│ Názov a hodnota    │ Popis                       │
├────────────────────┼─────────────────────────────┤
│ IDK = NaN          │ NASTAVENIA IDK              │
│ CB = 0.0318        │ Cena bodu Kapitovany SK/EU  │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ             │
│ CBEUNK = 0.0318    │ Cena bodu Nekapitovany      │
│ AGTC = 4.8         │ AGTC                        │
│ PP50 = 10          │ PP50                        │
└────────────────────┴─────────────────────────────┘


  CENY ZA PACIENTA
┌──────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                │ Premenná cena │ Vzorec   │ Podmienka          │
├──────────────────────┼───────────────┼──────────┼────────────────────┤
│ vek do 1 roku života │         11.81 │ IDK+cena │ p|vekMedzi(0, 1)   │
│ vek od 1 do 2        │         12.34 │ IDK+cena │ p|vekMedzi(1, 2)   │
│ vek od 2 do 7        │          7.92 │ IDK+cena │ p|vekMedzi(2, 7)   │
│ vek od 7 do 19       │           4.8 │ IDK+cena │ p|vekMedzi(7, 19)  │
│ vek od 19 do 26      │          3.03 │ IDK+cena │ p|vekMedzi(19, 26) │
└──────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['EU']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 15b - Zhodnotenie výsledkov             │ vv.kod in ['15b']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            1.37 │ vv.pocet*cena             │ Výkon 1                                       │ vv.kod in ['1']                                              │
│            5.11 │ vv.pocet*cena             │ Výkon 4                                       │ vv.kod in ['4']                                              │
│            7.17 │ vv.pocet*cena             │ Výkon 8                                       │ vv.kod in ['8']                                              │
│            2.03 │ vv.pocet*cena             │ Výkon 250,250a,250b                           │ !p.kapitacia && vv.kod in ['250','250a','250b']              │
│            null │ vv.bodyCelkom*CB          │ Výkon 299a,299b                               │ !p.kapitacia && vv.kod in ['299a','299b']                    │
│            8.63 │ vv.pocet*cena             │ Výkon 4-nekapitovaný                          │ !p.kapitacia && vv.kod in ['4']                              │
│           12.26 │ vv.pocet*cena             │ Výkon 8-nekapitovaný                          │ !p.kapitacia && vv.kod in ['8']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 10                                      │ vv.kod in ['10']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 60,63,64                                │ vv.kod in ['60','63','64']                                   │
│            0.05 │ vv.bodyCelkom*cena        │ Výkon 67                                      │ vv.kod in ['67']                                             │
│           0.079 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ !p.kapitacia && vv.kod in ['3671']                           │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252a','252b']                                    │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia                          │ vv.kod in ['271']                                            │
│        0.110198 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['142']                                            │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne výkony                            │ vv.kod in ['143','143a','144','145','145a','146','146a','146 │
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
│            null │ vv.bodyCelkom*0           │ SVALZ výkon                                   │ p.kapitacia && vv.jeSVaZL                                    │
│            null │ vv.bodyCelkom*0           │ iné ako SVALZ                                 │ p.kapitacia && !vv.jeSVaZL                                   │
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

