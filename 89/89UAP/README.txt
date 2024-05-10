                                                                        ===============
                                                                        Cenník pediater
                                                                        ===============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────────────────────┐
│ Názov a hodnota │ Popis                 │
├─────────────────┼───────────────────────┤
│ IDK = 1.2       │ IDK                   │
│ KPS = 1         │ KPS                   │
│ EL_POBOCKA = 1  │ Používa el. pobočku ? │
│ AGTC = 4.8      │ AGTC                  │
│ PP50 = 10       │ PP50                  │
│ PP05 = 10       │ PP05                  │
└─────────────────┴───────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            0.08 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143U', '143aU', '144U', '145U', '145aU', '146U', │
│                 │                           │                                               │ '146aU', '146bU', '146cU', '148U', '148aU', '148bU', '148cU' │
│                 │                           │                                               │ , '149U', '149aU', '149bU', '149cU', '149dU', '159bU', '950U │
│                 │                           │                                               │ ', '951U','952U','953U']                                     │
│            0.08 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['160U']                                           │
│         0.11187 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142U']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252bU']                                          │
│          0.0318 │ vv.bodyCelkom*cena        │ Rozbor a plánovanie cielených terapeutických  │ vv.kod in ['10U']                                            │
│                 │                           │ postupov v na ovplyvnenie                     │                                                              │
│                 │                           │ chronických ochorení                          │                                                              │
│           0.027 │ vv.bodyCelkom*cena        │ Telekomunikácia                               │ vv.kod in ['1BU','70U','11AU']                               │
│          0.0318 │ vv.bodyCelkom*cena        │ Komplexné vyšetrenie pri prevzatí do starostl │ vv.kod in ['60U']                                            │
│                 │                           │ ivosti                                        │                                                              │
│           0.029 │ vv.bodyCelkom*cena        │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67U']                                            │
│                 │                           │ nie do 5 roku života                          │                                                              │
│          0.0339 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25U','26U']                                      │
│            5.75 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571AU']                                         │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60BU']                                           │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62AU']                                           │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│               2 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250dU']                                          │
│            6.22 │ vv.pocet*cena             │ Intenzifikovaná zdravotná starostlivosť pre r │ vv.kod in ['H0002U']                                         │
│                 │                           │ izikových poistencov s obezitou               │                                                              │
│            null │ PP05                      │ Pripočitateľné položky                        │ vv.kod=='PP05'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│        0.009574 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaLZ                                   │
│          0.0339 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaLZ                                  │
│             6.5 │ vv.pocet*cena             │ UAO - KPU                                     │ vv.kod in ['KPU']                                            │
│            0.08 │ vv.bodyCelkom*cena        │ Preventívne zdravotné výkony                  │ vv.kod in ['143U', '143aU', '144U', '145U', '145aU', '146U', │
│                 │                           │                                               │ '146aU', '146bU', '146cU', '148U', '148aU', '148bU', '148cU' │
│                 │                           │                                               │ , '149U', '149aU', '149bU', '149cU', '149dU', '159bU', '950U │
│                 │                           │                                               │ ', '951U','952U','953U']                                     │
│            0.08 │ vv.bodyCelkom*cena        │ Preventívna prehliadka                        │ vv.kod in ['160U']                                           │
│         0.11187 │ vv.bodyCelkom*cena        │ Preventivne zdravotne vykony (142)            │ vv.kod in ['142U']                                           │
│            0.08 │ vv.bodyCelkom*cena        │ Očkovanie                                     │ vv.kod in ['252bU']                                          │
│          0.0318 │ vv.bodyCelkom*cena        │ Rozbor a plánovanie cielených terapeutických  │ vv.kod in ['10U']                                            │
│                 │                           │ postupov v na ovplyvnenie                     │                                                              │
│                 │                           │ chronických ochorení                          │                                                              │
│           0.027 │ vv.bodyCelkom*cena        │ Telekomunikácia                               │ vv.kod in ['1BU','70U','11AU']                               │
│          0.0318 │ vv.bodyCelkom*cena        │ Komplexné vyšetrenie pri prevzatí do starostl │ vv.kod in ['60U']                                            │
│                 │                           │ ivosti                                        │                                                              │
│           0.029 │ vv.bodyCelkom*cena        │ Príplatok pri sťaženom výkone - odber, očkova │ vv.kod in ['67U']                                            │
│                 │                           │ nie do 5 roku života                          │                                                              │
│          0.0339 │ vv.bodyCelkom*cena        │ Návšteva služba                               │ vv.kod in ['25U','26U']                                      │
│            5.75 │ vv.pocet*cena             │ CRP                                           │ vv.kod in ['4571AU']                                         │
│              16 │ vv.pocet*cena             │ Predoperačné vyšetrenie                       │ vv.kod in ['60BU']                                           │
│              20 │ vv.pocet*cena             │ Cielené vyšetrenie pacienta s respiračným syn │ vv.kod in ['62AU']                                           │
│                 │                           │ drómom pri pandémii COVID-19                  │                                                              │
│               2 │ vv.pocet*cena             │ Odbery                                        │ vv.kod in ['250dU']                                          │
│            6.22 │ vv.pocet*cena             │ Intenzifikovaná zdravotná starostlivosť pre r │ vv.kod in ['H0002U']                                         │
│                 │                           │ izikových poistencov s obezitou               │                                                              │
│            null │ PP05                      │ Pripočitateľné položky                        │ vv.kod=='PP05'                                               │
│            null │ AGTC                      │ Pripočitateľné položky                        │ vv.kod=='AGTC'                                               │
│          0.0318 │ vv.bodyCelkom*cena        │ Nekapitovaný - neodkladná starostlivosť       │ !p.kapitacia && d.od|ma('jeNeodkladna')                      │
│        0.009574 │ vv.bodyCelkom*cena        │ Nekapitovaný - SVALZ výkon                    │ !p.kapitacia && vv.jeSVaLZ                                   │
│          0.0339 │ vv.bodyCelkom*cena        │ Nekapitovaný - iné ako SVALZ                  │ !p.kapitacia && !vv.jeSVaLZ                                  │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│              40 │ 70                                                                                                        │                           │
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

