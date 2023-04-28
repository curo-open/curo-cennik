                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────┬────────────────────────────┐
│ Názov a hodnota  │ Popis                      │
├──────────────────┼────────────────────────────┤
│ IDK = 0          │ NASTAVENIA IDK             │
│ CB = 0           │ Cena bodu                  │
│ CBSVALZ = 0.0082 │ Cena bodu SVaLZ            │
│ CBEUNK = 0.026   │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8       │ AGTC                       │
│ PP50 = 10        │ PP50                       │
└──────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 50 │          2.54 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 50) │
│ vek od 50 do 60 │          2.92 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 60) │
│ vek od 60 do 80 │          4.07 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 80) │
│ vek od 80+      │          4.46 │ IDK+cena │ p.kapitacia && p|vekMedzi(80)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný EU - iné ako SVALZ               │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
│           0.026 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a']                                  │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           0.053 │ vv.bodyCelkom*cena        │ Výkon 159b                                    │ vv.kod in ['159b']                                           │
│           0.053 │ vv.bodyCelkom*cena        │ Určenie glykémie glukometrom                  │ vv.kod in ['3671']                                           │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│           0.025 │ vv.bodyCelkom*cena        │ Návštevná služba - výkony 25,26,29            │ vv.kod in ['25','26','29']                                   │
│           0.015 │ vv.bodyCelkom*cena        │ Návštevná služba - výkony 4,5,6,30            │ vv.kod in ['4','5','6','30']                                 │
│           0.015 │ vv.bodyCelkom*cena        │ Návštevná služba - výkony 40,41               │ vv.kod in ['40','41']                                        │
│           19.35 │ vv.pocet*cena             │ Preventina prehliadka                         │ vv.kod in ['160']                                            │
│             8.8 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│             8.8 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│             8.8 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│          0.0082 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│          0.0088 │ vv.bodyCelkom*cena        │ USG vyšetrenie                                │ vv.kod in ['5300','5301']                                    │
│            4.41 │ vv.pocet*cena             │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│               5 │ vv.pocet*cena             │ Meranie INR                                   │ vv.kod in ['3842a']                                          │
│              13 │ vv.pocet*cena             │ Celodenné snímanie tlaku                      │ vv.kod in ['5715']                                           │
│           0.012 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│              10 │ vv.pocet*cena             │ Vykon 10                                      │ vv.kod in ['10']                                             │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│               5 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│               6 │ vv.pocet*cena             │ Kognitívny deficit                            │ vv.kod in ['163']                                            │
│             4.5 │ vv.pocet*cena             │ Výkon 60                                      │ vv.kod in ['60']                                             │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D','250d']                                    │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
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

