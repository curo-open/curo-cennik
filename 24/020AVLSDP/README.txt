                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬─────────────────────────────────┐
│ Názov a hodnota │ Popis                           │
├─────────────────┼─────────────────────────────────┤
│ IDK = 0         │ NASTAVENIA IDK                  │
│ VCB1 = 0.41     │ Vypočítaná cena bodu. výkon 1   │
│ VCB4 = 1.54     │ Vypočítaná cena bodu. výkon 4   │
│ VCB8 = 2.06     │ Vypočítaná cena bodu. výkon 8   │
│ VCB250 = 0.41   │ Vypočítaná cena bodu. výkon 250 │
│ PPH1 = 10       │ PPH1                            │
│ PPH2 = 6.5      │ PPH2                            │
│ PREDOP = 12.9   │ PREDOP                          │
│ _4571a = 4      │ 4571a                           │
│ CHRSTAR = 10    │ CHRSTAR                         │
│ TELEKON = 1.3   │ TELEKON                         │
│ HYPVST = 8      │ HYPVST                          │
│ HYPKON = 5      │ HYPKON                          │
│ HYPSTA = 4      │ HYPSTA                          │
│ SKOR01 = 1.9    │ SKOR01                          │
│ SKOR02 = 2.1    │ SKOR02                          │
│ SKOR03 = 2.3    │ SKOR03                          │
│ SKOR04 = 2.5    │ SKOR04                          │
└─────────────────┴─────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 20 │          3.22 │ IDK+cena │ p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          2.13 │ IDK+cena │ p|vekMedzi(20, 28) │
│ vek od 28 do 46 │          2.24 │ IDK+cena │ p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          2.26 │ IDK+cena │ p|vekMedzi(46, 52) │
│ vek od 52 do 54 │           2.4 │ IDK+cena │ p|vekMedzi(52, 54) │
│ vek od 54 do 58 │           2.6 │ IDK+cena │ p|vekMedzi(54, 58) │
│ vek od 58 do 62 │          2.84 │ IDK+cena │ p|vekMedzi(58, 62) │
│ vek od 62 do 65 │          3.14 │ IDK+cena │ p|vekMedzi(62, 65) │
│ vek od 65 do 69 │          3.33 │ IDK+cena │ p|vekMedzi(65, 69) │
│ vek od 69 do 73 │          3.59 │ IDK+cena │ p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          4.03 │ IDK+cena │ p|vekMedzi(73, 88) │
│ vek od 88+      │             4 │ IDK+cena │ p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│                 │ PPH1                      │ Pripočitateľné položky                        │ vv.kod=='PPH1'                                               │
│                 │ PPH2                      │ Pripočitateľné položky                        │ vv.kod=='PPH2'                                               │
│                 │ PREDOP                    │ Pripočitateľné položky                        │ vv.kod=='PREDOP'                                             │
│                 │ _4571a                    │ Pripočitateľné položky                        │ vv.kod=='4571a'                                              │
│                 │ CHRSTAR                   │ Pripočitateľné položky                        │ vv.kod=='CHRSTAR'                                            │
│                 │ TELEKON                   │ Pripočitateľné položky                        │ vv.kod=='TELEKON'                                            │
│                 │ HYPVST                    │ Pripočitateľné položky                        │ vv.kod=='HYPVST'                                             │
│                 │ HYPKON                    │ Pripočitateľné položky                        │ vv.kod=='HYPKON'                                             │
│                 │ HYPSTA                    │ Pripočitateľné položky                        │ vv.kod=='HYPSTA'                                             │
│                 │ SKOR01                    │ Pripočitateľné položky                        │ vv.kod=='SKOR01'                                             │
│                 │ SKOR02                    │ Pripočitateľné položky                        │ vv.kod=='SKOR02'                                             │
│                 │ SKOR03                    │ Pripočitateľné položky                        │ vv.kod=='SKOR03'                                             │
│                 │ SKOR04                    │ Pripočitateľné položky                        │ vv.kod=='SKOR04'                                             │
│            4.79 │ vv.pocet*cena             │ Nekapitovaný - Vykon 4                        │ !p.kapitacia && vv.kod in ['4']                              │
│            6.38 │ vv.pocet*cena             │ Nekapitovaný - Vykon 8                        │ !p.kapitacia && vv.kod in ['8']                              │
│         0.00819 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│        0.022973 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│                 │ vv.pocet*VCB1             │ Vykon 1                                       │ vv.kod in ['1']                                              │
│                 │ vv.pocet*VCB4             │ Vykon 4                                       │ vv.kod in ['4']                                              │
│                 │ vv.pocet*VCB8             │ Vykon 8                                       │ vv.kod in ['8']                                              │
│                 │ vv.pocet*VCB250           │ Vykon 250                                     │ vv.kod in ['250']                                            │
│        0.048972 │ vv.pocet*180*cena         │ TOKS                                          │ vv.kod in ['159a','159b','159x','159z']                      │
│        0.048972 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│        0.048972 │ vv.pocet*390*cena         │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│            10.5 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│               8 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│        0.022089 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
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

