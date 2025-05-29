                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬─────────────────┐
│ Názov a hodnota │ Popis           │
├─────────────────┼─────────────────┤
│ IDK = 0         │ NASTAVENIA IDK  │
│ CB = 0          │ Cena bodu       │
│ CBEU = 0.0349   │ Cena bodu EU    │
│ CBSVALZ = 0.01  │ Cena bodu SVaLZ │
└─────────────────┴─────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬─────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka           │
├───────────┼───────────────┼──────────┼─────────────────────┤
│ Kapitácia │          2.03 │ IDK+cena │ p|vekMedzi(15, 130) │
└───────────┴───────────────┴──────────┴─────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0801 │ vv.bodyCelkom*cena        │ Výkon 100,102,103,105,157                     │ "Z" in vv.diagnoza && vv.kod in ['100','102','103','105','15 │
│                 │                           │                                               │ 7']                                                          │
│          0.0801 │ vv.bodyCelkom*cena        │ Výkon 108                                     │ "Z" in vv.diagnoza && vv.kod in ['108']                      │
│          0.0266 │ vv.bodyCelkom*cena        │ Výkon 118                                     │ "Z" in vv.diagnoza && vv.kod in ['118']                      │
│          0.0434 │ vv.bodyCelkom*cena        │ Výkon 297                                     │ "Z" in vv.diagnoza && vv.kod in ['297']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Výkon 252b                                    │ "Z" in vv.diagnoza && vv.kod in ['252b']                     │
│          0.0801 │ vv.bodyCelkom*cena        │ Výkon 1070                                    │ "Z" in vv.diagnoza && vv.kod in ['1070']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony 5303,5305                  │ "Z" in vv.diagnoza && vv.kod in ['5303','5305']              │
│         0.01107 │ vv.bodyCelkom*cena        │ Preventivny výkon 5308                        │ "Z" in vv.diagnoza && vv.kod in ['5308']                     │
│          0.0266 │ vv.bodyCelkom*cena        │ Preventívny výkon 5809                        │ "Z" in vv.diagnoza && vv.kod in ['5809']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Výkony 5301, 5304,5316,5807,5808              │ vv.kod in ['5301','5304','5316','5807','5808']               │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│              20 │ vv.pocet*cena             │ Covid 62a                                     │ vv.kod in ['62a']                                            │
│              25 │ vv.pocet*cena             │ Konzultačná - expertná kolposkopia            │ vv.kod in ['4M04004']                                        │
│              15 │ vv.pocet*cena             │ Punch biopsia                                 │ vv.kod in ['4M04007']                                        │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│            null │ vv.bodyCelkom*SVALZ       │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│            null │ vv.bodyCelkom*CBSVALZ     │ EÚ - SVALZ výkon                              │ p.typ in ['EU'] && vv.typ=='SVaLZ'                           │
│            null │ vv.bodyCelkom*CBEU        │ EÚ - iné ako SVALZ                            │ p.typ in ['EU'] && vv.typ!='SVaLZ'                           │
│         0.01031 │ vv.bodyCelkom*cena        │ Kapitovaný - SVALZ výkon                      │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CBEU        │ Kapitovaný - iné ako SVALZ                    │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CBEU        │ Výkony                                        │ 1                                                            │
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

