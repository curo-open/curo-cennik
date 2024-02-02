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
│              66 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia supraklavikulárny │ vv.kod in ['12m111']                                         │
│                 │                           │ ch lymfatických uzlín (Virchow uzlina)        │                                                              │
│             183 │ vv.pocet*cena             │ Perkutánna biopsia prostaty s použitím zobraz │ vv.kod in ['12o201']                                         │
│                 │                           │ ovacích metód                                 │                                                              │
│              72 │ vv.pocet*cena             │ Perkutánna biopsia penisu s použitím zobrazov │ vv.kod in ['12o203']                                         │
│                 │                           │ acích metód                                   │                                                              │
│              72 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia penisu            │ vv.kod in ['12p103']                                         │
│             137 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia svalov a mäkkých  │ vv.kod in ['12t130']                                         │
│                 │                           │ tkanív v oblasti krku                         │                                                              │
│              72 │ vv.pocet*cena             │ Biopsia s incíziou glans penis                │ vv.kod in ['13p010']                                         │
│             270 │ vv.pocet*cena             │ Ureterorenoskopia                             │ vv.kod in ['14o301']                                         │
│             159 │ vv.pocet*cena             │ Cystoskopia                                   │ vv.kod in ['14o302']                                         │
│             420 │ vv.pocet*cena             │ Diagnostická laparoskopia                     │ vv.kod in ['14v11']                                          │
│             270 │ vv.pocet*cena             │ Denervácia periférneho nervu                  │ vv.kod in ['5a4001']                                         │
│             292 │ vv.pocet*cena             │ Rekonštrukcia periférneho nervu nervovým štep │ vv.kod in ['5a4004']                                         │
│                 │                           │ om                                            │                                                              │
│             337 │ vv.pocet*cena             │ Transkutánna neurolýza nervov a nervových gan │ vv.kod in ['5a40g']                                          │
│                 │                           │ glií                                          │                                                              │
│             270 │ vv.pocet*cena             │ Dekompresia, deliberácia a uvoľnenie zrastov  │ vv.kod in ['5a50g']                                          │
│                 │                           │ periférneho nervu                             │                                                              │
│             256 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s dek │ vv.kod in ['5a50h63']                                        │
│                 │                           │ ompresiou nervu                               │                                                              │
│             337 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s dek │ vv.kod in ['5a50h63']                                        │
│                 │                           │ ompresiou nervu                               │                                                              │
│             222 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s tra │ vv.kod in ['5a50h64']                                        │
│                 │                           │ nspozíciou nervu                              │                                                              │
│             337 │ vv.pocet*cena             │ Operácia pre syndróm kubitálneho tunela s tra │ vv.kod in ['5a50h64']                                        │
│                 │                           │ nspozíciou nervu                              │                                                              │
│             270 │ vv.pocet*cena             │ Operácia pre úžinový syndróm na dolnej končat │ vv.kod in ['5a50h9']                                         │
│                 │                           │ ine                                           │                                                              │
│             270 │ vv.pocet*cena             │ Operácia pre poúrazové stavy periférneho nerv │ vv.kod in ['5a50ha']                                         │
│                 │                           │ u na dolnej končatine                         │                                                              │
│             270 │ vv.pocet*cena             │ Operácia pre pozápalové stavy periférneho ner │ vv.kod in ['5a50hb']                                         │
│                 │                           │ vu na dolnej končatine                        │                                                              │
│          248.88 │ vv.pocet*cena             │ Korekčné operácie entropia a extropia termoko │ vv.kod in ['5c230']                                          │
│                 │                           │ aguláciou                                     │                                                              │
│             407 │ vv.pocet*cena             │ Fixácia závaží na očnom viečku                │ vv.kod in ['5c290']                                          │
│             374 │ vv.pocet*cena             │ Korekcia nosového krídla excíziou kože        │ vv.kod in ['5f1191']                                         │
│             407 │ vv.pocet*cena             │ Korekcia poklesnutého a deformovaného nosovéh │ vv.kod in ['5f11b0']                                         │
│                 │                           │ o krídla pomocou kostného štepu               │                                                              │
│             354 │ vv.pocet*cena             │ Korekcia nosovej chlopne                      │ vv.kod in ['5f11e']                                          │
│          361.08 │ vv.pocet*cena             │ Septorinoplastika                             │ vv.kod in ['5f200']                                          │
│          295.61 │ vv.pocet*cena             │ Resekcia hrany alebo tŕňa nosového septa endo │ vv.kod in ['5f203']                                          │
│                 │                           │ skopicky                                      │                                                              │
│             354 │ vv.pocet*cena             │ Uzáver perforácie nosového septa implantátom  │ vv.kod in ['5f2071']                                         │
│             437 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['5l1901']                                         │
│             437 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['5l1902']                                         │
│             437 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['5l1903']                                         │
│             437 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             437 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             437 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['5l1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             437 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             437 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             437 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             437 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5l1930']                                         │
│             437 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5l1931']                                         │
│             437 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5l1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             437 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             437 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             437 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             437 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             437 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5l194x']                                         │
│             902 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             437 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['5l1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             798 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['5l1957']                                         │
│             380 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (Cimin │ vv.kod in ['5l50210']                                        │
│                 │                           │ o - Brescia)                                  │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie radiocefalickej A-V fistuly (fossa │ vv.kod in ['5l50211']                                        │
│                 │                           │ tabatiere- snuff box)                         │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na predlaktí HK (R-C,  │ vv.kod in ['5l5022']                                         │
│                 │                           │ R-B, U-C, U-B)                                │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly (sec │ vv.kod in ['5l50230']                                        │
│                 │                           │ . Gracz sec. Konner)                          │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5l50231']                                        │
│                 │                           │ . basilica                                    │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie brachiokubitálnej A-V fistuly na v │ vv.kod in ['5l50232']                                        │
│                 │                           │ . cephalica                                   │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5l50240']                                        │
│                 │                           │ ilica na predlaktí                            │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly s transpozíciou v. bas │ vv.kod in ['5l50241']                                        │
│                 │                           │ ilica na axile                                │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou autológnej cie │ vv.kod in ['5l50250']                                        │
│                 │                           │ vy                                            │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly pomocou allogénnej cie │ vv.kod in ['5l50251']                                        │
│                 │                           │ vy                                            │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na hornej končatine po │ vv.kod in ['5l5026']                                         │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5l50270']                                        │
│                 │                           │ mocou protetického materiálu                  │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5l50271']                                        │
│                 │                           │ transpozíciou VFS                             │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine s  │ vv.kod in ['5l50272']                                        │
│                 │                           │ transpozíciou žily                            │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie A-V fistuly na dolnej končatine po │ vv.kod in ['5l50273']                                        │
│                 │                           │ mocou cievnej protézy                         │                                                              │
│             380 │ vv.pocet*cena             │ Vytvorenie vonkajšieho A-V shuntu             │ vv.kod in ['5l5028']                                         │
│             380 │ vv.pocet*cena             │ Vytvorenie dočasného A-V shuntu (peroperačný) │ vv.kod in ['5l5029']                                         │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly [PAI, RUDI,  │ vv.kod in ['5l502a0']                                        │
│                 │                           │ DRAL, DRIL, PRAL, .....]                      │                                                              │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly s použitím i │ vv.kod in ['5l502a1']                                        │
│                 │                           │ nterpozitu                                    │                                                              │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5l502a2']                                        │
│                 │                           │ fia bez protetického materiálu                │                                                              │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, aneuryzmora │ vv.kod in ['5l502a3']                                        │
│                 │                           │ fia s protetickým materiálom                  │                                                              │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, banding     │ vv.kod in ['5l502a4']                                        │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia A-V fistuly, ligatúra ve │ vv.kod in ['5l502a5']                                        │
│                 │                           │ tiev                                          │                                                              │
│             380 │ vv.pocet*cena             │ Cievna rekonštrukcia arterio-venóznej fistuly │ vv.kod in ['5l502ax']                                        │
│                 │                           │ , ostatné                                     │                                                              │
│             380 │ vv.pocet*cena             │ Trombektómia A-V fistuly                      │ vv.kod in ['5l502b']                                         │
│             206 │ vv.pocet*cena             │ Zrušenie A-V fistuly bez rekonštrukcie tepny  │ vv.kod in ['5l502c0']                                        │
│             206 │ vv.pocet*cena             │ Zrušenie A-V fistuly bez rekonštrukcie tepny  │ vv.kod in ['5l502c0']                                        │
│             380 │ vv.pocet*cena             │ Vytvorenie arterio-venóznej fistuly, ostatné  │ vv.kod in ['5l502x']                                         │
│             264 │ vv.pocet*cena             │ Exstirpácia lymfangiómu                       │ vv.kod in ['5m103']                                          │
│             264 │ vv.pocet*cena             │ Exstirpácia viacerých lymfatických uzlín z to │ vv.kod in ['5m130']                                          │
│                 │                           │ ho istého miesta                              │                                                              │
│             480 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n2221']                                         │
│                 │                           │ hrubého čreva, polypektómia 1-2 polypov pomoc │                                                              │
│                 │                           │ ou slučky                                     │                                                              │
│             546 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             546 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5n3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             546 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5n361x']                                         │
│             269 │ vv.pocet*cena             │ Incízia chorého tkaniva análneho kanála/tkani │ vv.kod in ['5n440']                                          │
│                 │                           │ va perianálnej oblasti                        │                                                              │
│             383 │ vv.pocet*cena             │ Incízia análnej fistuly                       │ vv.kod in ['5n450']                                          │
│             383 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             383 │ vv.pocet*cena             │ Intersfinkterická excízia análnej fistuly     │ vv.kod in ['5n4511']                                         │
│             383 │ vv.pocet*cena             │ Transsfinkterická excízia análnej fistuly     │ vv.kod in ['5n4512']                                         │
│             383 │ vv.pocet*cena             │ Suprasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4513']                                         │
│             383 │ vv.pocet*cena             │ Extrasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4514']                                         │
│             383 │ vv.pocet*cena             │ Submukózna excízia análnej fistuly            │ vv.kod in ['5n4515']                                         │
│             383 │ vv.pocet*cena             │ Subanodermálna excízia análnej fistuly        │ vv.kod in ['5n4516']                                         │
│             383 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5n451x']                                         │
│             383 │ vv.pocet*cena             │ Závitová drenáž análnej fistuly               │ vv.kod in ['5n452']                                          │
│             383 │ vv.pocet*cena             │ Uzavretie análnej fistuly pomocou plugovej te │ vv.kod in ['5n453']                                          │
│                 │                           │ chniky                                        │                                                              │
│             383 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5n459']                                          │
│              96 │ vv.pocet*cena             │ Ligatúra hemoroidov                           │ vv.kod in ['5n45a']                                          │
│             409 │ vv.pocet*cena             │ Sklerotizácia hemoroidov                      │ vv.kod in ['5n45b']                                          │
│             409 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5n45c']                                          │
│             409 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             409 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             409 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             409 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5n45x']                                          │
│             607 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             351 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou                                     │                                                              │
│             351 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['5n8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou                                     │                                                              │
│             523 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             523 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             474 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             286 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['5o243r1']                                        │
│                 │                           │ u, transuretrálne retrográdne                 │                                                              │
│             286 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['5o243r2']                                        │
│                 │                           │ transuretrálne retrográdne                    │                                                              │
│             286 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['5o246r1']                                        │
│                 │                           │ u, perkutánne - transrenálne retrográdne      │                                                              │
│             286 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['5o246r2']                                        │
│                 │                           │ perkutánne-transrenálne retrográdne           │                                                              │
│             286 │ vv.pocet*cena             │ Odstránenie stentu z močovodu, retrográdne    │ vv.kod in ['5o247r']                                         │
│             343 │ vv.pocet*cena             │ Ureterotómia a odstránenie konkrementu pre ur │ vv.kod in ['5o2566']                                         │
│                 │                           │ eterolitiázu [litotripsia], ureterorenoskopic │                                                              │
│                 │                           │ ky                                            │                                                              │
│             286 │ vv.pocet*cena             │ Implantácia double pigtailu do močových ciest │ vv.kod in ['5o29a']                                          │
│             286 │ vv.pocet*cena             │ Implantácia stentu do močových ciest          │ vv.kod in ['5o29b']                                          │
│             224 │ vv.pocet*cena             │ Optická uretrotómia                           │ vv.kod in ['5o4111']                                         │
│             181 │ vv.pocet*cena             │ Excízia karunkuly chorého tkaniva močovej rúr │ vv.kod in ['5o421']                                          │
│                 │                           │ y                                             │                                                              │
│          225.68 │ vv.pocet*cena             │ Plastická meatotómia močovej rúry, meatoplast │ vv.kod in ['5o441']                                          │
│                 │                           │ ika                                           │                                                              │
│             110 │ vv.pocet*cena             │ Balóniková dilatácia striktúry močovej rúry   │ vv.kod in ['5o450']                                          │
│             191 │ vv.pocet*cena             │ Divulzia močovej rúry                         │ vv.kod in ['5o499']                                          │
│             377 │ vv.pocet*cena             │ Transvaginálna závesná operácia s použitím al │ vv.kod in ['5o9321']                                         │
│                 │                           │ oplastického materiálu bezťahová vaginálna pá │                                                              │
│                 │                           │ ska [TVT]                                     │                                                              │
│             340 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie, inguinálna  │ vv.kod in ['5p3010']                                         │
│                 │                           │ retencia semenníka                            │                                                              │
│             315 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie, inguinálna  │ vv.kod in ['5p3010']                                         │
│                 │                           │ retencia semenníka                            │                                                              │
│             340 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie skrotálne    │ vv.kod in ['5p3012']                                         │
│             286 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie skrotálne    │ vv.kod in ['5p3012']                                         │
│             248 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p3020']                                         │
│                 │                           │ etencia semenníka                             │                                                              │
│             340 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p3020']                                         │
│                 │                           │ etencia semenníka                             │                                                              │
│             340 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou skrotálne     │ vv.kod in ['5p3022']                                         │
│             320 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou skrotálne     │ vv.kod in ['5p3022']                                         │
│             340 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p304']                                          │
│                 │                           │ etencia semenníka                             │                                                              │
│             344 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p304']                                          │
│                 │                           │ etencia semenníka                             │                                                              │
│             340 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3050']                                         │
│                 │                           │ níka, inguinálne                              │                                                              │
│             120 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3050']                                         │
│                 │                           │ níka, inguinálne                              │                                                              │
│             340 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3052']                                         │
│                 │                           │ níka, skrotálne                               │                                                              │
│              83 │ vv.pocet*cena             │ Sutúra semenníka po poranení                  │ vv.kod in ['5p351']                                          │
│             365 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4020']                                         │
│                 │                           │ epny, inguinálne                              │                                                              │
│             365 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4021']                                         │
│                 │                           │ epny, otvorene mikrochirurgicky               │                                                              │
│             365 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4023']                                         │
│                 │                           │ epny, lumbálne                                │                                                              │
│             365 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4024']                                         │
│                 │                           │ epny, laparoskopicky                          │                                                              │
│             365 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['5p403']                                          │
│             317 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['5p404']                                          │
│             354 │ vv.pocet*cena             │ Excízia spermatokély v oblasti nadsemenníka   │ vv.kod in ['5p412']                                          │
│             354 │ vv.pocet*cena             │ Excízia spermatokély v oblasti nadsemenníka   │ vv.kod in ['5p412']                                          │
│             238 │ vv.pocet*cena             │ Frenulotómia predkožky                        │ vv.kod in ['5p501']                                          │
│             282 │ vv.pocet*cena             │ Dorzálne preťatie predkožky                   │ vv.kod in ['5p502']                                          │
│             282 │ vv.pocet*cena             │ Cirkumcízia                                   │ vv.kod in ['5p503']                                          │
│             238 │ vv.pocet*cena             │ Frenuloplastika a plastika predkožky          │ vv.kod in ['5p504']                                          │
│             191 │ vv.pocet*cena             │ Krvavá repozícia na predkožke pre parafimózu  │ vv.kod in ['5p5051']                                         │
│                 │                           │ v celkovej anestézii                          │                                                              │
│             248 │ vv.pocet*cena             │ Lokálna excízia chorého tkaniva penisu        │ vv.kod in ['5p511']                                          │
│             248 │ vv.pocet*cena             │ Lokálna deštrukcia chorého tkaniva penisu     │ vv.kod in ['5p512']                                          │
│             248 │ vv.pocet*cena             │ Lokálna excízia a deštrukcia chorého tkaniva  │ vv.kod in ['5p51x']                                          │
│                 │                           │ penisu, ostatné                               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia klaviku │ vv.kod in ['5t0710']                                         │
│                 │                           │ ly                                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0711']                                         │
│                 │                           │ lneho humeru                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0712']                                         │
│                 │                           │ rneho humeru                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0713']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0714']                                         │
│                 │                           │ lneho radia                                   │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0715']                                         │
│                 │                           │ rneho radia                                   │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0716']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t0717']                                         │
│                 │                           │ lnej ulny                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t0718']                                         │
│                 │                           │ rnej ulny                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t0719']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia karpáln │ vv.kod in ['5t071a']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metakar │ vv.kod in ['5t071b']                                         │
│                 │                           │ pálnych kostí                                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071c']                                         │
│                 │                           │ v prstov ruky                                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia panvy   │ vv.kod in ['5t071d']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia krčka s │ vv.kod in ['5t071e']                                         │
│                 │                           │ tehennej kosti                                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071f']                                         │
│                 │                           │ lneho femuru                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071g']                                         │
│                 │                           │ rneho femuru                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071h']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia pately  │ vv.kod in ['5t071j']                                         │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071k']                                         │
│                 │                           │ lnej tibie                                    │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071m']                                         │
│                 │                           │ rnej tibie                                    │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071n']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia proximá │ vv.kod in ['5t071p']                                         │
│                 │                           │ lnej fibuly                                   │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia diafyzá │ vv.kod in ['5t071q']                                         │
│                 │                           │ rnej fibuly                                   │                                                              │
│             250 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia distáln │ vv.kod in ['5t071r']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia talu    │ vv.kod in ['5t071s']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia kalkane │ vv.kod in ['5t071t']                                         │
│                 │                           │ a                                             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia tarzáln │ vv.kod in ['5t071u']                                         │
│                 │                           │ ych kostí                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia metatar │ vv.kod in ['5t071v']                                         │
│                 │                           │ zálnych kostí                                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia falango │ vv.kod in ['5t071w']                                         │
│                 │                           │ v prstov nohy                                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia ostatný │ vv.kod in ['5t071x']                                         │
│                 │                           │ ch kostí                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skrutky, prípadne revízia skapuly │ vv.kod in ['5t071z']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia klavikuly │ vv.kod in ['5t0720']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0721']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0722']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0723']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0724']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0725']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t0726']                                         │
│                 │                           │ o radia                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t0727']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t0728']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t0729']                                         │
│                 │                           │ ulny                                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia karpálnyc │ vv.kod in ['5t072a']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metakarpá │ vv.kod in ['5t072b']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia panvy     │ vv.kod in ['5t072d']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia krčka ste │ vv.kod in ['5t072e']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072f']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072g']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálneh │ vv.kod in ['5t072h']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia pately    │ vv.kod in ['5t072j']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072k']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072m']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072n']                                         │
│                 │                           │ tibie                                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia proximáln │ vv.kod in ['5t072p']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia diafyzárn │ vv.kod in ['5t072q']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia distálnej │ vv.kod in ['5t072r']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia talu      │ vv.kod in ['5t072s']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia kalkanea  │ vv.kod in ['5t072t']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia tarzálnyc │ vv.kod in ['5t072u']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia metatarzá │ vv.kod in ['5t072v']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia falangov  │ vv.kod in ['5t072w']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia ostatných │ vv.kod in ['5t072x']                                         │
│                 │                           │ kostí                                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie drôtu, prípadne revízia skapuly   │ vv.kod in ['5t072z']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia klavikuly │ vv.kod in ['5t0730']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia distálneh │ vv.kod in ['5t0736']                                         │
│                 │                           │ o radia                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia falangov  │ vv.kod in ['5t073c']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dlahy, prípadne revízia panvy     │ vv.kod in ['5t073d']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0740']                                         │
│                 │                           │ a klavikuly                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0741']                                         │
│                 │                           │ a proximálneho humeru                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0742']                                         │
│                 │                           │ a diafyzárneho humeru                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0743']                                         │
│                 │                           │ a distálneho humeru                           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0744']                                         │
│                 │                           │ a proximálneho radia                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0745']                                         │
│                 │                           │ a diafyzárneho radia                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0746']                                         │
│                 │                           │ a distálneho radia                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0747']                                         │
│                 │                           │ a proximálnej ulny                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0748']                                         │
│                 │                           │ a diafyzárnej ulny                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t0749']                                         │
│                 │                           │ a distálnej ulny                              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074a']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074b']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074c']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074d']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074e']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074f']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074g']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074h']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074j']                                         │
│                 │                           │ a pately                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074k']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074m']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074n']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074p']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074r']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074s']                                         │
│                 │                           │ a talu                                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074t']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074u']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074v']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074w']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074x']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075a']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075b']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075c']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075d']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075e']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075f']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075g']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075h']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075j']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075s']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075t']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075u']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075v']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075w']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075x']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076e']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076f']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076g']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076h']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076m']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076n']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076r']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077e']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077f']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077k']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077m']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077n']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077r']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ab']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ac']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ae']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07af']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ag']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ah']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aj']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ak']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07am']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07an']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ap']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aq']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ar']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07as']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07at']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07av']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aw']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ax']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07az']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bb']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bc']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07br']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bv']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bw']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5t07d0']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07d9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5t07da']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5t07db']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dc']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5t07dd']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5t07de']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07df']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dg']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07dh']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5t07dj']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dk']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dm']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dn']                                         │
│                 │                           │ tibie                                         │                                                              │
│             277 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dn']                                         │
│                 │                           │ tibie                                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dp']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             251 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dp']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dq']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dr']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             291 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dr']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5t07ds']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5t07dt']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5t07du']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5t07dv']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dw']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             281 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dw']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5t07dx']                                         │
│                 │                           │ kostí                                         │                                                              │
│             281 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5t07dx']                                         │
│                 │                           │ kostí                                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5t07dz']                                         │
│             247 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5t07dz']                                         │
│             297 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5t07e0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             210 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5t07e0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             587 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ta']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tb']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             337 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tb']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tc']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             337 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tc']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tk']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             321 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tk']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tm']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             321 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tm']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tn']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             321 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tn']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tp']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tq']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tr']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ts']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tt']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tu']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tv']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tw']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tx']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tz']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             195 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             210 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07va']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vb']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vk']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vm']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             385 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vm']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vn']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│          401.88 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vn']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vp']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│          360.33 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vp']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vq']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vq']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vr']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vs']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vt']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vu']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vv']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             196 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│          340.26 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xa']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xb']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             197 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xb']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xc']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xe']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xf']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xj']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xk']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xm']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xn']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xp']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xq']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xr']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xs']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xt']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xu']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xv']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xw']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             297 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xx']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             392 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['5t0800']                                         │
│             322 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['5t0800']                                         │
│             392 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['5t080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│             338 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['5t080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│             392 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho                                     │                                                              │
│             270 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho                                     │                                                              │
│             338 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0811']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             338 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0812']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             338 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0813']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             338 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0814']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             392 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['5t08201']                                        │
│             392 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['5t08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             338 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 1 metata │ vv.kod in ['5t08211']                                        │
│                 │                           │ rzálna kosť                                   │                                                              │
│             338 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 2 metata │ vv.kod in ['5t08212']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             338 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 3 metata │ vv.kod in ['5t08213']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             338 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 4 metata │ vv.kod in ['5t08214']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             392 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['5t0822a']                                        │
│             392 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['5t0830']                                         │
│             338 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0831']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             338 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0832']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             338 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0833']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             338 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0834']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             392 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083b']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             383 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083b']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             392 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083c']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             338 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083c']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             392 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083d']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             322 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083d']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             392 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083e']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             338 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083e']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             330 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1045']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza drôtom  │                                                              │
│                 │                           │ alebo ťaho                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1048']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahov                                    │                                                              │
│             330 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a5']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a8']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             438 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1211']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1217']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza skrutk                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza sk │                                                              │
│                 │                           │ rutkou                                        │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             330 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1236']                                         │
│                 │                           │ bnej oblasti distálneho radia , osteosyntéza  │                                                              │
│                 │                           │ štandardno                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t123r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza š │                                                              │
│                 │                           │ tandardnou                                    │                                                              │
│             438 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1241']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a drôtom a                                    │                                                              │
│             330 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1246']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza d │                                                              │
│                 │                           │ rôtom aleb                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1247']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza d │                                                              │
│                 │                           │ rôtom aleb                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1249']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza drô │                                                              │
│                 │                           │ tom alebo                                     │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124j']                                         │
│                 │                           │ bnej oblasti pately, osteosyntéza drôtom aleb │                                                              │
│                 │                           │ o ťahovou                                     │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza dr │                                                              │
│                 │                           │ ôtom alebo                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza transf                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a transfix                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a7']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza i │                                                              │
│                 │                           │ ntramedulá                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a9']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza int │                                                              │
│                 │                           │ ramedulárn                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12af']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a intramed                                    │                                                              │
│             330 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12b6']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza u │                                                              │
│                 │                           │ hlovostabi                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ce']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza uhlovo                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12cf']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a uhlovou/                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ch']                                         │
│                 │                           │ bnej oblasti distálneho femuru, osteosyntéza  │                                                              │
│                 │                           │ uhlovou/ko                                    │                                                              │
│             438 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12x1']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a iným ost                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t140a']                                         │
│                 │                           │ álnych kostí bez osteosyntézy                 │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140b']                                         │
│                 │                           │ karpálnych kostí bez osteosyntézy             │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140c']                                         │
│                 │                           │ ngov prstov ruky bez osteosyntézy             │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t140u']                                         │
│                 │                           │ álnych kosti bez osteosyntézy                 │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140v']                                         │
│                 │                           │ tarzálnych kosti bez osteosyntézy             │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140w']                                         │
│                 │                           │ ngov prstov nohy bez osteosyntézy             │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na o │ vv.kod in ['5t140x']                                         │
│                 │                           │ statných malých kostiach bez osteosyntézy     │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t140z']                                         │
│                 │                           │ uly bez osteosyntézy                          │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1410']                                         │
│                 │                           │ ikuly, osteosyntéza skrutkou                  │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t141a']                                         │
│                 │                           │ álnych kostí, osteosyntéza skrutkou           │                                                              │
│             403 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza skrutkou       │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza skrutkou       │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza skrutkou       │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza skrutkou       │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t141x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza skrutkou     │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1430']                                         │
│                 │                           │ ikuly, osteosyntéza štandardnou dlahou        │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t143v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t143x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza štandardnou  │                                                              │
│                 │                           │ dlahou                                        │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1440']                                         │
│                 │                           │ ikuly, osteosyntéza drôtom a ťahovou serklážo │                                                              │
│                 │                           │ u                                             │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t144a']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             403 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t144u']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t144x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza drôtom a ťah │                                                              │
│                 │                           │ ovou serkl                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na m │ vv.kod in ['5t144z']                                         │
│                 │                           │ alej kosti, osteosyntéza drôtom a ťahovou ser │                                                              │
│                 │                           │ klážou sk                                     │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14a0']                                         │
│                 │                           │ ikuly, osteosyntéza intramedulárnymi drôtmi a │                                                              │
│                 │                           │ prútmi                                        │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14ax']                                         │
│                 │                           │ tných malých kostí, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtm                                    │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14b0']                                         │
│                 │                           │ ikuly, osteosyntéza uhlovostabilnou dlahou    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t14ba']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bb']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bc']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t14bu']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bv']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bw']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14bx']                                         │
│                 │                           │ tných malých kostí, osteosyntéza uhlovostabil │                                                              │
│                 │                           │ nou dlahou                                    │                                                              │
│             383 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t14bz']                                         │
│                 │                           │ uly, osteosyntéza uhlovostabilnou dlahou      │                                                              │
│             403 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t151b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza skrutkou        │                                                              │
│             403 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t154b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza drôtom a ťahovo │                                                              │
│                 │                           │ u serklážo                                    │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1911']                                         │
│                 │                           │ eho kĺbu, osteosyntéza skrutkou               │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1941']                                         │
│                 │                           │ eho kĺbu, osteosyntéza drôtom alebo ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19b1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza uhlovostabilnou dlahou │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19x1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza iným osteosyntetickým  │                                                              │
│                 │                           │ materiálom                                    │                                                              │
│             460 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19z1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza rezorbovateľným materi │                                                              │
│                 │                           │ álom                                          │                                                              │
│             403 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211x']                                         │
│                 │                           │ ýzy ostatných kostí, osteosyntéza skrutkou    │                                                              │
│             460 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2140']                                         │
│                 │                           │ ýzy klavikuly, osteosyntéza drôtom alebo ťaho │                                                              │
│                 │                           │ vou serklá                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2145']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahov                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2146']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2149']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza drôtom alebo │                                                              │
│                 │                           │ ťahovou s                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214a']                                         │
│                 │                           │ ýzy karpálnych kostí, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou                                    │                                                              │
│             403 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t216f']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza nezaist │                                                              │
│                 │                           │ eným predv                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217e']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza zaist │                                                              │
│                 │                           │ eným intra                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217h']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217k']                                         │
│                 │                           │ ýzy proximálnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217m']                                         │
│                 │                           │ ýzy diafyzárnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217n']                                         │
│                 │                           │ ýzy distálnej tibie, osteosyntéza zaisteným i │                                                              │
│                 │                           │ ntramedulá                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a1']                                         │
│                 │                           │ ýzy proximálneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a2']                                         │
│                 │                           │ ýzy diafyzárneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a3']                                         │
│                 │                           │ ýzy distálneho humeru, osteosyntéza intramedu │                                                              │
│                 │                           │ lárnymi dr                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a6']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtm                                    │                                                              │
│             403 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ab']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ac']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ae']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza intra │                                                              │
│                 │                           │ medulárnym                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ag']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aq']                                         │
│                 │                           │ ýzy diafyzárnej fibuly, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ar']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21av']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aw']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetic                                    │                                                              │
│             330 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetic                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza iným osteosy │                                                              │
│                 │                           │ ntetickým                                     │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xb']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza iným o │                                                              │
│                 │                           │ steosyntet                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xe']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza iným  │                                                              │
│                 │                           │ osteosynte                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xf']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosynteti                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xg']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosynteti                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xh']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza iným oste │                                                              │
│                 │                           │ osyntetick                                    │                                                              │
│             383 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xr']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             302 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5t3044']                                         │
│             302 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5t3044']                                         │
│             383 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5t3044']                                         │
│             302 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5t3054']                                         │
│             302 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5t3054']                                         │
│             338 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5t3054']                                         │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) humeroglenoidáln │ vv.kod in ['5t3060']                                         │
│                 │                           │ eho kĺbu                                      │                                                              │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) lakťového kĺbu   │ vv.kod in ['5t3064']                                         │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) radiokarpálneho  │ vv.kod in ['5t3068']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) kolenného kĺbu   │ vv.kod in ['5t306h']                                         │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) horného členkové │ vv.kod in ['5t306k']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             482 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) metatarzofalange │ vv.kod in ['5t306q']                                         │
│                 │                           │ álnych kĺbov                                  │                                                              │
│             330 │ vv.pocet*cena             │ Odstránenie voľných telies z kolenného kĺbu   │ vv.kod in ['5t308h']                                         │
│          446.08 │ vv.pocet*cena             │ Refixácia labra                               │ vv.kod in ['5t350']                                          │
│             414 │ vv.pocet*cena             │ Refixácia labra                               │ vv.kod in ['5t350']                                          │
│             392 │ vv.pocet*cena             │ Refixácia okrajových kostných lézií oblasti l │ vv.kod in ['5t351']                                          │
│                 │                           │ abrum glenoidale                              │                                                              │
│          446.08 │ vv.pocet*cena             │ Refixácia okrajových kostných lézií oblasti l │ vv.kod in ['5t351']                                          │
│                 │                           │ abrum glenoidale                              │                                                              │
│             443 │ vv.pocet*cena             │ Rekonštrukcia rotátorovej manžety ramenného k │ vv.kod in ['5t357']                                          │
│                 │                           │ ĺbu sutúrou                                   │                                                              │
│             443 │ vv.pocet*cena             │ Rekonštrukcia rotátorovej manžety ramenného k │ vv.kod in ['5t358']                                          │
│                 │                           │ ĺbu transpozíciou šľachy                      │                                                              │
│             443 │ vv.pocet*cena             │ Rekonštrukcia rotátorovej manžety ramenného k │ vv.kod in ['5t359']                                          │
│                 │                           │ ĺbu transplantáciou                           │                                                              │
│             443 │ vv.pocet*cena             │ Rekonštrukcia rotátorovej manžety ramenného k │ vv.kod in ['5t35a']                                          │
│                 │                           │ ĺbu implantátom                               │                                                              │
│             297 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['5t3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             392 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['5t3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             392 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálnych a interfalan │ vv.kod in ['5t38a1']                                         │
│                 │                           │ geálnych kĺbov prsta nohy, 1 kĺb              │                                                              │
│             270 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálnych a interfalan │ vv.kod in ['5t38a1']                                         │
│                 │                           │ geálnych kĺbov prsta nohy, 1 kĺb              │                                                              │
│             367 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['5t38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│             392 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['5t38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5t4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5t4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             897 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5t4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             897 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5t4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5t4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5t4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5t400h']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             919 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5t400h']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             855 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5t400k']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             855 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5t400k']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             302 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5t40x4']                                         │
│             302 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5t40x4']                                         │
│             322 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5t40x4']                                         │
│             302 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5t4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5t4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             460 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5t4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5t4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5t4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             338 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5t4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5t4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5t4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│             460 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5t4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│             302 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5t41x4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             302 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5t41x4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             330 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5t41x4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│            1238 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421h']                                         │
│                 │                           │ gmentu kolenného kĺbu                         │                                                              │
│            1238 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t4220']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│            1238 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5t4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1238 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5t4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│            1215 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5t4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│            1215 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5t4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│            1331 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t422k']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│            1331 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t422k']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická refixácia labrum glenoidale ste │ vv.kod in ['5t440']                                          │
│                 │                           │ hom                                           │                                                              │
│             315 │ vv.pocet*cena             │ Artroskopická refixácia labrum glenoidale ste │ vv.kod in ['5t440']                                          │
│                 │                           │ hom                                           │                                                              │
│             392 │ vv.pocet*cena             │ Artroskopická refixácia labrum glenoidale iný │ vv.kod in ['5t441']                                          │
│                 │                           │ mi metódami                                   │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická refixácia labrum glenoidale iný │ vv.kod in ['5t441']                                          │
│                 │                           │ mi metódami                                   │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická refixácia kostného defektu labr │ vv.kod in ['5t442']                                          │
│                 │                           │ a                                             │                                                              │
│             338 │ vv.pocet*cena             │ Artroskopická refixácia kostného defektu labr │ vv.kod in ['5t442']                                          │
│                 │                           │ a                                             │                                                              │
│             438 │ vv.pocet*cena             │ Artroskopická zväčšenie subakromiálneho pries │ vv.kod in ['5t443']                                          │
│                 │                           │ toru                                          │                                                              │
│             443 │ vv.pocet*cena             │ Artroskopická rekonštrukcia rotátorovej manže │ vv.kod in ['5t4440']                                         │
│                 │                           │ ty, jednoduchá                                │                                                              │
│             443 │ vv.pocet*cena             │ Artroskopická rekonštrukcia rotátorovej manže │ vv.kod in ['5t4441']                                         │
│                 │                           │ ty, zložitá                                   │                                                              │
│             443 │ vv.pocet*cena             │ Artroskopická implantácia vstrebateľnej fyzic │ vv.kod in ['5t4442']                                         │
│                 │                           │ kej bariéry pri syndróme rotátorovej manžety  │                                                              │
│             443 │ vv.pocet*cena             │ Artroskopická rekonštrukcia rotátorovej manže │ vv.kod in ['5t444x']                                         │
│                 │                           │ ty, iná                                       │                                                              │
│             443 │ vv.pocet*cena             │ Artroskopická rekonštrukcia rotátorovej manže │ vv.kod in ['5t446']                                          │
│                 │                           │ ty pomocou transplantátu                      │                                                              │
│             383 │ vv.pocet*cena             │ Artroskopická tenotómia šľachy dlhej hlavy bi │ vv.kod in ['5t447']                                          │
│                 │                           │ cepsu                                         │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická tenotómia šľachy dlhej hlavy bi │ vv.kod in ['5t447']                                          │
│                 │                           │ cepsu                                         │                                                              │
│             338 │ vv.pocet*cena             │ Artroskopická sutúra šľachy dlhej hlavy bicep │ vv.kod in ['5t448']                                          │
│                 │                           │ su                                            │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická sutúra šľachy dlhej hlavy bicep │ vv.kod in ['5t448']                                          │
│                 │                           │ su                                            │                                                              │
│             322 │ vv.pocet*cena             │ Artroskopická tenodéza šľachy dlhej hlavy bic │ vv.kod in ['5t449']                                          │
│                 │                           │ epsu                                          │                                                              │
│          446.08 │ vv.pocet*cena             │ Artroskopická tenodéza šľachy dlhej hlavy bic │ vv.kod in ['5t449']                                          │
│                 │                           │ epsu                                          │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5t4914']                                         │
│                 │                           │ bu                                            │                                                              │
│             302 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5t4914']                                         │
│                 │                           │ bu                                            │                                                              │
│             438 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5t4914']                                         │
│                 │                           │ bu                                            │                                                              │
│             302 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5t49x4']                                         │
│             302 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5t49x4']                                         │
│             438 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5t49x4']                                         │
│             324 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│             324 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5t7022']                                         │
│             324 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             324 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5t7028']                                         │
│             434 │ vv.pocet*cena             │ Primárna sutúra ohýbača prsta                 │ vv.kod in ['5t7051']                                         │
│             434 │ vv.pocet*cena             │ Primárna sutúra vystierača prsta              │ vv.kod in ['5t7054']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza ohýbača prsta                        │ vv.kod in ['5t7071']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza ohýbača palca                        │ vv.kod in ['5t7072']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza vystierača prsta                     │ vv.kod in ['5t7074']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza vystierača palca                     │ vv.kod in ['5t7075']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza šľachových pošiev prsta              │ vv.kod in ['5t7077']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza šľachových pošiev palca              │ vv.kod in ['5t7078']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza šľachových pošiev dlane              │ vv.kod in ['5t7079']                                         │
│             347 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             321 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             347 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             321 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             321 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             321 │ vv.pocet*cena             │ Parciálna excízia retinaculum flexorum        │ vv.kod in ['5t7121']                                         │
│             286 │ vv.pocet*cena             │ Perkutánna fasciotómia jedného prsta          │ vv.kod in ['5t7211']                                         │
│             286 │ vv.pocet*cena             │ Perkutánna fasciotómia viac ako jedného prsta │ vv.kod in ['5t7212']                                         │
│             340 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             340 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             349 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│             349 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│             349 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5t7241']                                         │
│                 │                           │ u                                             │                                                              │
│             349 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5t7242']                                         │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) karpometakarpálneho kĺb │ vv.kod in ['5t7452']                                         │
│                 │                           │ u palca                                       │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálneho  │ vv.kod in ['5t7453']                                         │
│                 │                           │ kĺbu, jeden zákrok                            │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálnych  │ vv.kod in ['5t7454']                                         │
│                 │                           │ kĺbov, viaceré zákroky                        │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálneho kĺbu │ vv.kod in ['5t7455']                                         │
│                 │                           │ ruky, jeden zákrok                            │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7456']                                         │
│                 │                           │ v jedného prsta ruky, viaceré zákroky         │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7457']                                         │
│                 │                           │ v viacerých prstov ruky, viaceré zákroky      │                                                              │
│             327 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) ostatných kĺbov ruky    │ vv.kod in ['5t745x']                                         │
│             327 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t764']                                          │
│                 │                           │ ruky                                          │                                                              │
│             327 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t765']                                          │
│                 │                           │ ruky so spongioplastikou                      │                                                              │
│             327 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t766']                                          │
│                 │                           │ v ruky                                        │                                                              │
│             327 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t767']                                          │
│                 │                           │ v ruky so spongioplastikou                    │                                                              │
│             327 │ vv.pocet*cena             │ Ostatné artrodézy kĺbov ruky                  │ vv.kod in ['5t76x']                                          │
│              62 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5t790']                                          │
│             302 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5t8012']                                         │
│                 │                           │ a                                             │                                                              │
│             302 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5t8012']                                         │
│                 │                           │ a                                             │                                                              │
│             414 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5t8012']                                         │
│                 │                           │ a                                             │                                                              │
│             302 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5t80c2']                                         │
│             302 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5t80c2']                                         │
│          446.08 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5t80c2']                                         │
│             302 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5t80x2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             302 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5t80x2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             443 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5t80x2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             302 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5t8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             302 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5t8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             392 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5t8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             340 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia pr │ vv.kod in ['5t815x']                                         │
│                 │                           │ iečna, ostatné                                │                                                              │
│             340 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia po │ vv.kod in ['5t818x']                                         │
│                 │                           │ zdĺžna, jeden segment, ostatné                │                                                              │
│             286 │ vv.pocet*cena             │ Perkutánna fasciotómia pozdĺžna, ostatné      │ vv.kod in ['5t81ax']                                         │
│             302 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5t8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             302 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5t8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             315 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5t8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             338 │ vv.pocet*cena             │ Excízia fascie v oblasti nohy                 │ vv.kod in ['5t82a9']                                         │
│             302 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5t8402']                                         │
│             302 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5t8402']                                         │
│             392 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5t8402']                                         │
│             299 │ vv.pocet*cena             │ Transpozícia šliach, ostatné                  │ vv.kod in ['5t842x']                                         │
│             330 │ vv.pocet*cena             │ Plastika šliach náhradou, ostatné             │ vv.kod in ['5t844x']                                         │
│             330 │ vv.pocet*cena             │ Plastika šliach náhradou s interponátom, osta │ vv.kod in ['5t845x']                                         │
│                 │                           │ tné                                           │                                                              │
│             195 │ vv.pocet*cena             │ Plastika šliach náhradou s interponátom, osta │ vv.kod in ['5t845x']                                         │
│                 │                           │ tné                                           │                                                              │
│             330 │ vv.pocet*cena             │ Tvorba transplantátu šliach, ostatné          │ vv.kod in ['5t846x']                                         │
│             210 │ vv.pocet*cena             │ Tvorba transplantátu šliach, ostatné          │ vv.kod in ['5t846x']                                         │
│             330 │ vv.pocet*cena             │ Transplantácia šliach, ostatné                │ vv.kod in ['5t847x']                                         │
│             330 │ vv.pocet*cena             │ Výmena transplantátu šliach, ostatné          │ vv.kod in ['5t848x']                                         │
│             449 │ vv.pocet*cena             │ Reinzercia šľachy v oblasti predkolenia       │ vv.kod in ['5t8508']                                         │
│             434 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predlaktia   │ vv.kod in ['5t8513']                                         │
│             434 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti stehna a kol │ vv.kod in ['5t8517']                                         │
│                 │                           │ ena                                           │                                                              │
│             449 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predkolenia  │ vv.kod in ['5t8518']                                         │
│             449 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti nohy         │ vv.kod in ['5t8519']                                         │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti ramena a l │ vv.kod in ['5t8522']                                         │
│                 │                           │ akťa                                          │                                                              │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predlaktia │ vv.kod in ['5t8523']                                         │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti stehna a k │ vv.kod in ['5t8527']                                         │
│                 │                           │ olena                                         │                                                              │
│             449 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predkoleni │ vv.kod in ['5t8528']                                         │
│                 │                           │ a                                             │                                                              │
│             449 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti nohy       │ vv.kod in ['5t8529']                                         │
│             434 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8533']                                         │
│                 │                           │ dlaktia                                       │                                                              │
│             449 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8538']                                         │
│                 │                           │ dkolenia                                      │                                                              │
│             434 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti noh │ vv.kod in ['5t8539']                                         │
│                 │                           │ y                                             │                                                              │
│             434 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy, ostatné      │ vv.kod in ['5t853x']                                         │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8543']                                         │
│                 │                           │ redlaktia                                     │                                                              │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8548']                                         │
│                 │                           │ redkolenia                                    │                                                              │
│             434 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti n │ vv.kod in ['5t8549']                                         │
│                 │                           │ ohy                                           │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti ramena a axi │ vv.kod in ['5t8551']                                         │
│                 │                           │ ly                                            │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti ramena a lak │ vv.kod in ['5t8552']                                         │
│                 │                           │ ťa                                            │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti predlaktia   │ vv.kod in ['5t8553']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti stehna a kol │ vv.kod in ['5t8557']                                         │
│                 │                           │ ena                                           │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti predkolenia  │ vv.kod in ['5t8558']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy v oblasti nohy         │ vv.kod in ['5t8559']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza jednej šľachy, ostatné               │ vv.kod in ['5t855x']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach v oblasti ramena a  │ vv.kod in ['5t8561']                                         │
│                 │                           │ axily                                         │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach v oblasti ramena a  │ vv.kod in ['5t8562']                                         │
│                 │                           │ lakťa                                         │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach v oblasti predlakti │ vv.kod in ['5t8563']                                         │
│                 │                           │ a                                             │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach v oblasti predkolen │ vv.kod in ['5t8568']                                         │
│                 │                           │ ia                                            │                                                              │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach v oblasti nohy      │ vv.kod in ['5t8569']                                         │
│             319 │ vv.pocet*cena             │ Tenolýza viacerých šliach, ostatné            │ vv.kod in ['5t856x']                                         │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a axi │ vv.kod in ['5t8911']                                         │
│                 │                           │ ly                                            │                                                              │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a lak │ vv.kod in ['5t8912']                                         │
│                 │                           │ ťa                                            │                                                              │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predlaktia   │ vv.kod in ['5t8913']                                         │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti stehna a kol │ vv.kod in ['5t8917']                                         │
│                 │                           │ ena                                           │                                                              │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predkolenia  │ vv.kod in ['5t8918']                                         │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti nohy         │ vv.kod in ['5t8919']                                         │
│               0 │ vv.pocet*cena             │ Totálna resekcia burzy, ostatné               │ vv.kod in ['5t891x']                                         │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej o                                    │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              62 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             207 │ vv.pocet*cena             │ Amputácia prsta ruky                          │ vv.kod in ['5t933']                                          │
│             313 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, jedna  │ vv.kod in ['5u1100']                                         │
│                 │                           │ lézia                                         │                                                              │
│             313 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, viacpo │ vv.kod in ['5u1101']                                         │
│                 │                           │ četná lézia                                   │                                                              │
│             313 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             313 │ vv.pocet*cena             │ Lumpektómia                                   │ vv.kod in ['5u112']                                          │
│             313 │ vv.pocet*cena             │ Mikroduktektómia prsníka                      │ vv.kod in ['5u114']                                          │
│             214 │ vv.pocet*cena             │ Otvorenie flegmóny                            │ vv.kod in ['5v110']                                          │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatný                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130a']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130b']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušn                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130d']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v glute                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130e']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130f']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130g']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblas                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130x']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatn                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131a']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131b']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej                                     │                                                              │
│             137 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131c']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v inguinál                                    │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131d']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteál                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131e']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131f']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131g']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti                                     │                                                              │
│             103 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131x']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany os                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, o                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141c']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany hi                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany,                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             103 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             113 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['5v1500']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti p                                     │                                                              │
│           235.2 │ vv.pocet*cena             │ Totálna excízia nechta                        │ vv.kod in ['5v175']                                          │
│             367 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             367 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5v193']                                          │
│                 │                           │ né                                            │                                                              │
│             367 │ vv.pocet*cena             │ Incízia sinus pilonidalis                     │ vv.kod in ['5v194']                                          │
│          274.56 │ vv.pocet*cena             │ Excízia a exstirpácia hemangiómu na koži      │ vv.kod in ['5v482']                                          │
│             248 │ vv.pocet*cena             │ Odstránenie bradavíc alebo porovnateľných kož │ vv.kod in ['8z211']                                          │
│                 │                           │ ných zmien                                    │                                                              │
│          282.22 │ vv.pocet*cena             │ Jednodňová ZS - Operačné odstránenie benígnyc │ vv.kod in ['J0003']                                          │
│                 │                           │ h alebo malígnych útvarov kože a podkožia (pr │                                                              │
│                 │                           │ eaurikulár                                    │                                                              │
│             494 │ vv.pocet*cena             │ Jednodňová ZS - Korekčná osteotómia a osteosy │ vv.kod in ['J0007']                                          │
│                 │                           │ ntéza                                         │                                                              │
│             114 │ vv.pocet*cena             │ Jednodňová ZS - Presadrovanie v celkovej anes │ vv.kod in ['J0009']                                          │
│                 │                           │ tézii u detí                                  │                                                              │
│          300.76 │ vv.pocet*cena             │ Korekčné operácie entropia a extropia termoko │ vv.kod in ['Kc230']                                          │
│                 │                           │ aguláciou                                     │                                                              │
│             406 │ vv.pocet*cena             │ Resekcia tarsu pri blefaroptóze               │ vv.kod in ['Kc240']                                          │
│             372 │ vv.pocet*cena             │ Korekcia nozdier rázštepového nosa            │ vv.kod in ['Kf115']                                          │
│             542 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['Kl1901']                                         │
│             339 │ vv.pocet*cena             │ Implantácia double pigtailu do močových ciest │ vv.kod in ['Ko29a']                                          │
│             488 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['Kp4020']                                         │
│                 │                           │ epny, inguinálne                              │                                                              │
│             403 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['Kp403']                                          │
│             484 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['Kt0800']                                         │
│             214 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1500']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti p                                     │                                                              │
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

