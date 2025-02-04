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
│             418 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             418 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             418 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             418 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             418 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             418 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             418 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             749 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             412 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             412 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             412 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             412 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s plastik │ vv.kod in ['5n851']                                          │
│                 │                           │ ou                                            │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s alogénn │ vv.kod in ['5n853']                                          │
│                 │                           │ ym materiálom                                 │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             693 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             642 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             392 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             391 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             400 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             501 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             501 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             501 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             356 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             620 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│             104 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│            1003 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│            1003 │ vv.pocet*cena             │ Implantácia bipolárnej cervikokapitálnej prot │ vv.kod in ['5t5040']                                         │
│                 │                           │ ézy bedrového kĺbu, necementovaná             │                                                              │
│            1003 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│            1003 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│            1003 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│            1003 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│             385 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             425 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             392 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│             392 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             425 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             460 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│             460 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│             460 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5t7241']                                         │
│                 │                           │ u                                             │                                                              │
│             460 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5t7242']                                         │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8921X']                                        │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89210']                                        │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89211']                                        │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89212']                                        │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89213']                                        │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89214']                                        │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89215']                                        │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89216']                                        │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej oblasti                              │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89217']                                        │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89218']                                        │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T89219']                                        │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              85 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5T8921A']                                        │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
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

