                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────────────────┐
│ Názov a hodnota │ Popis                      │
├─────────────────┼────────────────────────────┤
│ IDK = 0         │ NASTAVENIA IDK             │
│ CB = 0          │ Cena bodu                  │
│ CBSVALZ = 0.01  │ Cena bodu SVaLZ            │
│ CBEUNK = 0.0349 │ Cena bodu Nekapitovany(EU) │
│ AGTC = 4.8      │ AGTC                       │
│ PP50 = 10       │ PP50                       │
│ PP05 = 10       │ PP05                       │
└─────────────────┴────────────────────────────┘


  CENY ZA PACIENTA
┌───────────────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis                     │ Premenná cena │ Vzorec   │ Podmienka                         │
├───────────────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ do  1 roku                │         10.55 │ IDK+cena │ p.kapitacia && p|vekMedzi(0, 1)   │
│ od  1 do 2 rokov vratane  │          9.36 │ IDK+cena │ p.kapitacia && p|vekMedzi(1, 3)   │
│ od  3 do 5 rokov vratane  │          7.99 │ IDK+cena │ p.kapitacia && p|vekMedzi(3, 6)   │
│ od  6 do 14 rokov vratane │          5.47 │ IDK+cena │ p.kapitacia && p|vekMedzi(6, 15)  │
│ od 15 do 18 rokov vratane │          3.68 │ IDK+cena │ p.kapitacia && p|vekMedzi(15, 19) │
│ od 19 do 25 rokov vratane │          3.43 │ IDK+cena │ p.kapitacia && p|vekMedzi(19, 26) │
└───────────────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.1284 │ vv.bodyCelkom*cena        │ Výkon 142                                     │ vv.kod in ['142']                                            │
│          0.0845 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.diagnoza=='Z00.1' && vv.kod in ['143','143a','144','145', │
│                 │                           │                                               │ '145a','146','146a','146b','146c','148','148a','148b','148c' │
│                 │                           │                                               │ ,'149','149a','149b','149d','149f','159b','950','951','952', │
│                 │                           │                                               │ '953']                                                       │
│          0.0931 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony pre P07*         │ vv.diagnoza in ['P07.00','P07.01','P07.02','P07.10','P07.11' │
│                 │                           │                                               │ ,'P07.12'] && vv.kod in ['143','143a','144','145','145a','14 │
│                 │                           │                                               │ 6','146a','146b','146c','148']                               │
│          0.0845 │ vv.bodyCelkom*cena        │ Výkon 159b                                    │ vv.diagnoza=='Z00.1' && vv.kod in ['159b']                   │
│          0.0845 │ vv.bodyCelkom*cena        │ Výkon 3671                                    │ vv.diagnoza in ['Z00.1','Z00.0','Z52.00','Z52.01','Z52.08',' │
│                 │                           │                                               │ Z52.1','Z52.2','Z52.3','Z52.4','Z52.5','Z52.6','Z52.7','Z52. │
│                 │                           │                                               │ 81','Z52.82','Z52.89','Z52.9'] && vv.kod in ['3671']         │
│           30.85 │ vv.pocet*cena             │ Preventívna prehliadka                        │ vv.kod in ['160']                                            │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62a','62b']                                      │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti rotavirusom                   │ vv.diagnoza in ['Z25.8','Z26.8'] && vv.kod in ['252a']       │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ vv.diagnoza=='Z25.1' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti diftérii a tetanu, pertusis,  │ vv.diagnoza in ['Z23.8','Z27.1','Z27.3','Z27.8','Z00.1'] &&  │
│                 │                           │ polio,                                        │ vv.kod in ['252b']                                           │
│                 │                           │ hepatitídy typu B, hemofilus a povinného očko │                                                              │
│                 │                           │ vania proti pneumokokom                       │                                                              │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A                  │ vv.diagnoza in ['Z20.5','Z24.6'] && vv.kod in ['252b']       │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A+B                │ vv.diagnoza=='Z24.6' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti meningitíde                   │ vv.diagnoza in ['Z20.8','Z23.8','Z26.8'] && vv.kod in ['252b │
│                 │                           │                                               │ ']                                                           │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti varicelle                     │ vv.diagnoza=='Z26.8' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti pneumokokom                   │ vv.diagnoza=='Z23.8' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti kliestovej encefalitide       │ vv.diagnoza=='Z24.1' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti HPV u dievčat a chlapcov      │ vv.diagnoza=='Z25.8' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti osýpkam, rubeole, parotitíde  │ vv.diagnoza in ['Z27.4','Z27.8','Z24.4'] && vv.kod in ['252b │
│                 │                           │                                               │ ']                                                           │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti tetanu                        │ vv.diagnoza=='Z00.0' && vv.kod in ['252b']                   │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie proti proti ochoreniu COVID-19      │ vv.diagnoza in ['Z25.7','Z25.70','Z25.71','Z25.79'] && vv.ko │
│                 │                           │                                               │ d in ['252b']                                                │
│          0.0931 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│          0.0349 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25','26','29']                                   │
│          0.0349 │ vv.bodyCelkom*cena        │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29"]') && vv.kod in ['4','5','6' │
│                 │                           │                                               │ ,'29','30','40','41','67','140']                             │
│          0.0158 │ vv.bodyCelkom*cena        │ CRP                                           │ vv.kod in ['4571a','4571A']                                  │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','11a', '70']                                 │
│            5.25 │ vv.pocet*cena             │ Výkon 60                                      │ vv.kod in ['60']                                             │
│           17.51 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            4.77 │ vv.pocet*cena             │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67']                                             │
│                 │                           │ nie do 5 roku života                          │                                                              │
│            1.22 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250D']                                           │
│            0.01 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│            5.52 │ vv.pocet*cena             │ EKG                                           │ vv.kod in ['5702Z']                                          │
│            5.12 │ vv.pocet*cena             │ Otoskopické vyšetrenie jednostranne           │ vv.kod in ['1544a']                                          │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│              14 │ vv.pocet*cena             │ Starostlivosť o poistenca s obezitou, artério │ vv.kod in ['10']                                             │
│                 │                           │ vou hypertenziou a/alebo dyslipidémiou        │                                                              │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ PP05                      │ Pripočitateľné položky                        │ vv.kod=='PP05'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
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
├─────────────────────────────────┼────────────┼──────────────────────────────────────────────────────┼──────────────────────────────────────────────────────┤
│ Preventivný výkon 142 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["142"]')             │ pacient.vekDni|vTyzdnoch >= 0 || pacient.vekDni|vTyz │
│ leného rozpǎtia (1-4 tyždne)    │            │                                                      │ dnoch < 4                                            │
│ Preventivný výkon 143 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["143"]')             │ pacient.vekDni|vTyzdnoch >= 2 || pacient.vekDni|vTyz │
│ leného rozpǎtia (2-5 tyždne)    │            │                                                      │ dnoch < 5                                            │
│ Preventivný výkon 143a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["143a"]')            │ pacient.vekDni|vTyzdnoch >= 5 || pacient.vekDni|vTyz │
│ oleného rozpǎtia (5-8 tyždne)   │            │                                                      │ dnoch < 8                                            │
│ Preventivný výkon 144 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["144"]')             │ pacient.vekDni|vTyzdnoch >= 8 || pacient.vekDni|vTyz │
│ leného rozpǎtia (8-11 tyždne)   │            │                                                      │ dnoch < 11                                           │
│ Preventivný výkon 145 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["145"]')             │ pacient.vekDni|vMesiacoch >= 3 || pacient.vekDni|vMe │
│ leného rozpǎtia (3-5 mesiacov)  │            │                                                      │ siacoch < 5                                          │
│ Preventivný výkon 145a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["145a"]')            │ pacient.vekDni|vMesiacoch >= 5 || pacient.vekDni|vMe │
│ oleného rozpǎtia (5-7 mesiacov) │            │                                                      │ siacoch < 7                                          │
│ Preventivný výkon 146 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["146"]')             │ pacient.vekDni|vMesiacoch >= 7 || pacient.vekDni|vMe │
│ leného rozpǎtia (7-9 mesiacov)  │            │                                                      │ siacoch < 9                                          │
│ Preventivný výkon 146a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146a"]')            │ pacient.vekDni|vMesiacoch >= 9 || pacient.vekDni|vMe │
│ oleného rozpǎtia (9-11 mesiacov │            │                                                      │ siacoch < 11                                         │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 146b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146b"]')            │ pacient.vekDni|vMesiacoch >= 11 || pacient.vekDni|vM │
│ oleného rozpǎtia (11-13 mesiaco │            │                                                      │ esiacoch < 13                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 146c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["146c"]')            │ pacient.vekDni|vMesiacoch >= 13 || pacient.vekDni|vM │
│ oleného rozpǎtia (13-24 mesiaco │            │                                                      │ esiacoch < 24                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["148"]')             │ pacient.vekDni|vMesiacoch >= 25 || pacient.vekDni|vM │
│ leného rozpǎtia (25-48 mesiacov │            │                                                      │ esiacoch < 48                                        │
│ )                               │            │                                                      │                                                      │
│ Preventivný výkon 148a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148a"]')            │ pacient.vekDni|vMesiacoch >= 49 || pacient.vekDni|vM │
│ oleného rozpǎtia (49-60 mesiaco │            │                                                      │ esiacoch < 60                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148b"]')            │ pacient.vekDni|vMesiacoch >= 61 || pacient.vekDni|vM │
│ oleného rozpǎtia (61-84 mesiaco │            │                                                      │ esiacoch < 84                                        │
│ v)                              │            │                                                      │                                                      │
│ Preventivný výkon 148c mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["148c"]')            │ pacient.vekDni|vMesiacoch >= 97 || pacient.vekDni|vM │
│ oleného rozpǎtia (97-120 mesiac │            │                                                      │ esiacoch < 120                                       │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149 mimo dovo │     0      │ p.kapitacia && d.vv|ma('kod in ["149"]')             │ pacient.vekDni|vMesiacoch >= 121 || pacient.vekDni|v │
│ leného rozpǎtia (121-144 mesiac │            │                                                      │ Mesiacoch < 144                                      │
│ ov)                             │            │                                                      │                                                      │
│ Preventivný výkon 149a mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149a"]')            │ pacient.vekDni|vMesiacoch >= 145 || pacient.vekDni|v │
│ oleného rozpǎtia (145-168 mesia │            │                                                      │ Mesiacoch < 168                                      │
│ cov)                            │            │                                                      │                                                      │
│ Preventivný výkon 149b mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149b"]')            │ pacient.vekDni|vMesiacoch >= 169 || pacient.vekDni|v │
│ oleného rozpǎtia (169-192 mesia │            │                                                      │ Mesiacoch < 192                                      │
│ cov)                            │            │                                                      │                                                      │
│ Preventivný výkon 149d mimo dov │     0      │ p.kapitacia && d.vv|ma('kod in ["149d"]')            │ p.vek >= 16                                          │
│ oleného rozpǎtia (iiba v 17 rok │            │                                                      │                                                      │
│ u)                              │            │                                                      │                                                      │
│ Preventivka: chyba vykon(950),  │     0      │ p.kapitacia && vv.kod in ['145', '145a', '146', '146 │ !(d.vv|ma('kod=="950"'))                             │
│ môžte to vykázať                │            │ a', '146b', '146c']                                  │                                                      │
│ Preventivka: chyba vykon(3671), │     0      │ p.kapitacia && vv.kod in ['149', '149d']             │ !(d.vv|ma('kod=="3671"'))                            │
│ môžte to vykázať                │            │                                                      │                                                      │
│ Preventivka: chýba Cholesterol( │     0      │ p.kapitacia && vv.kod in ['149', '149d']             │ !(d.vv|ma('kod=="159b"'))                            │
│ 159b) vyšetrenie, môžte to vyká │            │                                                      │                                                      │
│ zať                             │            │                                                      │                                                      │
│ Výkon 1025 a 1590 sa nemože vyk │     0      │ p.kapitacia && vv.kod in ['143', '143a', '144', '145 │ d.vv|ma('kod=="1205"') || d.vv|ma('kod=="1590"')     │
│ azovať spolu s 143, 143a, 144,  │            │ ', '145a', '146', '146a', '146b', '146c', '148', '14 │                                                      │
│ 145, 145a, 146, 146a, 146b, 146 │            │ 8b', '148c', '149', '149a', '149b', '149f']          │                                                      │
│ c, 148, 148b, 148c, 149, 149a,  │            │                                                      │                                                      │
│ 149b, 149f                      │            │                                                      │                                                      │
│ Výkon 1025 a 1590 sa nemože vyk │     0      │ p.kapitacia && vv.kod in ['143', '143a', '144', '145 │ d.vv|ma('kod=="1205"') || d.vv|ma('kod=="1590"')     │
│ azovať spolu s 143, 143a, 144,  │            │ ', '145a', '146', '146a', '146b', '146c', '148', '14 │                                                      │
│ 145, 145a, 146, 146a, 146b, 146 │            │ 8b', '148c', '149', '149a', '149b', '149f']          │                                                      │
│ c, 148, 148b, 148c, 149, 149a,  │            │                                                      │                                                      │
│ 149b, 149f                      │            │                                                      │                                                      │
│ Výkon 950 sa nemože vykazovať s │     0      │ p.kapitacia && vv.kod in ['143', '143a', '144', '148 │ d.vv|ma('kod=="950"')                                │
│ polu s 143, 143a, 144, 148, 148 │            │ ', '148b', '148c', '149', '149a', '149b', '149f']    │                                                      │
│ b, 148c, 149, 149a, 149b, 149f  │            │                                                      │                                                      │
│ Výkon 953 sa nemože vykazovať s │     0      │ p.kapitacia && vv.kod in ['953']                     │ d.vv|ma('kod=="1531"')                               │
│ polu s 1531                     │            │                                                      │                                                      │
│ Preventivka(160) je vykázana po │     0      │ vv.kod in ['160']                                    │ vv.diagnoza in ['Z00.0','Z52.0']                     │
│ d zlou diagnózou                │            │                                                      │                                                      │
│ Očkovanie(252b) je vykázané pod │     0      │ vv.kod in ['252b']                                   │ !(vv.diagnoza in ['Z26.8', 'Z25.1', 'Z20.5', 'Z24.6' │
│ zlou diagnózou                  │            │                                                      │ , 'Z20.8', 'Z23.8', 'Z24.1', 'Z00.0'])               │
│ Preventivka(160) je vykázana po │     0      │ vv.kod in ['160']                                    │ vv.diagnoza in ['Z00.0','Z52.0']                     │
│ d zlou diagnózou                │            │                                                      │                                                      │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

