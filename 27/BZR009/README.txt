                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌──────────────────────┬──────────────────────────────┐
│ Názov a hodnota      │ Popis                        │
├──────────────────────┼──────────────────────────────┤
│ IDK = 0.32           │ NASTAVENIA IDK               │
│ CB = 0.0349          │ Cena bodu                    │
│ CBP = 0.0801         │ Cena bodu preventívne výkony │
│ CBEU = 0.0349        │ Cena bodu EU                 │
│ CBSVALZ = 0.01       │ Cena bodu SVaLZ nekapitovaný │
│ CBSVALZEU = 0.01031  │ Cena bodu SVaLZ EU           │
│ CBSVALZUSG = 0.01031 │ Cena bodu SVaLZ USG          │
└──────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬─────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka           │
├───────────┼───────────────┼──────────┼─────────────────────┤
│ Kapitácia │          2.04 │ IDK+cena │ p|vekMedzi(15, 130) │
└───────────┴───────────────┴──────────┴─────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['100','102','103','105','157','108','1070']       │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│          0.0266 │ vv.bodyCelkom*cena        │ Výkon 118                                     │ vv.kod in ['118']                                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 122                                     │ p.kapitacia && vv.kod in ['122']                             │
│          0.0434 │ vv.bodyCelkom*cena        │ Výkon 297                                     │ vv.kod in ['297']                                            │
│          0.0801 │ vv.bodyCelkom*cena        │ Výkon 252b                                    │ p.kapitacia && vv.kod in ['252b']                            │
│            null │ vv.bodyCelkom*CB          │ Výkon 299a                                    │ !p.kapitacia && vv.kod in ['299a']                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 250a                                    │ !p.kapitacia && vv.kod in ['250a']                           │
│            0.02 │ vv.bodyCelkom*cena        │ Výkony SVALZ USG                              │ vv.diagnoza in ['Z'] && vv.kod in ['5303','5305']            │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkony SVALZ USG                              │ vv.kod in ['5301','5303','5305','5316','5807']               │
│         0.01107 │ vv.bodyCelkom*cena        │ Výkon 5308                                    │ vv.kod in ['5308']                                           │
│          0.0266 │ vv.bodyCelkom*cena        │ Výkon 5809                                    │ vv.kod in ['5809']                                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 60, 63                                  │ vv.kod in ['60','63']                                        │
│              20 │ vv.pocet*cena             │ Výkon 62a                                     │ vv.kod in ['62a']                                            │
│            0.01 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon a neodkladna       │ !p.kapitacia && d.od|ma('jeNeodkladna') && p.typ in ['EU'] & │
│                 │                           │                                               │ & vv.jeSVaZL                                                 │
│          0.0349 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ a neodkladna     │ !p.kapitacia && d.od|ma('jeNeodkladna') && p.typ in ['EU'] & │
│                 │                           │                                               │ & !vv.jeSVaZL                                                │
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
│              70 │ 252b                                                                                                      │                           │
│              70 │ 252C                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

