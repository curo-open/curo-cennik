                                                                          ===========
                                                                          Cenník ZVLD
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬────────────────────────────┐
│ Názov a hodnota    │ Popis                      │
├────────────────────┼────────────────────────────┤
│ IDK = 0            │ NASTAVENIA IDK             │
│ CB = 0             │ Cena bodu                  │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ            │
│ CBEU = 0.028704    │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8         │ AGTC                       │
│ PP50 = 10          │ PP50                       │
│ EDU = 2            │ EDU                        │
└────────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          5.09 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          3.21 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 28) │
│ vek od 28 do 46 │          3.29 │ IDK+cena │ p.kapitacia && p|vekMedzi(28, 46) │
│ vek od 46 do 52 │          3.31 │ IDK+cena │ p.kapitacia && p|vekMedzi(46, 52) │
│ vek od 52 do 54 │          3.61 │ IDK+cena │ p.kapitacia && p|vekMedzi(52, 54) │
│ vek od 54 do 58 │          4.33 │ IDK+cena │ p.kapitacia && p|vekMedzi(54, 58) │
│ vek od 58 do 62 │          4.74 │ IDK+cena │ p.kapitacia && p|vekMedzi(58, 62) │
│ vek od 62 do 65 │          5.48 │ IDK+cena │ p.kapitacia && p|vekMedzi(62, 65) │
│ vek od 65 do 69 │           6.3 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 69) │
│ vek od 69 do 73 │          6.82 │ IDK+cena │ p.kapitacia && p|vekMedzi(69, 73) │
│ vek od 73 do 88 │          7.49 │ IDK+cena │ p.kapitacia && p|vekMedzi(73, 88) │
│ vek od 88+      │          7.42 │ IDK+cena │ p.kapitacia && p|vekMedzi(88)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│        0.025959 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná - iné ako SVALZ     │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.084 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.084 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│           0.084 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│          0.0375 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29','30']                              │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│           18.08 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            5.98 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            5.98 │ vv.pocet*cena             │ EKG (5702,5702Z)                              │ vv.kod in ['5702Z','5702']                                   │
│              16 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│            5.65 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│              15 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              15 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│            8.98 │ vv.pocet*cena             │ Stanovenie D-diméru                           │ vv.kod in ['3860']                                           │
│            11.6 │ vv.pocet*cena             │ Stanovenie TroponínuT                         │ vv.kod in ['4485']                                           │
│           19.78 │ vv.pocet*cena             │ N-terminálny fragment (NT-pro BNP)            │ vv.kod in ['44418']                                          │
│            4.38 │ vv.pocet*cena             │ USG vyšetrenie POCUS                          │ vv.kod in ['5301']                                           │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['EU'] && vv.typ=='SVaLZ'           │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
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

