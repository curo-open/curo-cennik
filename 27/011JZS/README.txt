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
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             902 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             612 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['Kl1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             612 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['Kl1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['Kl1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['Kl1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['Kl1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['Kl1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│               0 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['Kl1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s plastik │ vv.kod in ['5n851']                                          │
│                 │                           │ ou                                            │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s alogénn │ vv.kod in ['5n853']                                          │
│                 │                           │ ym materiálom                                 │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             686 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             366 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             415 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             433 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             462 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             462 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             462 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             354 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             617 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│            1038 │ vv.pocet*cena             │ Implantácia bipolárnej cervikokapitálnej prot │ vv.kod in ['5t5040']                                         │
│                 │                           │ ézy bedrového kĺbu, necementovaná             │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│            1038 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│             405 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             384 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             384 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             384 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             394 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│             394 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│             394 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5t7241']                                         │
│                 │                           │ u                                             │                                                              │
│             394 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5t7242']                                         │
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

