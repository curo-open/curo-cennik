                                                                       ==================
                                                                       Cenník zupa hospic
                                                                       ==================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬────────────────────────────┐
│ Názov a hodnota   │ Popis                      │
├───────────────────┼────────────────────────────┤
│ IPP1 = 1.17       │ IPP1                       │
│ IPP2 = 1.89       │ IPP2                       │
│ IPP3 = 3.19       │ IPP3                       │
│ IPP4 = 4.9        │ IPP4                       │
│ CBD = 0.35        │ Cena bodu doprava do 60km  │
│ CBD60plus = 0.175 │ Cena bodu doprava nad 60km │
└───────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.pocet*CBD              │ DOPRAVA:  do 60 km                            │ vv.kod in ['doprava'] && vv.pocet < 60                       │
│            null │ vv.pocet*CBD60plus        │ DOPRAVA:  + 60 km                             │ vv.kod in ['doprava'] && vv.pocet >= 60                      │
│              61 │ vv.pocet*cena             │ Návšteva osoby v paliatívnej starostlivosti v │ vv.kod in ['25M']                                            │
│                 │                           │ domácom prostredí                             │                                                              │
│            3.61 │ vv.pocet*cena             │ PRÍJEM PACIENTA (KLIENTA) DO ADOS A ODOBRATIE │ vv.kod in ['3390']                                           │
│                 │                           │ SESTERSKEJ ANAMNÉZY                           │                                                              │
│             1.7 │ vv.pocet*cena             │ POUČENIE PRÍBUZNÝCH ALEBO ČLENOV KOMUNITY     │ vv.kod in ['3392A']                                          │
│            7.24 │ vv.pocet*cena             │ VYPRACOVANIE PLÁNU KOMPLEXNEJ OŠETROVATEĽSKEJ │ vv.kod in ['3393']                                           │
│                 │                           │ STAROSTLIVOSTI                                │                                                              │
│            7.82 │ vv.pocet*cena             │ PRIEBEŽNÉ HODNOTENIE KOS A ZMENAPLÁNU OŠETROV │ vv.kod in ['3394']                                           │
│                 │                           │ ATEĽSKEJ STAROSTLIVOSTI                       │                                                              │
│            5.44 │ vv.pocet*cena             │ VYHODNOTENIE KOS A ZÁVEREČNÁ SPRÁVA           │ vv.kod in ['3395']                                           │
│             5.5 │ vv.pocet*cena             │ ODBORNÝ NÁCVIK POTREBNÝCH VÝKONOV PRI OŠETROV │ vv.kod in ['3396']                                           │
│                 │                           │ ANÍ CHORÉHO V DOMÁCNOSTI                      │                                                              │
│             5.5 │ vv.pocet*cena             │ OŠETROVATEĽSKÁ HYGIENA                        │ vv.kod in ['3398']                                           │
│             5.5 │ vv.pocet*cena             │ STAROSTLIVOSŤ O CHORÉHO S PERMANENTNÝM KATÉTR │ vv.kod in ['3399A']                                          │
│                 │                           │ OM VRÁTANE JEHO VÝMENY                        │                                                              │
│            2.05 │ vv.pocet*cena             │ STAROSTLIVOSŤ O KAVALNÝ KATÉTER A INTRAVENÓZN │ vv.kod in ['3399B']                                          │
│                 │                           │ U KANYLU, PRAVIDELNE PREVÄZOVANIE A DEZINFEKC │                                                              │
│                 │                           │ IA                                            │                                                              │
│            2.05 │ vv.pocet*cena             │ STAROSTLIVOSŤ O EZOTRACHEÁLNU, NASOTRACHEÁLNU │ vv.kod in ['3399C']                                          │
│                 │                           │ A TRACHEOST. KANYLU                           │                                                              │
│            4.13 │ vv.pocet*cena             │ STAROSTLIVOSŤ O EPIDURÁLNY KATÉTER            │ vv.kod in ['3399D']                                          │
│            3.11 │ vv.pocet*cena             │ STAROSTLIVOSŤ O VÝŽIVU V PRÍSLUŠNEJ KVALITE A │ vv.kod in ['3401']                                           │
│                 │                           │ KVANTITE, VYPRACOVANIE INDIVIDUÁLNEHO DIETNEH │                                                              │
│                 │                           │ O REŽIMU, JEDEN RAZ PRE JEDNÉHO PACIENTA      │                                                              │
│            0.96 │ vv.pocet*cena             │ VÝŽIVA BEZVLÁDNEHO PACIENTA, ZA JEDEN VÝKON   │ vv.kod in ['3402']                                           │
│            1.36 │ vv.pocet*cena             │ VÝŽIVA PACIENTA SONDOU, ZA JEDEN VÝKON        │ vv.kod in ['3404']                                           │
│             4.4 │ vv.pocet*cena             │ OČISTNÁ KLYZMA                                │ vv.kod in ['3405']                                           │
│            3.38 │ vv.pocet*cena             │ KONTINUÁLNE SLEDOVANIE KLINICKÉHO STAVU PACIE │ vv.kod in ['3406']                                           │
│                 │                           │ NTA ZA KAŽDÉ DVE HODINY                       │                                                              │
│            1.02 │ vv.pocet*cena             │ ODMERANIE KRVNÉHO TLAKU, PULZU A TEPLOTY      │ vv.kod in ['3407']                                           │
│            0.85 │ vv.pocet*cena             │ SLEDOVANIE DIURÉZY, ZA KAŽDÝCH 12 HODÍN       │ vv.kod in ['3408']                                           │
│             2.2 │ vv.pocet*cena             │ CIEVKOVANIE ŽENY                              │ vv.kod in ['3409']                                           │
│            2.75 │ vv.pocet*cena             │ VÝMENA STOMICKÉHO SETU S NÁSLEDNOU TOALETOU P │ vv.kod in ['3410']                                           │
│                 │                           │ RI STÓMIACH                                   │                                                              │
│            0.85 │ vv.pocet*cena             │ ČISTENIE TRACHEÁLNEJ KANYLY                   │ vv.kod in ['3411']                                           │
│            0.74 │ vv.pocet*cena             │ APLIKÁCIA NEINJEKČNEJ LIEČBY                  │ vv.kod in ['3413']                                           │
│            1.19 │ vv.pocet*cena             │ APLIKÁCIA TERAPEUTICKÉHO CELOTELOVÉHO ZÁBALU  │ vv.kod in ['3414']                                           │
│                 │                           │ ALEBO LIEČIVÉHO KÚPEĽA                        │                                                              │
│            1.38 │ vv.pocet*cena             │ APLIKÁCIA LIEČIVA INTRAMUSKULÁRNE, S.C., I.C  │ vv.kod in ['3416']                                           │
│             1.7 │ vv.pocet*cena             │ APLIKÁCIA LIEČIVA INTRAVENÓZNE                │ vv.kod in ['3418']                                           │
│            3.42 │ vv.pocet*cena             │ PRÍPRAVA A PODÁVANIE INFÚZIE                  │ vv.kod in ['3419']                                           │
│            5.83 │ vv.pocet*cena             │ SLEDOVANIE INFÚZIE, ZA KAŽDÚ HODINU           │ vv.kod in ['3420']                                           │
│            1.02 │ vv.pocet*cena             │ PODÁVANIE LIEČIVA INFÚZNOU PUMPOU             │ vv.kod in ['3420A']                                          │
│             2.2 │ vv.pocet*cena             │ NÁCVIK PODÁVANIA INZULÍNU                     │ vv.kod in ['3421']                                           │
│            4.13 │ vv.pocet*cena             │ OŠETROVATEĽSKÁ STAROSTLIVOSŤ ZAMERANÁ NA PREV │ vv.kod in ['3422AA']                                         │
│                 │                           │ ENCIU DEKUBITOV                               │                                                              │
│            6.88 │ vv.pocet*cena             │ OŠETRENIE DEKUBITU VEĽKOSTI DO 5 CM2          │ vv.kod in ['3422B']                                          │
│            9.62 │ vv.pocet*cena             │ OŠETRENIE DEKUBITU VEĽKOSTI NAD 5 CM2         │ vv.kod in ['3422C']                                          │
│            2.39 │ vv.pocet*cena             │ VÝPLACH OKA                                   │ vv.kod in ['3423']                                           │
│            4.13 │ vv.pocet*cena             │ PREVÄZ RANY VEĽKOSTI DO 5 CM2                 │ vv.kod in ['3423A']                                          │
│            6.88 │ vv.pocet*cena             │ PREVÄZ RANY VEĽKOSTI NAD 5 CM2                │ vv.kod in ['3423B']                                          │
│            4.24 │ vv.pocet*cena             │ OŠETROVATEĽSKÁ REHABILITÁCIA,TRVANIE NAJVIAC  │ vv.kod in ['3424']                                           │
│                 │                           │ 30 MINÚT                                      │                                                              │
│             1.4 │ vv.pocet*cena             │ ODSÁVANIE PACIENTA                            │ vv.kod in ['3426']                                           │
│            3.51 │ vv.pocet*cena             │ ODSATIE ŽALÚDOČNÉHO OBSAHU                    │ vv.kod in ['3427']                                           │
│            3.38 │ vv.pocet*cena             │ VYŠETRENIE MOČU INDIKÁTOROVÝM MÉDIOM          │ vv.kod in ['3428']                                           │
│            0.93 │ vv.pocet*cena             │ ASISTENCIA PRI VÝPLACHU MOČOVÉHO MECHÚRA      │ vv.kod in ['3431']                                           │
│            5.84 │ vv.pocet*cena             │ PRÁCA SESTRY PRI DOMÁCEJ PERITONEÁLNEJ DIALÝZ │ vv.kod in ['3432']                                           │
│                 │                           │ E                                             │                                                              │
│            5.34 │ vv.pocet*cena             │ ODBER KRVI VENEPUNKCIOU DO JEDNEJ STRIEKAČKY  │ vv.kod in ['3433']                                           │
│                 │                           │ ALEBO JEDNEJ ODB. SÚPRAVY                     │                                                              │
│            0.85 │ vv.pocet*cena             │ ODBER KAPILÁRNEJ KRVI                         │ vv.kod in ['3434']                                           │
│            6.88 │ vv.pocet*cena             │ UMELÉ DÝCHANIE A MASÁŽ SRDCA                  │ vv.kod in ['3435']                                           │
│            1.65 │ vv.pocet*cena             │ ODBERY: TT, TN, VÝTER Z REKTA, ODBER SPÚTA    │ vv.kod in ['3436']                                           │
│            0.68 │ vv.pocet*cena             │ DOPRAVA BIOLOGICKÉHO MATERIÁLU                │ vv.kod in ['3437']                                           │
│            4.88 │ vv.pocet*cena             │ NÁVŠTEVA PACIENTA (KLIENTA) V PRACOVNOM ČASE  │ vv.kod in ['3439']                                           │
│            9.12 │ vv.pocet*cena             │ NÁVŠTEVA MIMO RIADNEHO PRACOVNÉHO ČASU (OD 19 │ vv.kod in ['3440']                                           │
│                 │                           │ .00 DO 7.00 HODINY V SOBOTU, V NEDEĽU A VO SV │                                                              │
│                 │                           │ IATOK)                                        │                                                              │
│            5.83 │ vv.pocet*cena             │ NÁVŠTEVA PACIENTA V RIZIKOVÝCH SKUPINÁCH POPU │ vv.kod in ['3441']                                           │
│                 │                           │ LÁCIE - KRÍZOVA INTERVENCIA PRI ZHORŠENÍ PSYC │                                                              │
│                 │                           │ HICKÉHO STAVU PACIENTA                        │                                                              │
│            2.75 │ vv.pocet*cena             │ PSYCHOSOMATICKÁ INTERVENCIA V TERMINÁLNOM ŠTÁ │ vv.kod in ['3447']                                           │
│                 │                           │ DIU ŽIVOTA                                    │                                                              │
│             3.3 │ vv.pocet*cena             │ KONTINUÁLNA STAROSTLIVOSŤ O UMIERAJÚCEHO PACI │ vv.kod in ['3449']                                           │
│                 │                           │ ENTA, ZA KAŽDÚ HODINU                         │                                                              │
│            0.68 │ vv.pocet*cena             │ KONZULTÁCIA SESTRY O JEDNOM PACIENTOVI S OŠET │ vv.kod in ['3451']                                           │
│                 │                           │ RUJÚCIM LEKÁROM                               │                                                              │
│            6.88 │ vv.pocet*cena             │ POSKYTNUTIE PREDLEKÁRSKEJ POMOCI PRI NÁHLYCH  │ vv.kod in ['3452']                                           │
│                 │                           │ STAVOCH OHROZUJÚCICH ŽIVOT                    │                                                              │
│            5.08 │ vv.pocet*cena             │ VERBÁLNA INTERVENCIA  PRI PSYCHOSOMATICKÝCH Ť │ vv.kod in ['3458']                                           │
│                 │                           │ AŽKOSTIACH U PACIENTA S NÁDOROVÝM OCHORENÍM   │                                                              │
│            4.23 │ vv.pocet*cena             │ OŠETRENIE DUTINY ÚSTNEJ U ONKOLOGICKÉHO PACIE │ vv.kod in ['3461']                                           │
│                 │                           │ NTA ALEBO U PACIENTA S IMUNODEFICIENTNYM STAV │                                                              │
│                 │                           │ OM                                            │                                                              │
│            1.02 │ vv.pocet*cena             │ KONTROLA GLYKÉMIE GLUKOMEROM                  │ vv.kod in ['3635A']                                          │
│            0.77 │ vv.pocet*cena             │ HYGIENA POŠVY ZA ÚĆELOM LIEČEBNÝM             │ vv.kod in ['3474']                                           │
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

