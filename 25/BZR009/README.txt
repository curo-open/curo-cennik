                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬──────────────────────────────┐
│ Názov a hodnota       │ Popis                        │
├───────────────────────┼──────────────────────────────┤
│ IDK = 0.57            │ IDK                          │
│ KPS = 1.99            │ KPS                          │
│ EL_POBOCKA = 1        │ Používa el. pobočku ?        │
│ CB = 0.0318           │ Cena bodu                    │
│ CBP = 0.084           │ Cena bodu preventívne výkony │
│ CBEU = 0.035          │ Cena bodu EU                 │
│ CBSVALZ = 0.01        │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG          │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬────────────────────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka                          │
├───────────┼───────────────┼──────────┼────────────────────────────────────┤
│ Kapitácia │          2.13 │ IDK+cena │ p.kapitacia && p|vekMedzi(15, 120) │
└───────────┴───────────────┴──────────┴────────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBP         │ Preventívne zdravotné výkony                  │ vv.kod in ['157','102','103','105','108','1070','297']       │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70']                                  │
│            null │ vv.bodyCelkom*CBP         │ Odber krvi                                    │ !p.kapitacia && vv.kod in ['250a']                           │
│            null │ vv.bodyCelkom*CBP         │ Odber biologického materiálu                  │ !p.kapitacia && vv.kod in ['299a']                           │
│           0.084 │ vv.bodyCelkom*cena        │ Výkon 252b, 252c                              │ !p.kapitacia && vv.kod in ['252b','252C']                    │
│         0.01917 │ vv.bodyCelkom*cena        │ Výkon 118                                     │ vv.kod in ['118']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkon SVALZ USG                               │ vv.diagnoza in ['Z'] && vv.kod in ['5303','5305','5808']     │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkon SVALZ USG                               │ vv.kod in ['5303','5305','5808','5316' ]                     │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkon 5308                                    │ vv.kod in ['5308']                                           │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 60                                      │ vv.kod in ['60']                                             │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 63                                      │ !p.kapitacia && vv.kod in ['63']                             │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 63a                                     │ vv.kod in ['63a']                                            │
│            null │ vv.bodyCelkom*CBEU        │ Výkon 67                                      │ vv.kod in ['67']                                             │
│             5.2 │ vv.pocet*cena             │ Skriningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skriningový poistencov. antigénový test SARS- │ vv.kod in ['629b']                                           │
│                 │                           │ CoV-2 imun. metód.                            │                                                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaZL                                   │
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaZL                                  │
│            null │ vv.bodyCelkom*0           │ SVALZ výkon                                   │ p.kapitacia && vv.jeSVaZL                                    │
│            null │ vv.bodyCelkom*0           │ iné ako SVALZ                                 │ p.kapitacia && !vv.jeSVaZL                                   │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             420 │ 60                                                                                                        │                           │
│             200 │ 63                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│             320 │ 102                                                                                                       │                           │
│             200 │ 103                                                                                                       │                           │
│             250 │ 105                                                                                                       │                           │
│             350 │ 108                                                                                                       │                           │
│             230 │ 118                                                                                                       │                           │
│             220 │ 157                                                                                                       │                           │
│             120 │ 168                                                                                                       │                           │
│              50 │ 297                                                                                                       │                           │
│             150 │ 1070                                                                                                      │                           │
│            1000 │ 5303                                                                                                      │                           │
│            1200 │ 5305                                                                                                      │                           │
│            1500 │ 5308                                                                                                      │                           │
│             600 │ 5808                                                                                                      │                           │
│             160 │ 1b                                                                                                        │                           │
│            1000 │ 1c                                                                                                        │                           │
│             210 │ 11a                                                                                                       │                           │
│             100 │ 63a                                                                                                       │                           │
│              70 │ 252b                                                                                                      │                           │
│              70 │ 252c                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

