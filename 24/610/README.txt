                                                                          ===========
                                                                          Cenník ados
                                                                          ===========

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌────────────────────┬────────────────────────────┐
│ Názov a hodnota    │ Popis                      │
├────────────────────┼────────────────────────────┤
│ IPP1 = 0           │ IPP1                       │
│ IPP2 = 0           │ IPP2                       │
│ IPP3 = 0           │ IPP3                       │
│ CBD = 0.37         │ Cena bodu doprava do 60km  │
│ CBD60plus = 0.185  │ Cena bodu doprava nad 60km │
│ LIMIT = 0          │ Limit                      │
│ CB = 0.019719      │ Cena bodu                  │
│ CBSVALZ = 0.019719 │ Cena bodu SVaLZ            │
└────────────────────┴────────────────────────────┘


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
│            10.2 │ vv.pocet*cena             │ Návšteva sestry v rámci vyhľadávania TBC a ko │ vv.kod in ['25a']                                            │
│                 │                           │ ntroly DDOT.                                  │                                                              │
│            null │ vv.bodyCelkom*CB          │ Vyhodnotenie KOS a záverečná správa           │ vv.kod in ['3395']                                           │
│            null │ vv.bodyCelkom*CB          │ Odmeranie krvného tlaku, pulzu a teploty      │ vv.kod in ['3407']                                           │
│            null │ vv.bodyCelkom*CB          │ Aplikácia neinjekčnej liečby                  │ vv.kod in ['3413']                                           │
│            null │ vv.bodyCelkom*CB          │ Príprava a podávanie infúzie                  │ vv.kod in ['3419']                                           │
│            null │ vv.bodyCelkom*CB          │ Sledovanie infúzie, za každú hodinu           │ vv.kod in ['3420']                                           │
│            null │ vv.bodyCelkom*CB          │ Podávanie liečiva infúznou pumpou             │ vv.kod in ['3420a']                                          │
│            null │ vv.bodyCelkom*CB          │ Nácvik podávania inzulínu                     │ vv.kod in ['3421']                                           │
│            null │ vv.bodyCelkom*CB          │ Príprava materiálu a sterilizácia             │ vv.kod in ['3423c']                                          │
│            null │ vv.bodyCelkom*CB          │ Vyšetrenie moču indikátorovým médiom          │ vv.kod in ['3428']                                           │
│            null │ vv.bodyCelkom*CB          │ Odber krvi venepunkciou do jednej striekačky  │ vv.kod in ['3433']                                           │
│                 │                           │ alebo jednej odberovej súpravy                │                                                              │
│            null │ vv.bodyCelkom*CB          │ Odber kapilárnej krvi                         │ vv.kod in ['3434']                                           │
│            null │ vv.bodyCelkom*CB          │ Doprava biologického materiálu, za každých 30 │ vv.kod in ['3437']                                           │
│                 │                           │ minút                                         │                                                              │
│            null │ vv.bodyCelkom*CB          │ Návšteva pacienta (klienta) v pracovnom čase  │ vv.kod in ['3439']                                           │
│            null │ vv.bodyCelkom*CB          │ Návšteva mimo riadneho pracovného času (od 19 │ vv.kod in ['3440']                                           │
│                 │                           │ .00 do 7.00 h v sobotu, v nedeľu a vo sviatok │                                                              │
│                 │                           │ )                                             │                                                              │
│            null │ vv.bodyCelkom*CB          │ Návšteva pacienta v rizikových skupinách popu │ vv.kod in ['3441']                                           │
│                 │                           │ lácie - krízová intervencia pri zhoršení psyc │                                                              │
│                 │                           │ hického stavu pacienta                        │                                                              │
│            null │ vv.bodyCelkom*CB          │ Psychosomatická intervencia v terminálnom štá │ vv.kod in ['3447']                                           │
│                 │                           │ diu života                                    │                                                              │
│            null │ vv.bodyCelkom*CB          │ Konzultácia sestry o jednom pacientovi s ošet │ vv.kod in ['3451']                                           │
│                 │                           │ rujúcim lekárom                               │                                                              │
│            null │ vv.bodyCelkom*CB          │ Depistáž ochorenia v mieste bydliska          │ vv.kod in ['3454']                                           │
│            null │ vv.bodyCelkom*CB          │ Podávanie cytostatík do zavedeného katétra    │ vv.kod in ['3457']                                           │
│            null │ vv.bodyCelkom*CB          │ Verbálna intervencia pri psychosomatických ta │ vv.kod in ['3458']                                           │
│                 │                           │ žkostiach u pacienta s nádorovým ochorením    │                                                              │
│            null │ vv.bodyCelkom*CB          │ Ochranný režim pri podávaní cytostatík a chem │ vv.kod in ['3460']                                           │
│                 │                           │ oterapeutík                                   │                                                              │
│            null │ vv.bodyCelkom*CB          │ Kontrola glykémie glukomerom                  │ vv.kod in ['3635a']                                          │
│            null │ vv.bodyCelkom*1.75*CB     │ Výkony - imobilný                             │ p.fs=='I'                                                    │
│            null │ vv.bodyCelkom*1.5*CB      │ Výkony - obmedzemá hybnosť                    │ p.fs=='H'                                                    │
│            null │ vv.bodyCelkom*1.5*CB      │ Výkony - psychiatrická diagnóza, kompenzovaný │ p.fs=='FK'                                                   │
│            null │ vv.bodyCelkom*1.75*CB     │ Výkony - psychiatrická diagnóza, dekompenzova │ p.fs=='FD'                                                   │
│                 │                           │ ný                                            │                                                              │
│            null │ vv.bodyCelkom*1.75*CB     │ Výkony - mentálná retardácia                  │ p.fs=='R'                                                    │
│            null │ vv.bodyCelkom*CBSVALZ     │ SVALZ výkony                                  │ vv.typ=='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony - iné ako SVALZ                        │ vv.typ!='SVaLZ'                                              │
│            null │ vv.bodyCelkom*CB          │ Výkony                                        │ 1                                                            │
└─────────────────┴───────────────────────────┴───────────────────────────────────────────────┴──────────────────────────────────────────────────────────────┘


  BODY ZA VÝKONY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│     Počet bodov │ Kódy výkonov                                                                                              │ Podmienka                 │
├─────────────────┼───────────────────────────────────────────────────────────────────────────────────────────────────────────┼───────────────────────────┤
│             160 │ 3419                                                                                                      │                           │
│             140 │ 3420                                                                                                      │                           │
│             150 │ 3424                                                                                                      │                           │
│             260 │ 3439                                                                                                      │                           │
│             390 │ 3440                                                                                                      │                           │
│             280 │ 3441                                                                                                      │                           │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  CENY ZA AMBULANTNE PODANÉ LIEKY
┌─────────────────┬───────────────────────────────────────────────────────────────────────────────────────────────────────────┬───────────────────────────┐
│            Cena │ Kódy                                                                                                      │ Typ                       │
└─────────────────┴───────────────────────────────────────────────────────────────────────────────────────────────────────────┴───────────────────────────┘


  KONTROLA DEKURZU
┌─────────────────────────────────┬────────────┬──────────────────────────────────────────────────────┬──────────────────────────────────────────────────────┐
│ Popis                           │ Dôležitosť │ Ak platí ...                                         │ tak má platiť                                        │
└─────────────────────────────────┴────────────┴──────────────────────────────────────────────────────┴──────────────────────────────────────────────────────┘

