                                                                         =============
                                                                         Cenník hospic
                                                                         =============

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬──────────────────────────────┐
│ Názov a hodnota    │ Popis                        │
├────────────────────┼──────────────────────────────┤
│ IPP1 = 1.17        │ IPP1                         │
│ IPP2 = 1.89        │ IPP2                         │
│ IPP3 = 3.19        │ IPP3                         │
│ ZCB = 0            │ Zvýhodnená cena bodu         │
│ CBD = 0.37         │ Cena bodu doprava do 60km    │
│ CBD60plus = 0.185  │ Cena bodu doprava nad 60km   │
│ LIMIT = 0          │ Limit                        │
│ CB = 0.0192        │ Cena bodu                    │
│ CBP = 6.88         │ Cena bodu preventívne výkony │
│ CBSVALZ = 0.019002 │ Cena bodu SVaLZ              │
└────────────────────┴──────────────────────────────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│            0.37 │ vv.pocet*CBD              │ Doprava:  do 60 km                            │ vv.kod in ['doprava'] && vv.pocet < 60                       │
│           0.185 │ vv.pocet*CBD60plus        │ Doprava:  + 60 km                             │ vv.kod in ['doprava'] && vv.pocet >= 60                      │
│              95 │ vv.pocet*cena             │ Návšteva osoby v paliatívnej starostlivosti v │ vv.kod in ['25M']                                            │
│                 │                           │ domácom prostredí                             │                                                              │
│             110 │ vv.pocet*cena             │ Urgentná návšteva osoby v paliatívnej starost │ vv.kod in ['27']                                             │
│                 │                           │ livosti - lekár a sestra mimo riadneho prac.  │                                                              │
│                 │                           │ času                                          │                                                              │
│              30 │ vv.pocet*cena             │ NÁVŠTEVA PACIENTA (KLIENTA) V PRACOVNOM ČASE  │ vv.kod in ['3439']                                           │
│              35 │ vv.pocet*cena             │ NÁVŠTEVA MIMO RIADNEHO PRACOVNÉHO ČASU (OD 19 │ vv.kod in ['3440']                                           │
│                 │                           │ .00 DO 7.00 HODINY V SOBOTU, V NEDEĽU A VO SV │                                                              │
│                 │                           │ IATOK)                                        │                                                              │
│        0.025903 │ vv.bodyCelkom*1.75*CB     │ Výkony - imobilný                             │ p.fs=='I'                                                    │
│        0.025903 │ vv.bodyCelkom*1.5*CB      │ Výkony - obmedzemá hybnosť                    │ p.fs=='H'                                                    │
│        0.025903 │ vv.bodyCelkom*1.5*CB      │ Výkony - psychiatrická diagnóza, kompenzovaný │ p.fs=='FK'                                                   │
│        0.025903 │ vv.bodyCelkom*1.75*CB     │ Výkony - psychiatrická diagnóza, dekompenzova │ p.fs=='FD'                                                   │
│                 │                           │ ný                                            │                                                              │
│        0.025903 │ vv.bodyCelkom*1.75*CB     │ Výkony - mentálná retardácia                  │ p.fs=='R'                                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│        0.027614 │ vv.bodyCelkom*cena        │ Výkony - iné ako SVALZ                        │ ZCB && vv.typ!='SVaLZ'                                       │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             160 │ 1                                                                                                         │                           │
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

