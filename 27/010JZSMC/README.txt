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
│             445 │ vv.pocet*cena             │ Diagnostická laparoskopia                     │ vv.kod in ['14v11']                                          │
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             494 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             494 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5l1930']                                         │
│             494 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5l1931']                                         │
│             494 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5l1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             494 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5l194x']                                         │
│             902 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             902 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['5l1957']                                         │
│             119 │ vv.pocet*cena             │ Exstirpácia lymfatickej uzliny                │ vv.kod in ['5m100']                                          │
│             617 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             617 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5n3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             617 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5n361x']                                         │
│             433 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5n451x']                                         │
│             433 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5n459']                                          │
│             462 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5n45c']                                          │
│             462 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             462 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             462 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             462 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5n45x']                                          │
│             686 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperit                                    │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8171']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparosko │                                                              │
│                 │                           │ picky tran                                    │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totáln                                    │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s au │ vv.kod in ['5n832']                                          │
│                 │                           │ tológnym materiálom                           │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n833x']                                         │
│                 │                           │ oplastickým materiálom, ostatné               │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8431']                                         │
│                 │                           │ loplastickým materiálom, laparoskopicky trans │                                                              │
│                 │                           │ peritoneál                                    │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n843x']                                         │
│                 │                           │ loplastickým materiálom, ostatné              │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s alogénn │ vv.kod in ['5n853']                                          │
│                 │                           │ ym materiálom                                 │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5n8541']                                         │
│                 │                           │ tickým materiálom, laparoskopicky transperito │                                                              │
│                 │                           │ neálne                                        │                                                              │
│             591 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5n854x']                                         │
│                 │                           │ tickým materiálom, ostatné                    │                                                              │
│             397 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n891']                                          │
│                 │                           │ rží] s plastikou                              │                                                              │
│             536 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8931']                                         │
│                 │                           │ rží] s aloplastickým materiálom, laparoskopic │                                                              │
│                 │                           │ ky transpe                                    │                                                              │
│             323 │ vv.pocet*cena             │ Odstránenie stentu z močovodu, retrográdne    │ vv.kod in ['5o247r']                                         │
│             216 │ vv.pocet*cena             │ Divulzia močovej rúry                         │ vv.kod in ['5o499']                                          │
│             384 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie, inguinálna  │ vv.kod in ['5p3010']                                         │
│                 │                           │ retencia semenníka                            │                                                              │
│             384 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie skrotálne    │ vv.kod in ['5p3012']                                         │
│             384 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p3020']                                         │
│                 │                           │ etencia semenníka                             │                                                              │
│             384 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou skrotálne     │ vv.kod in ['5p3022']                                         │
│             384 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p304']                                          │
│                 │                           │ etencia semenníka                             │                                                              │
│             384 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3050']                                         │
│                 │                           │ níka, inguinálne                              │                                                              │
│             384 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3052']                                         │
│                 │                           │ níka, skrotálne                               │                                                              │
│             412 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4020']                                         │
│                 │                           │ epny, inguinálne                              │                                                              │
│             405 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['5p403']                                          │
│             405 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['5p404']                                          │
│             400 │ vv.pocet*cena             │ Excízia cysty v oblasti nadsemenníka          │ vv.kod in ['5p411']                                          │
│             400 │ vv.pocet*cena             │ Excízia spermatokély v oblasti nadsemenníka   │ vv.kod in ['5p412']                                          │
│             400 │ vv.pocet*cena             │ Excízia spermatokély v oblasti nadsemenníka   │ vv.kod in ['5p412']                                          │
│             269 │ vv.pocet*cena             │ Frenulotómia predkožky                        │ vv.kod in ['5p501']                                          │
│             319 │ vv.pocet*cena             │ Dorzálne preťatie predkožky                   │ vv.kod in ['5p502']                                          │
│             319 │ vv.pocet*cena             │ Cirkumcízia                                   │ vv.kod in ['5p503']                                          │
│             269 │ vv.pocet*cena             │ Frenuloplastika a plastika predkožky          │ vv.kod in ['5p504']                                          │
│             280 │ vv.pocet*cena             │ Lokálna excízia chorého tkaniva penisu        │ vv.kod in ['5p511']                                          │
│             280 │ vv.pocet*cena             │ Lokálna deštrukcia chorého tkaniva penisu     │ vv.kod in ['5p512']                                          │
│             280 │ vv.pocet*cena             │ Lokálna excízia a deštrukcia chorého tkaniva  │ vv.kod in ['5p51x']                                          │
│                 │                           │ penisu, ostatné                               │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│            1038 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│            1038 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│             366 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│             366 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5t7022']                                         │
│             366 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             366 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5t7028']                                         │
│             405 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             405 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             405 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             405 │ vv.pocet*cena             │ Parciálna excízia retinaculum flexorum        │ vv.kod in ['5t7121']                                         │
│              70 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             354 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             158 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143c']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             116 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             415 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             415 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5v193']                                          │
│                 │                           │ né                                            │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['Kl1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['Kl1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['Kl1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['Kl1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             612 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['Kl194x']                                         │
│             411 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['Kp403']                                          │
│             411 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['Kp404']                                          │
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

