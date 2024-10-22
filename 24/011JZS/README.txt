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
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T892X']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│             318 │ vv.pocet*cena             │ Denervácia periférneho nervu                  │ vv.kod in ['5A4001']                                         │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 4 metata │ vv.kod in ['5T08214']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 3 metata │ vv.kod in ['5T08213']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 2 metata │ vv.kod in ['5T08212']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             393 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 1 metata │ vv.kod in ['5T08211']                                        │
│                 │                           │ rzálna kosť                                   │                                                              │
│             400 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['5T0822A']                                        │
│             530 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['KT0800']                                         │
│             530 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['KT38AA']                                         │
│                 │                           │ ohy                                           │                                                              │
│             530 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['KT3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             530 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['KT0830']                                         │
│             530 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['KT0822A']                                        │
│             530 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['KT08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             530 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['KT08201']                                        │
│             530 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['KT0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho lúča                                │                                                              │
│             530 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['KT080A']                                         │
│                 │                           │ tus I                                         │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT892X']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              89 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              89 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['KT790']                                          │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42C8']                                         │
│                 │                           │ astika] radiokarpálneho kĺbu                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42CG']                                         │
│                 │                           │ astika] bedrového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42CK']                                         │
│                 │                           │ astika] horného členkového kĺbu               │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42C0']                                         │
│                 │                           │ astika] humeroglenoidálneho kĺbu              │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42CH']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42C4']                                         │
│                 │                           │ astika] lakťového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42CM']                                         │
│                 │                           │ astika] dolného členkového kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5T42C9']                                         │
│                 │                           │ astika] ulnokarpálneho kĺbu                   │                                                              │
│             350 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5T8012']                                         │
│                 │                           │ a                                             │                                                              │
│              70 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5T790']                                          │
│            1470 │ vv.pocet*cena             │ Artroskopická operácia chrupavky bedrového kĺ │ vv.kod in ['5T42FG']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky radiokarpáln │ vv.kod in ['5T42F9']                                         │
│                 │                           │ eho kĺbu s transplantáciou chondrocytov na au │                                                              │
│                 │                           │ tológne indukovanej matrix                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kĺbov ruky s │ vv.kod in ['5T42F8']                                         │
│                 │                           │ transplantáciou chondrocytov na autológne ind │                                                              │
│                 │                           │ ukovanej matrix                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická operácia chrupavky lakťového kĺ │ vv.kod in ['5T42F4']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│            1995 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42EM']                                         │
│                 │                           │ implantáciou acelulárneho implantátu dolného  │                                                              │
│                 │                           │ členkového kĺbu                               │                                                              │
│            1995 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42EK']                                         │
│                 │                           │ implantáciou acelulárneho implantátu horného  │                                                              │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T405M']                                         │
│                 │                           │ alcifikátov z dolného členkového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T405K']                                         │
│                 │                           │ alcifikátov z horného členkového kĺbu         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T405G']                                         │
│                 │                           │ alcifikátov z bedrového kĺbu                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T4059']                                         │
│                 │                           │ alcifikátov z ulnokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T4058']                                         │
│                 │                           │ alcifikátov z radiokarpálneho kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T4054']                                         │
│                 │                           │ alcifikátov z lakťového kĺbu                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5T4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z do │ vv.kod in ['5T404M']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│            2118 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42EH']                                         │
│                 │                           │ implantáciou acelulárneho implantátu kolennéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42EG']                                         │
│                 │                           │ implantáciou acelulárneho implantátu bedrovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42E9']                                         │
│                 │                           │ implantáciou acelulárneho implantátu ulnokarp │                                                              │
│                 │                           │ álneho kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42E8']                                         │
│                 │                           │ implantáciou acelulárneho implantátu radiokar │                                                              │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5T42E4']                                         │
│                 │                           │ implantáciou acelulárneho implantátu lakťovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti d │ vv.kod in ['5T42DM']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5T42DK']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ho │ vv.kod in ['5T404K']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ko │ vv.kod in ['5T404H']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z be │ vv.kod in ['5T404G']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ul │ vv.kod in ['5T4049']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ra │ vv.kod in ['5T4048']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z la │ vv.kod in ['5T4044']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z hu │ vv.kod in ['5T4040']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T403M']                                         │
│                 │                           │ ateriálu z dolného členkového kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T403K']                                         │
│                 │                           │ ateriálu z horného členkového kĺbu            │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T403H']                                         │
│                 │                           │ ateriálu z kolenného kĺbu                     │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T403G']                                         │
│                 │                           │ ateriálu z bedrového kĺbu                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti k │ vv.kod in ['5T42DH']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti b │ vv.kod in ['5T42DG']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti u │ vv.kod in ['5T42D9']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti r │ vv.kod in ['5T42D8']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti l │ vv.kod in ['5T42D4']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5T42D0']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T4039']                                         │
│                 │                           │ ateriálu z ulnokarpálneho kĺbu                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T4038']                                         │
│                 │                           │ ateriálu z radiokarpálneho kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T4034']                                         │
│                 │                           │ ateriálu z lakťového kĺbu                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T4031']                                         │
│                 │                           │ ateriálu z akromioklavikulárneho kĺbu         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5T4030']                                         │
│                 │                           │ ateriálu z humeroglenoidálneho kĺbu           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) do │ vv.kod in ['5T402M']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ho │ vv.kod in ['5T402K']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ko │ vv.kod in ['5T402H']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) be │ vv.kod in ['5T402G']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ul │ vv.kod in ['5T4029']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ra │ vv.kod in ['5T4028']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             388 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5T767']                                          │
│                 │                           │ v ruky so spongioplastikou                    │                                                              │
│             388 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5T766']                                          │
│                 │                           │ v ruky                                        │                                                              │
│             388 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5T765']                                          │
│                 │                           │ ruky so spongioplastikou                      │                                                              │
│             388 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5T764']                                          │
│                 │                           │ ruky                                          │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T428M']                                         │
│                 │                           │ ých tkanivových kultúr dolného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T428K']                                         │
│                 │                           │ ých tkanivových kultúr horného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T428H']                                         │
│                 │                           │ ých tkanivových kultúr kolenného kĺbu         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T428G']                                         │
│                 │                           │ ých tkanivových kultúr bedrového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T4289']                                         │
│                 │                           │ ých tkanivových kultúr ulnokarpálneho kĺbu    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T4288']                                         │
│                 │                           │ ých tkanivových kultúr radiokarpálneho kĺbu   │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) ostatných kĺbov ruky    │ vv.kod in ['5T745X']                                         │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5T7457']                                         │
│                 │                           │ v viacerých prstov ruky, viaceré zákroky      │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5T7456']                                         │
│                 │                           │ v jedného prsta ruky, viaceré zákroky         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5T4284']                                         │
│                 │                           │ ých tkanivových kultúr lakťového kĺbu         │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky dolnéh │ vv.kod in ['5T427M']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky hornéh │ vv.kod in ['5T427K']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky kolenn │ vv.kod in ['5T427H']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky bedrov │ vv.kod in ['5T427G']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky ulnoka │ vv.kod in ['5T4279']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky radiok │ vv.kod in ['5T4278']                                         │
│                 │                           │ arpálneho kĺbu                                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky lakťov │ vv.kod in ['5T4274']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             350 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5T8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálneho kĺbu │ vv.kod in ['5T7455']                                         │
│                 │                           │ ruky, jeden zákrok                            │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálnych  │ vv.kod in ['5T7454']                                         │
│                 │                           │ kĺbov, viaceré zákroky                        │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálneho  │ vv.kod in ['5T7453']                                         │
│                 │                           │ kĺbu, jeden zákrok                            │                                                              │
│             388 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) karpometakarpálneho kĺb │ vv.kod in ['5T7452']                                         │
│                 │                           │ u palca                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický odber chondrálneho transplantát │ vv.kod in ['5T426H']                                         │
│                 │                           │ u z kolenného kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika d │ vv.kod in ['5T422M']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5T422K']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika k │ vv.kod in ['5T422H']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika b │ vv.kod in ['5T422G']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika u │ vv.kod in ['5T4229']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5T4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             400 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5T7241']                                         │
│                 │                           │ u                                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5T4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1265 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5T4220']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T421M']                                         │
│                 │                           │ gmentu dolného členkového kĺbu                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T421K']                                         │
│                 │                           │ gmentu horného členkového kĺbu                │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T421H']                                         │
│                 │                           │ gmentu kolenného kĺbu                         │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T421G']                                         │
│                 │                           │ gmentu bedrového kĺbu                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T4219']                                         │
│                 │                           │ gmentu ulnokarpálneho kĺbu                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T4218']                                         │
│                 │                           │ gmentu radiokarpálneho kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T4214']                                         │
│                 │                           │ gmentu lakťového kĺbu                         │                                                              │
│             400 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5T7234']                                         │
│             400 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5T7230']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5T4210']                                         │
│                 │                           │ gmentu humeroglenoidálneho kĺbu               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T420M']                                         │
│                 │                           │ nej chrupavky dolného členkového kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T420K']                                         │
│                 │                           │ nej chrupavky horného členkového kĺbu         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T420H']                                         │
│                 │                           │ nej chrupavky kolenného kĺbu                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T420G']                                         │
│                 │                           │ nej chrupavky bedrového kĺbu                  │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T4209']                                         │
│                 │                           │ nej chrupavky ulnokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T4208']                                         │
│                 │                           │ nej chrupavky radiokarpálneho kĺbu            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T4204']                                         │
│                 │                           │ nej chrupavky lakťového kĺbu                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5T4200']                                         │
│                 │                           │ nej chrupavky humeroglenoidálneho kĺbu        │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii dolného │ vv.kod in ['5T41XM']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii horného │ vv.kod in ['5T41XK']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii kolenné │ vv.kod in ['5T41XH']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1470 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii bedrové │ vv.kod in ['5T41XG']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii ulnokar │ vv.kod in ['5T41X9']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii radioka │ vv.kod in ['5T41X8']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│             350 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5T41X4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii akromio │ vv.kod in ['5T41X1']                                         │
│                 │                           │ klavikulárneho kĺbu                           │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii humerog │ vv.kod in ['5T41X0']                                         │
│                 │                           │ lenoidálneho kĺbu                             │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5T8548']                                         │
│                 │                           │ redkolenia                                    │                                                              │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5T8538']                                         │
│                 │                           │ dkolenia                                      │                                                              │
│             518 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predkoleni │ vv.kod in ['5T8528']                                         │
│                 │                           │ a                                             │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti stehna a k │ vv.kod in ['5T8527']                                         │
│                 │                           │ olena                                         │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5T4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a axily            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141C']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v inguináln │                                                              │
│                 │                           │ ej a genitálnej oblasti                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a axily                                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a axily              │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti ramena a l │ vv.kod in ['5T8522']                                         │
│                 │                           │ akťa                                          │                                                              │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predkolenia  │ vv.kod in ['5T8518']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti stehna a kol │ vv.kod in ['5T8517']                                         │
│                 │                           │ ena                                           │                                                              │
│             518 │ vv.pocet*cena             │ Reinzercia šľachy v oblasti predkolenia       │ vv.kod in ['5T8508']                                         │
│             350 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5T8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia dolného čl │ vv.kod in ['5T413M']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia horného čl │ vv.kod in ['5T413K']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna synovektómia kolenného  │ vv.kod in ['5T413H']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická totálna synovektómia bedrového  │ vv.kod in ['5T413G']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia ulnokarpál │ vv.kod in ['5T4139']                                         │
│                 │                           │ neho kĺbu                                     │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická totálna synovektómia radiokarpá │ vv.kod in ['5T4138']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5T4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna synovektómia humeroglen │ vv.kod in ['5T4130']                                         │
│                 │                           │ oidálneho kĺbu                                │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia dolného  │ vv.kod in ['5T412M']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia horného  │ vv.kod in ['5T412K']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a axily                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a axily                   │                                                              │
│             350 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5T80X2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             350 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5T80C2']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie dolného členko │ vv.kod in ['5T49XM']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia kolennéh │ vv.kod in ['5T412H']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia bedrovéh │ vv.kod in ['5T412G']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia ulnokarp │ vv.kod in ['5T4129']                                         │
│                 │                           │ álneho kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia radiokar │ vv.kod in ['5T4128']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5T4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia humerogl │ vv.kod in ['5T4120']                                         │
│                 │                           │ enoidálneho kĺbu                              │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie dolného členkového  │ vv.kod in ['5T40XM']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie horného členkového  │ vv.kod in ['5T40XK']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie kolenného kĺbu      │ vv.kod in ['5T40XH']                                         │
│            1470 │ vv.pocet*cena             │ Iné artroskopické revízie bedrového kĺbu      │ vv.kod in ['5T40XG']                                         │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie ulnokarpálneho kĺbu │ vv.kod in ['5T40X9']                                         │
│             846 │ vv.pocet*cena             │ Iné artroskopické revízie radiokarpálneho kĺb │ vv.kod in ['5T40X8']                                         │
│                 │                           │ u                                             │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predkolenia  │ vv.kod in ['5T8918']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti stehna a kol │ vv.kod in ['5T8917']                                         │
│                 │                           │ ena                                           │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a lak │ vv.kod in ['5T8912']                                         │
│                 │                           │ ťa                                            │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a axi │ vv.kod in ['5T8911']                                         │
│                 │                           │ ly                                            │                                                              │
│             350 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5T8402']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie horného členko │ vv.kod in ['5T49XK']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie kolenného kĺbu │ vv.kod in ['5T49XH']                                         │
│            1470 │ vv.pocet*cena             │ Ostatné artroskopické operácie bedrového kĺbu │ vv.kod in ['5T49XG']                                         │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie ulnokarpálneho │ vv.kod in ['5T49X9']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Ostatné artroskopické operácie radiokarpálneh │ vv.kod in ['5T49X8']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             350 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5T49X4']                                         │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie akromioklaviku │ vv.kod in ['5T49X1']                                         │
│                 │                           │ lárneho kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie humeroglenoidá │ vv.kod in ['5T49X0']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické resekcia ganglia kolenného kĺbu │ vv.kod in ['5T492H']                                         │
│             846 │ vv.pocet*cena             │ Artroskopický debridement šľachy horného člen │ vv.kod in ['5T491K']                                         │
│                 │                           │ kového kĺbu                                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu doln │ vv.kod in ['5T490M']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu horn │ vv.kod in ['5T490K']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             350 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5T40X4']                                         │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie akromioklavikulárne │ vv.kod in ['5T40X1']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické revízie humeroglenoidálneho │ vv.kod in ['5T40X0']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T409M']                                         │
│                 │                           │ v ligament z dolného členkového kĺbu          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T409K']                                         │
│                 │                           │ v ligament z horného členkového kĺbu          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T409H']                                         │
│                 │                           │ v ligament z kolenného kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T409G']                                         │
│                 │                           │ v ligament z bedrového kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T4099']                                         │
│                 │                           │ v ligament z ulnokarpálneho kĺbu              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T4098']                                         │
│                 │                           │ v ligament z radiokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T4094']                                         │
│                 │                           │ v ligament z lakťového kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu bedr │ vv.kod in ['5T490G']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu ulno │ vv.kod in ['5T4909']                                         │
│                 │                           │ karpálneho kĺbu                               │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu radi │ vv.kod in ['5T4908']                                         │
│                 │                           │ okarpálneho kĺbu                              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu lakť │ vv.kod in ['5T4904']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│            1265 │ vv.pocet*cena             │ Artroskopická stabilizácia akromioklavikulárn │ vv.kod in ['5T44B']                                          │
│                 │                           │ eho kĺbu fixačným výkonom                     │                                                              │
│            1035 │ vv.pocet*cena             │ Iné artroskopické operácie na chrupavke a men │ vv.kod in ['5T42IH']                                         │
│                 │                           │ iskoch kolenného kĺbu                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T4091']                                         │
│                 │                           │ v ligament z akromioklavikulárneho kĺbu       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5T4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42HM']                                         │
│                 │                           │ h osteofytov dolného členkového kĺbu          │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42HK']                                         │
│                 │                           │ h osteofytov horného členkového kĺbu          │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42HH']                                         │
│                 │                           │ h osteofytov kolenného kĺbu                   │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42HG']                                         │
│                 │                           │ h osteofytov bedrového kĺbu                   │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42H9']                                         │
│                 │                           │ h osteofytov ulnokarpálneho kĺbu              │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42H8']                                         │
│                 │                           │ h osteofytov radiokarpálneho kĺbu             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42H4']                                         │
│                 │                           │ h osteofytov lakťového kĺbu                   │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42H1']                                         │
│                 │                           │ h osteofytov akromioklavikulárneho kĺbu       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5T42H0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická operácia chrupavky dolného člen │ vv.kod in ['5T42FM']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne indukovanej matrix kosti            │                                                              │
│            3017 │ vv.pocet*cena             │ Artroskopická operácia chrupavky horného člen │ vv.kod in ['5T42FK']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne indukovanej matrix                  │                                                              │
│            3140 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kolenného kĺ │ vv.kod in ['5T42FH']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukovanej matrix                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T211X']                                         │
│                 │                           │ ýzy ostatných kostí, osteosyntéza skrutkou    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T211W']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T211V']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076H']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074Q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074K']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074G']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0749']                                         │
│                 │                           │ a distálnej ulny                              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0746']                                         │
│                 │                           │ a distálneho radia                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0745']                                         │
│                 │                           │ a diafyzárneho radia                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0742']                                         │
│                 │                           │ a diafyzárneho humeru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia distálneh │ vv.kod in ['5T0736']                                         │
│                 │                           │ o radia                                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T211C']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T211B']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072Q']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072K']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T0729']                                         │
│                 │                           │ ulny                                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T0726']                                         │
│                 │                           │ o radia                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0725']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0722']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T071Q']                                         │
│                 │                           │ rnej fibuly                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T071K']                                         │
│                 │                           │ lnej tibie                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T0719']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T0716']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T0715']                                         │
│                 │                           │ rneho radia                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T0712']                                         │
│                 │                           │ rneho humeru                                  │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AV']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AQ']                                         │
│                 │                           │ ýzy diafyzárnej fibuly, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AG']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AE']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza intra │                                                              │
│                 │                           │ medulárnymi drôtmi a prútmi                   │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AC']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AB']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A6']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A3']                                         │
│                 │                           │ ýzy distálneho humeru, osteosyntéza intramedu │                                                              │
│                 │                           │ lárnymi drôtmi a prútmi                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A2']                                         │
│                 │                           │ ýzy diafyzárneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5T14BU']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T14BB']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5T144X']                                         │
│                 │                           │ tných malých kostí, osteosyntéza drôtom a ťah │                                                              │
│                 │                           │ ovou serklážou                                │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T144W']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T144V']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5T144U']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T144C']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T144B']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serklážou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5T144A']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5T1440']                                         │
│                 │                           │ ikuly, osteosyntéza drôtom a ťahovou serklážo │                                                              │
│                 │                           │ u                                             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T143W']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5T141X']                                         │
│                 │                           │ tných malých kostí, osteosyntéza skrutkou     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T141W']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T141V']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T141C']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza skrutkou       │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T141B']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza skrutkou       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T217N']                                         │
│                 │                           │ ýzy distálnej tibie, osteosyntéza zaisteným i │                                                              │
│                 │                           │ ntramedulárnym klincom                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T217M']                                         │
│                 │                           │ ýzy diafyzárnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T217K']                                         │
│                 │                           │ ýzy proximálnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T217H']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedulárnym klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T217E']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza zaist │                                                              │
│                 │                           │ eným intramedulárnym klincom                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5T141A']                                         │
│                 │                           │ álnych kostí, osteosyntéza skrutkou           │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5T1410']                                         │
│                 │                           │ ikuly, osteosyntéza skrutkou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5T140Z']                                         │
│                 │                           │ uly bez osteosyntézy                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na o │ vv.kod in ['5T140X']                                         │
│                 │                           │ statných malých kostiach bez osteosyntézy     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T140V']                                         │
│                 │                           │ tarzálnych kosti bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5T140U']                                         │
│                 │                           │ álnych kosti bez osteosyntézy                 │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T140C']                                         │
│                 │                           │ ngov prstov ruky bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T140B']                                         │
│                 │                           │ karpálnych kostí bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5T140A']                                         │
│                 │                           │ álnych kostí bez osteosyntézy                 │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T216F']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza nezaist │                                                              │
│                 │                           │ eným predvŕtaným intramedulárnym klincom      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T214W']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T214V']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12CF']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a uhlovou/kondylárnou dlahou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T124N']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza dr │                                                              │
│                 │                           │ ôtom alebo ťahovou serklážou                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T124J']                                         │
│                 │                           │ bnej oblasti pately, osteosyntéza drôtom aleb │                                                              │
│                 │                           │ o ťahovou serklážou                           │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1249']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza drô │                                                              │
│                 │                           │ tom alebo ťahovou serklážou                   │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1247']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza d │                                                              │
│                 │                           │ rôtom alebo ťahovou serklážou                 │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1246']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza d │                                                              │
│                 │                           │ rôtom alebo ťahovou serklážou                 │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1241']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a drôtom alebo ťahovou serklážou              │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T121R']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T121N']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza sk │                                                              │
│                 │                           │ rutkou                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T121F']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T121E']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza skrutkou                                  │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1217']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1211']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T214C']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             435 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T214B']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T214A']                                         │
│                 │                           │ ýzy karpálnych kostí, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou serklážou                          │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5T1045']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza drôtom  │                                                              │
│                 │                           │ alebo ťahovou serklážou                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XH']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza iným oste │                                                              │
│                 │                           │ osyntetickým materiálom                       │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XG']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosyntetickým materiálom                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XF']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosyntetickým materiálom                     │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XE']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza iným  │                                                              │
│                 │                           │ osteosyntetickým materiálom                   │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XB']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza iným o │                                                              │
│                 │                           │ steosyntetickým materiálom                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21X9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza iným osteosy │                                                              │
│                 │                           │ ntetickým materiálom                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21X8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21X7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21X5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetickým materiálom                      │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21X4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetickým materiálom                      │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T2149']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza drôtom alebo │                                                              │
│                 │                           │ ťahovou serklážou                             │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T2146']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou serklážou                          │                                                              │
│             353 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T2145']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahovou serklážou                        │                                                              │
│             482 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T2140']                                         │
│                 │                           │ ýzy klavikuly, osteosyntéza drôtom alebo ťaho │                                                              │
│                 │                           │ vou serklážou                                 │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5T083E']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5T083D']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5T083C']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5T083B']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21XR']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetickým materiálom                        │                                                              │
│             400 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['5T080A']                                         │
│                 │                           │ tus I                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtmi a prútmi                          │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21A1']                                         │
│                 │                           │ ýzy proximálneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5T14AX']                                         │
│                 │                           │ tných malých kostí, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtmi a prútmi                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5T14A0']                                         │
│                 │                           │ ikuly, osteosyntéza intramedulárnymi drôtmi a │                                                              │
│                 │                           │ prútmi                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12AF']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a intramedulárnymi drôtmi a prútmi            │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12A9']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza int │                                                              │
│                 │                           │ ramedulárnymi drôtmi a prútmi                 │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12A7']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza i │                                                              │
│                 │                           │ ntramedulárnymi drôtmi a prútmi               │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5T10A8']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi drôtmi a prútmi                      │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5T10A5']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi drôtmi a prútmi                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VV']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VU']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VT']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VS']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VR']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VQ']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VP']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VN']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VM']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VK']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VB']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VA']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) la │ vv.kod in ['5T4024']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) hu │ vv.kod in ['5T4020']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach dolného členk │ vv.kod in ['5T400M']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5T400K']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5T4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AW']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi drôtmi a prútmi                    │                                                              │
│             400 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5T21AR']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drôtmi a prútmi                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre poúrazové stavy periférneho nerv │ vv.kod in ['5A50HA']                                         │
│                 │                           │ u na dolnej končatine                         │                                                              │
│             400 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['5T08201']                                        │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077R']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077N']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077M']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077K']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077F']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077E']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) metatarzofalange │ vv.kod in ['5T306Q']                                         │
│                 │                           │ álnych kĺbov                                  │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) horného členkové │ vv.kod in ['5T306K']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) kolenného kĺbu   │ vv.kod in ['5T306H']                                         │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) radiokarpálneho  │ vv.kod in ['5T3068']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) lakťového kĺbu   │ vv.kod in ['5T3064']                                         │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5T19B1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza uhlovostabilnou dlahou │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076R']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076Q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076N']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076M']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076G']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076F']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076E']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             493 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) humeroglenoidáln │ vv.kod in ['5T3060']                                         │
│                 │                           │ eho kĺbu                                      │                                                              │
│             350 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5T3054']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5T14BZ']                                         │
│                 │                           │ uly, osteosyntéza uhlovostabilnou dlahou      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5T14BX']                                         │
│                 │                           │ tných malých kostí, osteosyntéza uhlovostabil │                                                              │
│                 │                           │ nou dlahou                                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T14BW']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T14BV']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T14BC']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5T14BA']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5T14B0']                                         │
│                 │                           │ ikuly, osteosyntéza uhlovostabilnou dlahou    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na m │ vv.kod in ['5T144Z']                                         │
│                 │                           │ alej kosti, osteosyntéza drôtom a ťahovou ser │                                                              │
│                 │                           │ klážou skapuly                                │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5T0834']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5T0833']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5T0832']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             393 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5T0831']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075Z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075X']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075W']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075V']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075U']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075T']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075S']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             350 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5T3044']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5T143X']                                         │
│                 │                           │ tných malých kostí, osteosyntéza štandardnou  │                                                              │
│                 │                           │ dlahou                                        │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5T143V']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T143C']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             482 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5T1430']                                         │
│                 │                           │ ikuly, osteosyntéza štandardnou dlahou        │                                                              │
│             400 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['5T0830']                                         │
│             400 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['5T08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5T0814']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 4 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5T0813']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 3 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5T0812']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 2 metatarzofalangeálne lúč │                                                              │
│                 │                           │ e                                             │                                                              │
│             393 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5T0811']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeálneho lúča: 1 metatarzofalangeálny lúč │                                                              │
│             400 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5T0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho lúča                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075J']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075H']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075G']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075F']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075E']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075D']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075C']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075B']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075A']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5T1941']                                         │
│                 │                           │ eho kĺbu, osteosyntéza drôtom alebo ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5T140W']                                         │
│                 │                           │ ngov prstov nohy bez osteosyntézy             │                                                              │
│             400 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['5T0800']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XX']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XW']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XV']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XU']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XT']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XS']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XR']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XQ']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XP']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074Z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074X']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074W']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074V']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074U']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074T']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074S']                                         │
│                 │                           │ a talu                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074R']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074P']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074N']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074M']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074J']                                         │
│                 │                           │ a pately                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074H']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12X1']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a iným osteosyntetickým materiálom            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XN']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XM']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XK']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XJ']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XF']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XE']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XC']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XB']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XA']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074F']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074E']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074D']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074C']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074B']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074A']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0748']                                         │
│                 │                           │ a diafyzárnej ulny                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0747']                                         │
│                 │                           │ a proximálnej ulny                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0744']                                         │
│                 │                           │ a proximálneho radia                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0743']                                         │
│                 │                           │ a distálneho humeru                           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0741']                                         │
│                 │                           │ a proximálneho humeru                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0740']                                         │
│                 │                           │ a klavikuly                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia panvy     │ vv.kod in ['5T073D']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia falangov  │ vv.kod in ['5T073C']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5T1911']                                         │
│                 │                           │ eho kĺbu, osteosyntéza skrutkou               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TZ']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TX']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TW']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TV']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TU']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TT']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia klavikuly │ vv.kod in ['5T0730']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia skapuly   │ vv.kod in ['5T072Z']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia ostatných │ vv.kod in ['5T072X']                                         │
│                 │                           │ kostí                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5T072W']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metatarzá │ vv.kod in ['5T072V']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia tarzálnyc │ vv.kod in ['5T072U']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia kalkanea  │ vv.kod in ['5T072T']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia talu      │ vv.kod in ['5T072S']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T072R']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072P']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T072N']                                         │
│                 │                           │ tibie                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072M']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia pately    │ vv.kod in ['5T072J']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T072H']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072G']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072F']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia krčka ste │ vv.kod in ['5T072E']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia panvy     │ vv.kod in ['5T072D']                                         │
│             400 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['5T38AA']                                         │
│                 │                           │ ohy                                           │                                                              │
│             400 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálnych a interfalan │ vv.kod in ['5T38A1']                                         │
│                 │                           │ geálnych kĺbov prsta nohy, 1 kĺb              │                                                              │
│             400 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['5T3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12CH']                                         │
│                 │                           │ bnej oblasti distálneho femuru, osteosyntéza  │                                                              │
│                 │                           │ uhlovou/kondylárnou dlahou                    │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12CE']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza uhlovou/kondylárnou dlahou                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TS']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TR']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TQ']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TP']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TN']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TM']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TK']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TC']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TB']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TA']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5T072C']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metakarpá │ vv.kod in ['5T072B']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia karpálnyc │ vv.kod in ['5T072A']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0728']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0727']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0724']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T0723']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0721']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia klavikuly │ vv.kod in ['5T0720']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia skapuly │ vv.kod in ['5T071Z']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia ostatný │ vv.kod in ['5T071X']                                         │
│                 │                           │ ch kostí                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5T071W']                                         │
│                 │                           │ v prstov nohy                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metatar │ vv.kod in ['5T071V']                                         │
│                 │                           │ zálnych kostí                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia tarzáln │ vv.kod in ['5T071U']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia kalkane │ vv.kod in ['5T071T']                                         │
│                 │                           │ a                                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia talu    │ vv.kod in ['5T071S']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T071R']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T071P']                                         │
│                 │                           │ lnej fibuly                                   │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T12B6']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza u │                                                              │
│                 │                           │ hlovostabilnou dlahou                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5T07E0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5T07DZ']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5T07DX']                                         │
│                 │                           │ kostí                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5T07DW']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5T07DV']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5T07DU']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5T07DT']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5T07DS']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07DR']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DQ']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DP']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07DN']                                         │
│                 │                           │ tibie                                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DM']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DK']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T071N']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T071M']                                         │
│                 │                           │ rnej tibie                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia pately  │ vv.kod in ['5T071J']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T071H']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T071G']                                         │
│                 │                           │ rneho femuru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T071F']                                         │
│                 │                           │ lneho femuru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia krčka s │ vv.kod in ['5T071E']                                         │
│                 │                           │ tehennej kosti                                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia panvy   │ vv.kod in ['5T071D']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5T071C']                                         │
│                 │                           │ v prstov ruky                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metakar │ vv.kod in ['5T071B']                                         │
│                 │                           │ pálnych kostí                                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia karpáln │ vv.kod in ['5T071A']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T0718']                                         │
│                 │                           │ rnej ulny                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T0717']                                         │
│                 │                           │ lnej ulny                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T0714']                                         │
│                 │                           │ lneho radia                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T0713']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T0711']                                         │
│                 │                           │ lneho humeru                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia klaviku │ vv.kod in ['5T0710']                                         │
│                 │                           │ ly                                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5T07DJ']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07DH']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DG']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DF']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5T07DE']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5T07DD']                                         │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5T07DC']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5T07DB']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5T07DA']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07D9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07D6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07D3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5T07D0']                                         │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T129F']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a transfixačným klincom                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T129E']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza transfixačným klincom                     │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BW']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BV']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BR']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5T19Z1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza rezorbovateľným materi │                                                              │
│                 │                           │ álom                                          │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5T1048']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahovou serklážou                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BC']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BB']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07B6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             400 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T123R']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza š │                                                              │
│                 │                           │ tandardnou dlahou                             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07B0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AZ']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AX']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AW']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AV']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AT']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AS']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AR']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AQ']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AP']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AN']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AM']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AK']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AJ']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AH']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AG']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AF']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AE']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AC']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             412 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5T19X1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza iným osteosyntetickým  │                                                              │
│                 │                           │ materiálom                                    │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5T154B']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza drôtom a ťahovo │                                                              │
│                 │                           │ u serklážou                                   │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5T1236']                                         │
│                 │                           │ bnej oblasti distálneho radia , osteosyntéza  │                                                              │
│                 │                           │ štandardnou dlahou                            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AB']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             306 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             435 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5T151B']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza skrutkou        │                                                              │
│             353 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia pr │ vv.kod in ['5T815X']                                         │
│                 │                           │ iečna, ostatné                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143B']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143A']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142X']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany, ostatné                            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142G']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti nohy (chodidlo)           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142F']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predkolenia               │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142E']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti stehna a kolena           │                                                              │
│            1035 │ vv.pocet*cena             │ Ostatné artroskopické operácie menisku        │ vv.kod in ['5T423X']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopické odstránenie umelého menisku     │ vv.kod in ['5T4234']                                         │
│            1164 │ vv.pocet*cena             │ Artroskopická implantácia umelého menisku     │ vv.kod in ['5T4233']                                         │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra menisku, zložitá         │ vv.kod in ['5T42322']                                        │
│            1164 │ vv.pocet*cena             │ Artroskopická refixácia menisku               │ vv.kod in ['5T42320']                                        │
│            1035 │ vv.pocet*cena             │ Artroskopická totálna resekcia menisku        │ vv.kod in ['5T42311']                                        │
│            1035 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5T42310']                                        │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142D']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v gluteálnej oblasti                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142B']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v brušnej oblasti                   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142A']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti hrudnej steny a chrbta    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ruky                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predlaktia                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a lakťa            │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti krku                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany ostatných častí hlavy               │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti pery                      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141X']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované, ostatné    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141G']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti n │                                                              │
│                 │                           │ ohy (chodidlo)                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141F']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redkolenia                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141E']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti s │                                                              │
│                 │                           │ tehna a kolena                                │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141D']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v gluteálne │                                                              │
│                 │                           │ j oblasti                                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141B']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v brušnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141A']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti h │                                                              │
│                 │                           │ rudnej steny a chrbta                         │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ uky                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redlaktia                                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a lakťa                                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti k │                                                              │
│                 │                           │ rku                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované ostatných č │                                                              │
│                 │                           │ astí hlavy                                    │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti n │ vv.kod in ['5T8549']                                         │
│                 │                           │ ohy                                           │                                                              │
│             388 │ vv.pocet*cena             │ Ostatné artrodézy kĺbov ruky                  │ vv.kod in ['5T76X']                                          │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev dlane              │ vv.kod in ['5T7079']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev palca              │ vv.kod in ['5T7078']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza šľachových pošiev prsta              │ vv.kod in ['5T7077']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza vystierača palca                     │ vv.kod in ['5T7075']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza vystierača prsta                     │ vv.kod in ['5T7074']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza ohýbača palca                        │ vv.kod in ['5T7072']                                         │
│             330 │ vv.pocet*cena             │ Tenolýza ohýbača prsta                        │ vv.kod in ['5T7071']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra vystierača prsta              │ vv.kod in ['5T7054']                                         │
│            1035 │ vv.pocet*cena             │ Artroskopické resekcie ganglia humeroglenoidá │ vv.kod in ['5T4920']                                         │
│                 │                           │ lny kĺb                                       │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický debridement šľachy kolenného kĺ │ vv.kod in ['5T491H']                                         │
│                 │                           │ bu                                            │                                                              │
│             350 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5T4914']                                         │
│                 │                           │ bu                                            │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický debridement šľachy humeroglenoi │ vv.kod in ['5T4910']                                         │
│                 │                           │ dálneho kĺbu                                  │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5T400H']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopický aseptický výplach bedrového kĺb │ vv.kod in ['5T400G']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ ery                                           │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140X']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, ostatné                              │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140G']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti nohy (chodidlo)             │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140F']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predkolenia                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140E']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti stehna a kolena             │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140D']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v gluteálnej oblasti                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140B']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v brušnej oblasti                     │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140A']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti hrudnej steny a chrbta      │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ruky                        │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predlaktia                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a lakťa              │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti krku                        │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5T8543']                                         │
│                 │                           │ redlaktia                                     │                                                              │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy, ostatné      │ vv.kod in ['5T853X']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti noh │ vv.kod in ['5T8539']                                         │
│                 │                           │ y                                             │                                                              │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5T8533']                                         │
│                 │                           │ dlaktia                                       │                                                              │
│             518 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti nohy       │ vv.kod in ['5T8529']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra ohýbača prsta                 │ vv.kod in ['5T7051']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5T7028']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5T7027']                                         │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach ulnokarpálneh │ vv.kod in ['5T4009']                                         │
│                 │                           │ o kĺbu s drenážou                             │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5T4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             846 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5T4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany ostatných častí hlavy                 │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti pery                        │                                                              │
│             470 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predlaktia │ vv.kod in ['5T8523']                                         │
│             518 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti nohy         │ vv.kod in ['5T8519']                                         │
│             470 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predlaktia   │ vv.kod in ['5T8513']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5T7022']                                         │
│             353 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5T7021']                                         │
│            1265 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5T44X']                                          │
│                 │                           │ kapsuloligamentóznom aparáte ramenného kĺbu   │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická laterálna resekcia klavikuly    │ vv.kod in ['5T44A']                                          │
│            1265 │ vv.pocet*cena             │ Artroskopické spevnenie púzdra s fixáciou na  │ vv.kod in ['5T445']                                          │
│                 │                           │ glenoid stehom                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131X']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131G']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti nohy (chodidlo)                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131F']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predkolenia                         │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131E']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti stehna a kolena                     │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131D']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteálnej oblasti                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131B']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej oblasti                             │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131A']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti hrudnej steny a chrbta              │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ruky                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predlaktia                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a lakťa                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti krku                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných častí hlavy                         │                                                              │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy, ostatné               │ vv.kod in ['5T891X']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti nohy         │ vv.kod in ['5T8919']                                         │
│             388 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predlaktia   │ vv.kod in ['5T8913']                                         │
│            1164 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5T43X']                                          │
│                 │                           │ kapsuloligamentóznom aparáte kolenného kĺbu   │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika laterálneho kapsulolig │ vv.kod in ['5T43E']                                          │
│                 │                           │ amentózneho aparátu kolenného kĺbu            │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika mediálneho kapsuloliga │ vv.kod in ['5T43D']                                          │
│                 │                           │ mentózneho aparátu kolenného kĺbu             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra laterálneho kapsuloligam │ vv.kod in ['5T43B']                                          │
│                 │                           │ entózneho aparátu kolenného kĺbu              │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra mediálneho kapsuloligame │ vv.kod in ['5T43A']                                          │
│                 │                           │ ntózneho aparátu kolenného kĺbu               │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopické uvoľnenie kolenného púzdra (lat │ vv.kod in ['5T439']                                          │
│                 │                           │ eral release)                                 │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženeho väz │ vv.kod in ['5T438']                                          │
│                 │                           │ u s aloplastickou náhradou                    │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5T437']                                          │
│                 │                           │ u s iným autológnym ligamentom                │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5T436']                                          │
│                 │                           │ u s autogénnou patelárnou šľachou             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5T435']                                          │
│                 │                           │ zu s aloplastickou náhradou                   │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5T434']                                          │
│                 │                           │ zu iným autológnym ligamentom                 │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti pery                                │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130X']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatné                                   │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130G']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti nohy (chodidlo)                  │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130F']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predkolenia                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130E']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti stehna a kolena                  │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130D']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v gluteálnej oblasti                       │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130B']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušnej oblasti                          │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130A']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti hrudnej steny a chrbta           │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ruky                             │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predlaktia                       │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a lakťa                   │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti krku                             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5T433']                                          │
│                 │                           │ zu autológnym patelárnym ligamentom           │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická kostná refixácia skríženého väz │ vv.kod in ['5T432']                                          │
│                 │                           │ u                                             │                                                              │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra zadného skríženého väzu  │ vv.kod in ['5T431']                                          │
│            1164 │ vv.pocet*cena             │ Artroskopická sutúra predného skríženého väzu │ vv.kod in ['5T430']                                          │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatných častí hlavy                      │                                                              │
│              59 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti pery                             │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa kolenn │ vv.kod in ['5T411H']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1470 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa bedrov │ vv.kod in ['5T411G']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická resekcia plica synovialis kolen │ vv.kod in ['5T410H']                                         │
│                 │                           │ ného kĺbu                                     │                                                              │
│             294 │ vv.pocet*cena             │ Transpozícia šliach, ostatné                  │ vv.kod in ['5T842X']                                         │
│             400 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5T7242']                                         │
│             353 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5T7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             353 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5T7220']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia viac ako jedného prsta │ vv.kod in ['5T7212']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia jedného prsta          │ vv.kod in ['5T7211']                                         │
│             306 │ vv.pocet*cena             │ Perkutánna fasciotómia pozdĺžna, ostatné      │ vv.kod in ['5T81AX']                                         │
│             353 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia po │ vv.kod in ['5T818X']                                         │
│                 │                           │ zdĺžna, jeden segment, ostatné                │                                                              │
│             418 │ vv.pocet*cena             │ Parciálna excízia retinaculum flexorum        │ vv.kod in ['5T7121']                                         │
│             418 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5T71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             418 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5T71110']                                        │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143X']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované, ostatné       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143G']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143F']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143E']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│              59 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143D']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre pozápalové stavy periférneho ner │ vv.kod in ['5A50HB']                                         │
│                 │                           │ vu na dolnej končatine                        │                                                              │
│             318 │ vv.pocet*cena             │ Operácia pre úžinový syndróm na dolnej končat │ vv.kod in ['5A50H9']                                         │
│                 │                           │ ine                                           │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre úžinový syndróm na hornej končat │ vv.kod in ['5A50H6X']                                        │
│                 │                           │ ine, iný                                      │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s tra │ vv.kod in ['5A50H64']                                        │
│                 │                           │ nspozíciou nervu                              │                                                              │
│             294 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s dek │ vv.kod in ['5A50H63']                                        │
│                 │                           │ ompresiou nervu                               │                                                              │
│             318 │ vv.pocet*cena             │ Dekompresia, deliberácia a uvoľnenie zrastov  │ vv.kod in ['5A50G']                                          │
│                 │                           │ periférneho nervu                             │                                                              │
│            1035 │ vv.pocet*cena             │ Artroskopická biopsia kolenného kĺbu          │ vv.kod in ['12T007']                                         │
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

