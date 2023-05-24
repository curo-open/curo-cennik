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
│ CB = 0.08             │ Cena bodu                    │
│ CBP = 0.065           │ Cena bodu preventívne výkony │
│ CBEU = 0.0339         │ Cena bodu EU                 │
│ CBSVALZ = 0.009574    │ Cena bodu SVaLZ              │
│ CBSVALZUSG = 0.009574 │ Cena bodu SVaLZ USG          │
└───────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬────────────────────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka                          │
├───────────┼───────────────┼──────────┼────────────────────────────────────┤
│ Kapitácie │          1.84 │ IDK+cena │ p.kapitacia && p|vekMedzi(15, 120) │
└───────────┴───────────────┴──────────┴────────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            0.03 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CB          │ Preventívne zdravotné výkony                  │ vv.kod in ['157','102','103','105','108','1070','297']       │
│            null │ vv.bodyCelkom*CB          │ Výkon 252b, 252c                              │ vv.kod in ['252b','252C']                                    │
│         0.01917 │ vv.bodyCelkom*cena        │ Výkon 118                                     │ vv.kod in ['118']                                            │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkony 5303,5305,5308                         │ "Z" in vv.diagnoza && vv.kod in ['5303','5305','5308']       │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkony 5303,5305,5308                         │ vv.kod in ['5303','5305','5308']                             │
│        0.009574 │ vv.bodyCelkom*cena        │ Výkon 5808                                    │ vv.kod in ['5808']                                           │
│          0.0318 │ vv.bodyCelkom*cena        │ Výkon 60                                      │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*CBEU        │ Výkon 67                                      │ vv.kod in ['67']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína                                  │ vv.kod in ['11a','1b','70']                                  │
│             5.2 │ vv.pocet*cena             │ Skriningový antigénový test SARS-CoV-2        │ vv.kod in ['629a']                                           │
│              10 │ vv.pocet*cena             │ Skriningový poistencov. antigénový test SARS- │ vv.kod in ['629b']                                           │
│                 │                           │ CoV-2 imun. metód.                            │                                                              │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ=='SVaLZ' │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && p.typ in ['BE','CU','EU'] && vv.typ!='SVaLZ' │
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│            null │ vv.bodyCelkom*CBSVALZ     │ Nekapitovaný - SVALZ výkon                    │ vv.jeSVaLZ                                                   │
│            null │ vv.bodyCelkom*CB          │ Nekapitovaný - iné ako SVALZ                  │ !vv.jeSVaLZ                                                  │
│            null │ vv.bodyCelkom*CBEU        │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             420 │ 60                                                                                                        │                           │
│             200 │ 67                                                                                                        │                           │
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

