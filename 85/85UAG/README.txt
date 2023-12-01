                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────────┬──────────────────────────────┐
│ Názov a hodnota       │ Popis                        │
├───────────────────────┼──────────────────────────────┤
│ IDK = 0               │ IDK                          │
│ KPS = 1.58            │ KPS                          │
│ EL_POBOCKA = 1        │ Používa el. pobočku ?        │
│ CB = 0.0339           │ Cena bodu                    │
│ CBP = 0.065           │ Cena bodu preventívne výkony │
│ CBEU = 0.0339         │ Cena bodu EU                 │
│ CBSVALZ = 0.009574    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG          │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│             2.3 │ vv.pocet*cena             │ UAO - KPU                                     │ vv.kod in ['KPU']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Preventívny výkon                       │ vv.kod in ['157U','102U','105U']                             │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Vyšetrenie a rady v gravidite           │ vv.kod in ['103U']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Ultrazvuk vrátane biometrie a posúdenie │ vv.kod in ['108U']                                           │
│                 │                           │ vývoja orgánov                                │                                                              │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Kolposkopia                             │ vv.kod in ['1070U']                                          │
│          0.0318 │ vv.bodyCelkom*cena        │ UAO - Komplexné vyšetrenie                    │ vv.kod in ['60U']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Očkovanie                               │ vv.kod in ['252BU','252CU']                                  │
│            0.08 │ vv.bodyCelkom*cena        │ UAO - Cytologické vyšetrenie                  │ vv.kod in ['297U']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 11AU                              │ vv.kod in ['11AU']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 1BU                               │ vv.kod in ['1BU']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ UAO - Výkon 70U                               │ vv.kod in ['70U']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ UAO - Výkony 5303U,5305U,5308U                │ vv.kod in ['5303U','5305U','5308U']                          │
│        0.009574 │ vv.bodyCelkom*cena        │ UAO - Ultrazvuk vrátane biometrie plodu       │ vv.kod in ['5808U']                                          │
│         0.01917 │ vv.bodyCelkom*cena        │ UAO - Externé CTG                             │ vv.kod in ['118U']                                           │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný EU - SVALZ výkon                 │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný EU - iné ako SVALZ               │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Kapitovaný - SVALZ výkon                      │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Kapitovaný - iné ako SVALZ                    │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CBEU        │ Výkony                                        │ 1                                                            │
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

