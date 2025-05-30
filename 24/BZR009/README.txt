                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬──────────────────────────────┐
│ Názov a hodnota   │ Popis                        │
├───────────────────┼──────────────────────────────┤
│ IDK = 0.441659    │ NASTAVENIA IDK               │
│ CB = 0.022089     │ Cena bodu                    │
│ CBP = 0.084       │ Cena bodu preventívne výkony │
│ CBEUNK = 0.022973 │ Cena bodu EU/Nekapitovaný    │
│ CBSVALZ = 0.0086  │ Cena bodu SVaLZ              │
│ CBUSG = 0.009281  │ Cena bodu USG                │
└───────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka          │
├───────────┼───────────────┼──────────┼────────────────────┤
│ Kapitácia │          2.08 │ IDK+cena │ p|vekMedzi(0, 120) │
└───────────┴───────────────┴──────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBP         │ Preventívne zdravotné výkony                  │ vv.kod in ['157','102','103','105','108','1070','297']       │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','11a','70']                                  │
│            null │ vv.bodyCelkom*CBUSG       │ Výkon SVALZ USG                               │ vv.diagnoza in ['Z'] && vv.kod in ['5301','5303','5305','530 │
│                 │                           │                                               │ 8','5316','5807','5809']                                     │
│            null │ vv.bodyCelkom*CBUSG       │ Výkon SVALZ USG                               │ vv.kod in ['5301','5303','5305','5308','5316','5807','5809'] │
│           0.084 │ vv.bodyCelkom*cena        │ Populačný skríning                            │ vv.kod in ['297']                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5304,5808                               │ vv.kod in ['5808','5304']                                    │
│            null │ vv.bodyCelkom*CB          │ Výkon 60, 63                                  │ vv.kod in ['60','63']                                        │
│            null │ vv.bodyCelkom*CBUSG       │ Výkon 5308                                    │ vv.kod in ['5308']                                           │
│            null │ vv.bodyCelkom*CB          │ Odber krvi                                    │ !p.kapitacia && vv.kod in ['250a']                           │
│            null │ vv.bodyCelkom*CB          │ Odber biologického materiálu                  │ !p.kapitacia && vv.kod in ['299a']                           │
│            null │ vv.bodyCelkom*CB          │ Výkon 252, 252C                               │ !p.kapitacia && vv.kod in ['252','252C']                     │
│           0.084 │ vv.bodyCelkom*cena        │ Výkon 252b                                    │ !p.kapitacia && vv.kod in ['252b']                           │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaZL                                   │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaZL                                  │
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
│             160 │ 252b                                                                                                      │                           │
│             160 │ 252C                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

