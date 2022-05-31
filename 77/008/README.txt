                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────┬────────────────────────────┐
│ Názov a hodnota  │ Popis                      │
├──────────────────┼────────────────────────────┤
│ IDK = 0.01       │ NASTAVENIA IDK             │
│ CB = 0.02        │ Cena bodu                  │
│ CBSVALZ = 0.0082 │ Cena bodu SVaLZ            │
│ CBEUNK = 0.026   │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8       │ AGTC                       │
│ PP50 = 10        │ PP50                       │
└──────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌───────────────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis                     │ Premenná cena │ Vzorec   │ Podmienka          │
├───────────────────────────┼───────────────┼──────────┼────────────────────┤
│ do 1 roku                 │          7.49 │ IDK+cena │ p|vekMedzi(0, 1)   │
│ od 1 do 5 rokov vratane   │          5.89 │ IDK+cena │ p|vekMedzi(1, 6)   │
│ od 6 do 14 rokov vratane  │          4.07 │ IDK+cena │ p|vekMedzi(6, 15)  │
│ od 15 do 18 rokov vratane │          2.57 │ IDK+cena │ p|vekMedzi(15, 19) │
│ od 19 do 29 rokov vratane │          2.54 │ IDK+cena │ p|vekMedzi(19, 30) │
└───────────────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            0.09 │ vv.bodyCelkom*cena        │ Výkon 142                                     │ vv.kod in ['142']                                            │
│           0.053 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.diagnoza=='Z00.1' && vv.kod in ['143','143a','144','145', │
│                 │                           │                                               │ '145a','146','146a','146b','146c','148','148a','148b','148c' │
│                 │                           │                                               │ ,'149','149a','149b','149c','149d','149f','159b','950','953' │
│                 │                           │                                               │ ]                                                            │
│          0.0539 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.diagnoza in ['P07.00','P07.01','P07.02','P07.10','P07.11' │
│                 │                           │                                               │ ] && vv.kod in ['143','143a','144','145','145a','146','146a' │
│                 │                           │                                               │ ,'146b','146c','148']                                        │
│           0.053 │ vv.bodyCelkom*cena        │ Výkon 159b                                    │ vv.diagnoza=='Z00.1' && vv.kod in ['159b']                   │
│           0.053 │ vv.bodyCelkom*cena        │ Výkon 3671                                    │ vv.diagnoza in ['Z00.1','Z00.0','Z52.10'] && vv.kod in ['367 │
│                 │                           │                                               │ 1']                                                          │
│           19.35 │ vv.pocet*cena             │ Preventívna prehliadka                        │ vv.kod in ['160']                                            │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti rotavirusom                   │ vv.diagnoza in ['Z25.8','Z26.8'] && vv.kod in ['252a']       │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza=='Z25.1' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A                  │ vv.diagnoza in ['Z20.5','Z24.6'] && vv.kod in ['252b']       │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde B                  │ vv.diagnoza=='Z24.6' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti meningitíde                   │ vv.diagnoza in ['Z20.8','Z23.8'] && vv.kod in ['252b']       │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti varicelle                     │ vv.diagnoza=='Z26.8' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti pneumokokom                   │ vv.diagnoza=='Z23.8' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti kliestovej encefalitide       │ vv.diagnoza=='Z24.1' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti HPV u dievčat a chlapcov o    │ vv.diagnoza=='Z25.8' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie proti tetanu                        │ vv.diagnoza=='Z00.0' && vv.kod in ['252b']                   │
│            0.06 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│           0.025 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25','26','29']                                   │
│           0.015 │ vv.bodyCelkom*cena        │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29"]') && vv.kod in ['4','5','6' │
│                 │                           │                                               │ ,'29','30','40','41','67','140']                             │
│           0.012 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571a']                                          │
│           0.026 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','11a''70']                                   │
│             4.5 │ vv.pocet*cena             │ Výkon 60                                      │ vv.kod in ['60']                                             │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│             4.1 │ vv.pocet*cena             │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67']                                             │
│                 │                           │ nie do 5 roku života                          │                                                              │
│            1.05 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250D']                                           │
│            4.41 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702Z']                                          │
│             4.4 │ vv.pocet*cena             │ Otoskopické vyšetrenie jednostranne           │ vv.kod in ['1544a']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ vv.kod in ['252L']                                           │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│             8.8 │ vv.pocet*cena             │ Starostlivosť o poistenca s obezitou, artério │ vv.kod in ['10']                                             │
│                 │                           │ vou hypertenziou a/alebo dyslipidémiou        │                                                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && (p.typ in ['EU']) && vv.typ=='SVaLZ'         │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && (p.typ in ['EU']) && vv.typ!='SVaLZ'         │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
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

