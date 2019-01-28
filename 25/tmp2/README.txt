Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│  = 1            │ Používa el. pobočku ? │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬─────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec  │ Podmienka                         │
├─────────────────┼───────────────┼─────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          2.58 │         │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 29 │          2.03 │         │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 40 │          2.03 │         │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 45 │          2.07 │         │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 50 │          2.12 │         │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 55 │          2.19 │         │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 60 │           2.3 │         │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 65 │          2.43 │         │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 70 │          2.54 │         │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 75 │          2.66 │         │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 80 │          2.77 │         │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 85 │          3.11 │         │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │          3.18 │         │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴─────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.006639 │                           │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│        0.007303 │                           │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│        0.018257 │                           │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│        0.016597 │ 390                       │ Výkon 10                                      │ vv.kod in ['10']                                             │
│        0.016597 │ 390                       │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│           0.045 │ 390                       │ Preventívne prehliadky                        │ KPS && EL_POBOCKA && vv.kod in ['160']                       │
│           0.044 │ 390                       │ Preventívne prehliadky                        │ KPS && vv.kod in ['160']                                     │
│           0.041 │ 390                       │ Preventívne prehliadky                        │ EL_POBOCKA && vv.kod in ['160']                              │
│            0.04 │ 390                       │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │                           │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.007635 │ 550                       │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.007303 │ 550                       │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702']                                           │
│        0.016597 │ 550                       │ Celodenné snímanie tlaku                      │ vv.kod in ['5715','5716']                                    │
│           0.041 │ 70                        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.041 │ 70                        │ Očkovanie proti chrípke                       │ vv.diagnoza in ['Z25.1'] && vv.kod in ['252b','252c','252s'] │
│        0.016597 │                           │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│        0.007303 │ 500                       │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│              12 │                           │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │                           │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │                           │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              12 │                           │ Inicialne I10                                 │ vv.kod in ['H0003']                                          │
│              12 │                           │ Kontrolne I10                                 │ vv.kod in ['H0004']                                          │
│               6 │                           │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│               5 │                           │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              13 │                           │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             5.2 │                           │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│             4.5 │                           │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            1.05 │                           │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

