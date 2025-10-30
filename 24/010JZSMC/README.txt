                                                                         ==============
                                                                         Cenník chirurg
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
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t132']                                         │
│                 │                           │ tkanív v oblasti ramena a lakťa               │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             334 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             266 │ vv.pocet*cena             │ Endosonografia retroperitonea                 │ vv.kod in ['31314a']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia pankreasu                      │ vv.kod in ['313146']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia pažeráka                       │ vv.kod in ['313142']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia brucha, laparoskopická sonogra │ vv.kod in ['313149']                                         │
│                 │                           │ fia                                           │                                                              │
│             266 │ vv.pocet*cena             │ Endosonografia žlčových ciest                 │ vv.kod in ['313145']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia konečníka                      │ vv.kod in ['313148']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia dvanástnika                    │ vv.kod in ['313144']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia hrubého čreva                  │ vv.kod in ['313147']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia žalúdka                        │ vv.kod in ['313143']                                         │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│             227 │ vv.pocet*cena             │ Excízia a exstirpácia hemangiómu na koži      │ vv.kod in ['5v482']                                          │
│             418 │ vv.pocet*cena             │ Diagnostická laparoskopia                     │ vv.kod in ['14v11']                                          │
│             298 │ vv.pocet*cena             │ Jednodňová ZS - Ošetrenie popáleniny v celkov │ vv.kod in ['j0005']                                          │
│                 │                           │ ej anestéze                                   │                                                              │
│             262 │ vv.pocet*cena             │ Jednodňová ZS - Krytie defektov alebo korekci │ vv.kod in ['j0004']                                          │
│                 │                           │ a jazvy plastikou                             │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv15xx']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, ostatné       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150x']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha,  │                                                              │
│                 │                           │ ostatné                                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150g']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti nohy (chodidlo)                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150f']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti predkolenia                           │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150e']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti stehna a kolena                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150d']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ gluteálnej oblasti                            │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150c']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ inguinálnej a genitálnej oblasti              │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150b']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ brušnej oblasti                               │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv150a']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti hrudnej steny a chrbta                │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1509']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ruky                                  │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1508']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti predlaktia                            │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1507']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ramena a lakťa                        │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1506']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ramena a axily                        │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1505']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti krku                                  │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1504']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha o │                                                              │
│                 │                           │ statných častí hlavy                          │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['kv1500']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti pery                                  │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['kt8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              90 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['kt790']                                          │
│             795 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['kl1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             752 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['kl1957']                                         │
│             703 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['kl1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             703 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['kl194x']                                         │
│             743 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['kl1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             743 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['kl1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             743 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['kl1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             743 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['kl1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['kl1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['kl1931']                                         │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['kl1930']                                         │
│             703 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['kl1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             743 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['kl1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             743 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['kl1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             703 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['kl1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             703 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['kl19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             703 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['kl19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             703 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['kl1903']                                         │
│             703 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['kl1902']                                         │
│             703 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['kl1901']                                         │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['kn810x']                                         │
│                 │                           │ lastiky, ostatné                              │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn818']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, resekciou │                                                              │
│                 │                           │ čreva bez dodatočnej laparotómie              │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['kn8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8171']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparosko │                                                              │
│                 │                           │ picky transperitoneálne                       │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] bez │ vv.kod in ['5n840']                                          │
│                 │                           │ plastiky                                      │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totálny extraperitoneálny prístup         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n818']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, resekciou │                                                              │
│                 │                           │ čreva bez dodatočnej laparotómie              │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['kn8102']                                         │
│                 │                           │ lastiky s funikulolýzou a dislokáciou semenní │                                                              │
│                 │                           │ ka                                            │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['kn813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             477 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5n9342']                                         │
│                 │                           │ svalov s operáciou umbilikálnej hernie [priet │                                                              │
│                 │                           │ rže]                                          │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             618 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8930']                                         │
│                 │                           │ rží] aloplastickým materiálom, laparotomicky  │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže], ost │ vv.kod in ['5n83x']                                          │
│                 │                           │ atné                                          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5n8301']                                         │
│                 │                           │ plastiky s exstirpáciou pupočnej cysty        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n893x']                                         │
│                 │                           │ rží] s aloplastickým materiálom, ostatné      │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s res │ vv.kod in ['5n814']                                          │
│                 │                           │ ekciou čreva bez dodatočnej laparotómie       │                                                              │
│             428 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn8150']                                         │
│                 │                           │ ecidíve s plastikou bez funikulo-orchidolýzy  │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['kn8103']                                         │
│                 │                           │ lastiky bez ďalších výkonov                   │                                                              │
│             262 │ vv.pocet*cena             │ Biologická nekrektómia [Maggot therapy]       │ vv.kod in ['kg210']                                          │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn8151']                                         │
│                 │                           │ ecidíve s plastikou s funikulo-orchidolýzou   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['kn8101']                                         │
│                 │                           │ lastiky s resekciou steny hydrokély           │                                                              │
│             585 │ vv.pocet*cena             │ Iné uzavretie ďalších abdominálnych hernií [p │ vv.kod in ['5n89x']                                          │
│                 │                           │ rietrží], ostatné                             │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5n8302']                                         │
│                 │                           │ plastiky s odstránením urachu                 │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n816']                                          │
│                 │                           │ ecidíve s autológnym materiálom               │                                                              │
│             618 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5n830x']                                         │
│                 │                           │ plastiky, ostatné                             │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n833x']                                         │
│                 │                           │ oplastickým materiálom, ostatné               │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s aut │ vv.kod in ['kn812']                                          │
│                 │                           │ ológnym materiálom                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8432']                                         │
│                 │                           │ loplastickým materiálom, endoskopicky totálny │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn81x']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['kn811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] s alop │ vv.kod in ['5n8231']                                         │
│                 │                           │ lastickým materiálom, laparoskopicky transper │                                                              │
│                 │                           │ itoneálne                                     │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8332']                                         │
│                 │                           │ oplastickým materiálom, endoskopicky totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n892']                                          │
│                 │                           │ rží] s autológnym materiálom                  │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou resekciou                           │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5n8303']                                         │
│                 │                           │ plastiky bez ďalších výkonov                  │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5n8541']                                         │
│                 │                           │ tickým materiálom, laparoskopicky transperito │                                                              │
│                 │                           │ neálne                                        │                                                              │
│             555 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8431']                                         │
│                 │                           │ loplastickým materiálom, laparoskopicky trans │                                                              │
│                 │                           │ peritoneálne                                  │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8101']                                         │
│                 │                           │ lastiky s resekciou steny hydrokély           │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže], os │ vv.kod in ['5n84x']                                          │
│                 │                           │ tatné                                         │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totálny extraperitoneálny prístup         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n842']                                          │
│                 │                           │ utológnym materiálom                          │                                                              │
│             618 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n843x']                                         │
│                 │                           │ loplastickým materiálom, ostatné              │                                                              │
│             555 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             618 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8150']                                         │
│                 │                           │ ecidíve s plastikou bez funikulo-orchidolýzy  │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8102']                                         │
│                 │                           │ lastiky s funikulolýzou a dislokáciou semenní │                                                              │
│                 │                           │ ka                                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n81x']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8931']                                         │
│                 │                           │ rží] s aloplastickým materiálom, laparoskopic │                                                              │
│                 │                           │ ky transperitoneálne                          │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['kn816']                                          │
│                 │                           │ ecidíve s autológnym materiálom               │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['kn8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s au │ vv.kod in ['5n832']                                          │
│                 │                           │ tológnym materiálom                           │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické operácie na pankreatických cestá │ vv.kod in ['5n73g']                                          │
│                 │                           │ ch, prístup cez retrográdnu endoskopiu        │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8103']                                         │
│                 │                           │ lastiky bez ďalších výkonov                   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n891']                                          │
│                 │                           │ rží] s plastikou                              │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8151']                                         │
│                 │                           │ ecidíve s plastikou s funikulo-orchidolýzou   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['kn8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou resekciou                           │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8331']                                         │
│                 │                           │ oplastickým materiálom, laparoskopicky transp │                                                              │
│                 │                           │ eritoneálne                                   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] pri re │ vv.kod in ['5n8271']                                         │
│                 │                           │ cidíve s aloplastickým materiálom, laparoskop │                                                              │
│                 │                           │ icky transperitoneálne                        │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s aut │ vv.kod in ['5n812']                                          │
│                 │                           │ ológnym materiálom                            │                                                              │
│             618 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8932']                                         │
│                 │                           │ rží] s aloplastickým materiálom, endoskopicky │                                                              │
│                 │                           │ totálny extraperitoneálny prístup             │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n890']                                          │
│                 │                           │ rží] bez plastiky                             │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s res │ vv.kod in ['kn814']                                          │
│                 │                           │ ekciou čreva bez dodatočnej laparotómie       │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n810x']                                         │
│                 │                           │ lastiky, ostatné                              │                                                              │
│              71 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5t790']                                          │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ac']                                         │
│                 │                           │ plastika malej plochy v inguinálnej a genitál │                                                              │
│                 │                           │ nej oblasti                                   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a6']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a axil │                                                              │
│                 │                           │ y                                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232c']                                         │
│                 │                           │ anspozičná plastika malej plochy v inguinálne │                                                              │
│                 │                           │ j a genitálnej oblasti                        │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2326']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a axily                                  │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2324']                                         │
│                 │                           │ anspozičná plastika malej plochy v ostatných  │                                                              │
│                 │                           │ častiach hlavy                                │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231c']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ingui │                                                              │
│                 │                           │ nálnej a genitálnej oblasti                   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2316']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena a axily                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145c']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v in │                                                              │
│                 │                           │ guinálnej a genitálnej oblasti                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1456']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ramena a axily                          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1446']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ramena a axily      │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a axily            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141c']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v inguináln │                                                              │
│                 │                           │ ej a genitálnej oblasti                       │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a axily                                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a axily              │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a axily                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a axily                   │                                                              │
│             334 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, viacpo │ vv.kod in ['5u1101']                                         │
│                 │                           │ četná lézia                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076h']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074k']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074g']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0749']                                         │
│                 │                           │ a distálnej ulny                              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0746']                                         │
│                 │                           │ a distálneho radia                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0745']                                         │
│                 │                           │ a diafyzárneho radia                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0742']                                         │
│                 │                           │ a diafyzárneho humeru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia distálneh │ vv.kod in ['5t0736']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072q']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072k']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t0729']                                         │
│                 │                           │ ulny                                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0726']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0725']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0722']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0719']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0712']                                         │
│                 │                           │ rneho humeru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5n3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vv']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vu']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vt']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vs']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vr']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vq']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vp']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vn']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vm']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vk']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vb']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07va']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             429 │ vv.pocet*cena             │ Adheziolýza na čreve, laparoskopicky          │ vv.kod in ['5n3922']                                         │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou ostatných lymfatických uzl │ vv.kod in ['13m10x']                                         │
│                 │                           │ ín                                            │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou lymfatických uzlín panvy   │ vv.kod in ['13m107']                                         │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou inguinálnych lymfatických  │ vv.kod in ['13m106']                                         │
│                 │                           │ uzlín                                         │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou iliakálnych lymfatických u │ vv.kod in ['13m105']                                         │
│                 │                           │ zlín                                          │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou paraaortálnych lymfatickýc │ vv.kod in ['13m104']                                         │
│                 │                           │ h uzlín                                       │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou mediastinálnych lymfatický │ vv.kod in ['13m103']                                         │
│                 │                           │ ch uzlín                                      │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou axilárnych lymfatických uz │ vv.kod in ['13m102']                                         │
│                 │                           │ lín                                           │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou supraklavikulárnych lymfat │ vv.kod in ['13m101']                                         │
│                 │                           │ ických uzlín                                  │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou cervikálnych lymfatických  │ vv.kod in ['13m100']                                         │
│                 │                           │ uzlín                                         │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia viacerých lymfatických uzlín z to │ vv.kod in ['5m130']                                          │
│                 │                           │ ho istého miesta                              │                                                              │
│             120 │ vv.pocet*cena             │ Exstirpácia lymfangiómu                       │ vv.kod in ['5m103']                                          │
│             220 │ vv.pocet*cena             │ Exstirpácia axilárnych lymfatických uzlín jed │ vv.kod in ['5m102']                                          │
│                 │                           │ nostranne                                     │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia supraklavikulárnych lymfatických  │ vv.kod in ['5m101']                                          │
│                 │                           │ uzlín jednostranne                            │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia lymfatickej uzliny                │ vv.kod in ['5m100']                                          │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože tváre                │ vv.kod in ['12v008']                                         │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v007']                                         │
│                 │                           │ nohy                                          │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v006']                                         │
│                 │                           │ predkolenia                                   │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v005']                                         │
│                 │                           │ stehna                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v004']                                         │
│                 │                           │ trupu                                         │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v003']                                         │
│                 │                           │ ruky a predlaktia                             │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v002']                                         │
│                 │                           │ ramena a lakťa                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v001']                                         │
│                 │                           │ ramena                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12v000']                                         │
│                 │                           │ krku                                          │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t237']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti nohy   │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t236']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti predko │                                                              │
│                 │                           │ lenia                                         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t235']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti stehna │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t234']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti trupu  │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t233']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ruky a │                                                              │
│                 │                           │ predlaktia                                    │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t232']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ramena │                                                              │
│                 │                           │ a lakťa                                       │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t231']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ramena │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t230']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti krku   │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t131']                                         │
│                 │                           │ tkanív v oblasti ramena                       │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia supraklavikulárny │ vv.kod in ['12m111']                                         │
│                 │                           │ ch lymfatických uzlín (Virchow uzlina)        │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia povrchového nádoru krku           │ vv.kod in ['5b1664']                                         │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru hlbokých mäkkých tkanív kr │ vv.kod in ['5b1663']                                         │
│                 │                           │ ku                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5l50241']                                        │
│                 │                           │ ilica na axile                                │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5l50232']                                        │
│                 │                           │ . cephalica                                   │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5l50231']                                        │
│                 │                           │ . basilica                                    │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5g92102']                                        │
│                 │                           │ stí miestnou lalokovou plastikou              │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5g92101']                                        │
│                 │                           │ stí priamou sutúrou                           │                                                              │
│             561 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['5l1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             561 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['5l1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             418 │ vv.pocet*cena             │ Subanodermálna excízia análnej fistuly        │ vv.kod in ['5n4516']                                         │
│             418 │ vv.pocet*cena             │ Submukózna excízia análnej fistuly            │ vv.kod in ['5n4515']                                         │
│             418 │ vv.pocet*cena             │ Extrasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4514']                                         │
│             418 │ vv.pocet*cena             │ Suprasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4513']                                         │
│             418 │ vv.pocet*cena             │ Transsfinkterická excízia análnej fistuly     │ vv.kod in ['5n4512']                                         │
│             418 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             561 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             561 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             561 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['5l1903']                                         │
│             561 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['5l1902']                                         │
│             561 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['5l1901']                                         │
│             266 │ vv.pocet*cena             │ Jejunoskopia                                  │ vv.kod in ['14n113']                                         │
│             266 │ vv.pocet*cena             │ Ezofagogastroduodenoskopia                    │ vv.kod in ['14n112']                                         │
│             266 │ vv.pocet*cena             │ Ezofagogastroskopia                           │ vv.kod in ['14n111']                                         │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou ostatných svalov a mäkkých │ vv.kod in ['13t10x']                                         │
│                 │                           │ tkanív                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t107']                                         │
│                 │                           │ oblasti nohy                                  │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t106']                                         │
│                 │                           │ oblasti predkolenia                           │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t105']                                         │
│                 │                           │ oblasti stehna                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t104']                                         │
│                 │                           │ oblasti trupu                                 │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t103']                                         │
│                 │                           │ oblasti predlaktia a ruky                     │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t102']                                         │
│                 │                           │ oblasti ramena a lakťa                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t101']                                         │
│                 │                           │ oblasti ramena                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13t100']                                         │
│                 │                           │ oblasti krku                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077r']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077n']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077m']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077k']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077f']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077e']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076r']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076n']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076m']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076g']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076f']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076e']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075x']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075w']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075v']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075u']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075t']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075s']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075j']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075h']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075g']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075f']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075e']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075d']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075c']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075b']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075a']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xx']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xw']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xv']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xu']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xt']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xs']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xr']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xq']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xp']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074x']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074w']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074v']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074u']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074t']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074s']                                         │
│                 │                           │ a talu                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074r']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074p']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074n']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074m']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074j']                                         │
│                 │                           │ a pately                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074h']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xn']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xm']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xk']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xj']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xf']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xe']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xc']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xb']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xa']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074f']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074e']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074d']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074c']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074b']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074a']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0748']                                         │
│                 │                           │ a diafyzárnej ulny                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0747']                                         │
│                 │                           │ a proximálnej ulny                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0744']                                         │
│                 │                           │ a proximálneho radia                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0743']                                         │
│                 │                           │ a distálneho humeru                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0741']                                         │
│                 │                           │ a proximálneho humeru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0740']                                         │
│                 │                           │ a klavikuly                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia panvy     │ vv.kod in ['5t073d']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia falangov  │ vv.kod in ['5t073c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tz']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tx']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tw']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tv']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tu']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tt']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia klavikuly │ vv.kod in ['5t0730']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia skapuly   │ vv.kod in ['5t072z']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia ostatných │ vv.kod in ['5t072x']                                         │
│                 │                           │ kostí                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072w']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metatarzá │ vv.kod in ['5t072v']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia tarzálnyc │ vv.kod in ['5t072u']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia kalkanea  │ vv.kod in ['5t072t']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia talu      │ vv.kod in ['5t072s']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072r']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072p']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072n']                                         │
│                 │                           │ tibie                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072m']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia pately    │ vv.kod in ['5t072j']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t072h']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072g']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072f']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia krčka ste │ vv.kod in ['5t072e']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia panvy     │ vv.kod in ['5t072d']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ts']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tr']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tq']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tp']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tn']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tm']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tk']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tc']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tb']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ta']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metakarpá │ vv.kod in ['5t072b']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia karpálnyc │ vv.kod in ['5t072a']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0728']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0727']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0724']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0723']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0721']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia klavikuly │ vv.kod in ['5t0720']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia skapuly │ vv.kod in ['5t071z']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia ostatný │ vv.kod in ['5t071x']                                         │
│                 │                           │ ch kostí                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071w']                                         │
│                 │                           │ v prstov nohy                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metatar │ vv.kod in ['5t071v']                                         │
│                 │                           │ zálnych kostí                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia tarzáln │ vv.kod in ['5t071u']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia kalkane │ vv.kod in ['5t071t']                                         │
│                 │                           │ a                                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia talu    │ vv.kod in ['5t071s']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5t07e0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5t07dz']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5t07dx']                                         │
│                 │                           │ kostí                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dw']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5t07dv']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5t07du']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5t07dt']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5t07ds']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dr']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dq']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dp']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dn']                                         │
│                 │                           │ tibie                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dm']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dk']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia pately  │ vv.kod in ['5t071j']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071h']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071g']                                         │
│                 │                           │ rneho femuru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071f']                                         │
│                 │                           │ lneho femuru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia krčka s │ vv.kod in ['5t071e']                                         │
│                 │                           │ tehennej kosti                                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia panvy   │ vv.kod in ['5t071d']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071c']                                         │
│                 │                           │ v prstov ruky                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metakar │ vv.kod in ['5t071b']                                         │
│                 │                           │ pálnych kostí                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia karpáln │ vv.kod in ['5t071a']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0718']                                         │
│                 │                           │ rnej ulny                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0713']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0711']                                         │
│                 │                           │ lneho humeru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia klaviku │ vv.kod in ['5t0710']                                         │
│                 │                           │ ly                                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5t07dj']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07dh']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dg']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07df']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5t07de']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5t07dd']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dc']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5t07db']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5t07da']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07d9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5t07d0']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bw']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bv']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07br']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bc']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bb']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07az']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ax']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aw']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07av']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07at']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07as']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ar']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aq']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ap']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07an']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07am']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ak']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aj']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ah']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ag']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07af']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ae']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ac']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ab']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             418 │ vv.pocet*cena             │ Laparoskopia bez otvorenia pneumoperitonea    │ vv.kod in ['5z1121']                                         │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany, ostatné                            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti nohy (chodidlo)           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predkolenia               │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti stehna a kolena           │                                                              │
│             334 │ vv.pocet*cena             │ Lumpektómia                                   │ vv.kod in ['5u112']                                          │
│             334 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, jedna  │ vv.kod in ['5u1100']                                         │
│                 │                           │ lézia                                         │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v gluteálnej oblasti                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v brušnej oblasti                   │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti hrudnej steny a chrbta    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ruky                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predlaktia                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a lakťa            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti krku                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany ostatných častí hlavy               │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti pery                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované, ostatné    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti n │                                                              │
│                 │                           │ ohy (chodidlo)                                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redkolenia                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti s │                                                              │
│                 │                           │ tehna a kolena                                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v gluteálne │                                                              │
│                 │                           │ j oblasti                                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v brušnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti h │                                                              │
│                 │                           │ rudnej steny a chrbta                         │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ uky                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redlaktia                                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a lakťa                                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti k │                                                              │
│                 │                           │ rku                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované ostatných č │                                                              │
│                 │                           │ astí hlavy                                    │                                                              │
│              71 │ vv.pocet*cena             │ Exartikulácia prsta ruky                      │ vv.kod in ['5t935']                                          │
│              71 │ vv.pocet*cena             │ Amputácia prsta ruky                          │ vv.kod in ['5t933']                                          │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ ery                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, ostatné                              │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti nohy (chodidlo)             │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predkolenia                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti stehna a kolena             │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v gluteálnej oblasti                  │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v brušnej oblasti                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti hrudnej steny a chrbta      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ruky                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predlaktia                  │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a lakťa              │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti krku                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany ostatných častí hlavy                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti pery                        │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, os │ vv.kod in ['5v23xx']                                         │
│                 │                           │ tatné                                         │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131x']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131g']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti nohy (chodidlo)                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131f']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predkolenia                         │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131e']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti stehna a kolena                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131d']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteálnej oblasti                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131b']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej oblasti                             │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131a']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti hrudnej steny a chrbta              │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ruky                                │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predlaktia                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a lakťa                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti krku                                │                                                              │
│              63 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných častí hlavy                         │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ag']                                         │
│                 │                           │ plastika malej plochy v oblasti nohy (chodidl │                                                              │
│                 │                           │ o)                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23af']                                         │
│                 │                           │ plastika malej plochy v oblasti predkolenia   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ae']                                         │
│                 │                           │ plastika malej plochy v oblasti stehna a kole │                                                              │
│                 │                           │ na                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ad']                                         │
│                 │                           │ plastika malej plochy v gluteálnej oblasti    │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ab']                                         │
│                 │                           │ plastika malej plochy v brušnej oblasti       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23aa']                                         │
│                 │                           │ plastika malej plochy v oblasti hrudnej steny │                                                              │
│                 │                           │ a chrbta                                      │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a9']                                         │
│                 │                           │ plastika malej plochy v oblasti ruky          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a8']                                         │
│                 │                           │ plastika malej plochy v oblasti predlaktia    │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti pery                                │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130x']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatné                                   │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130g']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti nohy (chodidlo)                  │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130f']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predkolenia                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130e']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti stehna a kolena                  │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130d']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v gluteálnej oblasti                       │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130b']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušnej oblasti                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130a']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti hrudnej steny a chrbta           │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ruky                             │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predlaktia                       │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a lakťa                   │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti krku                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a7']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a lakť │                                                              │
│                 │                           │ a                                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a5']                                         │
│                 │                           │ plastika malej plochy v oblasti krku          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a4']                                         │
│                 │                           │ plastika malej plochy v ostatných častí hlavy │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a0']                                         │
│                 │                           │ plastika malej plochy v oblasti pery          │                                                              │
│             406 │ vv.pocet*cena             │ Incízia sinus pilonidalis                     │ vv.kod in ['5v194']                                          │
│             406 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5v193']                                          │
│                 │                           │ né                                            │                                                              │
│             406 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatných častí hlavy                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti pery                             │                                                              │
│             238 │ vv.pocet*cena             │ Odstránenie nechtovej matrix                  │ vv.kod in ['5v17a']                                          │
│             238 │ vv.pocet*cena             │ Plastika nechta                               │ vv.kod in ['5v179']                                          │
│             238 │ vv.pocet*cena             │ Excízia poškodeného tkaniva nechtového lôžka  │ vv.kod in ['5v176']                                          │
│             238 │ vv.pocet*cena             │ Totálna excízia nechta                        │ vv.kod in ['5v175']                                          │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145x']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou mikrografická chirurgia, osta │                                                              │
│                 │                           │ tné                                           │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145g']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti nohy (chodidlo)                         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145f']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti predkolenia                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145e']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti stehna a kolena                         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145d']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145b']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v br │                                                              │
│                 │                           │ ušnej oblasti                                 │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145a']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti hrudnej steny a chrbta                  │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1459']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ruky                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1458']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti predlaktia                              │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1457']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ramena a lakťa                          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232x']                                         │
│                 │                           │ anspozičná plastika malej plochy, ostatné     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232g']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti no │                                                              │
│                 │                           │ hy (chodidlo)                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232f']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edkolenia                                     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232e']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti st │                                                              │
│                 │                           │ ehna a kolena                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232d']                                         │
│                 │                           │ anspozičná plastika malej plochy v gluteálnej │                                                              │
│                 │                           │ oblasti                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232b']                                         │
│                 │                           │ anspozičná plastika malej plochy v brušnej ob │                                                              │
│                 │                           │ lasti                                         │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232a']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti hr │                                                              │
│                 │                           │ udnej steny a chrbta                          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2329']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ru │                                                              │
│                 │                           │ ky                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2328']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edlaktia                                      │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2327']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a lakťa                                  │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2325']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti kr │                                                              │
│                 │                           │ ku                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2320']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pe │                                                              │
│                 │                           │ ry                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231x']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1455']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti krku                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1454']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia osta │                                                              │
│                 │                           │ tných častí hlavy                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1450']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti pery                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144x']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, ostatné                      │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144g']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti nohy (chodidlo)     │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144f']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti predkolenia         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144e']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti stehna a kolena     │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144d']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v gluteálnej oblasti          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144b']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v brušnej oblasti             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144a']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti hrudnej steny a chr │                                                              │
│                 │                           │ bta                                           │                                                              │
│             334 │ vv.pocet*cena             │ Mikroduktektómia prsníka                      │ vv.kod in ['5u114']                                          │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231g']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti nohy (chodidlo)                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231f']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predkolenia                                │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231e']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti stehna a kolena                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231d']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v glute │                                                              │
│                 │                           │ álnej oblasti                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231b']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v brušn │                                                              │
│                 │                           │ ej oblasti                                    │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231a']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti hrudnej steny a chrbta                     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2319']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ruky                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2318']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predlaktia                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2317']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena a lakťa                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2315']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti krku                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2314']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ostat │                                                              │
│                 │                           │ ných častí hlavy                              │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2310']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti pery                                       │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1449']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ruky                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1448']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti predlaktia          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1447']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ramena a lakťa      │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1445']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti krku                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1444']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou ostatných častí hlavy         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1440']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti pery                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované, ostatné       │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│              63 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5n632x']                                         │
│                 │                           │ ých ciest, ostatné                            │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5n6323']                                         │
│                 │                           │ ých ciest elektrohydraulickou litotripsiou    │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5n6322']                                         │
│                 │                           │ ých ciest mechanickou litotripsiou            │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5n6321']                                         │
│                 │                           │ ých ciest balónovým katétrom                  │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5n6320']                                         │
│                 │                           │ ých ciest košíkom                             │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n2222']                                         │
│                 │                           │ hrubého čreva, polypektómia viac ako 2 polypo │                                                              │
│                 │                           │ v pomocou slučky                              │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n2221']                                         │
│                 │                           │ hrubého čreva, polypektómia 1-2 polypov pomoc │                                                              │
│                 │                           │ ou slučky                                     │                                                              │
│             996 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopická deštrukcia na pankreatických ces │ vv.kod in ['5n734']                                          │
│                 │                           │ tách                                          │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n732x']                                         │
│                 │                           │ eatických ciest, ostatné                      │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7325']                                         │
│                 │                           │ eatických ciest laserovou litotripsiou        │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7324']                                         │
│                 │                           │ eatických ciest elektrohydraulickou litotrips │                                                              │
│                 │                           │ iou a použitím laseru                         │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7323']                                         │
│                 │                           │ eatických ciest elektrohydraulickou litotrips │                                                              │
│                 │                           │ iou                                           │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7322']                                         │
│                 │                           │ eatických ciest mechanickou litotripsiou      │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7321']                                         │
│                 │                           │ eatických ciest balónovým katetétrom          │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5n7320']                                         │
│                 │                           │ eatických ciest košíkom                       │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n4122']                                         │
│                 │                           │ konečníka, polypektómia viac ako 2 polypov po │                                                              │
│                 │                           │ mocou slučky                                  │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n4121']                                         │
│                 │                           │ konečníka, polypektómia 1-2 polypov pomocou s │                                                              │
│                 │                           │ lučky                                         │                                                              │
│             429 │ vv.pocet*cena             │ Laparoskopia s adheziolýzou                   │ vv.kod in ['5n9981']                                         │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n410x']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4107']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picko-mikrochirurgicky                        │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4106']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picky                                         │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4100']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou peranál │                                                              │
│                 │                           │ ne                                            │                                                              │
│             477 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5n9341']                                         │
│                 │                           │ svalov                                        │                                                              │
│             477 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5n45x']                                          │
│             477 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             477 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             477 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             477 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5n45c']                                          │
│             477 │ vv.pocet*cena             │ Sklerotizácia hemoroidov                      │ vv.kod in ['5n45b']                                          │
│             418 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5n459']                                          │
│             418 │ vv.pocet*cena             │ Uzavretie análnej fistuly pomocou plugovej te │ vv.kod in ['5n453']                                          │
│                 │                           │ chniky                                        │                                                              │
│             418 │ vv.pocet*cena             │ Závitová drenáž análnej fistuly               │ vv.kod in ['5n452']                                          │
│             418 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5n451x']                                         │
│             418 │ vv.pocet*cena             │ Intersfinkterická excízia análnej fistuly     │ vv.kod in ['5n4511']                                         │
│             418 │ vv.pocet*cena             │ Incízia análnej fistuly                       │ vv.kod in ['5n450']                                          │
│             238 │ vv.pocet*cena             │ Incízia chorého tkaniva análneho kanála/tkani │ vv.kod in ['5n440']                                          │
│                 │                           │ va perianálnej oblasti                        │                                                              │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5n361x']                                         │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             632 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['5l1957']                                         │
│             668 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             561 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5l194x']                                         │
│             592 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             592 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             592 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             592 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5l1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5l1931']                                         │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5l1930']                                         │
│             592 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             592 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             592 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie arterio-venóznej fistuly, ostatné  │ vv.kod in ['5l502x']                                         │
│             238 │ vv.pocet*cena             │ Zrušenie A-V fistuly s rekonštrukciou tepny   │ vv.kod in ['5l502c1']                                        │
│             238 │ vv.pocet*cena             │ Zrušenie A-V fistuly bez rekonštrukcie tepny  │ vv.kod in ['5l502c0']                                        │
│             453 │ vv.pocet*cena             │ Trombektómia A-V fistuly                      │ vv.kod in ['5l502b']                                         │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia arterio-venóznej fistuly │ vv.kod in ['5l502ax']                                        │
│                 │                           │ , ostatné                                     │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, ligatúra ve │ vv.kod in ['5l502a5']                                        │
│                 │                           │ tiev                                          │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, banding     │ vv.kod in ['5l502a4']                                        │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5l502a3']                                        │
│                 │                           │ fia s protetickým materiálom                  │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5l502a2']                                        │
│                 │                           │ fia bez protetického materiálu                │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly s použitím i │ vv.kod in ['5l502a1']                                        │
│                 │                           │ nterpozitu                                    │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly [PAI, RUDI,  │ vv.kod in ['5l502a0']                                        │
│                 │                           │ DRAL, DRIL, PRAL, .....]                      │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie dočasného A-V shuntu (peroperačný) │ vv.kod in ['5l5029']                                         │
│             453 │ vv.pocet*cena             │ Vytvorenie vonkajšieho A-V shuntu             │ vv.kod in ['5l5028']                                         │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5l50273']                                        │
│                 │                           │ mocou cievnej protézy                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5l50272']                                        │
│                 │                           │ transpozíciou žily                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5l50271']                                        │
│                 │                           │ transpozíciou VFS                             │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5l50270']                                        │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na hornej končatine po │ vv.kod in ['5l5026']                                         │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou allogénnej cie │ vv.kod in ['5l50251']                                        │
│                 │                           │ vy                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou autológnej cie │ vv.kod in ['5l50250']                                        │
│                 │                           │ vy                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5l50240']                                        │
│                 │                           │ ilica na predlaktí                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly (sec │ vv.kod in ['5l50230']                                        │
│                 │                           │ . Gracz sec. Konner)                          │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na predlaktí HK (R-C,  │ vv.kod in ['5l5022']                                         │
│                 │                           │ R-B, U-C, U-B)                                │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (fossa │ vv.kod in ['5l50211']                                        │
│                 │                           │ tabatiere- snuff box)                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (Cimin │ vv.kod in ['5l50210']                                        │
│                 │                           │ o - Brescia)                                  │                                                              │
│             266 │ vv.pocet*cena             │ Rigídna rektoskopia                           │ vv.kod in ['14n2122']                                        │
│             266 │ vv.pocet*cena             │ Flexibilná rektoskopia                        │ vv.kod in ['14n2121']                                        │
│             266 │ vv.pocet*cena             │ Proktoskopia                                  │ vv.kod in ['14n2120']                                        │
│             266 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14n211x']                                        │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická rektoskopia, stómický prístup    │ vv.kod in ['14n2114']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická proktoskopia, stómický prístup   │ vv.kod in ['14n2113']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická sigmoideoskopia, stómický prístu │ vv.kod in ['14n2112']                                        │
│                 │                           │ p                                             │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická kolonoskopia, stómický prístup   │ vv.kod in ['14n2111']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická ileoskopia, stómický prístup     │ vv.kod in ['14n2110']                                        │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t130']                                         │
│                 │                           │ tkanív v oblasti krku                         │                                                              │
│             266 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14n210x']                                        │
│                 │                           │ tráviaceho systému, okrem stómického prístupu │                                                              │
│             266 │ vv.pocet*cena             │ Chromoendoskopia hrubého čreva                │ vv.kod in ['14n2104']                                        │
│             266 │ vv.pocet*cena             │ Sigmoideoskopia (okrem stómického prístupu)   │ vv.kod in ['14n2103']                                        │
│             266 │ vv.pocet*cena             │ Totálna kolonoskopia s ileoskopiou            │ vv.kod in ['14n2102']                                        │
│             266 │ vv.pocet*cena             │ Totálna kolonoskopia bez ileoskopie           │ vv.kod in ['14n2101']                                        │
│             266 │ vv.pocet*cena             │ Parciálna kolonoskopia                        │ vv.kod in ['14n2100']                                        │
│             266 │ vv.pocet*cena             │ Chromoendoskopia hornej časti tráviaceho syst │ vv.kod in ['14n132']                                         │
│                 │                           │ ému                                           │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická endoskopia ostatnej hornej časti │ vv.kod in ['14n12x']                                         │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             266 │ vv.pocet*cena             │ Jejunoskopia stómický prístup                 │ vv.kod in ['14n125']                                         │
│             266 │ vv.pocet*cena             │ Ezofagoskopia stómický prístup                │ vv.kod in ['14n121']                                         │
│             266 │ vv.pocet*cena             │ Intestinoskopia, ostatné                      │ vv.kod in ['14n114x']                                        │
│             266 │ vv.pocet*cena             │ Intestinoskopia "push-pull-back" technikou    │ vv.kod in ['14n1141']                                        │
│             266 │ vv.pocet*cena             │ Intestinoskopia "push" technikou              │ vv.kod in ['14n1140']                                        │
│             266 │ vv.pocet*cena             │ Ezofagoskopia, iná                            │ vv.kod in ['14n110x']                                        │
│             266 │ vv.pocet*cena             │ Flexibilná ezofagoskopia                      │ vv.kod in ['14n1102']                                        │
│             266 │ vv.pocet*cena             │ Rigídna ezofagoskopia                         │ vv.kod in ['14n1101']                                        │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12m216']                                         │
│                 │                           │ n panvy s použitím zobrazovacích metód        │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia iliakálnych lymfa │ vv.kod in ['12m215']                                         │
│                 │                           │ tických uzlín s použitím zobrazovacích metód  │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia paraaortálnych ly │ vv.kod in ['12m214']                                         │
│                 │                           │ mfatických uzlín s použitím zobrazovacích met │                                                              │
│                 │                           │ ód                                            │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia mediastinálnych l │ vv.kod in ['12m213']                                         │
│                 │                           │ ymfatických uzlín s použitím zobrazovacích me │                                                              │
│                 │                           │ tód                                           │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia axilárnych lymfat │ vv.kod in ['12m212']                                         │
│                 │                           │ ických uzlín s použitím zobrazovacích metód   │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia supraklavikulárny │ vv.kod in ['12m211']                                         │
│                 │                           │ ch lymfatických uzlín (Virchow uzlina) s použ │                                                              │
│                 │                           │ itím zobrazovacích metód                      │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12m210']                                         │
│                 │                           │ n krku s použitím zobrazovacích metód         │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia inguinálnych lymf │ vv.kod in ['12m117']                                         │
│                 │                           │ atických uzlín                                │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12m116']                                         │
│                 │                           │ n panvy                                       │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia iliakálnych lymfa │ vv.kod in ['12m115']                                         │
│                 │                           │ tických uzlín                                 │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia paraaortálnych ly │ vv.kod in ['12m114']                                         │
│                 │                           │ mfatických uzlín                              │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia mediastinálnych l │ vv.kod in ['12m113']                                         │
│                 │                           │ ymfatických uzlín                             │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia axilárnych lymfat │ vv.kod in ['12m112']                                         │
│                 │                           │ ických uzlín                                  │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12m110']                                         │
│                 │                           │ n krku                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia, ostatné  │ vv.kod in ['12v00x']                                         │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12t23x']                                         │
│                 │                           │ použitím zobrazovacích metód, ostatné         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t13x']                                         │
│                 │                           │ tkanív, ostatné                               │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t137']                                         │
│                 │                           │ tkanív v oblasti nohy                         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t136']                                         │
│                 │                           │ tkanív oblasti predkolenia                    │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t135']                                         │
│                 │                           │ tkanív v oblasti stehna                       │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t134']                                         │
│                 │                           │ tkanív v oblasti trupu                        │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t133']                                         │
│                 │                           │ tkanív v oblasti ruky a predlaktia            │                                                              │
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

