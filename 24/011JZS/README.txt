                                                                         ==============
                                                                         Cenník ortoped
                                                                         ==============

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
│               1 │ vv.pocet*cena             │ Výkon 99999                                   │ vv.kod in ['99999']                                          │
│             331 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             331 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             375 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│             375 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│             318 │ vv.pocet*cena             │ Denervácia periférneho nervu                  │ vv.kod in ['5a4001']                                         │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 4 metata │ vv.kod in ['5t08214']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 3 metata │ vv.kod in ['5t08213']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 2 metata │ vv.kod in ['5t08212']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 1 metata │ vv.kod in ['5t08211']                                        │
│                 │                           │ rzálna kosť                                   │                                                              │
│             400 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['5t0822a']                                        │
│             530 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['kt0800']                                         │
│             530 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['kt38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│             530 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['kt3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             530 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['kt0830']                                         │
│             530 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['kt0822a']                                        │
│             530 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['kt08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             530 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['kt08201']                                        │
│             530 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['kt0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho lúča                                │                                                              │
│             530 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['kt080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              89 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['kt790']                                          │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c8']                                         │
│                 │                           │ astika] radiokarpálneho kĺbu                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42cg']                                         │
│                 │                           │ astika] bedrového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ck']                                         │
│                 │                           │ astika] horného členkového kĺbu               │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c0']                                         │
│                 │                           │ astika] humeroglenoidálneho kĺbu              │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c4']                                         │
│                 │                           │ astika] lakťového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42cm']                                         │
│                 │                           │ astika] dolného členkového kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c9']                                         │
│                 │                           │ astika] ulnokarpálneho kĺbu                   │                                                              │
│             350 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5t8012']                                         │
│                 │                           │ a                                             │                                                              │
│              70 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5t790']                                          │
│            1470 │ vv.pocet*cena             │ Artroskopická operácia chrupavky bedrového kĺ │ vv.kod in ['5t42fg']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky radiokarpáln │ vv.kod in ['5t42f9']                                         │
│                 │                           │ eho kĺbu s transplantáciou chondrocytov na au │                                                              │
│                 │                           │ tológne indukovanej matrix                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kĺbov ruky s │ vv.kod in ['5t42f8']                                         │
│                 │                           │ transplantáciou chondrocytov na autológne ind │                                                              │
│                 │                           │ ukovanej matrix                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky lakťového kĺ │ vv.kod in ['5t42f4']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│            1995 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42em']                                         │
│                 │                           │ implantáciou acelulárneho implantátu dolného  │                                                              │
│                 │                           │ členkového kĺbu                               │                                                              │
│            1995 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42ek']                                         │
│                 │                           │ implantáciou acelulárneho implantátu horného  │                                                              │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405m']                                         │
│                 │                           │ alcifikátov z dolného členkového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405k']                                         │
│                 │                           │ alcifikátov z horného členkového kĺbu         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405g']                                         │
│                 │                           │ alcifikátov z bedrového kĺbu                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4059']                                         │
│                 │                           │ alcifikátov z ulnokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4058']                                         │
│                 │                           │ alcifikátov z radiokarpálneho kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4054']                                         │
│                 │                           │ alcifikátov z lakťového kĺbu                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z do │ vv.kod in ['5t404m']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│            2118 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42eh']                                         │
│                 │                           │ implantáciou acelulárneho implantátu kolennéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42eg']                                         │
│                 │                           │ implantáciou acelulárneho implantátu bedrovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e9']                                         │
│                 │                           │ implantáciou acelulárneho implantátu ulnokarp │                                                              │
│                 │                           │ álneho kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e8']                                         │
│                 │                           │ implantáciou acelulárneho implantátu radiokar │                                                              │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e4']                                         │
│                 │                           │ implantáciou acelulárneho implantátu lakťovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti d │ vv.kod in ['5t42dm']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5t42dk']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ho │ vv.kod in ['5t404k']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ko │ vv.kod in ['5t404h']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z be │ vv.kod in ['5t404g']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ul │ vv.kod in ['5t4049']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ra │ vv.kod in ['5t4048']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z la │ vv.kod in ['5t4044']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z hu │ vv.kod in ['5t4040']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403m']                                         │
│                 │                           │ ateriálu z dolného členkového kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403k']                                         │
│                 │                           │ ateriálu z horného členkového kĺbu            │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403h']                                         │
│                 │                           │ ateriálu z kolenného kĺbu                     │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403g']                                         │
│                 │                           │ ateriálu z bedrového kĺbu                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti k │ vv.kod in ['5t42dh']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti b │ vv.kod in ['5t42dg']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti u │ vv.kod in ['5t42d9']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti r │ vv.kod in ['5t42d8']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti l │ vv.kod in ['5t42d4']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5t42d0']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4039']                                         │
│                 │                           │ ateriálu z ulnokarpálneho kĺbu                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4038']                                         │
│                 │                           │ ateriálu z radiokarpálneho kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4034']                                         │
│                 │                           │ ateriálu z lakťového kĺbu                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4031']                                         │
│                 │                           │ ateriálu z akromioklavikulárneho kĺbu         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4030']                                         │
│                 │                           │ ateriálu z humeroglenoidálneho kĺbu           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) do │ vv.kod in ['5t402m']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ho │ vv.kod in ['5t402k']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ko │ vv.kod in ['5t402h']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) be │ vv.kod in ['5t402g']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ul │ vv.kod in ['5t4029']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ra │ vv.kod in ['5t4028']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             388 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t767']                                          │
│                 │                           │ v ruky so spongioplastikou                    │                                                              │
│             388 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t766']                                          │
│                 │                           │ v ruky                                        │                                                              │
│             388 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t765']                                          │
│                 │                           │ ruky so spongioplastikou                      │                                                              │
│             388 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t764']                                          │
│                 │                           │ ruky                                          │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428m']                                         │
│                 │                           │ ých tkanivových kultúr dolného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428k']                                         │
│                 │                           │ ých tkanivových kultúr horného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428h']                                         │
│                 │                           │ ých tkanivových kultúr kolenného kĺbu         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428g']                                         │
│                 │                           │ ých tkanivových kultúr bedrového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4289']                                         │
│                 │                           │ ých tkanivových kultúr ulnokarpálneho kĺbu    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4288']                                         │
│                 │                           │ ých tkanivových kultúr radiokarpálneho kĺbu   │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) ostatných kĺbov ruky    │ vv.kod in ['5t745x']                                         │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7457']                                         │
│                 │                           │ v viacerých prstov ruky, viaceré zákroky      │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7456']                                         │
│                 │                           │ v jedného prsta ruky, viaceré zákroky         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4284']                                         │
│                 │                           │ ých tkanivových kultúr lakťového kĺbu         │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky dolnéh │ vv.kod in ['5t427m']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky hornéh │ vv.kod in ['5t427k']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky kolenn │ vv.kod in ['5t427h']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky bedrov │ vv.kod in ['5t427g']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky ulnoka │ vv.kod in ['5t4279']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky radiok │ vv.kod in ['5t4278']                                         │
│                 │                           │ arpálneho kĺbu                                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky lakťov │ vv.kod in ['5t4274']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             350 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5t8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálneho kĺbu │ vv.kod in ['5t7455']                                         │
│                 │                           │ ruky, jeden zákrok                            │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálnych  │ vv.kod in ['5t7454']                                         │
│                 │                           │ kĺbov, viaceré zákroky                        │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálneho  │ vv.kod in ['5t7453']                                         │
│                 │                           │ kĺbu, jeden zákrok                            │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) karpometakarpálneho kĺb │ vv.kod in ['5t7452']                                         │
│                 │                           │ u palca                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický odber chondrálneho transplantát │ vv.kod in ['5t426h']                                         │
│                 │                           │ u z kolenného kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika d │ vv.kod in ['5t422m']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t422k']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika k │ vv.kod in ['5t422h']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika b │ vv.kod in ['5t422g']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika u │ vv.kod in ['5t4229']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5t4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             400 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5t7241']                                         │
│                 │                           │ u                                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5t4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1265 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t4220']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421m']                                         │
│                 │                           │ gmentu dolného členkového kĺbu                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421k']                                         │
│                 │                           │ gmentu horného členkového kĺbu                │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421h']                                         │
│                 │                           │ gmentu kolenného kĺbu                         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421g']                                         │
│                 │                           │ gmentu bedrového kĺbu                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4219']                                         │
│                 │                           │ gmentu ulnokarpálneho kĺbu                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4218']                                         │
│                 │                           │ gmentu radiokarpálneho kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4214']                                         │
│                 │                           │ gmentu lakťového kĺbu                         │                                                              │
│             400 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│             400 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4210']                                         │
│                 │                           │ gmentu humeroglenoidálneho kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420m']                                         │
│                 │                           │ nej chrupavky dolného členkového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420k']                                         │
│                 │                           │ nej chrupavky horného členkového kĺbu         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420h']                                         │
│                 │                           │ nej chrupavky kolenného kĺbu                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420g']                                         │
│                 │                           │ nej chrupavky bedrového kĺbu                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4209']                                         │
│                 │                           │ nej chrupavky ulnokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4208']                                         │
│                 │                           │ nej chrupavky radiokarpálneho kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4204']                                         │
│                 │                           │ nej chrupavky lakťového kĺbu                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4200']                                         │
│                 │                           │ nej chrupavky humeroglenoidálneho kĺbu        │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii dolného │ vv.kod in ['5t41xm']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii horného │ vv.kod in ['5t41xk']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii kolenné │ vv.kod in ['5t41xh']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1470 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii bedrové │ vv.kod in ['5t41xg']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii ulnokar │ vv.kod in ['5t41x9']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii radioka │ vv.kod in ['5t41x8']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│             350 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5t41x4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii akromio │ vv.kod in ['5t41x1']                                         │
│                 │                           │ klavikulárneho kĺbu                           │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii humerog │ vv.kod in ['5t41x0']                                         │
│                 │                           │ lenoidálneho kĺbu                             │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8548']                                         │
│                 │                           │ redkolenia                                    │                                                              │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8538']                                         │
│                 │                           │ dkolenia                                      │                                                              │
│             518 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predkoleni │ vv.kod in ['5t8528']                                         │
│                 │                           │ a                                             │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti stehna a k │ vv.kod in ['5t8527']                                         │
│                 │                           │ olena                                         │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5t4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a axily            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141c']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v inguináln │                                                              │
│                 │                           │ ej a genitálnej oblasti                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a axily                                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a axily              │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti ramena a l │ vv.kod in ['5t8522']                                         │
│                 │                           │ akťa                                          │                                                              │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predkolenia  │ vv.kod in ['5t8518']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti stehna a kol │ vv.kod in ['5t8517']                                         │
│                 │                           │ ena                                           │                                                              │
│             518 │ vv.pocet*cena             │ Reinzercia šľachy v oblasti predkolenia       │ vv.kod in ['5t8508']                                         │
│             350 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5t8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia dolného čl │ vv.kod in ['5t413m']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia horného čl │ vv.kod in ['5t413k']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna synovektómia kolenného  │ vv.kod in ['5t413h']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická totálna synovektómia bedrového  │ vv.kod in ['5t413g']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia ulnokarpál │ vv.kod in ['5t4139']                                         │
│                 │                           │ neho kĺbu                                     │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia radiokarpá │ vv.kod in ['5t4138']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5t4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna synovektómia humeroglen │ vv.kod in ['5t4130']                                         │
│                 │                           │ oidálneho kĺbu                                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia dolného  │ vv.kod in ['5t412m']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia horného  │ vv.kod in ['5t412k']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a axily                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a axily                   │                                                              │
│             350 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5t80x2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             350 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5t80c2']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie dolného členko │ vv.kod in ['5t49xm']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia kolennéh │ vv.kod in ['5t412h']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia bedrovéh │ vv.kod in ['5t412g']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia ulnokarp │ vv.kod in ['5t4129']                                         │
│                 │                           │ álneho kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia radiokar │ vv.kod in ['5t4128']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5t4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia humerogl │ vv.kod in ['5t4120']                                         │
│                 │                           │ enoidálneho kĺbu                              │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie dolného členkového  │ vv.kod in ['5t40xm']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie horného členkového  │ vv.kod in ['5t40xk']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie kolenného kĺbu      │ vv.kod in ['5t40xh']                                         │
│            1470 │ vv.pocet*cena             │ Iné artroskopické revízie bedrového kĺbu      │ vv.kod in ['5t40xg']                                         │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie ulnokarpálneho kĺbu │ vv.kod in ['5t40x9']                                         │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie radiokarpálneho kĺb │ vv.kod in ['5t40x8']                                         │
│                 │                           │ u                                             │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predkolenia  │ vv.kod in ['5t8918']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti stehna a kol │ vv.kod in ['5t8917']                                         │
│                 │                           │ ena                                           │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a lak │ vv.kod in ['5t8912']                                         │
│                 │                           │ ťa                                            │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a axi │ vv.kod in ['5t8911']                                         │
│                 │                           │ ly                                            │                                                              │
│             350 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5t8402']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie horného členko │ vv.kod in ['5t49xk']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie kolenného kĺbu │ vv.kod in ['5t49xh']                                         │
│            1470 │ vv.pocet*cena             │ Ostatné artroskopické operácie bedrového kĺbu │ vv.kod in ['5t49xg']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie ulnokarpálneho │ vv.kod in ['5t49x9']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie radiokarpálneh │ vv.kod in ['5t49x8']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             350 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5t49x4']                                         │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie akromioklaviku │ vv.kod in ['5t49x1']                                         │
│                 │                           │ lárneho kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie humeroglenoidá │ vv.kod in ['5t49x0']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické resekcia ganglia kolenného kĺbu │ vv.kod in ['5t492h']                                         │
│             846 │ vv.pocet*cena             │ Artroskopický debridement šľachy horného člen │ vv.kod in ['5t491k']                                         │
│                 │                           │ kového kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu doln │ vv.kod in ['5t490m']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu horn │ vv.kod in ['5t490k']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             350 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5t40x4']                                         │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie akromioklavikulárne │ vv.kod in ['5t40x1']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie humeroglenoidálneho │ vv.kod in ['5t40x0']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409m']                                         │
│                 │                           │ v ligament z dolného členkového kĺbu          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409k']                                         │
│                 │                           │ v ligament z horného členkového kĺbu          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409h']                                         │
│                 │                           │ v ligament z kolenného kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409g']                                         │
│                 │                           │ v ligament z bedrového kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4099']                                         │
│                 │                           │ v ligament z ulnokarpálneho kĺbu              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4098']                                         │
│                 │                           │ v ligament z radiokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4094']                                         │
│                 │                           │ v ligament z lakťového kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu bedr │ vv.kod in ['5t490g']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu ulno │ vv.kod in ['5t4909']                                         │
│                 │                           │ karpálneho kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu radi │ vv.kod in ['5t4908']                                         │
│                 │                           │ okarpálneho kĺbu                              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu lakť │ vv.kod in ['5t4904']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│            1265 │ vv.pocet*cena             │ Artroskopická stabilizácia akromioklavikulárn │ vv.kod in ['5t44b']                                          │
│                 │                           │ eho kĺbu fixačným výkonom                     │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na chrupavke a men │ vv.kod in ['5t42ih']                                         │
│                 │                           │ iskoch kolenného kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4091']                                         │
│                 │                           │ v ligament z akromioklavikulárneho kĺbu       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hm']                                         │
│                 │                           │ h osteofytov dolného členkového kĺbu          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hk']                                         │
│                 │                           │ h osteofytov horného členkového kĺbu          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hh']                                         │
│                 │                           │ h osteofytov kolenného kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hg']                                         │
│                 │                           │ h osteofytov bedrového kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h9']                                         │
│                 │                           │ h osteofytov ulnokarpálneho kĺbu              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h8']                                         │
│                 │                           │ h osteofytov radiokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h4']                                         │
│                 │                           │ h osteofytov lakťového kĺbu                   │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h1']                                         │
│                 │                           │ h osteofytov akromioklavikulárneho kĺbu       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická operácia chrupavky dolného člen │ vv.kod in ['5t42fm']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne indukovanej matrix kosti            │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická operácia chrupavky horného člen │ vv.kod in ['5t42fk']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne indukovanej matrix                  │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kolenného kĺ │ vv.kod in ['5t42fh']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211x']                                         │
│                 │                           │ ýzy ostatných kostí, osteosyntéza skrutkou    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076h']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074k']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074g']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0749']                                         │
│                 │                           │ a distálnej ulny                              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0746']                                         │
│                 │                           │ a distálneho radia                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0745']                                         │
│                 │                           │ a diafyzárneho radia                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0742']                                         │
│                 │                           │ a diafyzárneho humeru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia distálneh │ vv.kod in ['5t0736']                                         │
│                 │                           │ o radia                                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072q']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072k']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t0729']                                         │
│                 │                           │ ulny                                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0726']                                         │
│                 │                           │ o radia                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0725']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0722']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071q']                                         │
│                 │                           │ rnej fibuly                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071k']                                         │
│                 │                           │ lnej tibie                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0719']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0716']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0715']                                         │
│                 │                           │ rneho radia                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0712']                                         │
│                 │                           │ rneho humeru                                  │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21av']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aq']                                         │
│                 │                           │ ýzy diafyzárnej fibuly, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ag']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ae']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza intra │                                                              │
│                 │                           │ medulárnymi drôtmi a prútmi                   │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ac']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ab']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a6']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a3']                                         │
│                 │                           │ ýzy distálneho humeru, osteosyntéza intramedu │                                                              │
│                 │                           │ lárnymi drôtmi a prútmi                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a2']                                         │
│                 │                           │ ýzy diafyzárneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t14bu']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bb']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t144x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza drôtom a ťah │                                                              │
│                 │                           │ ovou serklážou                                │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t144u']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t144a']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1440']                                         │
│                 │                           │ ikuly, osteosyntéza drôtom a ťahovou serklážo │                                                              │
│                 │                           │ u                                             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t141x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza skrutkou     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza skrutkou       │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217n']                                         │
│                 │                           │ ýzy distálnej tibie, osteosyntéza zaisteným i │                                                              │
│                 │                           │ ntramedulárnym klincom                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217m']                                         │
│                 │                           │ ýzy diafyzárnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217k']                                         │
│                 │                           │ ýzy proximálnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217h']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217e']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza zaist │                                                              │
│                 │                           │ eným intramedulárnym klincom                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t141a']                                         │
│                 │                           │ álnych kostí, osteosyntéza skrutkou           │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1410']                                         │
│                 │                           │ ikuly, osteosyntéza skrutkou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t140z']                                         │
│                 │                           │ uly bez osteosyntézy                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na o │ vv.kod in ['5t140x']                                         │
│                 │                           │ statných malých kostiach bez osteosyntézy     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140v']                                         │
│                 │                           │ tarzálnych kosti bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t140u']                                         │
│                 │                           │ álnych kosti bez osteosyntézy                 │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140c']                                         │
│                 │                           │ ngov prstov ruky bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140b']                                         │
│                 │                           │ karpálnych kostí bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t140a']                                         │
│                 │                           │ álnych kostí bez osteosyntézy                 │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t216f']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza nezaist │                                                              │
│                 │                           │ eným predvŕtaným intramedulárnym klincom      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12cf']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a uhlovou/kondylárnou dlahou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza dr │                                                              │
│                 │                           │ ôtom alebo ťahovou serklážou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124j']                                         │
│                 │                           │ bnej oblasti pately, osteosyntéza drôtom aleb │                                                              │
│                 │                           │ o ťahovou serklážou                           │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1249']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza drô │                                                              │
│                 │                           │ tom alebo ťahovou serklážou                   │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1247']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza d │                                                              │
│                 │                           │ rôtom alebo ťahovou serklážou                 │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1246']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza d │                                                              │
│                 │                           │ rôtom alebo ťahovou serklážou                 │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1241']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a drôtom alebo ťahovou serklážou              │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza sk │                                                              │
│                 │                           │ rutkou                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza skrutkou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1217']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1211']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214a']                                         │
│                 │                           │ ýzy karpálnych kostí, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou serklážou                          │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1045']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza drôtom  │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xh']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza iným oste │                                                              │
│                 │                           │ osyntetickým materiálom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xg']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosyntetickým materiálom                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xf']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosyntetickým materiálom                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xe']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza iným  │                                                              │
│                 │                           │ osteosyntetickým materiálom                   │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xb']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza iným o │                                                              │
│                 │                           │ steosyntetickým materiálom                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza iným osteosy │                                                              │
│                 │                           │ ntetickým materiálom                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetickým materiálom                      │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetickým materiálom                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2149']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza drôtom alebo │                                                              │
│                 │                           │ ťahovou serklážou                             │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2146']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou serklážou                          │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2145']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahovou serklážou                        │                                                              │
│             482 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2140']                                         │
│                 │                           │ ýzy klavikuly, osteosyntéza drôtom alebo ťaho │                                                              │
│                 │                           │ vou serklážou                                 │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083e']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083d']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083c']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083b']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xr']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             400 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['5t080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtmi a prútmi                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a1']                                         │
│                 │                           │ ýzy proximálneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14ax']                                         │
│                 │                           │ tných malých kostí, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtmi a prútmi                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14a0']                                         │
│                 │                           │ ikuly, osteosyntéza intramedulárnymi drôtmi a │                                                              │
│                 │                           │ prútmi                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12af']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a intramedulárnymi drôtmi a prútmi            │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a9']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza int │                                                              │
│                 │                           │ ramedulárnymi drôtmi a prútmi                 │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a7']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza i │                                                              │
│                 │                           │ ntramedulárnymi drôtmi a prútmi               │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a8']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a5']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vv']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vu']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vt']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vs']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vr']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vq']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vp']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vn']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vm']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vk']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vb']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07va']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) la │ vv.kod in ['5t4024']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) hu │ vv.kod in ['5t4020']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach dolného členk │ vv.kod in ['5t400m']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5t400k']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5t4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aw']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ar']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre poúrazové stavy periférneho nerv │ vv.kod in ['5a50ha']                                         │
│                 │                           │ u na dolnej končatine                         │                                                              │
│             400 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['5t08201']                                        │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077r']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077n']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077m']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077k']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077f']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077e']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) metatarzofalange │ vv.kod in ['5t306q']                                         │
│                 │                           │ álnych kĺbov                                  │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) horného členkové │ vv.kod in ['5t306k']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) kolenného kĺbu   │ vv.kod in ['5t306h']                                         │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) radiokarpálneho  │ vv.kod in ['5t3068']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) lakťového kĺbu   │ vv.kod in ['5t3064']                                         │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19b1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza uhlovostabilnou dlahou │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076r']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076n']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076m']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076g']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076f']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076e']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) humeroglenoidáln │ vv.kod in ['5t3060']                                         │
│                 │                           │ eho kĺbu                                      │                                                              │
│             350 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5t3054']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t14bz']                                         │
│                 │                           │ uly, osteosyntéza uhlovostabilnou dlahou      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14bx']                                         │
│                 │                           │ tných malých kostí, osteosyntéza uhlovostabil │                                                              │
│                 │                           │ nou dlahou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bw']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bv']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bc']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t14ba']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14b0']                                         │
│                 │                           │ ikuly, osteosyntéza uhlovostabilnou dlahou    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na m │ vv.kod in ['5t144z']                                         │
│                 │                           │ alej kosti, osteosyntéza drôtom a ťahovou ser │                                                              │
│                 │                           │ klážou skapuly                                │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0834']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0833']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0832']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0831']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075x']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075w']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075v']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075u']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075t']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075s']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             350 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5t3044']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t143x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza štandardnou  │                                                              │
│                 │                           │ dlahou                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t143v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1430']                                         │
│                 │                           │ ikuly, osteosyntéza štandardnou dlahou        │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['5t0830']                                         │
│             400 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['5t08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0814']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 4 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0813']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 3 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0812']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 2 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0811']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 1 metatarzofalangeálny lúč │                                                              │
│             400 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho lúča                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075j']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075h']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075g']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075f']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075e']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075d']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075c']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075b']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075a']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1941']                                         │
│                 │                           │ eho kĺbu, osteosyntéza drôtom alebo ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140w']                                         │
│                 │                           │ ngov prstov nohy bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['5t0800']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xx']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xw']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xv']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xu']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xt']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xs']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xr']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xq']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xp']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074x']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074w']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074v']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074u']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074t']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074s']                                         │
│                 │                           │ a talu                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074r']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074p']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074n']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074m']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074j']                                         │
│                 │                           │ a pately                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074h']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12x1']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a iným osteosyntetickým materiálom            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xn']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xm']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xk']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xj']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xf']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xe']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xc']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xb']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xa']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074f']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074e']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074d']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074c']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074b']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074a']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0748']                                         │
│                 │                           │ a diafyzárnej ulny                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0747']                                         │
│                 │                           │ a proximálnej ulny                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0744']                                         │
│                 │                           │ a proximálneho radia                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0743']                                         │
│                 │                           │ a distálneho humeru                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0741']                                         │
│                 │                           │ a proximálneho humeru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0740']                                         │
│                 │                           │ a klavikuly                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia panvy     │ vv.kod in ['5t073d']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia falangov  │ vv.kod in ['5t073c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1911']                                         │
│                 │                           │ eho kĺbu, osteosyntéza skrutkou               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tz']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tx']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tw']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tv']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tu']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tt']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia klavikuly │ vv.kod in ['5t0730']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia skapuly   │ vv.kod in ['5t072z']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia ostatných │ vv.kod in ['5t072x']                                         │
│                 │                           │ kostí                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072w']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metatarzá │ vv.kod in ['5t072v']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia tarzálnyc │ vv.kod in ['5t072u']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia kalkanea  │ vv.kod in ['5t072t']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia talu      │ vv.kod in ['5t072s']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072r']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072p']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072n']                                         │
│                 │                           │ tibie                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072m']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia pately    │ vv.kod in ['5t072j']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t072h']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072g']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072f']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia krčka ste │ vv.kod in ['5t072e']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia panvy     │ vv.kod in ['5t072d']                                         │
│             400 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['5t38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│             400 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálnych a interfalan │ vv.kod in ['5t38a1']                                         │
│                 │                           │ geálnych kĺbov prsta nohy, 1 kĺb              │                                                              │
│             400 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['5t3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ch']                                         │
│                 │                           │ bnej oblasti distálneho femuru, osteosyntéza  │                                                              │
│                 │                           │ uhlovou/kondylárnou dlahou                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ce']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza uhlovou/kondylárnou dlahou                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ts']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tr']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tq']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tp']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tn']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tm']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tk']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tc']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tb']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ta']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metakarpá │ vv.kod in ['5t072b']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia karpálnyc │ vv.kod in ['5t072a']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0728']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0727']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0724']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0723']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0721']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia klavikuly │ vv.kod in ['5t0720']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia skapuly │ vv.kod in ['5t071z']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia ostatný │ vv.kod in ['5t071x']                                         │
│                 │                           │ ch kostí                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071w']                                         │
│                 │                           │ v prstov nohy                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metatar │ vv.kod in ['5t071v']                                         │
│                 │                           │ zálnych kostí                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia tarzáln │ vv.kod in ['5t071u']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia kalkane │ vv.kod in ['5t071t']                                         │
│                 │                           │ a                                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia talu    │ vv.kod in ['5t071s']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071r']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071p']                                         │
│                 │                           │ lnej fibuly                                   │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12b6']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza u │                                                              │
│                 │                           │ hlovostabilnou dlahou                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5t07e0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5t07dz']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5t07dx']                                         │
│                 │                           │ kostí                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dw']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5t07dv']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5t07du']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5t07dt']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5t07ds']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dr']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dq']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dp']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dn']                                         │
│                 │                           │ tibie                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dm']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dk']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071n']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071m']                                         │
│                 │                           │ rnej tibie                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia pately  │ vv.kod in ['5t071j']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071h']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071g']                                         │
│                 │                           │ rneho femuru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071f']                                         │
│                 │                           │ lneho femuru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia krčka s │ vv.kod in ['5t071e']                                         │
│                 │                           │ tehennej kosti                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia panvy   │ vv.kod in ['5t071d']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071c']                                         │
│                 │                           │ v prstov ruky                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metakar │ vv.kod in ['5t071b']                                         │
│                 │                           │ pálnych kostí                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia karpáln │ vv.kod in ['5t071a']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0718']                                         │
│                 │                           │ rnej ulny                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0717']                                         │
│                 │                           │ lnej ulny                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0714']                                         │
│                 │                           │ lneho radia                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0713']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0711']                                         │
│                 │                           │ lneho humeru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia klaviku │ vv.kod in ['5t0710']                                         │
│                 │                           │ ly                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5t07dj']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07dh']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dg']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07df']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5t07de']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5t07dd']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dc']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5t07db']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5t07da']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07d9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5t07d0']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a transfixačným klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza transfixačným klincom                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bw']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bv']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07br']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19z1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza rezorbovateľným materi │                                                              │
│                 │                           │ álom                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1048']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahovou serklážou                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bc']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bb']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t123r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza š │                                                              │
│                 │                           │ tandardnou dlahou                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07az']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ax']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aw']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07av']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07at']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07as']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ar']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aq']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ap']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07an']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07am']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ak']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aj']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ah']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ag']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07af']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ae']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ac']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19x1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza iným osteosyntetickým  │                                                              │
│                 │                           │ materiálom                                    │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t154b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza drôtom a ťahovo │                                                              │
│                 │                           │ u serklážou                                   │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1236']                                         │
│                 │                           │ bnej oblasti distálneho radia , osteosyntéza  │                                                              │
│                 │                           │ štandardnou dlahou                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ab']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t151b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza skrutkou        │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia pr │ vv.kod in ['5t815x']                                         │
│                 │                           │ iečna, ostatné                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany, ostatné                            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti nohy (chodidlo)           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predkolenia               │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti stehna a kolena           │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie menisku        │ vv.kod in ['5t423x']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie umelého menisku     │ vv.kod in ['5t4234']                                         │
│            1164 │ vv.pocet*cena             │ Artroskopická implantácia umelého menisku     │ vv.kod in ['5t4233']                                         │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra menisku, zložitá         │ vv.kod in ['5t42322']                                        │
│            1164 │ vv.pocet*cena             │ Artroskopická refixácia menisku               │ vv.kod in ['5t42320']                                        │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna resekcia menisku        │ vv.kod in ['5t42311']                                        │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v gluteálnej oblasti                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v brušnej oblasti                   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti hrudnej steny a chrbta    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ruky                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predlaktia                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a lakťa            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti krku                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany ostatných častí hlavy               │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti pery                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované, ostatné    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti n │                                                              │
│                 │                           │ ohy (chodidlo)                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redkolenia                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti s │                                                              │
│                 │                           │ tehna a kolena                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v gluteálne │                                                              │
│                 │                           │ j oblasti                                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v brušnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti h │                                                              │
│                 │                           │ rudnej steny a chrbta                         │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ uky                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redlaktia                                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a lakťa                                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti k │                                                              │
│                 │                           │ rku                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované ostatných č │                                                              │
│                 │                           │ astí hlavy                                    │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti n │ vv.kod in ['5t8549']                                         │
│                 │                           │ ohy                                           │                                                              │
│             388 │ vv.pocet*cena             │ Ostatné artrodézy kĺbov ruky                  │ vv.kod in ['5t76x']                                          │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev dlane              │ vv.kod in ['5t7079']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev palca              │ vv.kod in ['5t7078']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev prsta              │ vv.kod in ['5t7077']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza vystierača palca                     │ vv.kod in ['5t7075']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza vystierača prsta                     │ vv.kod in ['5t7074']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza ohýbača palca                        │ vv.kod in ['5t7072']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza ohýbača prsta                        │ vv.kod in ['5t7071']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra vystierača prsta              │ vv.kod in ['5t7054']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopické resekcie ganglia humeroglenoidá │ vv.kod in ['5t4920']                                         │
│                 │                           │ lny kĺb                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický debridement šľachy kolenného kĺ │ vv.kod in ['5t491h']                                         │
│                 │                           │ bu                                            │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5t4914']                                         │
│                 │                           │ bu                                            │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický debridement šľachy humeroglenoi │ vv.kod in ['5t4910']                                         │
│                 │                           │ dálneho kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5t400h']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopický aseptický výplach bedrového kĺb │ vv.kod in ['5t400g']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ ery                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, ostatné                              │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti nohy (chodidlo)             │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predkolenia                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti stehna a kolena             │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v gluteálnej oblasti                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v brušnej oblasti                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti hrudnej steny a chrbta      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ruky                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predlaktia                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a lakťa              │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti krku                        │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8543']                                         │
│                 │                           │ redlaktia                                     │                                                              │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy, ostatné      │ vv.kod in ['5t853x']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti noh │ vv.kod in ['5t8539']                                         │
│                 │                           │ y                                             │                                                              │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8533']                                         │
│                 │                           │ dlaktia                                       │                                                              │
│             518 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti nohy       │ vv.kod in ['5t8529']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra ohýbača prsta                 │ vv.kod in ['5t7051']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5t7028']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach ulnokarpálneh │ vv.kod in ['5t4009']                                         │
│                 │                           │ o kĺbu s drenážou                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5t4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5t4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany ostatných častí hlavy                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti pery                        │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predlaktia │ vv.kod in ['5t8523']                                         │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti nohy         │ vv.kod in ['5t8519']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predlaktia   │ vv.kod in ['5t8513']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5t7022']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│            1265 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5t44x']                                          │
│                 │                           │ kapsuloligamentóznom aparáte ramenného kĺbu   │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická laterálna resekcia klavikuly    │ vv.kod in ['5t44a']                                          │
│            1265 │ vv.pocet*cena             │ Artroskopické spevnenie púzdra s fixáciou na  │ vv.kod in ['5t445']                                          │
│                 │                           │ glenoid stehom                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131x']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131g']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti nohy (chodidlo)                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131f']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predkolenia                         │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131e']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti stehna a kolena                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131d']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteálnej oblasti                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131b']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej oblasti                             │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131a']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti hrudnej steny a chrbta              │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ruky                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predlaktia                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a lakťa                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti krku                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných častí hlavy                         │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy, ostatné               │ vv.kod in ['5t891x']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti nohy         │ vv.kod in ['5t8919']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predlaktia   │ vv.kod in ['5t8913']                                         │
│            1164 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5t43x']                                          │
│                 │                           │ kapsuloligamentóznom aparáte kolenného kĺbu   │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika laterálneho kapsulolig │ vv.kod in ['5t43e']                                          │
│                 │                           │ amentózneho aparátu kolenného kĺbu            │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika mediálneho kapsuloliga │ vv.kod in ['5t43d']                                          │
│                 │                           │ mentózneho aparátu kolenného kĺbu             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra laterálneho kapsuloligam │ vv.kod in ['5t43b']                                          │
│                 │                           │ entózneho aparátu kolenného kĺbu              │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra mediálneho kapsuloligame │ vv.kod in ['5t43a']                                          │
│                 │                           │ ntózneho aparátu kolenného kĺbu               │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické uvoľnenie kolenného púzdra (lat │ vv.kod in ['5t439']                                          │
│                 │                           │ eral release)                                 │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženeho väz │ vv.kod in ['5t438']                                          │
│                 │                           │ u s aloplastickou náhradou                    │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5t437']                                          │
│                 │                           │ u s iným autológnym ligamentom                │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5t436']                                          │
│                 │                           │ u s autogénnou patelárnou šľachou             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t435']                                          │
│                 │                           │ zu s aloplastickou náhradou                   │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t434']                                          │
│                 │                           │ zu iným autológnym ligamentom                 │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti pery                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130x']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatné                                   │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130g']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti nohy (chodidlo)                  │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130f']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predkolenia                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130e']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti stehna a kolena                  │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130d']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v gluteálnej oblasti                       │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130b']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušnej oblasti                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130a']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti hrudnej steny a chrbta           │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ruky                             │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predlaktia                       │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a lakťa                   │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti krku                             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t433']                                          │
│                 │                           │ zu autológnym patelárnym ligamentom           │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická kostná refixácia skríženého väz │ vv.kod in ['5t432']                                          │
│                 │                           │ u                                             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra zadného skríženého väzu  │ vv.kod in ['5t431']                                          │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra predného skríženého väzu │ vv.kod in ['5t430']                                          │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatných častí hlavy                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti pery                             │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa kolenn │ vv.kod in ['5t411h']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa bedrov │ vv.kod in ['5t411g']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia plica synovialis kolen │ vv.kod in ['5t410h']                                         │
│                 │                           │ ného kĺbu                                     │                                                              │
│             294 │ vv.pocet*cena             │ Transpozícia šliach, ostatné                  │ vv.kod in ['5t842x']                                         │
│             400 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5t7242']                                         │
│             353 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             353 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia viac ako jedného prsta │ vv.kod in ['5t7212']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia jedného prsta          │ vv.kod in ['5t7211']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia pozdĺžna, ostatné      │ vv.kod in ['5t81ax']                                         │
│             353 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia po │ vv.kod in ['5t818x']                                         │
│                 │                           │ zdĺžna, jeden segment, ostatné                │                                                              │
│             418 │ vv.pocet*cena             │ Parciálna excízia retinaculum flexorum        │ vv.kod in ['5t7121']                                         │
│             418 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             418 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované, ostatné       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre pozápalové stavy periférneho ner │ vv.kod in ['5a50hb']                                         │
│                 │                           │ vu na dolnej končatine                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre úžinový syndróm na dolnej končat │ vv.kod in ['5a50h9']                                         │
│                 │                           │ ine                                           │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre úžinový syndróm na hornej končat │ vv.kod in ['5a50h6x']                                        │
│                 │                           │ ine, iný                                      │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s tra │ vv.kod in ['5a50h64']                                        │
│                 │                           │ nspozíciou nervu                              │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s dek │ vv.kod in ['5a50h63']                                        │
│                 │                           │ ompresiou nervu                               │                                                              │
│             318 │ vv.pocet*cena             │ Dekompresia, deliberácia a uvoľnenie zrastov  │ vv.kod in ['5a50g']                                          │
│                 │                           │ periférneho nervu                             │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická biopsia kolenného kĺbu          │ vv.kod in ['12t007']                                         │
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

