                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IDK = 0.01      │ IDK                   │
│ KPS = 1         │ KPS                   │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────────────────────────┬───────────────┬──────────┬───────────────────────────────────┐
│ Popis                     │ Premenná cena │ Vzorec   │ Podmienka                         │
├───────────────────────────┼───────────────┼──────────┼───────────────────────────────────┤
│ do 1 roku                 │          6.63 │ IDK+cena │ p.kapitacia && p|vekMedzi(0, 1)   │
│ od 1 do 2 rokov vratane   │          5.85 │ IDK+cena │ p.kapitacia && p|vekMedzi(1, 3)   │
│ od 3 do 5 rokov vratane   │          5.01 │ IDK+cena │ p.kapitacia && p|vekMedzi(3, 6)   │
│ od 6 do 9 rokov vratane   │          3.37 │ IDK+cena │ p.kapitacia && p|vekMedzi(6, 10)  │
│ od 10 do 19 rokov vratane │          2.58 │ IDK+cena │ p.kapitacia && p|vekMedzi(10, 20) │
│ od 20 do 28 rokov vratane │          2.03 │ IDK+cena │ p.kapitacia && p|vekMedzi(20, 29) │
└───────────────────────────┴───────────────┴──────────┴───────────────────────────────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│        0.006639 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|has('jeNeodkladna')                     │
│        0.007303 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaZL                                   │
│        0.018257 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaZL                                  │
│           0.041 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143', '143a', '144', '145', '145a', '146', '146a │
│                 │                           │                                               │ ', '146b', '146c', '148', '148a', '148b', '148c', '149', '14 │
│                 │                           │                                               │ 9a', '149b', '149c', '149d', '159b', '950', '953']           │
│           0.041 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['160']                                            │
│           0.041 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142']                                            │
│           0.041 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252b']                                           │
│        0.016597 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25', '26']                                       │
│             4.4 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571a']                                          │
│              13 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60b']                                            │
│            1.05 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250D']                                           │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

