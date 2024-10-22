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
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T132']                                         │
│                 │                           │ tkanív v oblasti ramena a lakťa               │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T892X']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             334 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5U111']                                          │
│             266 │ vv.pocet*cena             │ Endosonografia retroperitonea                 │ vv.kod in ['31314A']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia pankreasu                      │ vv.kod in ['313146']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia pažeráka                       │ vv.kod in ['313142']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia brucha, laparoskopická sonogra │ vv.kod in ['313149']                                         │
│                 │                           │ fia                                           │                                                              │
│             266 │ vv.pocet*cena             │ Endosonografia žlčových ciest                 │ vv.kod in ['313145']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia konečníka                      │ vv.kod in ['313148']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia dvanástnika                    │ vv.kod in ['313144']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia hrubého čreva                  │ vv.kod in ['313147']                                         │
│             266 │ vv.pocet*cena             │ Endosonografia žalúdka                        │ vv.kod in ['313143']                                         │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              71 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│             227 │ vv.pocet*cena             │ Excízia a exstirpácia hemangiómu na koži      │ vv.kod in ['5V482']                                          │
│             418 │ vv.pocet*cena             │ Diagnostická laparoskopia                     │ vv.kod in ['14V11']                                          │
│             298 │ vv.pocet*cena             │ Jednodňová ZS - Ošetrenie popáleniny v celkov │ vv.kod in ['J0005']                                          │
│                 │                           │ ej anestéze                                   │                                                              │
│             262 │ vv.pocet*cena             │ Jednodňová ZS - Krytie defektov alebo korekci │ vv.kod in ['J0004']                                          │
│                 │                           │ a jazvy plastikou                             │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV15XX']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, ostatné       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150X']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha,  │                                                              │
│                 │                           │ ostatné                                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150G']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti nohy (chodidlo)                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150F']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti predkolenia                           │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150E']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti stehna a kolena                       │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150D']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ gluteálnej oblasti                            │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150C']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ inguinálnej a genitálnej oblasti              │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150B']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ brušnej oblasti                               │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV150A']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti hrudnej steny a chrbta                │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1509']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ruky                                  │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1508']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti predlaktia                            │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1507']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ramena a lakťa                        │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1506']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti ramena a axily                        │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1505']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti krku                                  │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1504']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha o │                                                              │
│                 │                           │ statných častí hlavy                          │                                                              │
│             262 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['KV1500']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti pery                                  │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT892X']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              90 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['KT8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              90 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['KT790']                                          │
│             752 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['KL1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             752 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['KL1957']                                         │
│             703 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['KL1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             703 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['KL194X']                                         │
│             703 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['KL1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             703 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['KL1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             703 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['KL1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             703 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['KL1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['KL1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['KL1931']                                         │
│             703 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['KL1930']                                         │
│             703 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['KL1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             703 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['KL1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             703 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['KL1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             703 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['KL1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             703 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['KL19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             703 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['KL19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             703 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['KL1903']                                         │
│             703 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['KL1902']                                         │
│             703 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['KL1901']                                         │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['KN810X']                                         │
│                 │                           │ lastiky, ostatné                              │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN818']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, resekciou │                                                              │
│                 │                           │ čreva bez dodatočnej laparotómie              │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['KN8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N8171']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparosko │                                                              │
│                 │                           │ picky transperitoneálne                       │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] bez │ vv.kod in ['5N840']                                          │
│                 │                           │ plastiky                                      │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totálny extraperitoneálny prístup         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N818']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, resekciou │                                                              │
│                 │                           │ čreva bez dodatočnej laparotómie              │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['KN8102']                                         │
│                 │                           │ lastiky s funikulolýzou a dislokáciou semenní │                                                              │
│                 │                           │ ka                                            │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['KN813X']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             477 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5N9342']                                         │
│                 │                           │ svalov s operáciou umbilikálnej hernie [priet │                                                              │
│                 │                           │ rže]                                          │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N817X']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5N8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N8930']                                         │
│                 │                           │ rží] aloplastickým materiálom, laparotomicky  │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže], ost │ vv.kod in ['5N83X']                                          │
│                 │                           │ atné                                          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5N8301']                                         │
│                 │                           │ plastiky s exstirpáciou pupočnej cysty        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N893X']                                         │
│                 │                           │ rží] s aloplastickým materiálom, ostatné      │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s res │ vv.kod in ['5N814']                                          │
│                 │                           │ ekciou čreva bez dodatočnej laparotómie       │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5N811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN8150']                                         │
│                 │                           │ ecidíve s plastikou bez funikulo-orchidolýzy  │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN817X']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['KN8103']                                         │
│                 │                           │ lastiky bez ďalších výkonov                   │                                                              │
│             262 │ vv.pocet*cena             │ Biologická nekrektómia [Maggot therapy]       │ vv.kod in ['KG210']                                          │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN8151']                                         │
│                 │                           │ ecidíve s plastikou s funikulo-orchidolýzou   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['KN8101']                                         │
│                 │                           │ lastiky s resekciou steny hydrokély           │                                                              │
│             585 │ vv.pocet*cena             │ Iné uzavretie ďalších abdominálnych hernií [p │ vv.kod in ['5N89X']                                          │
│                 │                           │ rietrží], ostatné                             │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5N8302']                                         │
│                 │                           │ plastiky s odstránením urachu                 │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N816']                                          │
│                 │                           │ ecidíve s autológnym materiálom               │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5N830X']                                         │
│                 │                           │ plastiky, ostatné                             │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5N833X']                                         │
│                 │                           │ oplastickým materiálom, ostatné               │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s aut │ vv.kod in ['KN812']                                          │
│                 │                           │ ológnym materiálom                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5N8432']                                         │
│                 │                           │ loplastickým materiálom, endoskopicky totálny │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN81X']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['KN811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] s alop │ vv.kod in ['5N8231']                                         │
│                 │                           │ lastickým materiálom, laparoskopicky transper │                                                              │
│                 │                           │ itoneálne                                     │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5N8332']                                         │
│                 │                           │ oplastickým materiálom, endoskopicky totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N892']                                          │
│                 │                           │ rží] s autológnym materiálom                  │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5N8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou resekciou                           │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] bez  │ vv.kod in ['5N8303']                                         │
│                 │                           │ plastiky bez ďalších výkonov                  │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5N8541']                                         │
│                 │                           │ tickým materiálom, laparoskopicky transperito │                                                              │
│                 │                           │ neálne                                        │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5N8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5N8431']                                         │
│                 │                           │ loplastickým materiálom, laparoskopicky trans │                                                              │
│                 │                           │ peritoneálne                                  │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5N8101']                                         │
│                 │                           │ lastiky s resekciou steny hydrokély           │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže], os │ vv.kod in ['5N84X']                                          │
│                 │                           │ tatné                                         │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totálny extraperitoneálny prístup         │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5N842']                                          │
│                 │                           │ utológnym materiálom                          │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5N8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5N843X']                                         │
│                 │                           │ loplastickým materiálom, ostatné              │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5N831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5N841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N8150']                                         │
│                 │                           │ ecidíve s plastikou bez funikulo-orchidolýzy  │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5N8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperitoneálny prístup                     │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5N8102']                                         │
│                 │                           │ lastiky s funikulolýzou a dislokáciou semenní │                                                              │
│                 │                           │ ka                                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N81X']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N8931']                                         │
│                 │                           │ rží] s aloplastickým materiálom, laparoskopic │                                                              │
│                 │                           │ ky transperitoneálne                          │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['KN816']                                          │
│                 │                           │ ecidíve s autológnym materiálom               │                                                              │
│             716 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['KN8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             525 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s au │ vv.kod in ['5N832']                                          │
│                 │                           │ tológnym materiálom                           │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické operácie na pankreatických cestá │ vv.kod in ['5N73G']                                          │
│                 │                           │ ch, prístup cez retrográdnu endoskopiu        │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5N8103']                                         │
│                 │                           │ lastiky bez ďalších výkonov                   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N891']                                          │
│                 │                           │ rží] s plastikou                              │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5N8151']                                         │
│                 │                           │ ecidíve s plastikou s funikulo-orchidolýzou   │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['KN8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou resekciou                           │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5N8331']                                         │
│                 │                           │ oplastickým materiálom, laparoskopicky transp │                                                              │
│                 │                           │ eritoneálne                                   │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] pri re │ vv.kod in ['5N8271']                                         │
│                 │                           │ cidíve s aloplastickým materiálom, laparoskop │                                                              │
│                 │                           │ icky transperitoneálne                        │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s aut │ vv.kod in ['5N812']                                          │
│                 │                           │ ológnym materiálom                            │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5N8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N8932']                                         │
│                 │                           │ rží] s aloplastickým materiálom, endoskopicky │                                                              │
│                 │                           │ totálny extraperitoneálny prístup             │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5N890']                                          │
│                 │                           │ rží] bez plastiky                             │                                                              │
│             537 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s res │ vv.kod in ['KN814']                                          │
│                 │                           │ ekciou čreva bez dodatočnej laparotómie       │                                                              │
│             585 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5N813X']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             406 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5N810X']                                         │
│                 │                           │ lastiky, ostatné                              │                                                              │
│              71 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5T790']                                          │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AC']                                         │
│                 │                           │ plastika malej plochy v inguinálnej a genitál │                                                              │
│                 │                           │ nej oblasti                                   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A6']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a axil │                                                              │
│                 │                           │ y                                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232C']                                         │
│                 │                           │ anspozičná plastika malej plochy v inguinálne │                                                              │
│                 │                           │ j a genitálnej oblasti                        │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2326']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a axily                                  │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2324']                                         │
│                 │                           │ anspozičná plastika malej plochy v ostatných  │                                                              │
│                 │                           │ častiach hlavy                                │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231C']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ingui │                                                              │
│                 │                           │ nálnej a genitálnej oblasti                   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2316']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena a axily                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145C']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v in │                                                              │
│                 │                           │ guinálnej a genitálnej oblasti                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1456']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ramena a axily                          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1446']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ramena a axily      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a axily            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141C']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v inguináln │                                                              │
│                 │                           │ ej a genitálnej oblasti                       │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a axily                                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a axily              │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a axily                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a axily                   │                                                              │
│             334 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, viacpo │ vv.kod in ['5U1101']                                         │
│                 │                           │ četná lézia                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076H']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074Q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074K']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074G']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0749']                                         │
│                 │                           │ a distálnej ulny                              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0746']                                         │
│                 │                           │ a distálneho radia                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0745']                                         │
│                 │                           │ a diafyzárneho radia                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0742']                                         │
│                 │                           │ a diafyzárneho humeru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia distálneh │ vv.kod in ['5T0736']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072Q']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072K']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T0729']                                         │
│                 │                           │ ulny                                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T0726']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0725']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0722']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T0719']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T0712']                                         │
│                 │                           │ rneho humeru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5N3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VV']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VU']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VT']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VS']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VR']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VQ']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VP']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VN']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VM']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VK']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VB']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07VA']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5T07V4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             429 │ vv.pocet*cena             │ Adheziolýza na čreve, laparoskopicky          │ vv.kod in ['5N3922']                                         │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou ostatných lymfatických uzl │ vv.kod in ['13M10X']                                         │
│                 │                           │ ín                                            │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou lymfatických uzlín panvy   │ vv.kod in ['13M107']                                         │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou inguinálnych lymfatických  │ vv.kod in ['13M106']                                         │
│                 │                           │ uzlín                                         │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou iliakálnych lymfatických u │ vv.kod in ['13M105']                                         │
│                 │                           │ zlín                                          │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou paraaortálnych lymfatickýc │ vv.kod in ['13M104']                                         │
│                 │                           │ h uzlín                                       │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou mediastinálnych lymfatický │ vv.kod in ['13M103']                                         │
│                 │                           │ ch uzlín                                      │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou axilárnych lymfatických uz │ vv.kod in ['13M102']                                         │
│                 │                           │ lín                                           │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou supraklavikulárnych lymfat │ vv.kod in ['13M101']                                         │
│                 │                           │ ických uzlín                                  │                                                              │
│             220 │ vv.pocet*cena             │ Biopsia s incíziou cervikálnych lymfatických  │ vv.kod in ['13M100']                                         │
│                 │                           │ uzlín                                         │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia viacerých lymfatických uzlín z to │ vv.kod in ['5M130']                                          │
│                 │                           │ ho istého miesta                              │                                                              │
│             120 │ vv.pocet*cena             │ Exstirpácia lymfangiómu                       │ vv.kod in ['5M103']                                          │
│             220 │ vv.pocet*cena             │ Exstirpácia axilárnych lymfatických uzlín jed │ vv.kod in ['5M102']                                          │
│                 │                           │ nostranne                                     │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia supraklavikulárnych lymfatických  │ vv.kod in ['5M101']                                          │
│                 │                           │ uzlín jednostranne                            │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia lymfatickej uzliny                │ vv.kod in ['5M100']                                          │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože tváre                │ vv.kod in ['12V008']                                         │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V007']                                         │
│                 │                           │ nohy                                          │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V006']                                         │
│                 │                           │ predkolenia                                   │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V005']                                         │
│                 │                           │ stehna                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V004']                                         │
│                 │                           │ trupu                                         │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V003']                                         │
│                 │                           │ ruky a predlaktia                             │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V002']                                         │
│                 │                           │ ramena a lakťa                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V001']                                         │
│                 │                           │ ramena                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia v oblasti │ vv.kod in ['12V000']                                         │
│                 │                           │ krku                                          │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T237']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti nohy   │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T236']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti predko │                                                              │
│                 │                           │ lenia                                         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T235']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti stehna │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T234']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti trupu  │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T233']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ruky a │                                                              │
│                 │                           │ predlaktia                                    │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T232']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ramena │                                                              │
│                 │                           │ a lakťa                                       │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T231']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti ramena │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T230']                                         │
│                 │                           │ použitím zobrazovacích metód v oblasti krku   │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T131']                                         │
│                 │                           │ tkanív v oblasti ramena                       │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia supraklavikulárny │ vv.kod in ['12M111']                                         │
│                 │                           │ ch lymfatických uzlín (Virchow uzlina)        │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia povrchového nádoru krku           │ vv.kod in ['5B1664']                                         │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru hlbokých mäkkých tkanív kr │ vv.kod in ['5B1663']                                         │
│                 │                           │ ku                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5L50241']                                        │
│                 │                           │ ilica na axile                                │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5L50232']                                        │
│                 │                           │ . cephalica                                   │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5L50231']                                        │
│                 │                           │ . basilica                                    │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5G92102']                                        │
│                 │                           │ stí miestnou lalokovou plastikou              │                                                              │
│             220 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5G92101']                                        │
│                 │                           │ stí priamou sutúrou                           │                                                              │
│             561 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['5L1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             561 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['5L1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             418 │ vv.pocet*cena             │ Subanodermálna excízia análnej fistuly        │ vv.kod in ['5N4516']                                         │
│             418 │ vv.pocet*cena             │ Submukózna excízia análnej fistuly            │ vv.kod in ['5N4515']                                         │
│             418 │ vv.pocet*cena             │ Extrasfinkterická excízia análnej fistuly     │ vv.kod in ['5N4514']                                         │
│             418 │ vv.pocet*cena             │ Suprasfinkterická excízia análnej fistuly     │ vv.kod in ['5N4513']                                         │
│             418 │ vv.pocet*cena             │ Transsfinkterická excízia análnej fistuly     │ vv.kod in ['5N4512']                                         │
│             418 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5N4510']                                         │
│             561 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5L19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             561 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5L19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             561 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['5L1903']                                         │
│             561 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['5L1902']                                         │
│             561 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['5L1901']                                         │
│             266 │ vv.pocet*cena             │ Jejunoskopia                                  │ vv.kod in ['14N113']                                         │
│             266 │ vv.pocet*cena             │ Ezofagogastroduodenoskopia                    │ vv.kod in ['14N112']                                         │
│             266 │ vv.pocet*cena             │ Ezofagogastroskopia                           │ vv.kod in ['14N111']                                         │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou ostatných svalov a mäkkých │ vv.kod in ['13T10X']                                         │
│                 │                           │ tkanív                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T107']                                         │
│                 │                           │ oblasti nohy                                  │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T106']                                         │
│                 │                           │ oblasti predkolenia                           │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T105']                                         │
│                 │                           │ oblasti stehna                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T104']                                         │
│                 │                           │ oblasti trupu                                 │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T103']                                         │
│                 │                           │ oblasti predlaktia a ruky                     │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T102']                                         │
│                 │                           │ oblasti ramena a lakťa                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T101']                                         │
│                 │                           │ oblasti ramena                                │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia s incíziou svalov a mäkkých tkanív v  │ vv.kod in ['13T100']                                         │
│                 │                           │ oblasti krku                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077R']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077N']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077M']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077K']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077F']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5T077E']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076R']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076Q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076N']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076M']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076G']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076F']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5T076E']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075Z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075X']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075W']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075V']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075U']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075T']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075S']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075J']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075H']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075G']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075F']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075E']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075D']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075C']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075B']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T075A']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XX']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XW']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XV']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XU']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XT']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XS']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XR']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XQ']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XP']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5T0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074Z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074X']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074W']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074V']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074U']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074T']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074S']                                         │
│                 │                           │ a talu                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074R']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074P']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074N']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074M']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074J']                                         │
│                 │                           │ a pately                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074H']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XN']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XM']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XK']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XJ']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XF']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XE']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XC']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XB']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07XA']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5T07X5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074F']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074E']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074D']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074C']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074B']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T074A']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0748']                                         │
│                 │                           │ a diafyzárnej ulny                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0747']                                         │
│                 │                           │ a proximálnej ulny                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0744']                                         │
│                 │                           │ a proximálneho radia                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0743']                                         │
│                 │                           │ a distálneho humeru                           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0741']                                         │
│                 │                           │ a proximálneho humeru                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5T0740']                                         │
│                 │                           │ a klavikuly                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia panvy     │ vv.kod in ['5T073D']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia falangov  │ vv.kod in ['5T073C']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TZ']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TX']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TW']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TV']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TU']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TT']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia klavikuly │ vv.kod in ['5T0730']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia skapuly   │ vv.kod in ['5T072Z']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia ostatných │ vv.kod in ['5T072X']                                         │
│                 │                           │ kostí                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5T072W']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metatarzá │ vv.kod in ['5T072V']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia tarzálnyc │ vv.kod in ['5T072U']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia kalkanea  │ vv.kod in ['5T072T']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia talu      │ vv.kod in ['5T072S']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T072R']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072P']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5T072N']                                         │
│                 │                           │ tibie                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072M']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia pately    │ vv.kod in ['5T072J']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T072H']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T072G']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T072F']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia krčka ste │ vv.kod in ['5T072E']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia panvy     │ vv.kod in ['5T072D']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TS']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TR']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TQ']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TP']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TN']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TM']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TK']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TC']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TB']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07TA']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5T072C']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metakarpá │ vv.kod in ['5T072B']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia karpálnyc │ vv.kod in ['5T072A']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5T0728']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0727']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0724']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5T0723']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5T0721']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia klavikuly │ vv.kod in ['5T0720']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia skapuly │ vv.kod in ['5T071Z']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia ostatný │ vv.kod in ['5T071X']                                         │
│                 │                           │ ch kostí                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5T071W']                                         │
│                 │                           │ v prstov nohy                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metatar │ vv.kod in ['5T071V']                                         │
│                 │                           │ zálnych kostí                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia tarzáln │ vv.kod in ['5T071U']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia kalkane │ vv.kod in ['5T071T']                                         │
│                 │                           │ a                                             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia talu    │ vv.kod in ['5T071S']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5T07T4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5T07E0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5T07DZ']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5T07DX']                                         │
│                 │                           │ kostí                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5T07DW']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5T07DV']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5T07DU']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5T07DT']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5T07DS']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07DR']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DQ']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DP']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07DN']                                         │
│                 │                           │ tibie                                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DM']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DK']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia pately  │ vv.kod in ['5T071J']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T071H']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T071G']                                         │
│                 │                           │ rneho femuru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T071F']                                         │
│                 │                           │ lneho femuru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia krčka s │ vv.kod in ['5T071E']                                         │
│                 │                           │ tehennej kosti                                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia panvy   │ vv.kod in ['5T071D']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5T071C']                                         │
│                 │                           │ v prstov ruky                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metakar │ vv.kod in ['5T071B']                                         │
│                 │                           │ pálnych kostí                                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia karpáln │ vv.kod in ['5T071A']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5T0718']                                         │
│                 │                           │ rnej ulny                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5T0713']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5T0711']                                         │
│                 │                           │ lneho humeru                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia klaviku │ vv.kod in ['5T0710']                                         │
│                 │                           │ ly                                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5T07DJ']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07DH']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07DG']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07DF']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5T07DE']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5T07DD']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5T07DC']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5T07DB']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5T07DA']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5T07D9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07D6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5T07D3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5T07D2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5T07D1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5T07D0']                                         │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BW']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BV']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BR']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BC']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07BB']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07B6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5T07B0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AZ']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AX']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AW']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AV']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AT']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AS']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AR']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AQ']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AP']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AN']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AM']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AK']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AJ']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AH']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AG']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AF']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AE']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AC']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07AB']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             310 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5T07A0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             418 │ vv.pocet*cena             │ Laparoskopia bez otvorenia pneumoperitonea    │ vv.kod in ['5Z1121']                                         │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143B']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143A']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142X']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany, ostatné                            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142G']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti nohy (chodidlo)           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142F']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predkolenia               │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142E']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti stehna a kolena           │                                                              │
│             334 │ vv.pocet*cena             │ Lumpektómia                                   │ vv.kod in ['5U112']                                          │
│             334 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, jedna  │ vv.kod in ['5U1100']                                         │
│                 │                           │ lézia                                         │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142D']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v gluteálnej oblasti                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142B']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v brušnej oblasti                   │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V142A']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti hrudnej steny a chrbta    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ruky                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predlaktia                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a lakťa            │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti krku                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany ostatných častí hlavy               │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti pery                      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141X']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované, ostatné    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141G']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti n │                                                              │
│                 │                           │ ohy (chodidlo)                                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141F']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redkolenia                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141E']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti s │                                                              │
│                 │                           │ tehna a kolena                                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141D']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v gluteálne │                                                              │
│                 │                           │ j oblasti                                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141B']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v brušnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V141A']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti h │                                                              │
│                 │                           │ rudnej steny a chrbta                         │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ uky                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redlaktia                                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a lakťa                                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti k │                                                              │
│                 │                           │ rku                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované ostatných č │                                                              │
│                 │                           │ astí hlavy                                    │                                                              │
│              71 │ vv.pocet*cena             │ Exartikulácia prsta ruky                      │ vv.kod in ['5T935']                                          │
│              71 │ vv.pocet*cena             │ Amputácia prsta ruky                          │ vv.kod in ['5T933']                                          │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ ery                                           │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140X']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, ostatné                              │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140G']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti nohy (chodidlo)             │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140F']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predkolenia                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140E']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti stehna a kolena             │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140D']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v gluteálnej oblasti                  │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140B']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v brušnej oblasti                     │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V140A']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti hrudnej steny a chrbta      │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ruky                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predlaktia                  │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a lakťa              │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti krku                        │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany ostatných častí hlavy                 │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti pery                        │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, os │ vv.kod in ['5V23XX']                                         │
│                 │                           │ tatné                                         │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131X']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131G']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti nohy (chodidlo)                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131F']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predkolenia                         │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131E']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti stehna a kolena                     │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131D']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteálnej oblasti                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131B']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej oblasti                             │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V131A']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti hrudnej steny a chrbta              │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ruky                                │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predlaktia                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a lakťa                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti krku                                │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných častí hlavy                         │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AG']                                         │
│                 │                           │ plastika malej plochy v oblasti nohy (chodidl │                                                              │
│                 │                           │ o)                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AF']                                         │
│                 │                           │ plastika malej plochy v oblasti predkolenia   │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AE']                                         │
│                 │                           │ plastika malej plochy v oblasti stehna a kole │                                                              │
│                 │                           │ na                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AD']                                         │
│                 │                           │ plastika malej plochy v gluteálnej oblasti    │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AB']                                         │
│                 │                           │ plastika malej plochy v brušnej oblasti       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23AA']                                         │
│                 │                           │ plastika malej plochy v oblasti hrudnej steny │                                                              │
│                 │                           │ a chrbta                                      │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A9']                                         │
│                 │                           │ plastika malej plochy v oblasti ruky          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A8']                                         │
│                 │                           │ plastika malej plochy v oblasti predlaktia    │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti pery                                │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130X']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatné                                   │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130G']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti nohy (chodidlo)                  │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130F']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predkolenia                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130E']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti stehna a kolena                  │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130D']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v gluteálnej oblasti                       │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130B']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušnej oblasti                          │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V130A']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti hrudnej steny a chrbta           │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ruky                             │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predlaktia                       │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a lakťa                   │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti krku                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A7']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a lakť │                                                              │
│                 │                           │ a                                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A5']                                         │
│                 │                           │ plastika malej plochy v oblasti krku          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A4']                                         │
│                 │                           │ plastika malej plochy v ostatných častí hlavy │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5V23A0']                                         │
│                 │                           │ plastika malej plochy v oblasti pery          │                                                              │
│             406 │ vv.pocet*cena             │ Incízia sinus pilonidalis                     │ vv.kod in ['5V194']                                          │
│             406 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5V193']                                          │
│                 │                           │ né                                            │                                                              │
│             406 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5V191']                                          │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatných častí hlavy                      │                                                              │
│              60 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5V1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti pery                             │                                                              │
│             238 │ vv.pocet*cena             │ Odstránenie nechtovej matrix                  │ vv.kod in ['5V17A']                                          │
│             238 │ vv.pocet*cena             │ Plastika nechta                               │ vv.kod in ['5V179']                                          │
│             238 │ vv.pocet*cena             │ Excízia poškodeného tkaniva nechtového lôžka  │ vv.kod in ['5V176']                                          │
│             238 │ vv.pocet*cena             │ Totálna excízia nechta                        │ vv.kod in ['5V175']                                          │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145X']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou mikrografická chirurgia, osta │                                                              │
│                 │                           │ tné                                           │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145G']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti nohy (chodidlo)                         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145F']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti predkolenia                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145E']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti stehna a kolena                         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145D']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145B']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v br │                                                              │
│                 │                           │ ušnej oblasti                                 │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V145A']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti hrudnej steny a chrbta                  │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1459']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ruky                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1458']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti predlaktia                              │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1457']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti ramena a lakťa                          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232X']                                         │
│                 │                           │ anspozičná plastika malej plochy, ostatné     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232G']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti no │                                                              │
│                 │                           │ hy (chodidlo)                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232F']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edkolenia                                     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232E']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti st │                                                              │
│                 │                           │ ehna a kolena                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232D']                                         │
│                 │                           │ anspozičná plastika malej plochy v gluteálnej │                                                              │
│                 │                           │ oblasti                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232B']                                         │
│                 │                           │ anspozičná plastika malej plochy v brušnej ob │                                                              │
│                 │                           │ lasti                                         │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V232A']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti hr │                                                              │
│                 │                           │ udnej steny a chrbta                          │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2329']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ru │                                                              │
│                 │                           │ ky                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2328']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edlaktia                                      │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2327']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a lakťa                                  │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2325']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti kr │                                                              │
│                 │                           │ ku                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5V2320']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pe │                                                              │
│                 │                           │ ry                                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231X']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1455']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti krku                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1454']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia osta │                                                              │
│                 │                           │ tných častí hlavy                             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1450']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, mikrografická chirurgia v ob │                                                              │
│                 │                           │ lasti pery                                    │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144X']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou, ostatné                      │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144G']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti nohy (chodidlo)     │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144F']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti predkolenia         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144E']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti stehna a kolena     │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144D']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v gluteálnej oblasti          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144B']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v brušnej oblasti             │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V144A']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti hrudnej steny a chr │                                                              │
│                 │                           │ bta                                           │                                                              │
│             334 │ vv.pocet*cena             │ Mikroduktektómia prsníka                      │ vv.kod in ['5U114']                                          │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231G']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti nohy (chodidlo)                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231F']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predkolenia                                │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231E']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti stehna a kolena                            │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231D']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v glute │                                                              │
│                 │                           │ álnej oblasti                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231B']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v brušn │                                                              │
│                 │                           │ ej oblasti                                    │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V231A']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti hrudnej steny a chrbta                     │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2319']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ruky                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2318']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predlaktia                                 │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2317']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena a lakťa                             │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2315']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti krku                                       │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2314']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ostat │                                                              │
│                 │                           │ ných častí hlavy                              │                                                              │
│             238 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5V2310']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti pery                                       │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1449']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ruky                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1448']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti predlaktia          │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1447']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti ramena a lakťa      │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1445']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti krku                │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1444']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou ostatných častí hlavy         │                                                              │
│             238 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V1440']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpozíciou v oblasti pery                │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143X']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované, ostatné       │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143G']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143F']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143E']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│              60 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5V143D']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5N632X']                                         │
│                 │                           │ ých ciest, ostatné                            │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5N6323']                                         │
│                 │                           │ ých ciest elektrohydraulickou litotripsiou    │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5N6322']                                         │
│                 │                           │ ých ciest mechanickou litotripsiou            │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5N6321']                                         │
│                 │                           │ ých ciest balónovým katétrom                  │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementu zo žlčov │ vv.kod in ['5N6320']                                         │
│                 │                           │ ých ciest košíkom                             │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N2222']                                         │
│                 │                           │ hrubého čreva, polypektómia viac ako 2 polypo │                                                              │
│                 │                           │ v pomocou slučky                              │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N2221']                                         │
│                 │                           │ hrubého čreva, polypektómia 1-2 polypov pomoc │                                                              │
│                 │                           │ ou slučky                                     │                                                              │
│             942 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5N6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopická deštrukcia na pankreatických ces │ vv.kod in ['5N734']                                          │
│                 │                           │ tách                                          │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N732X']                                         │
│                 │                           │ eatických ciest, ostatné                      │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7325']                                         │
│                 │                           │ eatických ciest laserovou litotripsiou        │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7324']                                         │
│                 │                           │ eatických ciest elektrohydraulickou litotrips │                                                              │
│                 │                           │ iou a použitím laseru                         │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7323']                                         │
│                 │                           │ eatických ciest elektrohydraulickou litotrips │                                                              │
│                 │                           │ iou                                           │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7322']                                         │
│                 │                           │ eatických ciest mechanickou litotripsiou      │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7321']                                         │
│                 │                           │ eatických ciest balónovým katetétrom          │                                                              │
│             406 │ vv.pocet*cena             │ Endoskopické odstránenie konkrementov z pankr │ vv.kod in ['5N7320']                                         │
│                 │                           │ eatických ciest košíkom                       │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N4122']                                         │
│                 │                           │ konečníka, polypektómia viac ako 2 polypov po │                                                              │
│                 │                           │ mocou slučky                                  │                                                              │
│             215 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5N4121']                                         │
│                 │                           │ konečníka, polypektómia 1-2 polypov pomocou s │                                                              │
│                 │                           │ lučky                                         │                                                              │
│             429 │ vv.pocet*cena             │ Laparoskopia s adheziolýzou                   │ vv.kod in ['5N9981']                                         │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N410X']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4107']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picko-mikrochirurgicky                        │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4106']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picky                                         │                                                              │
│             215 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5N4100']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou peranál │                                                              │
│                 │                           │ ne                                            │                                                              │
│             477 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5N9341']                                         │
│                 │                           │ svalov                                        │                                                              │
│             477 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5N45X']                                          │
│             477 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5N45F']                                          │
│                 │                           │ u                                             │                                                              │
│             477 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5N45E']                                          │
│             477 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5N45D']                                          │
│             477 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5N45C']                                          │
│             477 │ vv.pocet*cena             │ Sklerotizácia hemoroidov                      │ vv.kod in ['5N45B']                                          │
│             418 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5N459']                                          │
│             418 │ vv.pocet*cena             │ Uzavretie análnej fistuly pomocou plugovej te │ vv.kod in ['5N453']                                          │
│                 │                           │ chniky                                        │                                                              │
│             418 │ vv.pocet*cena             │ Závitová drenáž análnej fistuly               │ vv.kod in ['5N452']                                          │
│             418 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5N451X']                                         │
│             418 │ vv.pocet*cena             │ Intersfinkterická excízia análnej fistuly     │ vv.kod in ['5N4511']                                         │
│             418 │ vv.pocet*cena             │ Incízia análnej fistuly                       │ vv.kod in ['5N450']                                          │
│             238 │ vv.pocet*cena             │ Incízia chorého tkaniva análneho kanála/tkani │ vv.kod in ['5N440']                                          │
│                 │                           │ va perianálnej oblasti                        │                                                              │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5N361X']                                         │
│             942 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5N3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             632 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['5L1957']                                         │
│             632 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5L1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             561 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5L194X']                                         │
│             561 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5L1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             561 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5L1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             561 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5L1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             561 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5L1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5L1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5L1931']                                         │
│             561 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5L1930']                                         │
│             561 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5L1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             561 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5L1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             561 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5L1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie arterio-venóznej fistuly, ostatné  │ vv.kod in ['5L502X']                                         │
│             238 │ vv.pocet*cena             │ Zrušenie A-V fistuly s rekonštrukciou tepny   │ vv.kod in ['5L502C1']                                        │
│             238 │ vv.pocet*cena             │ Zrušenie A-V fistuly bez rekonštrukcie tepny  │ vv.kod in ['5L502C0']                                        │
│             453 │ vv.pocet*cena             │ Trombektómia A-V fistuly                      │ vv.kod in ['5L502B']                                         │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia arterio-venóznej fistuly │ vv.kod in ['5L502AX']                                        │
│                 │                           │ , ostatné                                     │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, ligatúra ve │ vv.kod in ['5L502A5']                                        │
│                 │                           │ tiev                                          │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, banding     │ vv.kod in ['5L502A4']                                        │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5L502A3']                                        │
│                 │                           │ fia s protetickým materiálom                  │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5L502A2']                                        │
│                 │                           │ fia bez protetického materiálu                │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly s použitím i │ vv.kod in ['5L502A1']                                        │
│                 │                           │ nterpozitu                                    │                                                              │
│             453 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly [PAI, RUDI,  │ vv.kod in ['5L502A0']                                        │
│                 │                           │ DRAL, DRIL, PRAL, .....]                      │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie dočasného A-V shuntu (peroperačný) │ vv.kod in ['5L5029']                                         │
│             453 │ vv.pocet*cena             │ Vytvorenie vonkajšieho A-V shuntu             │ vv.kod in ['5L5028']                                         │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5L50273']                                        │
│                 │                           │ mocou cievnej protézy                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5L50272']                                        │
│                 │                           │ transpozíciou žily                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5L50271']                                        │
│                 │                           │ transpozíciou VFS                             │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5L50270']                                        │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na hornej končatine po │ vv.kod in ['5L5026']                                         │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou allogénnej cie │ vv.kod in ['5L50251']                                        │
│                 │                           │ vy                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou autológnej cie │ vv.kod in ['5L50250']                                        │
│                 │                           │ vy                                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5L50240']                                        │
│                 │                           │ ilica na predlaktí                            │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly (sec │ vv.kod in ['5L50230']                                        │
│                 │                           │ . Gracz sec. Konner)                          │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na predlaktí HK (R-C,  │ vv.kod in ['5L5022']                                         │
│                 │                           │ R-B, U-C, U-B)                                │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (fossa │ vv.kod in ['5L50211']                                        │
│                 │                           │ tabatiere- snuff box)                         │                                                              │
│             453 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (Cimin │ vv.kod in ['5L50210']                                        │
│                 │                           │ o - Brescia)                                  │                                                              │
│             266 │ vv.pocet*cena             │ Rigídna rektoskopia                           │ vv.kod in ['14N2122']                                        │
│             266 │ vv.pocet*cena             │ Flexibilná rektoskopia                        │ vv.kod in ['14N2121']                                        │
│             266 │ vv.pocet*cena             │ Proktoskopia                                  │ vv.kod in ['14N2120']                                        │
│             266 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14N211X']                                        │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická rektoskopia, stómický prístup    │ vv.kod in ['14N2114']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická proktoskopia, stómický prístup   │ vv.kod in ['14N2113']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická sigmoideoskopia, stómický prístu │ vv.kod in ['14N2112']                                        │
│                 │                           │ p                                             │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická kolonoskopia, stómický prístup   │ vv.kod in ['14N2111']                                        │
│             266 │ vv.pocet*cena             │ Diagnostická ileoskopia, stómický prístup     │ vv.kod in ['14N2110']                                        │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T130']                                         │
│                 │                           │ tkanív v oblasti krku                         │                                                              │
│             266 │ vv.pocet*cena             │ Ostatné diagnostické endoskopie dolnej časti  │ vv.kod in ['14N210X']                                        │
│                 │                           │ tráviaceho systému, okrem stómického prístupu │                                                              │
│             266 │ vv.pocet*cena             │ Chromoendoskopia hrubého čreva                │ vv.kod in ['14N2104']                                        │
│             266 │ vv.pocet*cena             │ Sigmoideoskopia (okrem stómického prístupu)   │ vv.kod in ['14N2103']                                        │
│             266 │ vv.pocet*cena             │ Totálna kolonoskopia s ileoskopiou            │ vv.kod in ['14N2102']                                        │
│             266 │ vv.pocet*cena             │ Totálna kolonoskopia bez ileoskopie           │ vv.kod in ['14N2101']                                        │
│             266 │ vv.pocet*cena             │ Parciálna kolonoskopia                        │ vv.kod in ['14N2100']                                        │
│             266 │ vv.pocet*cena             │ Chromoendoskopia hornej časti tráviaceho syst │ vv.kod in ['14N132']                                         │
│                 │                           │ ému                                           │                                                              │
│             266 │ vv.pocet*cena             │ Diagnostická endoskopia ostatnej hornej časti │ vv.kod in ['14N12X']                                         │
│                 │                           │ tráviaceho systému, stómický prístup          │                                                              │
│             266 │ vv.pocet*cena             │ Jejunoskopia stómický prístup                 │ vv.kod in ['14N125']                                         │
│             266 │ vv.pocet*cena             │ Ezofagoskopia stómický prístup                │ vv.kod in ['14N121']                                         │
│             266 │ vv.pocet*cena             │ Intestinoskopia, ostatné                      │ vv.kod in ['14N114X']                                        │
│             266 │ vv.pocet*cena             │ Intestinoskopia "push-pull-back" technikou    │ vv.kod in ['14N1141']                                        │
│             266 │ vv.pocet*cena             │ Intestinoskopia "push" technikou              │ vv.kod in ['14N1140']                                        │
│             266 │ vv.pocet*cena             │ Ezofagoskopia, iná                            │ vv.kod in ['14N110X']                                        │
│             266 │ vv.pocet*cena             │ Flexibilná ezofagoskopia                      │ vv.kod in ['14N1102']                                        │
│             266 │ vv.pocet*cena             │ Rigídna ezofagoskopia                         │ vv.kod in ['14N1101']                                        │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12M216']                                         │
│                 │                           │ n panvy s použitím zobrazovacích metód        │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia iliakálnych lymfa │ vv.kod in ['12M215']                                         │
│                 │                           │ tických uzlín s použitím zobrazovacích metód  │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia paraaortálnych ly │ vv.kod in ['12M214']                                         │
│                 │                           │ mfatických uzlín s použitím zobrazovacích met │                                                              │
│                 │                           │ ód                                            │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia mediastinálnych l │ vv.kod in ['12M213']                                         │
│                 │                           │ ymfatických uzlín s použitím zobrazovacích me │                                                              │
│                 │                           │ tód                                           │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia axilárnych lymfat │ vv.kod in ['12M212']                                         │
│                 │                           │ ických uzlín s použitím zobrazovacích metód   │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia supraklavikulárny │ vv.kod in ['12M211']                                         │
│                 │                           │ ch lymfatických uzlín (Virchow uzlina) s použ │                                                              │
│                 │                           │ itím zobrazovacích metód                      │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12M210']                                         │
│                 │                           │ n krku s použitím zobrazovacích metód         │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia inguinálnych lymf │ vv.kod in ['12M117']                                         │
│                 │                           │ atických uzlín                                │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12M116']                                         │
│                 │                           │ n panvy                                       │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia iliakálnych lymfa │ vv.kod in ['12M115']                                         │
│                 │                           │ tických uzlín                                 │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia paraaortálnych ly │ vv.kod in ['12M114']                                         │
│                 │                           │ mfatických uzlín                              │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia mediastinálnych l │ vv.kod in ['12M113']                                         │
│                 │                           │ ymfatických uzlín                             │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia axilárnych lymfat │ vv.kod in ['12M112']                                         │
│                 │                           │ ických uzlín                                  │                                                              │
│             220 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia lymfatických uzlí │ vv.kod in ['12M110']                                         │
│                 │                           │ n krku                                        │                                                              │
│              71 │ vv.pocet*cena             │ Biopsia bez incízie kože a podkožia, ostatné  │ vv.kod in ['12V00X']                                         │
│              71 │ vv.pocet*cena             │ Perkutánna biopsia svalov a mäkkých tkanív s  │ vv.kod in ['12T23X']                                         │
│                 │                           │ použitím zobrazovacích metód, ostatné         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T13X']                                         │
│                 │                           │ tkanív, ostatné                               │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T137']                                         │
│                 │                           │ tkanív v oblasti nohy                         │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T136']                                         │
│                 │                           │ tkanív oblasti predkolenia                    │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T135']                                         │
│                 │                           │ tkanív v oblasti stehna                       │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T134']                                         │
│                 │                           │ tkanív v oblasti trupu                        │                                                              │
│              71 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12T133']                                         │
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

