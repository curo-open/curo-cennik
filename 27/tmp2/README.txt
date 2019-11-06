Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────┐
│ Názov a hodnota │ Popis          │
├─────────────────┼────────────────┤
│  = 0.03         │ NASTAVENIA IDK │
└─────────────────┴────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬─────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec  │ Podmienka          │
├─────────────────┼───────────────┼─────────┼────────────────────┤
│ vek od 18 do 51 │          2.22 │         │ p|vekMedzi(18, 51) │
│ vek od 51 do 61 │          2.41 │         │ p|vekMedzi(51, 61) │
│ vek od 61 do 81 │          2.85 │         │ p|vekMedzi(61, 81) │
│ vek od 81+      │          3.05 │         │ p|vekMedzi(81)     │
└─────────────────┴───────────────┴─────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│           0.015 │                           │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['BE','CU','EU']                    │
│          0.0073 │                           │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│           0.015 │                           │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│           16.43 │                           │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│           0.045 │                           │ Preventívne zisťovanie cukru v krvi           │ vv.kod in ['3671']                                           │
│          0.0482 │                           │ Očkovanie proti chrípke                       │ vv.diagnoza=='Z25.1' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti hepatitíde A                  │ vv.diagnoza=='Z20.5' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti hepatitíde B                  │ vv.diagnoza=='Z24.6' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti meningitíde                   │ vv.diagnoza=='Z20.8' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti pneumokokom                   │ vv.diagnoza=='Z23.8' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti kliestovej encefalitide       │ vv.diagnoza=='Z24.1' && vv.kod in ['252b']                   │
│          0.0266 │                           │ Očkovanie proti tetanu                        │ vv.diagnoza=='Z00.0' && vv.kod in ['252b']                   │
│          0.0076 │                           │ EKG                                           │ vv.kod in ['5702']                                           │
│          0.0116 │                           │ CRP                                           │ vv.kod in ['4571A']                                          │
│          0.0237 │                           │ Návštevná služba                              │ vv.kod in ['25','26','29']                                   │
│           0.015 │                           │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29"]') && vv.kod in ['4','5','6' │
│                 │                           │                                               │ ,'30','40','41','64']                                        │
│            6.04 │                           │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│            6.04 │                           │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            2.01 │                           │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│           0.045 │                           │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│              10 │                           │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            4.18 │                           │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│               5 │                           │ INR                                           │ vv.kod in ['3842a']                                          │
│               9 │                           │ 24h meranie tlaku                             │ vv.kod in ['5715']                                           │
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

