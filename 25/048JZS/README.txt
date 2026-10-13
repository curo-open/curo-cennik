                                                                    ========================
                                                                    Cenník gastroenterologia
                                                                    ========================

Autor: curo.sk

  PREMENNÉ PARAMETRE
┌─────────────────┬───────┐
│ Názov a hodnota │ Popis │
└─────────────────┴───────┘


  CENY ZA PACIENTA
┌───────┬───────────────┬─────────┬───────────┐
│ Popis │ Premenná cena │ Vzorec  │ Podmienka │
└───────┴───────────────┴─────────┴───────────┘


  CENY ZA VÝKONY
┌─────────────────┬───────────────────────────┬───────────────────────────────────────────────┬──────────────────────────────────────────────────────────────┐
│   Premenná cena │ Vzorec                    │ Popis                                         │ Podmienka                                                    │
├─────────────────┼───────────────────────────┼───────────────────────────────────────────────┼──────────────────────────────────────────────────────────────┤
│             217 │ vv.pocet*cena             │ Rigídna ezofagoskopia                         │ vv.kod in ['14N1101','14n1101']                              │
│             217 │ vv.pocet*cena             │ Flexibilná ezofagoskopia                      │ vv.kod in ['14N1102','14n1102']                              │
│             217 │ vv.pocet*cena             │ Ezofagoskopia, iná                            │ vv.kod in ['14N110X','14n110x']                              │
│             217 │ vv.pocet*cena             │ Ezofagogastroskopia                           │ vv.kod in ['14N111','14n111']                                │
│             217 │ vv.pocet*cena             │ Ezofagogastroduodenoskopia                    │ vv.kod in ['14N112','14n112']                                │
│             217 │ vv.pocet*cena             │ Jejunoskopia                                  │ vv.kod in ['14N113','14n113']                                │
│             217 │ vv.pocet*cena             │ Intestinoskopia "push" technikou              │ vv.kod in ['14N1140','14n1140']                              │
│             217 │ vv.pocet*cena             │ Intestinoskopia "push-pull-back" technikou    │ vv.kod in ['14N1141','14n1141']                              │
│             217 │ vv.pocet*cena             │ Intestinoskopia, ostatné                      │ vv.kod in ['14N114X','14n114x']                              │
│             217 │ vv.pocet*cena             │ Ezofagoskopia stómický prístup                │ vv.kod in ['14N121','14n121']                                │
│             217 │ vv.pocet*cena             │ Jejunoskopia stómický prístup                 │ vv.kod in ['14N125','14n125']                                │
│             217 │ vv.pocet*cena             │ Diagnostická endoskopia ostatnej hornej časti │ vv.kod in ['14N12X','14n12x']                                │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             217 │ vv.pocet*cena             │ Chromoendoskopia hornej časti tráviaceho syst │ vv.kod in ['14N132','14n132']                                │
│                 │                           │ ému                                           │                                                              │
│             217 │ vv.pocet*cena             │ Parciálna kolonoskopia                        │ vv.kod in ['14N2100','14n2100']                              │
│             217 │ vv.pocet*cena             │ Totálna kolonoskopia bez ileoskopie           │ vv.kod in ['14N2101','14n2101']                              │
│             217 │ vv.pocet*cena             │ Totálna kolonoskopia s ileoskopiou            │ vv.kod in ['14N2102','14n2102']                              │
│             217 │ vv.pocet*cena             │ Sigmoideoskopia (okrem stómického prístupu)   │ vv.kod in ['14N2103','14n2103']                              │
│             217 │ vv.pocet*cena             │ Chromoendoskopia hrubého čreva                │ vv.kod in ['14N2104','14n2104']                              │
│             217 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14N210X','14n210x']                              │
│                 │                           │ tráviaceho systému, okrem stómického prístupu │                                                              │
│             217 │ vv.pocet*cena             │ Diagnostická ileoskopia, stómický prístup     │ vv.kod in ['14N2110','14n2110']                              │
│             217 │ vv.pocet*cena             │ Diagnostická kolonoskopia, stómický prístup   │ vv.kod in ['14N2111','14n2111']                              │
│             217 │ vv.pocet*cena             │ Diagnostická sigmoideoskopia, stómický prístu │ vv.kod in ['14N2112','14n2112']                              │
│                 │                           │ p                                             │                                                              │
│             217 │ vv.pocet*cena             │ Diagnostická proktoskopia, stómický prístup   │ vv.kod in ['14N2113','14n2113']                              │
│             217 │ vv.pocet*cena             │ Diagnostická rektoskopia, stómický prístup    │ vv.kod in ['14N2114','14n2114']                              │
│             217 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14N211X','14n211x']                              │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             217 │ vv.pocet*cena             │ Proktoskopia                                  │ vv.kod in ['14N2120','14n2120']                              │
│             217 │ vv.pocet*cena             │ Flexibilná rektoskopia                        │ vv.kod in ['14N2121','14n2121']                              │
│             217 │ vv.pocet*cena             │ Rigídna rektoskopia                           │ vv.kod in ['14N2122','14n2122']                              │
│             469 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N2221','5n2221']                                │
│                 │                           │ hrubého čreva, polypektómia 1-2 polypov pomoc │                                                              │
│                 │                           │ ou slučky                                     │                                                              │
│             469 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N2222','5n2222']                                │
│                 │                           │ hrubého čreva, polypektómia viac ako 2 polypo │                                                              │
│                 │                           │ v pomocou slučky                              │                                                              │
│             469 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4100','5n4100']                                │
│                 │                           │ o tkaniva konečníka, resekcia slučkou peranál │                                                              │
│                 │                           │ ne                                            │                                                              │
│             469 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4106','5n4106']                                │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picky                                         │                                                              │
│             469 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4107','5n4107']                                │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picko-mikrochirurgicky                        │                                                              │
│             469 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N410X','5n410x']                                │
│                 │                           │ o tkaniva konečníka, resekcia slučkou, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             469 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N4121','5n4121']                                │
│                 │                           │ konečníka, polypektómia 1-2 polypov pomocou s │                                                              │
│                 │                           │ lučky                                         │                                                              │
│             469 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N4122','5n4122']                                │
│                 │                           │ konečníka, polypektómia viac ako 2 polypov po │                                                              │
│                 │                           │ mocou slučky                                  │                                                              │
│             413 │ vv.pocet*cena             │ Endo-loop pažeráka                            │ vv.kod in ['5N09C','5n09c']                                  │
│             413 │ vv.pocet*cena             │ Endo-Loop žalúdka, endoskopicky               │ vv.kod in ['5N19C6','5n19c6']                                │
│             413 │ vv.pocet*cena             │ Endo-Loop čreva, endoskopicky                 │ vv.kod in ['5N39C6','5n39c6']                                │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N44C','5n44c']                                  │
│                 │                           │ análneho kanála                               │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická deštrukcia chorého tkani │ vv.kod in ['5N44D','5n44d']                                  │
│                 │                           │ va análneho kanála                            │                                                              │
│             413 │ vv.pocet*cena             │ Endo-Loop konečníka                           │ vv.kod in ['5N49E','5n49e']                                  │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N222X','5n222x']                                │
│                 │                           │ hrubého čreva, ostatné                        │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N0321','5n0321']                                │
│                 │                           │ pažeráka, polypektómia 1-2 polypov slučkou    │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N0322','5n0322']                                │
│                 │                           │ pažeráka, polypektómia viac ako 2 polypov slu │                                                              │
│                 │                           │ čkou                                          │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N0323','5n0323']                                │
│                 │                           │ pažeráka, endoskopická resekcia mukózy        │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorobou zmenené │ vv.kod in ['5N1121','5n1121']                                │
│                 │                           │ ho žalúdočného tkaniva, polypektómia 1-2 poly │                                                              │
│                 │                           │ pov pomocou slučky                            │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorobou zmenené │ vv.kod in ['5N1122','5n1122']                                │
│                 │                           │ ho žalúdočného tkaniva, polypektómia viac ako │                                                              │
│                 │                           │ 2 polypov pomocou slučky                      │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorobou zmenené │ vv.kod in ['5N1123','5n1123']                                │
│                 │                           │ ho žalúdočného tkaniva, endoskopická resekcia │                                                              │
│                 │                           │ mukózy                                        │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N2223','5n2223']                                │
│                 │                           │ hrubého čreva, endoskopická resekcia mukózy   │                                                              │
│             413 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N4123','5n4123']                                │
│                 │                           │ konečníka, endoskopická resekcia mukózy       │                                                              │
│             413 │ vv.pocet*cena             │ Endoskopická excízia chorého tkaniva tenkého  │ vv.kod in ['5N21711','5n21711']                              │
│                 │                           │ čreva, jednoduchá (Push-technika) polypektómi │                                                              │
│                 │                           │ a 1-2 polypov pomocou slučky                  │                                                              │
│             413 │ vv.pocet*cena             │ Endoskopická excízia chorého tkaniva tenkého  │ vv.kod in ['5N21712','5n21712']                              │
│                 │                           │ čreva, jednoduchá (Push-technika) polypektómi │                                                              │
│                 │                           │ a viac ako 2 polypov pomocou slučky           │                                                              │
│             413 │ vv.pocet*cena             │ Endoskopická excízia chorého tkaniva tenkého  │ vv.kod in ['5N21713','5n21713']                              │
│                 │                           │ čreva, jednoduchá (Push-technika) endoskopick │                                                              │
│                 │                           │ á resekcia mukózy                             │                                                              │
│             217 │ vv.pocet*cena             │ Endosonografia retroperitonea                 │ vv.kod in ['313141A','313141a']                              │
│             217 │ vv.pocet*cena             │ Endosonografia pažeráka                       │ vv.kod in ['3131412']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia žalúdka                        │ vv.kod in ['3131413']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia dvanástnika                    │ vv.kod in [']3131414']                                       │
│             217 │ vv.pocet*cena             │ Endosonografia žlčových ciest                 │ vv.kod in ['3131415']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia pankreasu                      │ vv.kod in ['3131416']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia hrubého čreva                  │ vv.kod in ['3131417']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia konečníka                      │ vv.kod in ['3131418']                                        │
│             217 │ vv.pocet*cena             │ Endosonografia brucha, laparoskopická sonogra │ vv.kod in ['3131419']                                        │
│                 │                           │ fia                                           │                                                              │
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

