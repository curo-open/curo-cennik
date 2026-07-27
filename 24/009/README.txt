                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬──────────────────────────────┐
│ Názov a hodnota   │ Popis                        │
├───────────────────┼──────────────────────────────┤
│ IDK = 0           │ NASTAVENIA IDK               │
│ CB = 0.022089     │ Cena bodu                    │
│ CBP = 0.062       │ Cena bodu preventívne výkony │
│ CBEUNK = 0.023193 │ Cena bodu EU/Nekapitovaný    │
│ CBSVALZ = 0.00903 │ Cena bodu SVaLZ              │
│ CBUSG = 0.008839  │ Cena bodu USG                │
│ KP = 2.16         │ Kapitačná platba             │
└───────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬─────────┬────────────────────┐
│ Popis     │ Premenná cena │ Vzorec  │ Podmienka          │
├───────────┼───────────────┼─────────┼────────────────────┤
│ Kapitácia │          null │ KP+IDK  │ p|vekMedzi(0, 120) │
└───────────┴───────────────┴─────────┴────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│        0.024122 │ vv.bodyCelkom*cena        │ Nekapitovaný - Neodkladna statostlivost       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 102        │ vv.kod in ['102']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 103        │ vv.kod in ['103']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 105        │ vv.kod in ['105']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 108        │ vv.kod in ['108']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 157        │ vv.kod in ['157']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 297        │ vv.kod in ['297']                                            │
│          0.0882 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 1070       │ vv.kod in ['1070']                                           │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5301                 │ "Z" in vv.diagnoza && vv.kod in ['5301']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5303                 │ "Z" in vv.diagnoza && vv.kod in ['5303']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5305                 │ "Z" in vv.diagnoza && vv.kod in ['5305']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5308                 │ "Z" in vv.diagnoza && vv.kod in ['5308']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5316                 │ "Z" in vv.diagnoza && vv.kod in ['5316']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5807                 │ "Z" in vv.diagnoza && vv.kod in ['5807']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5809                 │ "Z" in vv.diagnoza && vv.kod in ['5809']                     │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5301                 │ vv.kod in ['5301']                                           │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5316                 │ vv.kod in ['5316']                                           │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5807                 │ vv.kod in ['5807']                                           │
│            null │ vv.bodyCelkom*CBUSG       │ Preventivné výkony - vv. 5809                 │ vv.kod in ['5809']                                           │
│          0.0882 │ vv.bodyCelkom*cena        │ Výkon 252b                                    │ !p.kapitacia && vv.kod in ['252b']                           │
│          0.0882 │ vv.bodyCelkom*cena        │ Výkon 297                                     │ "Z12.4" in vv.diagnoza && vv.kod in ['297']                  │
│          0.0882 │ vv.bodyCelkom*cena        │ Výkon 297                                     │ "Z01.4" in vv.diagnoza && vv.kod in ['297']                  │
│        0.010232 │ vv.bodyCelkom*cena        │ Výkony 5303                                   │ vv.kod in ['5303']                                           │
│        0.010232 │ vv.bodyCelkom*cena        │ Výkony 5305                                   │ vv.kod in ['5305']                                           │
│        0.010232 │ vv.bodyCelkom*cena        │ Výkony 5308                                   │ vv.kod in ['5308']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5304                                    │ vv.kod in ['5304']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Výkon 5808                                    │ vv.kod in ['5808']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 1b                                      │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 11a                                     │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Výkon 70                                      │ vv.kod in ['70']                                             │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && !(p.typ in ['EU'] │
│                 │                           │                                               │ ) && vv.typ=='SVaLZ'                                         │
│            null │ vv.bodyCelkom*CBEUNK      │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && d.od|ma('jeNeodkladna') && !(p.typ in ['EU'] │
│                 │                           │                                               │ ) && vv.typ!='SVaLZ'                                         │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.typ=='SVaLZ'                              │
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && vv.typ!='SVaLZ'                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ Kapitovaný - SVALZ výkon                      │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Kapitovaný - iné ako SVALZ                    │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             650 │ 60                                                                                                        │                           │
│             650 │ 60                                                                                                        │                           │
│              40 │ 70                                                                                                        │                           │
│              50 │ 297                                                                                                       │                           │
│             160 │ 1b                                                                                                        │                           │
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

