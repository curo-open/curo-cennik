                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────────────────┐
│ Názov a hodnota │ Popis                      │
├─────────────────┼────────────────────────────┤
│ IDK = 0         │ NASTAVENIA IDK             │
│ CB = 0          │ Cena bodu                  │
│ CBSVALZ = 0.01  │ Cena bodu SVaLZ            │
│ CBEU = 0.0349   │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8      │ AGTC                       │
│ PP50 = 10       │ PP50                       │
│ FOB = 2         │ FOB                        │
│ EDU = 2         │ EDU                        │
│ AAA1 = 3.55     │ AAA1                       │
│ AAA2 = 3.55     │ AAA2                       │
│ AAA3 = 3.55     │ AAA3                       │
│ AAA4 = 3.55     │ AAA4                       │
└─────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 51 │          3.43 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 51) │
│ vek od 51 do 61 │          3.93 │ IDK+cena │ p.kapitacia && p|vekMedzi(51, 61) │
│ vek od 61 do 81 │          6.31 │ IDK+cena │ p.kapitacia && p|vekMedzi(61, 81) │
│ vek od 81+      │          8.24 │ IDK+cena │ p.kapitacia && p|vekMedzi(81)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladná statostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - Neodkladná statostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            1.22 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D','250d']                                    │
│           30.85 │ vv.pocet*cena             │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│          0.0845 │ vv.bodyCelkom*cena        │ Preventívne zisťovanie cukru v krvi           │ vv.kod in ['3671']                                           │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza=='Z25.1' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A                  │ vv.diagnoza=='Z20.5' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde B/Tetanus          │ vv.diagnoza=='Z00.0' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A+B                │ vv.diagnoza=='Z24.6' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti meningitíde                   │ vv.diagnoza=='Z20.8' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti pneumokokom                   │ vv.diagnoza=='Z23.5' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti kliestovej encefalitide       │ vv.diagnoza=='Z24.1' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde B/Tetanus          │ vv.diagnoza=='Z23.8' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti osýpkam                       │ vv.diagnoza in ['Z27.4','Z27.8','Z27.3','Z27.1','Z24.4'] &&  │
│                 │                           │                                               │ vv.kod in ['252b']                                           │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│            0.01 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│          0.0158 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│          0.0349 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29']                                   │
│          0.0349 │ vv.bodyCelkom*cena        │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29","30"]') && vv.kod in ['4','5 │
│                 │                           │                                               │ ','6','30','40','41','64']                                   │
│           12.36 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│           12.36 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│           12.36 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│          0.0845 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│           17.51 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            5.52 │ vv.pocet*cena             │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│            0.01 │ vv.bodyCelkom*cena        │ EKG (5702)                                    │ vv.kod in ['5702']                                           │
│               5 │ vv.pocet*cena             │ INR                                           │ vv.kod in ['3842a']                                          │
│           19.21 │ vv.pocet*cena             │ 24h meranie tlaku                             │ vv.kod in ['5715']                                           │
│              14 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│              14 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│         0.01075 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5300','5301']                                    │
│            6.98 │ vv.pocet*cena             │ ABI (H0008)                                   │ vv.kod in ['H0008']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            1.16 │ vv.pocet*cena             │ Výplach zvukovodu (jedno ucho)                │ vv.kod in ['1540']                                           │
│               7 │ vv.pocet*cena             │ Kognitívny deficit                            │ vv.kod in ['163']                                            │
│             8.8 │ vv.pocet*cena             │ Starostlivosť o poistenca s artériovou hypert │ vv.kod in ['10']                                             │
│                 │                           │ enziou, dyslipidémiou a/alebo obezitou        │                                                              │
│            5.82 │ vv.pocet*cena             │ Stratifikácia kardiovaskulárneho rizika       │ vv.kod in ['H0006']                                          │
│            6.06 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│            5.25 │ vv.pocet*cena             │ Výkon 60                                      │ vv.kod in ['60']                                             │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a']                                            │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│            null │ AAA1                      │ Pripočitateľné položky                        │ vv.kod=='AAA1'                                               │
│            null │ AAA2                      │ Pripočitateľné položky                        │ vv.kod=='AAA2'                                               │
│            null │ AAA3                      │ Pripočitateľné položky                        │ vv.kod=='AAA3'                                               │
│            null │ AAA4                      │ Pripočitateľné položky                        │ vv.kod=='AAA4'                                               │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && (p.typ in ['EU']) && vv.typ=='SVaLZ'         │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && (p.typ in ['EU']) && vv.typ!='SVaLZ'         │
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

