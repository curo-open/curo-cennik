                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota │ Popis                                             │
├─────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0         │ IDK                                               │
│ KPS = 1         │ KPS                                               │
│ EL_POBOCKA = 1  │ Používa el. pobočku ?                             │
│ CB = 0.035      │ Cena bodu                                         │
│ CBSVALZ = 0.01  │ Cena bodu SVaLZ                                   │
│ CBEU = 0.035    │ Cena bodu Nekapitovany(EU)                        │
│ AGTC = 4.8      │ AGTC                                              │
│ PP50 = 10       │ PP50                                              │
│ FOB = 2         │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ EDU = 2         │ EDU k výkonom H0003, H0004                        │
└─────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek do 19       │          4.66 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 28 │          3.61 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 39 │          3.38 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 44 │           3.4 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 49 │          3.44 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 54 │          3.95 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 59 │          4.53 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 64 │          5.05 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 69 │          5.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 74 │          6.21 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 79 │          6.97 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 84 │          7.83 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │          8.18 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ=='SVaLZ'      │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU'] && vv.typ!='SVaLZ'      │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.035 │ vv.bodyCelkom*cena        │ Návštevná služba (vv. 25,26,29,30)            │ vv.kod in ['25','26','29','30']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 10                                      │ vv.kod in ['10']                                             │
│          0.0318 │ vv.bodyCelkom*cena        │ Vstupná prehliadka (vv. 60)                   │ vv.kod in ['60']                                             │
│           0.084 │ vv.bodyCelkom*cena        │ Preventívne prehliadky (vv. 160)              │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (vv. 15P)     │ vv.kod in ['15P']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (vv. 5702P)   │ vv.kod in ['5702P']                                          │
│        0.009574 │ vv.bodyCelkom*cena        │ EKG (vv. 5702)                                │ vv.kod in ['5702']                                           │
│        0.021999 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku  (vv. 5715)          │ vv.kod in ['5715']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Celodenné snímanie tlaku - vyhodnotenie  (vv. │ vv.kod in ['5716']                                           │
│                 │                           │ 5716)                                         │                                                              │
│            0.09 │ vv.bodyCelkom*cena        │ Očkovanie  (vv. 252b, 252c)                   │ vv.kod in ['252b','252c']                                    │
│          0.0073 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5301']                                           │
│              10 │ vv.pocet*cena             │ Očkovanie Covid (vv. 252L)                    │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid (vv. 252K)                    │ vv.kod in ['252K']                                           │
│            4.78 │ vv.pocet*cena             │ Akútne EKG  (vv. 5702c)                       │ vv.kod in ['5702c']                                          │
│            6.78 │ vv.pocet*cena             │ Výkon 163                                     │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ TOKS pozitívny (vv. 159a)                     │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny  (vv. 159z)                    │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený  (vv. 159x)                 │ vv.kod in ['159x']                                           │
│              15 │ vv.pocet*cena             │ Inicialne I10/E78 (vv. H0003)                 │ vv.kod in ['H0003']                                          │
│              15 │ vv.pocet*cena             │ Kontrolne I10/E78 (vv .H0004)                 │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10  (vv. H0005)                       │ vv.kod in ['H0005']                                          │
│            5.65 │ vv.pocet*cena             │ Stratifikacia CMP  (vv. H0006)                │ vv.kod in ['H0006']                                          │
│           17.33 │ vv.pocet*cena             │ Predoperačné vyšetrenie  (vv. 60b)            │ vv.kod in ['60b']                                            │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT  (vv. H0007 │ vv.kod in ['H0007']                                          │
│                 │                           │ )                                             │                                                              │
│            6.78 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky  (vv. H0008)    │ vv.kod in ['H0008']                                          │
│               2 │ vv.pocet*cena             │ Delegovaný odber krvi  (vv. 250D)             │ vv.kod in ['250D','250d']                                    │
│        0.020895 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom (vv. 3671)       │ vv.kod in ['3671']                                           │
│            5.75 │ vv.pocet*cena             │ C-reaktívny proteín  (vv. 4571A, 4571a)       │ vv.kod in ['4571a','4571A']                                  │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19  (vv. 62a)       │                                                              │
│            8.98 │ vv.pocet*cena             │ Stanovenie D-diméru                           │ vv.kod in ['3860']                                           │
│            11.6 │ vv.pocet*cena             │ Stanovenie Troponínu                          │ vv.kod in ['4485']                                           │
│           19.78 │ vv.pocet*cena             │ N-terminálny fragment (NT-pro BNP)            │ vv.kod in ['44418']                                          │
│            0.08 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['160R']                                           │
│                 │                           │ jicajtov, hasičov a záchranárov - PP  (vv. 16 │                                                              │
│                 │                           │ 0R)                                           │                                                              │
│        0.009574 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5702R']                                          │
│                 │                           │ jicajtov, hasičov a záchranárov - EKG  (vv. 5 │                                                              │
│                 │                           │ 702R)                                         │                                                              │
│           0.065 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','250bR','3525R','3592R','252bR','3784 │
│                 │                           │                                               │ R','3671R','3679R','3693R','3692R','3674aR','3677aR','5051R' │
│                 │                           │                                               │ ,'FotoR','PACSR']                                            │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2  (vv.  │ vv.kod in ['629a']                                           │
│                 │                           │ 629a)                                         │                                                              │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou  (vv. 629b)            │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && (p.typ in ['EU']) && vv.typ=='SVaLZ'         │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && (p.typ in ['EU']) && vv.typ!='SVaLZ'         │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ Neodkladná starostlivosť                      │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             180 │ 10                                                                                                        │                           │
│             620 │ 60                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             390 │ 160                                                                                                       │                           │
│             550 │ 5702                                                                                                      │                           │
│             750 │ 5715                                                                                                      │                           │
│             240 │ 5716                                                                                                      │                           │
│             180 │ 159b                                                                                                      │                           │
│             390 │ 160R                                                                                                      │                           │
│             550 │ 5702P                                                                                                     │                           │
│              70 │ 252b                                                                                                      │                           │
│              70 │ 252c                                                                                                      │                           │
│              70 │ 252s                                                                                                      │                           │
│             500 │ 5702c                                                                                                     │                           │
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
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Preventivka: chýba EKG vyšetren │     0      │ p.kapitacia && d.vv|ma('kod in ["160"]') && p.vek >= │ d.vv|ma('kod=="5702P"')                              │
│ ie                              │            │ 40                                                   │                                                      │
│ Možnosť vykázať výkon 10        │     0      │ d.vv|ma('kod in ["60"]')                             │ d.vv|ma('kod=="10"')                                 │
│ Chyba: Akútne EKG vykázane súbe │     0      │ vv.kod in ['5702c']                                  │ d.vv|ma('kod in ["160","15P","15C","5702P"]')        │
│ žne s 160, 15P, 15C alebo 5702P │            │                                                      │                                                      │
│ Chyba: EKG 15P/5702P vykázane s │     0      │ vv.kod in ['15P']                                    │ d.vv|ma('kod in ["5702P"]')                          │
│ úbežne                          │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

