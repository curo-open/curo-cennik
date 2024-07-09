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
│             405 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             405 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             405 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             405 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5l1930']                                         │
│             405 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5l1931']                                         │
│             405 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5l1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             405 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             405 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             405 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             405 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             405 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5l194x']                                         │
│             602 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             602 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5n3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             602 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5n361x']                                         │
│             388 │ vv.pocet*cena             │ Incízia análnej fistuly                       │ vv.kod in ['5n450']                                          │
│             388 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             388 │ vv.pocet*cena             │ Intersfinkterická excízia análnej fistuly     │ vv.kod in ['5n4511']                                         │
│             388 │ vv.pocet*cena             │ Transsfinkterická excízia análnej fistuly     │ vv.kod in ['5n4512']                                         │
│             388 │ vv.pocet*cena             │ Suprasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4513']                                         │
│             388 │ vv.pocet*cena             │ Extrasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4514']                                         │
│             388 │ vv.pocet*cena             │ Submukózna excízia análnej fistuly            │ vv.kod in ['5n4515']                                         │
│             388 │ vv.pocet*cena             │ Subanodermálna excízia análnej fistuly        │ vv.kod in ['5n4516']                                         │
│             388 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5n451x']                                         │
│             388 │ vv.pocet*cena             │ Závitová drenáž análnej fistuly               │ vv.kod in ['5n452']                                          │
│             388 │ vv.pocet*cena             │ Uzavretie análnej fistuly pomocou plugovej te │ vv.kod in ['5n453']                                          │
│                 │                           │ chniky                                        │                                                              │
│             388 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5n459']                                          │
│             486 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5n45c']                                          │
│             486 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             486 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             486 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             486 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5n45x']                                          │
│             623 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperit                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8171']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparosko │                                                              │
│                 │                           │ picky tran                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totáln                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n81x']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] s alop │ vv.kod in ['5n8231']                                         │
│                 │                           │ lastickým materiálom, laparoskopicky transper │                                                              │
│                 │                           │ itoneálne                                     │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] pri re │ vv.kod in ['5n8271']                                         │
│                 │                           │ cidíve s aloplastickým materiálom, laparoskop │                                                              │
│                 │                           │ icky trans                                    │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8331']                                         │
│                 │                           │ oplastickým materiálom, laparoskopicky transp │                                                              │
│                 │                           │ eritoneáln                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n833x']                                         │
│                 │                           │ oplastickým materiálom, ostatné               │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže], ost │ vv.kod in ['5n83x']                                          │
│                 │                           │ atné                                          │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8431']                                         │
│                 │                           │ loplastickým materiálom, laparoskopicky trans │                                                              │
│                 │                           │ peritoneál                                    │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n843x']                                         │
│                 │                           │ loplastickým materiálom, ostatné              │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s plastik │ vv.kod in ['5n851']                                          │
│                 │                           │ ou                                            │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s alogénn │ vv.kod in ['5n853']                                          │
│                 │                           │ ym materiálom                                 │                                                              │
│             620 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5n8541']                                         │
│                 │                           │ tickým materiálom, laparoskopicky transperito │                                                              │
│                 │                           │ neálne                                        │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie hernie [prietrže] v jazve s aloplas │ vv.kod in ['5n854x']                                         │
│                 │                           │ tickým materiálom, ostatné                    │                                                              │
│             400 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n891']                                          │
│                 │                           │ rží] s plastikou                              │                                                              │
│             672 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8930']                                         │
│                 │                           │ rží] aloplastickým materiálom, laparotomicky  │                                                              │
│             602 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8931']                                         │
│                 │                           │ rží] s aloplastickým materiálom, laparoskopic │                                                              │
│                 │                           │ ky transpe                                    │                                                              │
│            1057 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│            1057 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│            1057 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│            1057 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│            1057 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│             413 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│             413 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5t7022']                                         │
│             413 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             413 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5t7028']                                         │
│             406 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             406 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             406 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             448 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│              80 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             346 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             101 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             101 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130g']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             101 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             379 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             379 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5v193']                                          │
│                 │                           │ né                                            │                                                              │
│             749 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
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

