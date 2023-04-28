                                                                        ================
                                                                        Cenník gynekolog
                                                                        ================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌───────────────────┬──────────────────────────────┐
│ Názov a hodnota   │ Popis                        │
├───────────────────┼──────────────────────────────┤
│ IDK = 0.21        │ NASTAVENIA IDK               │
│ CB = 0.0305       │ Cena bodu                    │
│ CBO = 0.0305      │ Cena bodu ostatné ŠAS výkony │
│ CBP = 0.0583      │ Cena bodu preventívne výkony │
│ CBEU = 0.03       │ Cena bodu EU                 │
│ CBSVALZ = 0.00973 │ Cena bodu SVaLZ              │
└───────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬─────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka           │
├───────────┼───────────────┼──────────┼─────────────────────┤
│ Kapitácia │          1.84 │ IDK+cena │ p|vekMedzi(15, 130) │
└───────────┴───────────────┴──────────┴─────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && !(p.typ in ['EU'] │
│                 │                           │                                               │ ) && vv.typ=='SVaLZ'                                         │
│            null │ vv.bodyCelkom*CBSEUNK     │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && d.od|ma('jeNeodkladna') && !(p.typ in ['EU'] │
│                 │                           │                                               │ ) && vv.typ!='SVaLZ'                                         │
│          0.0735 │ vv.bodyCelkom*cena        │ Výkon 100,102,103,105,157                     │ "Z" in vv.diagnoza && vv.kod in ['100','102','103','105','15 │
│                 │                           │                                               │ 7']                                                          │
│          0.0735 │ vv.bodyCelkom*cena        │ Výkon 108                                     │ "Z" in vv.diagnoza && vv.kod in ['108']                      │
│          0.0266 │ vv.bodyCelkom*cena        │ Výkon 118                                     │ "Z" in vv.diagnoza && vv.kod in ['118']                      │
│          0.0398 │ vv.bodyCelkom*cena        │ Výkon 297                                     │ "Z" in vv.diagnoza && vv.kod in ['297']                      │
│          0.0583 │ vv.bodyCelkom*cena        │ Výkon 252b                                    │ "Z" in vv.diagnoza && vv.kod in ['252b']                     │
│          0.0735 │ vv.bodyCelkom*cena        │ Výkon 1070                                    │ "Z" in vv.diagnoza && vv.kod in ['1070']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony 5303,5305                  │ "Z" in vv.diagnoza && vv.kod in ['5303','5305']              │
│         0.01044 │ vv.bodyCelkom*cena        │ Preventivny výkon 5308                        │ "Z" in vv.diagnoza && vv.kod in ['5308']                     │
│          0.0266 │ vv.bodyCelkom*cena        │ Preventívny výkon 5309                        │ "Z" in vv.diagnoza && vv.kod in ['5309']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Výkony 5301, 5304,5316,5807,5808              │ vv.kod in ['5301','5304','5316','5807','5808']               │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['1b','1c','11a','70']                             │
│              20 │ vv.pocet*cena             │ Covid 62a                                     │ vv.kod in ['62a']                                            │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && d.od|ma('jeNeodkladna') && p.typ in ['EU'] & │
│                 │                           │                                               │ & vv.jeSVaZL                                                 │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nepreventivný - SVALZ výkon                   │ vv.jeSVaZL                                                   │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && d.od|ma('jeNeodkladna') && p.typ in ['EU'] & │
│                 │                           │                                               │ & !vv.jeSVaZL                                                │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
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

