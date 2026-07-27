                                                                  ============================
                                                                  Cenník pediatricky gynekolog
                                                                  ============================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬────────────────────┐
│ Názov a hodnota │ Popis              │
├─────────────────┼────────────────────┤
│ IDK = 0.21      │ NASTAVENIA IDK     │
│ CB = 0.0363     │ Cena bodu          │
│ CBEU = 0.0349   │ Cena bodu EU       │
│ CBSVALZ = 0.01  │ Cena bodu SVaLZ    │
│ NCB = 0         │ Navysena cena bodu │
└─────────────────┴────────────────────┘


  CENY ZA PACIENTA
┌───────────┬───────────────┬──────────┬─────────────────────┐
│ Popis     │ Premenná cena │ Vzorec   │ Podmienka           │
├───────────┼───────────────┼──────────┼─────────────────────┤
│ Kapitácia │          1.97 │ IDK+cena │ p|vekMedzi(15, 130) │
└───────────┴───────────────┴──────────┴─────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 100        │ "Z" in vv.diagnoza && vv.kod in ['100']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 102        │ "Z" in vv.diagnoza && vv.kod in ['102']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 103        │ "Z" in vv.diagnoza && vv.kod in ['103']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 105        │ "Z" in vv.diagnoza && vv.kod in ['105']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony - vv. 157        │ "Z" in vv.diagnoza && vv.kod in ['157']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 108                   │ "Z" in vv.diagnoza && vv.kod in ['108']                      │
│          0.0266 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 118                   │ "Z" in vv.diagnoza && vv.kod in ['118']                      │
│          0.0434 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 297                   │ "Z" in vv.diagnoza && vv.kod in ['297']                      │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 252b                  │ "Z" in vv.diagnoza && vv.kod in ['252b']                     │
│          0.0801 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 1070                  │ "Z" in vv.diagnoza && vv.kod in ['1070']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony - vv. 5303                 │ "Z" in vv.diagnoza && vv.kod in ['5303']                     │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony - vv. 5305                 │ "Z" in vv.diagnoza && vv.kod in ['5305']                     │
│         0.01107 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 5308                  │ "Z" in vv.diagnoza && vv.kod in ['5308']                     │
│          0.0266 │ vv.bodyCelkom*cena        │ Preventívny výkon - vv. 5309                  │ "Z" in vv.diagnoza && vv.kod in ['5309']                     │
│          0.0266 │ vv.bodyCelkom*cena        │ Vyšetrenie šijového prejasnenia (NT) plodu -  │ "Z" in vv.diagnoza && vv.kod in ['5809']                     │
│                 │                           │ - vv. 5809                                    │                                                              │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon - vv.  5301                             │ vv.kod in ['5301']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon - vv.  5304                             │ vv.kod in ['5304']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon - vv.  5316                             │ vv.kod in ['5316']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon - vv.  5807                             │ vv.kod in ['5807']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Výkon - vv.  5808                             │ vv.kod in ['5808']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony - vv. 5303                 │ vv.kod in ['5303']                                           │
│            0.02 │ vv.bodyCelkom*cena        │ Preventívne výkony - vv. 5305                 │ vv.kod in ['5305']                                           │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína -  vv. 11a                       │ vv.kod in ['11a']                                            │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína -  vv. 11b                       │ vv.kod in ['1b']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína -  vv. 70                        │ vv.kod in ['70']                                             │
│           0.027 │ vv.bodyCelkom*cena        │ Telemedicína -  vv. 11c                       │ vv.kod in ['11c']                                            │
│              20 │ vv.pocet*cena             │ Covid 62a                                     │ vv.kod in ['62a']                                            │
│              25 │ vv.pocet*cena             │ Konzultačná - expertná kolposkopia            │ vv.kod in ['4M04004']                                        │
│              15 │ vv.pocet*cena             │ Punch biopsia                                 │ vv.kod in ['4M04007']                                        │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 60,62,63                          │ vv.kod in ['60']                                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 62                                │ vv.kod in ['62']                                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 63                                │ vv.kod in ['63']                                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 65                                │ vv.kod in ['65']                                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 66                                │ vv.kod in ['66']                                             │
│            null │ vv.bodyCelkom*(CB+NCB)    │ Výkon - vv. 67                                │ vv.kod in ['67']                                             │
│            null │ vv.bodyCelkom*CBEU        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ!='SVaLZ'   │
│            null │ vv.bodyCelkom*SVALZ       │ Nekapitovaný - neodkladná starostlivosť - SVA │ !p.kapitacia && d.od|ma('jeNeodkladna') && vv.typ=='SVaLZ'   │
│                 │                           │ LZ výkon                                      │                                                              │
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
│             420 │ 60                                                                                                        │                           │
│             270 │ 62                                                                                                        │                           │
│             210 │ 63                                                                                                        │                           │
│             200 │ 65                                                                                                        │                           │
│             320 │ 66                                                                                                        │                           │
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

