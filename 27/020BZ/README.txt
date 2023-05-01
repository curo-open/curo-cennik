                                                                    ========================
                                                                    Cenník VLD Bez zdruzenia
                                                                    ========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬───────────────────────────────────────────────────┐
│ Názov a hodnota   │ Popis                                             │
├───────────────────┼───────────────────────────────────────────────────┤
│ IDK = 0           │ NASTAVENIA IDK                                    │
│ CB = 0            │ Cena bodu                                         │
│ CBSVALZ = 0.00973 │ Cena bodu SVaLZ                                   │
│ CBEUNK = 0.0339   │ Cena bodu Nekapitovany(EU)                        │
│ AGTC = 4.8        │ AGTC                                              │
│ PP50 = 10         │ PP50                                              │
│ FOB = 2           │ Pripočítaľná položka FOB k výkonom 159a,159z,159x │
│ EDU = 2           │ EDU                                               │
└───────────────────┴───────────────────────────────────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 51 │          3.07 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 51) │
│ vek od 51 do 61 │          3.53 │ IDK+cena │ p.kapitacia && p|vekMedzi(51, 61) │
│ vek od 61 do 81 │          5.52 │ IDK+cena │ p.kapitacia && p|vekMedzi(61, 81) │
│ vek od 81+      │           7.2 │ IDK+cena │ p.kapitacia && p|vekMedzi(81)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && (p.typ in ['EU']) && vv.typ=='SVaLZ'         │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && (p.typ in ['EU']) && vv.typ!='SVaLZ'         │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│           28.83 │ vv.pocet*cena             │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│          0.0485 │ vv.bodyCelkom*cena        │ Preventívne zisťovanie cukru v krvi           │ vv.kod in ['3671']                                           │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza=='Z25.1' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A                  │ vv.diagnoza=='Z20.5' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde B                  │ vv.diagnoza=='Z00.0' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A+B                │ vv.diagnoza=='Z24.6' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti meningitíde                   │ vv.diagnoza=='Z20.8' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti pneumokokom                   │ vv.diagnoza=='Z23.8' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti kliestovej encefalitide       │ vv.diagnoza=='Z24.1' && vv.kod in ['252b']                   │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti diftérii a tetanu             │ vv.diagnoza in ['Z00.','Z23.5'] && vv.kod in ['252b']        │
│          0.0904 │ vv.bodyCelkom*cena        │ Očkovanie proti osýpkam                       │ vv.diagnoza in ['Z27.4','Z27.8','Z27.3','Z27.1','Z24.4'] &&  │
│                 │                           │                                               │ vv.kod in ['252b']                                           │
│          0.0082 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│           0.015 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│          0.0339 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29']                                   │
│          0.0339 │ vv.bodyCelkom*cena        │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29"]') && vv.kod in ['4','5','6' │
│                 │                           │                                               │ ,'30','40','41','64']                                        │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│              12 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│           0.079 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│           0.079 │ vv.bodyCelkom*cena        │ Glukóza                                       │ vv.kod in ['3671']                                           │
│              17 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            5.36 │ vv.pocet*cena             │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│         0.00973 │ vv.bodyCelkom*cena        │ EKG (5702)                                    │ vv.kod in ['5702']                                           │
│               5 │ vv.pocet*cena             │ INR                                           │ vv.kod in ['3842a']                                          │
│           18.65 │ vv.pocet*cena             │ 24h meranie tlaku                             │ vv.kod in ['5715']                                           │
│         0.01044 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5300','5301']                                    │
│           13.56 │ vv.pocet*cena             │ Inicialne I10/E78 (H0003)                     │ vv.kod in ['H0003']                                          │
│           13.56 │ vv.pocet*cena             │ Kontrolne I10/E78 (H0004)                     │ vv.kod in ['H0004']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│            5.88 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│            6.78 │ vv.pocet*cena             │ ABI (H0008)                                   │ vv.kod in ['H0008']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            6.78 │ vv.pocet*cena             │ Kognitívny deficit                            │ vv.kod in ['163']                                            │
│            1.13 │ vv.pocet*cena             │ Odstránenie ušného mazu                       │ vv.kod in ['1540']                                           │
│              10 │ vv.pocet*cena             │ Starostlivosť o poistenca s artériovou hypert │ vv.kod in ['10']                                             │
│                 │                           │ enziou, dyslipidémiou a/alebo obezitou        │                                                              │
│            5.65 │ vv.pocet*cena             │ Kardio riziko                                 │ vv.kod in ['H0006']                                          │
│            5.09 │ vv.pocet*cena             │ Komplexné vyšetrenie pri prevzatí pacienta do │ vv.kod in ['60']                                             │
│                 │                           │ starostlivosti                                │                                                              │
│            1.19 │ vv.pocet*cena             │ Delegovaný odber                              │ vv.kod in ['250D','250d']                                    │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ vv.kod in ['252K']                                           │
│              20 │ vv.pocet*cena             │ Vyšetrenie pacienta s COVID 19                │ vv.kod in ['62a']                                            │
│              10 │ vv.pocet*cena             │ Očkovanie prosti COVID 19                     │ vv.kod in ['252L']                                           │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
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

