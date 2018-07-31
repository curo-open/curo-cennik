                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IDK = 0         │ IDK                   │
│ KPS = 1         │ KPS                   │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka                         │
├─────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ vek od 18 do 20 │          2.58 │ IDK+cena │ p.kapitacia && p|vekMedzi(18, 20) │
│ vek od 20 do 29 │          2.03 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
│ vek od 29 do 40 │          2.03 │ IDK+cena │ p.kapitacia && p|vekMedzi(29, 40) │
│ vek od 40 do 45 │          2.07 │ IDK+cena │ p.kapitacia && p|vekMedzi(40, 45) │
│ vek od 45 do 50 │          2.12 │ IDK+cena │ p.kapitacia && p|vekMedzi(45, 50) │
│ vek od 50 do 55 │          2.19 │ IDK+cena │ p.kapitacia && p|vekMedzi(50, 55) │
│ vek od 55 do 60 │           2.3 │ IDK+cena │ p.kapitacia && p|vekMedzi(55, 60) │
│ vek od 60 do 65 │          2.43 │ IDK+cena │ p.kapitacia && p|vekMedzi(60, 65) │
│ vek od 65 do 70 │          2.54 │ IDK+cena │ p.kapitacia && p|vekMedzi(65, 70) │
│ vek od 70 do 75 │          2.66 │ IDK+cena │ p.kapitacia && p|vekMedzi(70, 75) │
│ vek od 75 do 80 │          2.77 │ IDK+cena │ p.kapitacia && p|vekMedzi(75, 80) │
│ vek od 80 do 85 │          3.11 │ IDK+cena │ p.kapitacia && p|vekMedzi(80, 85) │
│ vek od 85+      │          3.18 │ IDK+cena │ p.kapitacia && p|vekMedzi(85)     │
└─────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.006639 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│        0.007303 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│        0.018257 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│        0.016597 │ vv.pocet*390*cena         │ Výkon 10                                      │ vv.kod in ['10']                                             │
│        0.016597 │ vv.pocet*390*cena         │ Vstupná prehliadka (výkon 60)                 │ vv.kod in ['60']                                             │
│           0.045 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ KPS && EL_POBOCKA && vv.kod in ['160']                       │
│           0.044 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ KPS && vv.kod in ['160']                                     │
│           0.041 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ EL_POBOCKA && vv.kod in ['160']                              │
│            0.04 │ vv.pocet*390*cena         │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│        0.039833 │ vv.bodyCelkom*cena        │ EKG pri preventívnej prehliadke (15P)         │ vv.kod in ['15P']                                            │
│        0.007635 │ vv.pocet*550*cena         │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702P']                                          │
│        0.007303 │ vv.pocet*550*cena         │ EKG pri preventívnej prehliadke               │ vv.kod in ['5702']                                           │
│        0.016597 │ vv.pocet*550*cena         │ Celodenné snímanie tlaku                      │ vv.kod in ['5715','5716']                                    │
│           0.041 │ vv.pocet*70*cena          │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.041 │ vv.pocet*70*cena          │ Očkovanie proti chrípke                       │ vv.diagnoza in ['Z25.1'] && vv.kod in ['252b','252c','252s'] │
│        0.016597 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26']                                        │
│        0.007303 │ vv.pocet*500*cena         │ Akútne EKG                                    │ vv.kod in ['5702c']                                          │
│              12 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│              12 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            3.02 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│              12 │ vv.pocet*cena             │ Inicialne I10                                 │ vv.kod in ['H0003']                                          │
│              12 │ vv.pocet*cena             │ Kontrolne I10                                 │ vv.kod in ['H0004']                                          │
│               6 │ vv.pocet*cena             │ Akutne I10                                    │ vv.kod in ['H0005']                                          │
│               5 │ vv.pocet*cena             │ Stratifikacia CMP                             │ vv.kod in ['H0006']                                          │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             5.2 │ vv.pocet*cena             │ Kvantitatívne vyšetrenie INR POCT             │ vv.kod in ['H0007']                                          │
│             4.5 │ vv.pocet*cena             │ Stanovenie ABI oscilometricky                 │ vv.kod in ['H0008']                                          │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Preventivka: chýba EKG vyšetren │     0      │ p.kapitacia && d.vv|ma('kod in ["160"]') && p.vek >= │ d.vv|ma('kod=="5702P"')                              │
│ ie                              │            │ 40                                                   │                                                      │
│ Preventivka: možno chýba TOKS v │     0      │ p.kapitacia && d.vv|ma('kod in ["160"]') && p.vek >= │ d.vv|ma('kod in ["159a", "159z", "159x"]')           │
│ ýkon/vyšetrenie                 │            │ 40                                                   │                                                      │
│ Možnosť vykázať výkon 10        │     0      │ d.vv|ma('kod in ["60", "H0003", "H0004", "H0004"]')  │ d.vv|ma('kod=="10"')                                 │
│ Chyba: Akútne EKG vykázane súbe │     0      │ vv.kod in ['5702c']                                  │ d.vv|ma('kod in ["160","15P","15C","5702P"]')        │
│ žne s 160, 15P, 15C alebo 5702P │            │                                                      │                                                      │
│ Chyba: EKG 15P/5702P vykázane s │     0      │ vv.kod in ['15P']                                    │ d.vv|ma('kod in ["5702P"]')                          │
│ úbežne                          │            │                                                      │                                                      │
│ Preventivka: chýba EKG(15P/5702 │     0      │ p.kapitacia && d.vv|ma('kod in ["160"]') && p.vek >= │ d.vv|ma('kod in ["15P","5702P"]')                    │
│ P) vyšetrenie, môžte to vykázať │            │ 40                                                   │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

