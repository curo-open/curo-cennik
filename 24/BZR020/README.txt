                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬─────────────────────────────┐
│ Názov a hodnota    │ Popis                       │
├────────────────────┼─────────────────────────────┤
│ IDK = 0.34991      │ NASTAVENIA IDK              │
│ CB = 0.028704      │ Cena bodu Kapitovany SK/EU  │
│ CBSVALZ = 0.009718 │ Cena bodu SVaLZ             │
│ CBEUNK = 0.025959  │ Cena bodu Nekapitovany      │
│ AGTC = 4.8         │ AGTC                        │
│ PP50 = 10          │ PP50                        │
└────────────────────┴─────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek do 18 do 19 │          5.09 │ IDK+cena │ p|vekMedzi(18, 19) │
│ vek od 19 do 27 │          3.21 │ IDK+cena │ p|vekMedzi(19, 27) │
│ vek od 27 do 45 │          3.29 │ IDK+cena │ p|vekMedzi(27, 45) │
│ vek od 45 do 51 │          3.47 │ IDK+cena │ p|vekMedzi(45, 51) │
│ vek od 51 do 53 │          3.78 │ IDK+cena │ p|vekMedzi(51, 53) │
│ vek od 53 do 57 │          4.53 │ IDK+cena │ p|vekMedzi(53, 57) │
│ vek od 57 do 61 │          4.87 │ IDK+cena │ p|vekMedzi(57, 61) │
│ vek od 61 do 64 │          5.34 │ IDK+cena │ p|vekMedzi(61, 64) │
│ vek od 64 do 68 │          6.13 │ IDK+cena │ p|vekMedzi(64, 68) │
│ vek od 68 do 72 │          6.63 │ IDK+cena │ p|vekMedzi(68, 72) │
│ vek od 72 do 87 │          7.31 │ IDK+cena │ p|vekMedzi(72, 87) │
│ vek od 87+      │          7.21 │ IDK+cena │ p|vekMedzi(87)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 1                                       │ vv.kod in ['1']                                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 4                                       │ !p.kapitacia && vv.kod in ['4']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 8                                       │ !p.kapitacia && vv.kod in ['8']                              │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            null │ vv.bodyCelkom*CB          │ Vystavenie návrhu na kúpeľnú starostlivosť    │ !p.kapitacia && vv.kod in ['75a']                            │
│            null │ vv.bodyCelkom*CB          │ Komunikácia v cudziom jazyku                  │ !p.kapitacia && vv.kod in ['79a']                            │
│           0.084 │ vv.bodyCelkom*cena        │ TOKS                                          │ vv.kod in ['159a','159x','159z']                             │
│           0.084 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│           0.084 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            null │ vv.bodyCelkom*CB          │ Injekcia                                      │ !p.kapitacia && vv.kod in ['252']                            │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ !p.kapitacia && vv.kod in ['252b']                           │
│            null │ vv.bodyCelkom*CB          │ Intravenózna infúzia                          │ !p.kapitacia && vv.kod in ['271']                            │
│            null │ vv.bodyCelkom*CB          │ Odber biologického materiálu                  │ !p.kapitacia && vv.kod in ['299a']                           │
│            null │ vv.bodyCelkom*CB          │ Odber krvi                                    │ !p.kapitacia && vv.kod in ['250a','250b']                    │
│          0.0375 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ !p.kapitacia && vv.kod in ['25','26','29','30']              │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│           18.08 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            5.98 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702','5702C']                                   │
│            5.98 │ vv.pocet*cena             │ EKG (5702,5702ZV)                             │ vv.kod in ['5702ZV','5702']                                  │
│              20 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│            8.98 │ vv.pocet*cena             │ Stanovenie hodnoty D-diméru                   │ vv.kod in ['3860']                                           │
│            11.6 │ vv.pocet*cena             │ Stanovenie hodnoty troponínu                  │ vv.kod in ['4485']                                           │
│           19.78 │ vv.pocet*cena             │ Stanovenie hodnoty NT-proBNP                  │ vv.kod in ['44418']                                          │
│            5.65 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│            4.38 │ vv.pocet*cena             │ Výkon 5301                                    │ vv.kod in ['5301']                                           │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│              12 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              12 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP (H0006)                     │ vv.kod in ['H0006']                                          │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['EU'] && vv.typ!='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['EU'] && vv.typ=='SVaLZ'           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ=='SVaLZ'      │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ!='SVaLZ'      │
│            null │ vv.bodyCelkom*0           │ SVALZ výkon                                   │ p.kapitacia && vv.jeSVaZL                                    │
│            null │ vv.bodyCelkom*0           │ iné ako SVALZ                                 │ p.kapitacia && !vv.jeSVaZL                                   │
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

