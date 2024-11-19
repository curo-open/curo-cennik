                                                                           ==========
                                                                           Cenník VLD
                                                                           ==========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬─────────────────┐
│ Názov a hodnota │ Popis           │
├─────────────────┼─────────────────┤
│ IDK = 0         │ NASTAVENIA IDK  │
│ CB = 0.035      │ Cena bodu       │
│ CBSVALZ = 0.015 │ Cena bodu SVaLZ │
│ AGTC = 4.8      │ AGTC            │
│ PP50 = 10       │ PP50            │
│ FOB = 2         │ FOB             │
│ EDU = 2         │ EDU             │
└─────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌─────────────────┬───────────────┬──────────┬────────────────────┐
│ Popis           │ Premenná cena │ Vzorec   │ Podmienka          │
├─────────────────┼───────────────┼──────────┼────────────────────┤
│ vek od 18 do 51 │          2.83 │ IDK+cena │ p|vekMedzi(18, 51) │
│ vek od 51 do 61 │          3.03 │ IDK+cena │ p|vekMedzi(51, 61) │
│ vek od 61 do 81 │          4.15 │ IDK+cena │ p|vekMedzi(61, 81) │
│ vek od 81+      │           4.7 │ IDK+cena │ p|vekMedzi(81)     │
└─────────────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CB          │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 79a                                     │ vv.kod in ['79a']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 60                                      │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 64                                      │ vv.kod in ['64']                                             │
│            null │ vv.bodyCelkom*CB          │ Výkon 4                                       │ !p.kapitacia && vv.kod in ['4']                              │
│            null │ vv.bodyCelkom*CB          │ Výkon 8                                       │ !p.kapitacia && vv.kod in ['8']                              │
│               0 │ vv.bodyCelkom*cena        │ Výkon 4                                       │ vv.kod in ['4']                                              │
│               0 │ vv.bodyCelkom*cena        │ Výkon 8                                       │ vv.kod in ['8']                                              │
│            0.06 │ vv.bodyCelkom*cena        │ Preventívne prehliadky                        │ vv.kod in ['160']                                            │
│            0.06 │ vv.bodyCelkom*cena        │ Preventívne zisťovanie cukru v krvi           │ vv.kod in ['3671']                                           │
│               0 │ vv.bodyCelkom*cena        │ Očkovanie - kapitovaný                        │ vv.kod in ['252b']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti chrípke                       │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A                  │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde B                  │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti hepatitíde A+B                │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti meningitíde                   │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti pneumokokom                   │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti kliestovej encefalitide       │ !p.kapitacia && vv.kod in ['252b']                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti tetanu                        │ vv.kod in ['252b']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie proti osýpkam                       │ !p.kapitacia && vv.kod in ['252b']                           │
│          0.0082 │ vv.bodyCelkom*cena        │ EKG                                           │ vv.kod in ['5702']                                           │
│             4.5 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571A','4571a']                                  │
│            0.03 │ vv.bodyCelkom*cena        │ Návštevná služba                              │ vv.kod in ['25','26','29']                                   │
│           0.015 │ vv.bodyCelkom*cena        │ Vykony pocas navstevy                         │ d.vv|ma('kod in ["25","26","29"]') && vv.kod in ['4','5','6' │
│                 │                           │                                               │ ,'30','40','41','64']                                        │
│            9.68 │ vv.pocet*cena             │ TOKS pozitívny                                │ vv.kod in ['159a']                                           │
│            9.68 │ vv.pocet*cena             │ TOKS negatívny                                │ vv.kod in ['159z']                                           │
│            9.68 │ vv.pocet*cena             │ TOKS znehodnotený                             │ vv.kod in ['159x']                                           │
│           0.065 │ vv.bodyCelkom*cena        │ Cholesterol ako cast PP                       │ vv.kod in ['159b']                                           │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            4.74 │ vv.pocet*cena             │ EKG (5702Z)                                   │ vv.kod in ['5702Z']                                          │
│         0.00861 │ vv.bodyCelkom*cena        │ EKG (5702)                                    │ vv.kod in ['5702']                                           │
│             5.2 │ vv.pocet*cena             │ INR                                           │ vv.kod in ['3842a','H0007' ]                                 │
│            16.5 │ vv.pocet*cena             │ 24h meranie tlaku                             │ vv.kod in ['5715']                                           │
│         0.00924 │ vv.bodyCelkom*cena        │ USG                                           │ vv.kod in ['5300','5301']                                    │
│               6 │ vv.pocet*cena             │ ABI (H0008)                                   │ vv.kod in ['H0008']                                          │
│               6 │ vv.pocet*cena             │ Kognitívny deficit                            │ vv.kod in ['163']                                            │
│              12 │ vv.pocet*cena             │ Starostlivosť o poistenca s artériovou hypert │ vv.kod in ['10','H0003','H0004']                             │
│                 │                           │ enziou, dyslipidémiou a/alebo obezitou        │                                                              │
│             5.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│            10.2 │ vv.pocet*cena             │ Skríningový antigénový test SARS-CoV-2 imunof │ vv.kod in ['629b']                                           │
│                 │                           │ luorerscenčnou metódou                        │                                                              │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│            null │ PP50                      │ Pripočitateľné položky                        │ vv.kod=='PP50'                                               │
│            null │ FOB                       │ Pripočitateľné položky                        │ vv.kod=='FOB'                                                │
│            null │ EDU                       │ Pripočitateľné položky                        │ vv.kod=='EDU'                                                │
│               1 │ vv.pocet*cena             │ Výplach zvukovodu (jedno ucho)                │ vv.kod in ['1540']                                           │
│               5 │ vv.pocet*cena             │ Stratifikácia kardiovaskulárneho rizika       │ vv.kod in ['H0006']                                          │
│             NaN │ vv.pocet*cena             │ Komplexné vyšetrenie poistenca pri prevzatí d │ vv.kod in ['60']                                             │
│                 │                           │ ospelej osoby do zdravotnej starostlivosti    │                                                              │
│              10 │ vv.pocet*cena             │ Očkovanie Covid 252L                          │ !p.kapitacia && vv.kod in ['252L']                           │
│             7.5 │ vv.pocet*cena             │ Očkovanie Covid 252K                          │ !p.kapitacia && vv.kod in ['252K']                           │
│            1.05 │ vv.pocet*cena             │ Delegovaný odber krvi                         │ vv.kod in ['250D']                                           │
│             NaN │ vv.pocet*cena             │ Stanovenie D-diméru                           │ vv.kod in ['3860']                                           │
│             NaN │ vv.pocet*cena             │ Stanovenie TroponínuT                         │ vv.kod in ['4485']                                           │
│             NaN │ vv.pocet*cena             │ N-terminálny fragment (NT-pro BNP)            │ vv.kod in ['44418']                                          │
│        0.020995 │ vv.bodyCelkom*cena        │ Špecializovaná zdravotná starostlivosť pre po │ vv.kod in ['5766R','5708R','15bR','1227R','1255R','1544aR',' │
│                 │                           │ jicajtov, hasičov a záchranárov               │ 5708R','1205R','1591R','160R','250bR','3525R','3592R','252bR │
│                 │                           │                                               │ ','3784R','3671R','3679R','3693R','3692R','3674aR','3677aR', │
│                 │                           │                                               │ '5051R','FotoR','PACSR','5702R']                             │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - Bezdomovec, Cudzinec, EU       │ !p.kapitacia && p.typ in ['BE','CU','EU']                    │
│            null │ vv.bodyCelkom*CBSVLAZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
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

