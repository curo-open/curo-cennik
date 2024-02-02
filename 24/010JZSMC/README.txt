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
│             203 │ vv.pocet*cena             │ Exstirpácia nádoru hlbokých mäkkých tkanív kr │ vv.kod in ['5b1663']                                         │
│                 │                           │ ku                                            │                                                              │
│             203 │ vv.pocet*cena             │ Exstirpácia povrchového nádoru krku           │ vv.kod in ['5b1664']                                         │
│             203 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5g92101']                                        │
│                 │                           │ stí priamou sutúrou                           │                                                              │
│             203 │ vv.pocet*cena             │ Exstirpácia nádoru na tvári a priľahlých obla │ vv.kod in ['5g92102']                                        │
│                 │                           │ stí miestnou lalokovou plastikou              │                                                              │
│             518 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['5l1901']                                         │
│             518 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['5l1902']                                         │
│             518 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['5l1903']                                         │
│             518 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             518 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['5l19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             518 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['5l1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             518 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             518 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             518 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['5l1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             518 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['5l1930']                                         │
│             518 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['5l1931']                                         │
│             518 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['5l1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             518 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['5l1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             518 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['5l1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             518 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['5l1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             518 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['5l1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             518 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['5l194x']                                         │
│             584 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['5l1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             518 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['5l1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             584 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['5l1957']                                         │
│             203 │ vv.pocet*cena             │ Exstirpácia lymfatickej uzliny                │ vv.kod in ['5m100']                                          │
│             203 │ vv.pocet*cena             │ Exstirpácia supraklavikulárnych lymfatických  │ vv.kod in ['5m101']                                          │
│                 │                           │ uzlín jednostranne                            │                                                              │
│             203 │ vv.pocet*cena             │ Exstirpácia axilárnych lymfatických uzlín jed │ vv.kod in ['5m102']                                          │
│                 │                           │ nostranne                                     │                                                              │
│             871 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou slučky a │ vv.kod in ['5n3610']                                         │
│                 │                           │ lebo ligatúry                                 │                                                              │
│             871 │ vv.pocet*cena             │ Apendektómia, laparoskopicky pomocou clampu ( │ vv.kod in ['5n3611']                                         │
│                 │                           │ stapler)                                      │                                                              │
│             871 │ vv.pocet*cena             │ Apendektómia, laparoskopicky, ostatné         │ vv.kod in ['5n361x']                                         │
│             396 │ vv.pocet*cena             │ Adheziolýza na čreve, laparoskopicky          │ vv.kod in ['5n3922']                                         │
│             199 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4100']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou peranál │                                                              │
│                 │                           │ ne                                            │                                                              │
│             199 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4106']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picky                                         │                                                              │
│             199 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n4107']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou endosko │                                                              │
│                 │                           │ picko-mikr                                    │                                                              │
│             199 │ vv.pocet*cena             │ Peranálna lokálna excízia a deštrukcia choréh │ vv.kod in ['5n410x']                                         │
│                 │                           │ o tkaniva konečníka, resekcia slučkou, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             199 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n4121']                                         │
│                 │                           │ konečníka, polypektómia 1-2 polypov pomocou s │                                                              │
│                 │                           │ lučky                                         │                                                              │
│             199 │ vv.pocet*cena             │ Lokálna endoskopická excízia chorého tkaniva  │ vv.kod in ['5n4122']                                         │
│                 │                           │ konečníka, polypektómia viac ako 2 polypov po │                                                              │
│                 │                           │ mocou sluč                                    │                                                              │
│             220 │ vv.pocet*cena             │ Incízia chorého tkaniva análneho kanála/tkani │ vv.kod in ['5n440']                                          │
│                 │                           │ va perianálnej oblasti                        │                                                              │
│             387 │ vv.pocet*cena             │ Incízia análnej fistuly                       │ vv.kod in ['5n450']                                          │
│             387 │ vv.pocet*cena             │ Subkutánna excízia análnej fistuly            │ vv.kod in ['5n4510']                                         │
│             387 │ vv.pocet*cena             │ Intersfinkterická excízia análnej fistuly     │ vv.kod in ['5n4511']                                         │
│             387 │ vv.pocet*cena             │ Transsfinkterická excízia análnej fistuly     │ vv.kod in ['5n4512']                                         │
│             387 │ vv.pocet*cena             │ Suprasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4513']                                         │
│             387 │ vv.pocet*cena             │ Extrasfinkterická excízia análnej fistuly     │ vv.kod in ['5n4514']                                         │
│             387 │ vv.pocet*cena             │ Submukózna excízia análnej fistuly            │ vv.kod in ['5n4515']                                         │
│             387 │ vv.pocet*cena             │ Subanodermálna excízia análnej fistuly        │ vv.kod in ['5n4516']                                         │
│             387 │ vv.pocet*cena             │ Excízia análnej fistuly, ostatné              │ vv.kod in ['5n451x']                                         │
│             387 │ vv.pocet*cena             │ Závitová drenáž análnej fistuly               │ vv.kod in ['5n452']                                          │
│             387 │ vv.pocet*cena             │ Uzavretie análnej fistuly pomocou plugovej te │ vv.kod in ['5n453']                                          │
│                 │                           │ chniky                                        │                                                              │
│             387 │ vv.pocet*cena             │ Operatívna liečba análnej fistuly, ostatné    │ vv.kod in ['5n459']                                          │
│             441 │ vv.pocet*cena             │ Sklerotizácia hemoroidov                      │ vv.kod in ['5n45b']                                          │
│             441 │ vv.pocet*cena             │ Excízia hemoroidov                            │ vv.kod in ['5n45c']                                          │
│             441 │ vv.pocet*cena             │ Deštrukcia hemoroidov                         │ vv.kod in ['5n45d']                                          │
│             441 │ vv.pocet*cena             │ Operačné ošetrenie hemoroidov so staplerom    │ vv.kod in ['5n45e']                                          │
│             441 │ vv.pocet*cena             │ Excízia hemoroidov s plastickou rekonštrukcio │ vv.kod in ['5n45f']                                          │
│                 │                           │ u                                             │                                                              │
│             441 │ vv.pocet*cena             │ Iné operačné ošetrenie hemoroidov             │ vv.kod in ['5n45x']                                          │
│             871 │ vv.pocet*cena             │ Cholecystektómia jednoduchá bez revízie žlčov │ vv.kod in ['5n6202']                                         │
│                 │                           │ ých ciest, laparoskopicky                     │                                                              │
│             375 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['5n811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8131']                                         │
│                 │                           │ plastickým materiálom, laparoskopicky transpe │                                                              │
│                 │                           │ ritoneálne                                    │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperit                                    │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['5n813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8171']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparosko │                                                              │
│                 │                           │ picky tran                                    │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totáln                                    │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['5n81x']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] s alop │ vv.kod in ['5n8231']                                         │
│                 │                           │ lastickým materiálom, laparoskopicky transper │                                                              │
│                 │                           │ itoneálne                                     │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie femorálnej hernie [prietrže] pri re │ vv.kod in ['5n8271']                                         │
│                 │                           │ cidíve s aloplastickým materiálom, laparoskop │                                                              │
│                 │                           │ icky trans                                    │                                                              │
│             485 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s pl │ vv.kod in ['5n831']                                          │
│                 │                           │ astikou                                       │                                                              │
│             485 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n8330']                                         │
│                 │                           │ oplastickým materiálom, laparotomicky         │                                                              │
│             485 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže] s al │ vv.kod in ['5n833x']                                         │
│                 │                           │ oplastickým materiálom, ostatné               │                                                              │
│             485 │ vv.pocet*cena             │ Uzavretie umbilikálnej hernie [prietrže], ost │ vv.kod in ['5n83x']                                          │
│                 │                           │ atné                                          │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s p │ vv.kod in ['5n841']                                          │
│                 │                           │ lastikou                                      │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n8430']                                         │
│                 │                           │ loplastickým materiálom, laparotomicky        │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže] s a │ vv.kod in ['5n843x']                                         │
│                 │                           │ loplastickým materiálom, ostatné              │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie epigastrickej hernie [prietrže], os │ vv.kod in ['5n84x']                                          │
│                 │                           │ tatné                                         │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n891']                                          │
│                 │                           │ rží] s plastikou                              │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n8930']                                         │
│                 │                           │ rží] aloplastickým materiálom, laparotomicky  │                                                              │
│             540 │ vv.pocet*cena             │ Uzavretie ďalších abdominálnych hernií [priet │ vv.kod in ['5n893x']                                         │
│                 │                           │ rží] s aloplastickým materiálom, ostatné      │                                                              │
│             540 │ vv.pocet*cena             │ Iné uzavretie ďalších abdominálnych hernií [p │ vv.kod in ['5n89x']                                          │
│                 │                           │ rietrží], ostatné                             │                                                              │
│             441 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5n9341']                                         │
│                 │                           │ svalov                                        │                                                              │
│             441 │ vv.pocet*cena             │ Plastická operácia diastázy priamych brušných │ vv.kod in ['5n9342']                                         │
│                 │                           │ svalov s operáciou umbilikálnej hernie [priet │                                                              │
│                 │                           │ rže]                                          │                                                              │
│             396 │ vv.pocet*cena             │ Laparoskopia s adheziolýzou                   │ vv.kod in ['5n9981']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074a']                                         │
│                 │                           │ a karpálnych kostí                            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074b']                                         │
│                 │                           │ a metakarpálnych kostí                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074c']                                         │
│                 │                           │ a falangov prstov ruky                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074d']                                         │
│                 │                           │ a panvy                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074e']                                         │
│                 │                           │ a krčka stehennej kosti                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074f']                                         │
│                 │                           │ a proximálneho femuru                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074g']                                         │
│                 │                           │ a diafyzárneho femuru                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074h']                                         │
│                 │                           │ a distálneho femuru                           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074j']                                         │
│                 │                           │ a pately                                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074k']                                         │
│                 │                           │ a proximálnej tibie                           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074m']                                         │
│                 │                           │ a diafyzárnej tibie                           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074n']                                         │
│                 │                           │ a distálnej tibie                             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074p']                                         │
│                 │                           │ a proximálnej fibuly                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074q']                                         │
│                 │                           │ a diafyzárnej fibuly                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074r']                                         │
│                 │                           │ a distálnej fibuly                            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074s']                                         │
│                 │                           │ a talu                                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074t']                                         │
│                 │                           │ a kalkanea                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074u']                                         │
│                 │                           │ a tarzálnych kostí                            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074v']                                         │
│                 │                           │ a metatarzálnych kostí                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074w']                                         │
│                 │                           │ a falangov prstov nohy                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074x']                                         │
│                 │                           │ a ostatných kostí                             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie ťahovej serkláže, prípadne revízi │ vv.kod in ['5t074z']                                         │
│                 │                           │ a skapuly                                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0750']                                         │
│                 │                           │ prípadne revízia klavikuly                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0751']                                         │
│                 │                           │ prípadne revízia proximálneho humeru          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0752']                                         │
│                 │                           │ prípadne revízia diafyzárneho humeru          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0753']                                         │
│                 │                           │ prípadne revízia distálneho humeru            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0754']                                         │
│                 │                           │ prípadne revízia proximálneho radia           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0755']                                         │
│                 │                           │ prípadne revízia diafyzárneho radia           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0757']                                         │
│                 │                           │ prípadne revízia proximálnej ulny             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t0758']                                         │
│                 │                           │ prípadne revízia diafyzárnej ulny             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075a']                                         │
│                 │                           │ prípadne revízia karpálnych kostí             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075b']                                         │
│                 │                           │ prípadne revízia metakarpálnych kostí         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075c']                                         │
│                 │                           │ prípadne revízia falangov prstov ruky         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075d']                                         │
│                 │                           │ prípadne revízia panvy                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075e']                                         │
│                 │                           │ prípadne revízia krčka stehennej kosti        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075f']                                         │
│                 │                           │ prípadne revízia proximálneho femuru          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075g']                                         │
│                 │                           │ prípadne revízia diafyzárneho femuru          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075h']                                         │
│                 │                           │ prípadne revízia distálneho femuru            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075j']                                         │
│                 │                           │ prípadne revízia pately                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075s']                                         │
│                 │                           │ prípadne revízia talu                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075t']                                         │
│                 │                           │ prípadne revízia kalkanea                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075u']                                         │
│                 │                           │ prípadne revízia tarzálnych kostí             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075v']                                         │
│                 │                           │ prípadne revízia metatarzálnych kostí         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075w']                                         │
│                 │                           │ prípadne revízia falangov prstov nohy         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075x']                                         │
│                 │                           │ prípadne revízia ostatných kostí              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie dynamickej kompresívnej skrutky,  │ vv.kod in ['5t075z']                                         │
│                 │                           │ prípadne revízia skapuly                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076e']                                         │
│                 │                           │ nia, prípadne revízia krčka stehennej kosti   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076f']                                         │
│                 │                           │ nia, prípadne revízia proximálneho femuru     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076g']                                         │
│                 │                           │ nia, prípadne revízia diafyzárneho femuru     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076h']                                         │
│                 │                           │ nia, prípadne revízia distálneho femuru       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076m']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej tibie       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076n']                                         │
│                 │                           │ nia, prípadne revízia distálnej tibie         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076q']                                         │
│                 │                           │ nia, prípadne revízia diafyzárnej fibuly      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca bez zaiste │ vv.kod in ['5t076r']                                         │
│                 │                           │ nia, prípadne revízia distálnej fibuly        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t0776']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077e']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077f']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077k']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077m']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077n']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vnútrodreňového klinca zaisteného │ vv.kod in ['5t077r']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a0']                                         │
│                 │                           │ padne revízia klavikuly                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a1']                                         │
│                 │                           │ padne revízia proximálneho humeru             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a2']                                         │
│                 │                           │ padne revízia diafyzárneho humeru             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a3']                                         │
│                 │                           │ padne revízia distálneho humeru               │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a4']                                         │
│                 │                           │ padne revízia proximálneho radia              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a5']                                         │
│                 │                           │ padne revízia diafyzárneho radia              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a6']                                         │
│                 │                           │ padne revízia distálneho radia                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a7']                                         │
│                 │                           │ padne revízia proximálnej ulny                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a8']                                         │
│                 │                           │ padne revízia diafyzárnej ulny                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07a9']                                         │
│                 │                           │ padne revízia distálnej ulny                  │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ab']                                         │
│                 │                           │ padne revízia metakarpálnych kostí            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ac']                                         │
│                 │                           │ padne revízia falangov prstov ruky            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ae']                                         │
│                 │                           │ padne revízia krčka stehennej kosti           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07af']                                         │
│                 │                           │ padne revízia proximálneho femuru             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ag']                                         │
│                 │                           │ padne revízia diafyzárneho femuru             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ah']                                         │
│                 │                           │ padne revízia distálneho femuru               │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aj']                                         │
│                 │                           │ padne revízia patela                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ak']                                         │
│                 │                           │ padne revízia proximálnej tibie               │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07am']                                         │
│                 │                           │ padne revízia diafyzárnej tibie               │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07an']                                         │
│                 │                           │ padne revízia distálnej tibie                 │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ap']                                         │
│                 │                           │ padne revízia proximálnej fibuly              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aq']                                         │
│                 │                           │ padne revízia diafyzárnej fibuly              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ar']                                         │
│                 │                           │ padne revízia distálnej fibuly                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07as']                                         │
│                 │                           │ padne revízia talu                            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07at']                                         │
│                 │                           │ padne revízia kalkanea                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07av']                                         │
│                 │                           │ padne revízia metatarzálnych kostí            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07aw']                                         │
│                 │                           │ padne revízia falangov prstov nohy            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07ax']                                         │
│                 │                           │ padne revízia ostatných kostí                 │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie intramedulárneho prúta/drôtu, prí │ vv.kod in ['5t07az']                                         │
│                 │                           │ padne revízia skapuly                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b0']                                         │
│                 │                           │ evízia klavikuly                              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07b6']                                         │
│                 │                           │ evízia distálneho radia                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bb']                                         │
│                 │                           │ evízia metakarpálnych kostí                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bc']                                         │
│                 │                           │ evízia falangov prstov ruky                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07br']                                         │
│                 │                           │ evízia distálnej fibuly                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bv']                                         │
│                 │                           │ evízia metatarzálnych kostí                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie uhlovostabilnej dlahy, prípadne r │ vv.kod in ['5t07bw']                                         │
│                 │                           │ evízia falangov prstov nohy                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia klavikuly │ vv.kod in ['5t07d0']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d1']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d2']                                         │
│                 │                           │ eho humeru                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d3']                                         │
│                 │                           │ o humeru                                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d4']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d5']                                         │
│                 │                           │ eho radia                                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07d6']                                         │
│                 │                           │ o radia                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07d7']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07d8']                                         │
│                 │                           │ ej ulny                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07d9']                                         │
│                 │                           │ ulny                                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia karpálnyc │ vv.kod in ['5t07da']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metakarpá │ vv.kod in ['5t07db']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dc']                                         │
│                 │                           │ prstov ruky                                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia panvy     │ vv.kod in ['5t07dd']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia krčka ste │ vv.kod in ['5t07de']                                         │
│                 │                           │ hennej kosti                                  │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07df']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dg']                                         │
│                 │                           │ eho femuru                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálneh │ vv.kod in ['5t07dh']                                         │
│                 │                           │ o femuru                                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia patela    │ vv.kod in ['5t07dj']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dk']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dm']                                         │
│                 │                           │ ej tibie                                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dn']                                         │
│                 │                           │ tibie                                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia proximáln │ vv.kod in ['5t07dp']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia diafyzárn │ vv.kod in ['5t07dq']                                         │
│                 │                           │ ej fibuly                                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia distálnej │ vv.kod in ['5t07dr']                                         │
│                 │                           │ fibuly                                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia talu      │ vv.kod in ['5t07ds']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia kalkanea  │ vv.kod in ['5t07dt']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia tarzálnyc │ vv.kod in ['5t07du']                                         │
│                 │                           │ h kostí                                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia metatarzá │ vv.kod in ['5t07dv']                                         │
│                 │                           │ lnych kostí                                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia falangov  │ vv.kod in ['5t07dw']                                         │
│                 │                           │ prstov nohy                                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia ostatných │ vv.kod in ['5t07dx']                                         │
│                 │                           │ kostí                                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie skoby, prípadne revízia skapuly   │ vv.kod in ['5t07dz']                                         │
│             287 │ vv.pocet*cena             │ Odstránenie vnútorného predlžovacieho alebo p │ vv.kod in ['5t07e0']                                         │
│                 │                           │ osuvného systému, prípadne revízia klavikuly  │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t4']                                         │
│                 │                           │ vízia proximálneho radia                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t5']                                         │
│                 │                           │ vízia diafyzárneho radia                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t6']                                         │
│                 │                           │ vízia distálneho radia                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t7']                                         │
│                 │                           │ vízia proximálnej ulny                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t8']                                         │
│                 │                           │ vízia diafyzárnej ulny                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07t9']                                         │
│                 │                           │ vízia distálnej ulny                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ta']                                         │
│                 │                           │ vízia karpálnych kostí                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tb']                                         │
│                 │                           │ vízia metakarpálnych kostí                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tc']                                         │
│                 │                           │ vízia falangov prstov ruky                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tk']                                         │
│                 │                           │ vízia proximálnej tibie                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tm']                                         │
│                 │                           │ vízia diafyzárnej tibie                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tn']                                         │
│                 │                           │ vízia distálnej tibie                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tp']                                         │
│                 │                           │ vízia proximálnej fibuly                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tq']                                         │
│                 │                           │ vízia diafyzárnej fibuly                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tr']                                         │
│                 │                           │ vízia distálnej fibuly                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07ts']                                         │
│                 │                           │ vízia talu                                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tt']                                         │
│                 │                           │ vízia kalkanea                                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tu']                                         │
│                 │                           │ vízia tarzálnych kostí                        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tv']                                         │
│                 │                           │ vízia metatarzálnych kostí                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tw']                                         │
│                 │                           │ vízia falangov prstov nohy                    │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tx']                                         │
│                 │                           │ vízia ostatných kostí                         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie vonkajšieho fixátora, prípadne re │ vv.kod in ['5t07tz']                                         │
│                 │                           │ vízia skapuly                                 │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v4']                                         │
│                 │                           │ rípadne revízia proximálneho radia            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v5']                                         │
│                 │                           │ rípadne revízia diafyzárneho radia            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v6']                                         │
│                 │                           │ rípadne revízia distálneho radia              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v7']                                         │
│                 │                           │ rípadne revízia proximálnej ulny              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v8']                                         │
│                 │                           │ rípadne revízia diafyzárnej ulny              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07v9']                                         │
│                 │                           │ rípadne revízia distálnej ulny                │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07va']                                         │
│                 │                           │ rípadne revízia karpálnych kostí              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vb']                                         │
│                 │                           │ rípadne revízia metakarpálnych kostí          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vk']                                         │
│                 │                           │ rípadne revízia proximálnej tibie             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vm']                                         │
│                 │                           │ rípadne revízia diafyzárnej tibie             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vn']                                         │
│                 │                           │ rípadne revízia distálnej tibie               │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vp']                                         │
│                 │                           │ rípadne revízia proximálnej fibuly            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vq']                                         │
│                 │                           │ rípadne revízia diafyzárnej fibuly            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vr']                                         │
│                 │                           │ rípadne revízia distálnej fibuly              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vs']                                         │
│                 │                           │ rípadne revízia talu                          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vt']                                         │
│                 │                           │ rípadne revízia kalkanea                      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vu']                                         │
│                 │                           │ rípadne revízia tarzálnych kostí              │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie kruhového vonkajšieho fixátora, p │ vv.kod in ['5t07vv']                                         │
│                 │                           │ rípadne revízia metatarzálnych kostí          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x5']                                         │
│                 │                           │ , prípadne revízia diafyzárneho radia         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x6']                                         │
│                 │                           │ , prípadne revízia distálneho radia           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x7']                                         │
│                 │                           │ , prípadne revízia proximálnej ulny           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x8']                                         │
│                 │                           │ , prípadne revízia diafyzárnej ulny           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07x9']                                         │
│                 │                           │ , prípadne revízia distálnej ulny             │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xa']                                         │
│                 │                           │ , prípadne revízia karpálnych kostí           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xb']                                         │
│                 │                           │ , prípadne revízia metakarpálnych kostí       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xc']                                         │
│                 │                           │ , prípadne revízia falangov prstov ruky       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xe']                                         │
│                 │                           │ , prípadne revízia krčka stehennej kosti      │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xf']                                         │
│                 │                           │ , prípadne revízia proximálneho femuru        │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xj']                                         │
│                 │                           │ , prípadne revízia pately                     │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xk']                                         │
│                 │                           │ , prípadne revízia proximálnej tibie          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xm']                                         │
│                 │                           │ , prípadne revízia diafyzárnej tibie          │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xn']                                         │
│                 │                           │ , prípadne revízia distálnej tibie            │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xp']                                         │
│                 │                           │ , prípadne revízia proximálnej fibuly         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xq']                                         │
│                 │                           │ , prípadne revízia diafyzárnej fibuly         │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xr']                                         │
│                 │                           │ , prípadne revízia distálnej fibuly           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xs']                                         │
│                 │                           │ , prípadne revízia talu                       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xt']                                         │
│                 │                           │ , prípadne revízia kalkanea                   │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xu']                                         │
│                 │                           │ , prípadne revízia tarzálnych kostí           │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xv']                                         │
│                 │                           │ , prípadne revízia metatarzálnych kostí       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xw']                                         │
│                 │                           │ , prípadne revízia falangov prstov nohy       │                                                              │
│             287 │ vv.pocet*cena             │ Odstránenie iného osteosyntetického materiálu │ vv.kod in ['5t07xx']                                         │
│                 │                           │ , prípadne revízia ostatných kostí            │                                                              │
│             375 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['5t0800']                                         │
│             375 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['5t080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│             375 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho                                     │                                                              │
│             369 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0811']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             369 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0812']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             369 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0813']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             369 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['5t0814']                                         │
│                 │                           │ článkov prstov nohy vo výške 2.-5. metatarzof │                                                              │
│                 │                           │ alangeáln                                     │                                                              │
│             375 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['5t08201']                                        │
│             375 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['5t08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             369 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 1 metata │ vv.kod in ['5t08211']                                        │
│                 │                           │ rzálna kosť                                   │                                                              │
│             369 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 2 metata │ vv.kod in ['5t08212']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             369 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 3 metata │ vv.kod in ['5t08213']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             369 │ vv.pocet*cena             │ Osteotomia ossa metatarsalia II - V, 4 metata │ vv.kod in ['5t08214']                                        │
│                 │                           │ rzálnych kostí                                │                                                              │
│             375 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['5t0822a']                                        │
│             375 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['5t0830']                                         │
│             369 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0831']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             369 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0832']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             369 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0833']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             369 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu II  │ vv.kod in ['5t0834']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             375 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083b']                                         │
│                 │                           │ - V, 1 kĺb                                    │                                                              │
│             375 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083c']                                         │
│                 │                           │ - V, 2 kĺby                                   │                                                              │
│             375 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083d']                                         │
│                 │                           │ - V, 3 kĺby                                   │                                                              │
│             375 │ vv.pocet*cena             │ Artroplastika interfalangeálneho kĺbu nohy II │ vv.kod in ['5t083e']                                         │
│                 │                           │ - V, 4 kĺby                                   │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1045']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza drôtom  │                                                              │
│                 │                           │ alebo ťaho                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t1048']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahov                                    │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a5']                                         │
│                 │                           │ afyzárnej oblasti radia, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v di │ vv.kod in ['5t10a8']                                         │
│                 │                           │ afyzárnej oblasti ulny, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1211']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1217']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza skrutk                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a skrutkou                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza sk │                                                              │
│                 │                           │ rutkou                                        │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t121r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza s │                                                              │
│                 │                           │ krutkou                                       │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1236']                                         │
│                 │                           │ bnej oblasti distálneho radia , osteosyntéza  │                                                              │
│                 │                           │ štandardno                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t123r']                                         │
│                 │                           │ bnej oblasti distálnej fibuly, osteosyntéza š │                                                              │
│                 │                           │ tandardnou                                    │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1241']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a drôtom a                                    │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1246']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza d │                                                              │
│                 │                           │ rôtom aleb                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1247']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza d │                                                              │
│                 │                           │ rôtom aleb                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t1249']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza drô │                                                              │
│                 │                           │ tom alebo                                     │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124j']                                         │
│                 │                           │ bnej oblasti pately, osteosyntéza drôtom aleb │                                                              │
│                 │                           │ o ťahovou                                     │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t124n']                                         │
│                 │                           │ bnej oblasti distálnej tibie, osteosyntéza dr │                                                              │
│                 │                           │ ôtom alebo                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129e']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza transf                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t129f']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a transfix                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a7']                                         │
│                 │                           │ bnej oblasti proximálnej ulny, osteosyntéza i │                                                              │
│                 │                           │ ntramedulá                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12a9']                                         │
│                 │                           │ bnej oblasti distálnej ulny, osteosyntéza int │                                                              │
│                 │                           │ ramedulárn                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12af']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a intramed                                    │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12b6']                                         │
│                 │                           │ bnej oblasti distálneho radia, osteosyntéza u │                                                              │
│                 │                           │ hlovostabi                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ce']                                         │
│                 │                           │ bnej oblasti krčka stehennej kosti, osteosynt │                                                              │
│                 │                           │ éza uhlovo                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12cf']                                         │
│                 │                           │ bnej oblasti proximálneho femuru, osteosyntéz │                                                              │
│                 │                           │ a uhlovou/                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12ch']                                         │
│                 │                           │ bnej oblasti distálneho femuru, osteosyntéza  │                                                              │
│                 │                           │ uhlovou/ko                                    │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny v kĺ │ vv.kod in ['5t12x1']                                         │
│                 │                           │ bnej oblasti proximálneho humeru, osteosyntéz │                                                              │
│                 │                           │ a iným ost                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t140a']                                         │
│                 │                           │ álnych kostí bez osteosyntézy                 │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140b']                                         │
│                 │                           │ karpálnych kostí bez osteosyntézy             │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140c']                                         │
│                 │                           │ ngov prstov ruky bez osteosyntézy             │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t140u']                                         │
│                 │                           │ álnych kosti bez osteosyntézy                 │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t140v']                                         │
│                 │                           │ tarzálnych kosti bez osteosyntézy             │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t140w']                                         │
│                 │                           │ ngov prstov nohy bez osteosyntézy             │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na o │ vv.kod in ['5t140x']                                         │
│                 │                           │ statných malých kostiach bez osteosyntézy     │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t140z']                                         │
│                 │                           │ uly bez osteosyntézy                          │                                                              │
│             452 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1410']                                         │
│                 │                           │ ikuly, osteosyntéza skrutkou                  │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t141a']                                         │
│                 │                           │ álnych kostí, osteosyntéza skrutkou           │                                                              │
│             408 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza skrutkou       │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza skrutkou       │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t141v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza skrutkou       │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t141w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza skrutkou       │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t141x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza skrutkou     │                                                              │
│             452 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1430']                                         │
│                 │                           │ ikuly, osteosyntéza štandardnou dlahou        │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t143v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t143w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza štandardnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t143x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza štandardnou  │                                                              │
│                 │                           │ dlahou                                        │                                                              │
│             452 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t1440']                                         │
│                 │                           │ ikuly, osteosyntéza drôtom a ťahovou serklážo │                                                              │
│                 │                           │ u                                             │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t144a']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             408 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144b']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144c']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t144u']                                         │
│                 │                           │ álnych kostí, osteosyntéza drôtom a ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t144v']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t144w']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza drôtom a ťahov │                                                              │
│                 │                           │ ou serkláž                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t144x']                                         │
│                 │                           │ tných malých kostí, osteosyntéza drôtom a ťah │                                                              │
│                 │                           │ ovou serkl                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny na m │ vv.kod in ['5t144z']                                         │
│                 │                           │ alej kosti, osteosyntéza drôtom a ťahovou ser │                                                              │
│                 │                           │ klážou sk                                     │                                                              │
│             452 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14a0']                                         │
│                 │                           │ ikuly, osteosyntéza intramedulárnymi drôtmi a │                                                              │
│                 │                           │ prútmi                                        │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14ax']                                         │
│                 │                           │ tných malých kostí, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtm                                    │                                                              │
│             452 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny klav │ vv.kod in ['5t14b0']                                         │
│                 │                           │ ikuly, osteosyntéza uhlovostabilnou dlahou    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny karp │ vv.kod in ['5t14ba']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bb']                                         │
│                 │                           │ karpálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bc']                                         │
│                 │                           │ ngov prstov ruky, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny tarz │ vv.kod in ['5t14bu']                                         │
│                 │                           │ álnych kostí, osteosyntéza uhlovostabilnou dl │                                                              │
│                 │                           │ ahou                                          │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny meta │ vv.kod in ['5t14bv']                                         │
│                 │                           │ tarzálnych kostí, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny fala │ vv.kod in ['5t14bw']                                         │
│                 │                           │ ngov prstov nohy, osteosyntéza uhlovostabilno │                                                              │
│                 │                           │ u dlahou                                      │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny osta │ vv.kod in ['5t14bx']                                         │
│                 │                           │ tných malých kostí, osteosyntéza uhlovostabil │                                                              │
│                 │                           │ nou dlahou                                    │                                                              │
│             375 │ vv.pocet*cena             │ Otvorená repozícia jednoduchej zlomeniny skap │ vv.kod in ['5t14bz']                                         │
│                 │                           │ uly, osteosyntéza uhlovostabilnou dlahou      │                                                              │
│             408 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t151b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza skrutkou        │                                                              │
│             408 │ vv.pocet*cena             │ Otvorená repozícia trieštivej zlomeniny metak │ vv.kod in ['5t154b']                                         │
│                 │                           │ arpálnych kostí, osteosyntéza drôtom a ťahovo │                                                              │
│                 │                           │ u serklážo                                    │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1911']                                         │
│                 │                           │ eho kĺbu, osteosyntéza skrutkou               │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t1941']                                         │
│                 │                           │ eho kĺbu, osteosyntéza drôtom alebo ťahovou s │                                                              │
│                 │                           │ erklážou                                      │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19b1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza uhlovostabilnou dlahou │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19x1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza iným osteosyntetickým  │                                                              │
│                 │                           │ materiálom                                    │                                                              │
│             387 │ vv.pocet*cena             │ Otvorená repozícia luxácie akromioklavikulárn │ vv.kod in ['5t19z1']                                         │
│                 │                           │ eho kĺbu, osteosyntéza rezorbovateľným materi │                                                              │
│                 │                           │ álom                                          │                                                              │
│             408 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza skrutk │                                                              │
│                 │                           │ ou                                            │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t211x']                                         │
│                 │                           │ ýzy ostatných kostí, osteosyntéza skrutkou    │                                                              │
│             452 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2140']                                         │
│                 │                           │ ýzy klavikuly, osteosyntéza drôtom alebo ťaho │                                                              │
│                 │                           │ vou serklá                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2145']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza drôtom a │                                                              │
│                 │                           │ lebo ťahov                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2146']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t2149']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza drôtom alebo │                                                              │
│                 │                           │ ťahovou s                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214a']                                         │
│                 │                           │ ýzy karpálnych kostí, osteosyntéza drôtom ale │                                                              │
│                 │                           │ bo ťahovou                                    │                                                              │
│             408 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214b']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214c']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214v']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t214w']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza drôtom │                                                              │
│                 │                           │ alebo ťah                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t216f']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza nezaist │                                                              │
│                 │                           │ eným predv                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217e']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza zaist │                                                              │
│                 │                           │ eným intra                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217h']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217k']                                         │
│                 │                           │ ýzy proximálnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217m']                                         │
│                 │                           │ ýzy diafyzárnej tibie, osteosyntéza zaisteným │                                                              │
│                 │                           │ intramedu                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t217n']                                         │
│                 │                           │ ýzy distálnej tibie, osteosyntéza zaisteným i │                                                              │
│                 │                           │ ntramedulá                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a1']                                         │
│                 │                           │ ýzy proximálneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a2']                                         │
│                 │                           │ ýzy diafyzárneho humeru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a3']                                         │
│                 │                           │ ýzy distálneho humeru, osteosyntéza intramedu │                                                              │
│                 │                           │ lárnymi dr                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a6']                                         │
│                 │                           │ ýzy distálneho radia, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21a9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza intramedulár │                                                              │
│                 │                           │ nymi drôtm                                    │                                                              │
│             408 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ab']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ac']                                         │
│                 │                           │ ýzy falangov prstov ruky, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ae']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza intra │                                                              │
│                 │                           │ medulárnym                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ag']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza intrame │                                                              │
│                 │                           │ dulárnymi                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aq']                                         │
│                 │                           │ ýzy diafyzárnej fibuly, osteosyntéza intramed │                                                              │
│                 │                           │ ulárnymi d                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21ar']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza intramedul │                                                              │
│                 │                           │ árnymi drô                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21av']                                         │
│                 │                           │ ýzy metatarzálnych kostí, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21aw']                                         │
│                 │                           │ ýzy falangov prstov nohy, osteosyntéza intram │                                                              │
│                 │                           │ edulárnymi                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x4']                                         │
│                 │                           │ ýzy proximálneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetic                                    │                                                              │
│             331 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x5']                                         │
│                 │                           │ ýzy diafyzárneho radia, osteosyntéza iným ost │                                                              │
│                 │                           │ eosyntetic                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x7']                                         │
│                 │                           │ ýzy proximálnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x8']                                         │
│                 │                           │ ýzy diafyzárnej ulny, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21x9']                                         │
│                 │                           │ ýzy distálnej ulny, osteosyntéza iným osteosy │                                                              │
│                 │                           │ ntetickým                                     │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xb']                                         │
│                 │                           │ ýzy metakarpálnych kostí, osteosyntéza iným o │                                                              │
│                 │                           │ steosyntet                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xe']                                         │
│                 │                           │ ýzy krčka stehennej kosti, osteosyntéza iným  │                                                              │
│                 │                           │ osteosynte                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xf']                                         │
│                 │                           │ ýzy proximálneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosynteti                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xg']                                         │
│                 │                           │ ýzy diafyzárneho femuru, osteosyntéza iným os │                                                              │
│                 │                           │ teosynteti                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xh']                                         │
│                 │                           │ ýzy distálneho femuru, osteosyntéza iným oste │                                                              │
│                 │                           │ osyntetick                                    │                                                              │
│             375 │ vv.pocet*cena             │ Zatvorená repozícia zlomeniny alebo epifyzeol │ vv.kod in ['5t21xr']                                         │
│                 │                           │ ýzy distálnej fibuly, osteosyntéza iným osteo │                                                              │
│                 │                           │ syntetický                                    │                                                              │
│             328 │ vv.pocet*cena             │ Parciálna synovektómia lakťového kĺbu         │ vv.kod in ['5t3044']                                         │
│             328 │ vv.pocet*cena             │ Totálna synovektómia lakťového kĺbu           │ vv.kod in ['5t3054']                                         │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) humeroglenoidáln │ vv.kod in ['5t3060']                                         │
│                 │                           │ eho kĺbu                                      │                                                              │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) lakťového kĺbu   │ vv.kod in ['5t3064']                                         │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) radiokarpálneho  │ vv.kod in ['5t3068']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) kolenného kĺbu   │ vv.kod in ['5t306h']                                         │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) horného členkové │ vv.kod in ['5t306k']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             463 │ vv.pocet*cena             │ Mobilizácia kĺbu (artrolýza) metatarzofalange │ vv.kod in ['5t306q']                                         │
│                 │                           │ álnych kĺbov                                  │                                                              │
│             375 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['5t3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             375 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálnych a interfalan │ vv.kod in ['5t38a1']                                         │
│                 │                           │ geálnych kĺbov prsta nohy, 1 kĺb              │                                                              │
│             375 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['5t38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5t4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický aseptický výplach humeroglenoid │ vv.kod in ['5t4000']                                         │
│                 │                           │ álneho kĺbu s drenážou                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5t4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach lakťového kĺb │ vv.kod in ['5t4004']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5t4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach radiokarpálne │ vv.kod in ['5t4008']                                         │
│                 │                           │ ho kĺbu s drenážou                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach ulnokarpálneh │ vv.kod in ['5t4009']                                         │
│                 │                           │ o kĺbu s drenážou                             │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopický aseptický výplach bedrového kĺb │ vv.kod in ['5t400g']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5t400h']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický aseptický výplach kolenného kĺb │ vv.kod in ['5t400h']                                         │
│                 │                           │ u s drenážou                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5t400k']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach horného členk │ vv.kod in ['5t400k']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický aseptický výplach dolného členk │ vv.kod in ['5t400m']                                         │
│                 │                           │ ového kĺbu s drenážou                         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) hu │ vv.kod in ['5t4020']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) la │ vv.kod in ['5t4024']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ra │ vv.kod in ['5t4028']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ul │ vv.kod in ['5t4029']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) be │ vv.kod in ['5t402g']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ko │ vv.kod in ['5t402h']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) ho │ vv.kod in ['5t402k']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická mobilizácia kĺbu (artrolýza) do │ vv.kod in ['5t402m']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4030']                                         │
│                 │                           │ ateriálu z humeroglenoidálneho kĺbu           │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4031']                                         │
│                 │                           │ ateriálu z akromioklavikulárneho kĺbu         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4034']                                         │
│                 │                           │ ateriálu z lakťového kĺbu                     │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4038']                                         │
│                 │                           │ ateriálu z radiokarpálneho kĺbu               │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t4039']                                         │
│                 │                           │ ateriálu z ulnokarpálneho kĺbu                │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403g']                                         │
│                 │                           │ ateriálu z bedrového kĺbu                     │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403h']                                         │
│                 │                           │ ateriálu z kolenného kĺbu                     │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403k']                                         │
│                 │                           │ ateriálu z horného členkového kĺbu            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie osteosyntetického m │ vv.kod in ['5t403m']                                         │
│                 │                           │ ateriálu z dolného členkového kĺbu            │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z hu │ vv.kod in ['5t4040']                                         │
│                 │                           │ meroglenoidálneho kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z la │ vv.kod in ['5t4044']                                         │
│                 │                           │ kťového kĺbu                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ra │ vv.kod in ['5t4048']                                         │
│                 │                           │ diokarpálneho kĺbu                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ul │ vv.kod in ['5t4049']                                         │
│                 │                           │ nokarpálneho kĺbu                             │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z be │ vv.kod in ['5t404g']                                         │
│                 │                           │ drového kĺbu                                  │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ko │ vv.kod in ['5t404h']                                         │
│                 │                           │ lenného kĺbu                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z ho │ vv.kod in ['5t404k']                                         │
│                 │                           │ rného členkového kĺbu                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie voľných telies z do │ vv.kod in ['5t404m']                                         │
│                 │                           │ lného členkového kĺbu                         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4050']                                         │
│                 │                           │ alcifikátov z humeroglenoidálneho kĺbu        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4054']                                         │
│                 │                           │ alcifikátov z lakťového kĺbu                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4058']                                         │
│                 │                           │ alcifikátov z radiokarpálneho kĺbu            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t4059']                                         │
│                 │                           │ alcifikátov z ulnokarpálneho kĺbu             │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405g']                                         │
│                 │                           │ alcifikátov z bedrového kĺbu                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405k']                                         │
│                 │                           │ alcifikátov z horného členkového kĺbu         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické odstránenie periartikulárnych k │ vv.kod in ['5t405m']                                         │
│                 │                           │ alcifikátov z dolného členkového kĺbu         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4090']                                         │
│                 │                           │ v ligament z humeroglenoidálneho kĺbu         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4091']                                         │
│                 │                           │ v ligament z akromioklavikulárneho kĺbu       │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4094']                                         │
│                 │                           │ v ligament z lakťového kĺbu                   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4098']                                         │
│                 │                           │ v ligament z radiokarpálneho kĺbu             │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t4099']                                         │
│                 │                           │ v ligament z ulnokarpálneho kĺbu              │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409g']                                         │
│                 │                           │ v ligament z bedrového kĺbu                   │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409h']                                         │
│                 │                           │ v ligament z kolenného kĺbu                   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409k']                                         │
│                 │                           │ v ligament z horného členkového kĺbu          │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia častí ligament, zbytko │ vv.kod in ['5t409m']                                         │
│                 │                           │ v ligament z dolného členkového kĺbu          │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické revízie humeroglenoidálneho │ vv.kod in ['5t40x0']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické revízie akromioklavikulárne │ vv.kod in ['5t40x1']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             328 │ vv.pocet*cena             │ Iné artroskopické revízie lakťového kĺbu      │ vv.kod in ['5t40x4']                                         │
│             793 │ vv.pocet*cena             │ Iné artroskopické revízie radiokarpálneho kĺb │ vv.kod in ['5t40x8']                                         │
│                 │                           │ u                                             │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické revízie ulnokarpálneho kĺbu │ vv.kod in ['5t40x9']                                         │
│            1378 │ vv.pocet*cena             │ Iné artroskopické revízie bedrového kĺbu      │ vv.kod in ['5t40xg']                                         │
│             971 │ vv.pocet*cena             │ Iné artroskopické revízie kolenného kĺbu      │ vv.kod in ['5t40xh']                                         │
│             793 │ vv.pocet*cena             │ Iné artroskopické revízie horného členkového  │ vv.kod in ['5t40xk']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické revízie dolného členkového  │ vv.kod in ['5t40xm']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia plica synovialis kolen │ vv.kod in ['5t410h']                                         │
│                 │                           │ ného kĺbu                                     │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa bedrov │ vv.kod in ['5t411g']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia tukového telesa kolenn │ vv.kod in ['5t411h']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia humerogl │ vv.kod in ['5t4120']                                         │
│                 │                           │ enoidálneho kĺbu                              │                                                              │
│             328 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia lakťovéh │ vv.kod in ['5t4124']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia radiokar │ vv.kod in ['5t4128']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia ulnokarp │ vv.kod in ['5t4129']                                         │
│                 │                           │ álneho kĺbu                                   │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia bedrovéh │ vv.kod in ['5t412g']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia kolennéh │ vv.kod in ['5t412h']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia horného  │ vv.kod in ['5t412k']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická parciálna synovektómia dolného  │ vv.kod in ['5t412m']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická totálna synovektómia humeroglen │ vv.kod in ['5t4130']                                         │
│                 │                           │ oidálneho kĺbu                                │                                                              │
│             328 │ vv.pocet*cena             │ Artroskopická totálna synovektómia lakťového  │ vv.kod in ['5t4134']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická totálna synovektómia radiokarpá │ vv.kod in ['5t4138']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická totálna synovektómia ulnokarpál │ vv.kod in ['5t4139']                                         │
│                 │                           │ neho kĺbu                                     │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická totálna synovektómia bedrového  │ vv.kod in ['5t413g']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická totálna synovektómia kolenného  │ vv.kod in ['5t413h']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická totálna synovektómia horného čl │ vv.kod in ['5t413k']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická totálna synovektómia dolného čl │ vv.kod in ['5t413m']                                         │
│                 │                           │ enkového kĺbu                                 │                                                              │
│             328 │ vv.pocet*cena             │ Artroskopická elektrotermická denervácia syno │ vv.kod in ['5t4144']                                         │
│                 │                           │ vie a tkaniva kĺbneho púzdra lakťového kĺbu   │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii humerog │ vv.kod in ['5t41x0']                                         │
│                 │                           │ lenoidálneho kĺbu                             │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii akromio │ vv.kod in ['5t41x1']                                         │
│                 │                           │ klavikulárneho kĺbu                           │                                                              │
│             328 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii lakťové │ vv.kod in ['5t41x4']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii radioka │ vv.kod in ['5t41x8']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii ulnokar │ vv.kod in ['5t41x9']                                         │
│                 │                           │ pálneho kĺbu                                  │                                                              │
│            1378 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii bedrové │ vv.kod in ['5t41xg']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii kolenné │ vv.kod in ['5t41xh']                                         │
│                 │                           │ ho kĺbu                                       │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii horného │ vv.kod in ['5t41xk']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             793 │ vv.pocet*cena             │ Iné artroskopické operácie na synovii dolného │ vv.kod in ['5t41xm']                                         │
│                 │                           │ členkového kĺbu                               │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4200']                                         │
│                 │                           │ nej chrupavky humeroglenoidálneho kĺbu        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4204']                                         │
│                 │                           │ nej chrupavky lakťového kĺbu                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4208']                                         │
│                 │                           │ nej chrupavky radiokarpálneho kĺbu            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t4209']                                         │
│                 │                           │ nej chrupavky ulnokarpálneho kĺbu             │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420g']                                         │
│                 │                           │ nej chrupavky bedrového kĺbu                  │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420h']                                         │
│                 │                           │ nej chrupavky kolenného kĺbu                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420k']                                         │
│                 │                           │ nej chrupavky horného členkového kĺbu         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická excízia poškodeného tkaniva kĺb │ vv.kod in ['5t420m']                                         │
│                 │                           │ nej chrupavky dolného členkového kĺbu         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4210']                                         │
│                 │                           │ gmentu humeroglenoidálneho kĺbu               │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4214']                                         │
│                 │                           │ gmentu lakťového kĺbu                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4218']                                         │
│                 │                           │ gmentu radiokarpálneho kĺbu                   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t4219']                                         │
│                 │                           │ gmentu ulnokarpálneho kĺbu                    │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421g']                                         │
│                 │                           │ gmentu bedrového kĺbu                         │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421h']                                         │
│                 │                           │ gmentu kolenného kĺbu                         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421k']                                         │
│                 │                           │ gmentu horného členkového kĺbu                │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická refixácia osteochondrálneho fra │ vv.kod in ['5t421m']                                         │
│                 │                           │ gmentu dolného členkového kĺbu                │                                                              │
│            1186 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t4220']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5t4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika l │ vv.kod in ['5t4224']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5t4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika r │ vv.kod in ['5t4228']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika u │ vv.kod in ['5t4229']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika b │ vv.kod in ['5t422g']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika k │ vv.kod in ['5t422h']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t422k']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika h │ vv.kod in ['5t422k']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická subchondrálna spongioplastika d │ vv.kod in ['5t422m']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická parciálna resekcia menisku      │ vv.kod in ['5t42310']                                        │
│             971 │ vv.pocet*cena             │ Artroskopická totálna resekcia menisku        │ vv.kod in ['5t42311']                                        │
│            1091 │ vv.pocet*cena             │ Artroskopická refixácia menisku               │ vv.kod in ['5t42320']                                        │
│            1091 │ vv.pocet*cena             │ Artroskopická sutúra menisku, zložitá         │ vv.kod in ['5t42322']                                        │
│            1091 │ vv.pocet*cena             │ Artroskopická implantácia umelého menisku     │ vv.kod in ['5t4233']                                         │
│             971 │ vv.pocet*cena             │ Artroskopické odstránenie umelého menisku     │ vv.kod in ['5t4234']                                         │
│             971 │ vv.pocet*cena             │ Ostatné artroskopické operácie menisku        │ vv.kod in ['5t423x']                                         │
│             971 │ vv.pocet*cena             │ Artroskopický odber chondrálneho transplantát │ vv.kod in ['5t426h']                                         │
│                 │                           │ u z kolenného kĺbu                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky lakťov │ vv.kod in ['5t4274']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky radiok │ vv.kod in ['5t4278']                                         │
│                 │                           │ arpálneho kĺbu                                │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky ulnoka │ vv.kod in ['5t4279']                                         │
│                 │                           │ rpálneho kĺbu                                 │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky bedrov │ vv.kod in ['5t427g']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            2944 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky kolenn │ vv.kod in ['5t427h']                                         │
│                 │                           │ ého kĺbu                                      │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky hornéh │ vv.kod in ['5t427k']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická transplantácia chrupavky dolnéh │ vv.kod in ['5t427m']                                         │
│                 │                           │ o členkového kĺbu                             │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4284']                                         │
│                 │                           │ ých tkanivových kultúr lakťového kĺbu         │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4288']                                         │
│                 │                           │ ých tkanivových kultúr radiokarpálneho kĺbu   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t4289']                                         │
│                 │                           │ ých tkanivových kultúr ulnokarpálneho kĺbu    │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428g']                                         │
│                 │                           │ ých tkanivových kultúr bedrového kĺbu         │                                                              │
│            2944 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428h']                                         │
│                 │                           │ ých tkanivových kultúr kolenného kĺbu         │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428k']                                         │
│                 │                           │ ých tkanivových kultúr horného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická implantácia in vitro vypestovan │ vv.kod in ['5t428m']                                         │
│                 │                           │ ých tkanivových kultúr dolného členkového kĺb │                                                              │
│                 │                           │ u                                             │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c0']                                         │
│                 │                           │ astika] humeroglenoidálneho kĺbu              │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c4']                                         │
│                 │                           │ astika] lakťového kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c8']                                         │
│                 │                           │ astika] radiokarpálneho kĺbu                  │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42c9']                                         │
│                 │                           │ astika] ulnokarpálneho kĺbu                   │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42cg']                                         │
│                 │                           │ astika] bedrového kĺbu                        │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ch']                                         │
│                 │                           │ astika] kolenného kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42ck']                                         │
│                 │                           │ astika] horného členkového kĺbu               │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické vyhladenie chrupavky [chondropl │ vv.kod in ['5t42cm']                                         │
│                 │                           │ astika] dolného členkového kĺbu               │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5t42d0']                                         │
│                 │                           │ umeroglenoidálneho kĺbu                       │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti l │ vv.kod in ['5t42d4']                                         │
│                 │                           │ akťového kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti r │ vv.kod in ['5t42d8']                                         │
│                 │                           │ adiokarpálneho kĺbu                           │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti u │ vv.kod in ['5t42d9']                                         │
│                 │                           │ lnokarpálneho kĺbu                            │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti b │ vv.kod in ['5t42dg']                                         │
│                 │                           │ edrového kĺbu                                 │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti k │ vv.kod in ['5t42dh']                                         │
│                 │                           │ olenného kĺbu                                 │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti h │ vv.kod in ['5t42dk']                                         │
│                 │                           │ orného členkového kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti d │ vv.kod in ['5t42dm']                                         │
│                 │                           │ olného členkového kĺbu                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e4']                                         │
│                 │                           │ implantáciou acelulárneho implantátu lakťovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e8']                                         │
│                 │                           │ implantáciou acelulárneho implantátu radiokar │                                                              │
│                 │                           │ pálneho k                                     │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42e9']                                         │
│                 │                           │ implantáciou acelulárneho implantátu ulnokarp │                                                              │
│                 │                           │ álneho kĺ                                     │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42eg']                                         │
│                 │                           │ implantáciou acelulárneho implantátu bedrovéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│            1985 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42eh']                                         │
│                 │                           │ implantáciou acelulárneho implantátu kolennéh │                                                              │
│                 │                           │ o kĺbu                                        │                                                              │
│            1870 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42ek']                                         │
│                 │                           │ implantáciou acelulárneho implantátu horného  │                                                              │
│                 │                           │ členkovéh                                     │                                                              │
│            1870 │ vv.pocet*cena             │ Artroskopické subchondrálne otvorenie kosti s │ vv.kod in ['5t42em']                                         │
│                 │                           │ implantáciou acelulárneho implantátu dolného  │                                                              │
│                 │                           │ členkovéh                                     │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická operácia chrupavky lakťového kĺ │ vv.kod in ['5t42f4']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukova                                    │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kĺbov ruky s │ vv.kod in ['5t42f8']                                         │
│                 │                           │ transplantáciou chondrocytov na autológne ind │                                                              │
│                 │                           │ ukovanej                                      │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická operácia chrupavky radiokarpáln │ vv.kod in ['5t42f9']                                         │
│                 │                           │ eho kĺbu s transplantáciou chondrocytov na au │                                                              │
│                 │                           │ tológne in                                    │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická operácia chrupavky bedrového kĺ │ vv.kod in ['5t42fg']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukova                                    │                                                              │
│            2944 │ vv.pocet*cena             │ Artroskopická operácia chrupavky kolenného kĺ │ vv.kod in ['5t42fh']                                         │
│                 │                           │ bu s transplantáciou chondrocytov na autológn │                                                              │
│                 │                           │ e indukova                                    │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická operácia chrupavky horného člen │ vv.kod in ['5t42fk']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne                                     │                                                              │
│            2828 │ vv.pocet*cena             │ Artroskopická operácia chrupavky dolného člen │ vv.kod in ['5t42fm']                                         │
│                 │                           │ kového kĺbu s transplantáciou chondrocytov na │                                                              │
│                 │                           │ autológne                                     │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h0']                                         │
│                 │                           │ h osteofytov humeroglenoidálneho kĺbu         │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h1']                                         │
│                 │                           │ h osteofytov akromioklavikulárneho kĺbu       │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h4']                                         │
│                 │                           │ h osteofytov lakťového kĺbu                   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h8']                                         │
│                 │                           │ h osteofytov radiokarpálneho kĺbu             │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42h9']                                         │
│                 │                           │ h osteofytov ulnokarpálneho kĺbu              │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hg']                                         │
│                 │                           │ h osteofytov bedrového kĺbu                   │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hh']                                         │
│                 │                           │ h osteofytov kolenného kĺbu                   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hk']                                         │
│                 │                           │ h osteofytov horného členkového kĺbu          │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopická resekcia jedného alebo viacerýc │ vv.kod in ['5t42hm']                                         │
│                 │                           │ h osteofytov dolného členkového kĺbu          │                                                              │
│             971 │ vv.pocet*cena             │ Iné artroskopické operácie na chrupavke a men │ vv.kod in ['5t42ih']                                         │
│                 │                           │ iskoch kolenného kĺbu                         │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická sutúra predného skríženého väzu │ vv.kod in ['5t430']                                          │
│            1091 │ vv.pocet*cena             │ Artroskopická sutúra zadného skríženého väzu  │ vv.kod in ['5t431']                                          │
│            1091 │ vv.pocet*cena             │ Artroskopická kostná refixácia skríženého väz │ vv.kod in ['5t432']                                          │
│                 │                           │ u                                             │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t433']                                          │
│                 │                           │ zu autológnym patelárnym ligamentom           │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t434']                                          │
│                 │                           │ zu iným autológnym ligamentom                 │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika predného skríženého vä │ vv.kod in ['5t435']                                          │
│                 │                           │ zu s aloplastickou náhradou                   │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5t436']                                          │
│                 │                           │ u s autogénnou patelárnou šľachou             │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženého väz │ vv.kod in ['5t437']                                          │
│                 │                           │ u s iným autológnym ligamentom                │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika zadného skríženeho väz │ vv.kod in ['5t438']                                          │
│                 │                           │ u s aloplastickou náhradou                    │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické uvoľnenie kolenného púzdra (lat │ vv.kod in ['5t439']                                          │
│                 │                           │ eral release)                                 │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická sutúra mediálneho kapsuloligame │ vv.kod in ['5t43a']                                          │
│                 │                           │ ntózneho aparátu kolenného kĺbu               │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická sutúra laterálneho kapsuloligam │ vv.kod in ['5t43b']                                          │
│                 │                           │ entózneho aparátu kolenného kĺbu              │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika mediálneho kapsuloliga │ vv.kod in ['5t43d']                                          │
│                 │                           │ mentózneho aparátu kolenného kĺbu             │                                                              │
│            1091 │ vv.pocet*cena             │ Artroskopická plastika laterálneho kapsulolig │ vv.kod in ['5t43e']                                          │
│                 │                           │ amentózneho aparátu kolenného kĺbu            │                                                              │
│            1091 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5t43x']                                          │
│                 │                           │ kapsuloligamentóznom aparáte kolenného kĺbu   │                                                              │
│            1186 │ vv.pocet*cena             │ Artroskopické spevnenie púzdra s fixáciou na  │ vv.kod in ['5t445']                                          │
│                 │                           │ glenoid stehom                                │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopická laterálna resekcia klavikuly    │ vv.kod in ['5t44a']                                          │
│            1186 │ vv.pocet*cena             │ Artroskopická stabilizácia akromioklavikulárn │ vv.kod in ['5t44b']                                          │
│                 │                           │ eho kĺbu fixačným výkonom                     │                                                              │
│            1186 │ vv.pocet*cena             │ Ostatné artroskopické refixácie a plastiky na │ vv.kod in ['5t44x']                                          │
│                 │                           │ kapsuloligamentóznom aparáte ramenného kĺbu   │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu lakť │ vv.kod in ['5t4904']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu radi │ vv.kod in ['5t4908']                                         │
│                 │                           │ okarpálneho kĺbu                              │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu ulno │ vv.kod in ['5t4909']                                         │
│                 │                           │ karpálneho kĺbu                               │                                                              │
│            1378 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu bedr │ vv.kod in ['5t490g']                                         │
│                 │                           │ ového kĺbu                                    │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu horn │ vv.kod in ['5t490k']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopické rozdelenie/prerušenie väzu doln │ vv.kod in ['5t490m']                                         │
│                 │                           │ ého členkového kĺbu                           │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický debridement šľachy humeroglenoi │ vv.kod in ['5t4910']                                         │
│                 │                           │ dálneho kĺbu                                  │                                                              │
│             328 │ vv.pocet*cena             │ Artroskopický debridement šľachy lakťového kĺ │ vv.kod in ['5t4914']                                         │
│                 │                           │ bu                                            │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopický debridement šľachy kolenného kĺ │ vv.kod in ['5t491h']                                         │
│                 │                           │ bu                                            │                                                              │
│             793 │ vv.pocet*cena             │ Artroskopický debridement šľachy horného člen │ vv.kod in ['5t491k']                                         │
│                 │                           │ kového kĺbu                                   │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické resekcie ganglia humeroglenoidá │ vv.kod in ['5t4920']                                         │
│                 │                           │ lny kĺb                                       │                                                              │
│             971 │ vv.pocet*cena             │ Artroskopické resekcia ganglia kolenného kĺbu │ vv.kod in ['5t492h']                                         │
│             971 │ vv.pocet*cena             │ Ostatné artroskopické operácie humeroglenoidá │ vv.kod in ['5t49x0']                                         │
│                 │                           │ lneho kĺbu                                    │                                                              │
│             971 │ vv.pocet*cena             │ Ostatné artroskopické operácie akromioklaviku │ vv.kod in ['5t49x1']                                         │
│                 │                           │ lárneho kĺbu                                  │                                                              │
│             328 │ vv.pocet*cena             │ Ostatné artroskopické operácie lakťového kĺbu │ vv.kod in ['5t49x4']                                         │
│             793 │ vv.pocet*cena             │ Ostatné artroskopické operácie radiokarpálneh │ vv.kod in ['5t49x8']                                         │
│                 │                           │ o kĺbu                                        │                                                              │
│             793 │ vv.pocet*cena             │ Ostatné artroskopické operácie ulnokarpálneho │ vv.kod in ['5t49x9']                                         │
│                 │                           │ kĺbu                                          │                                                              │
│            1378 │ vv.pocet*cena             │ Ostatné artroskopické operácie bedrového kĺbu │ vv.kod in ['5t49xg']                                         │
│             971 │ vv.pocet*cena             │ Ostatné artroskopické operácie kolenného kĺbu │ vv.kod in ['5t49xh']                                         │
│             793 │ vv.pocet*cena             │ Ostatné artroskopické operácie horného členko │ vv.kod in ['5t49xk']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│             793 │ vv.pocet*cena             │ Ostatné artroskopické operácie dolného členko │ vv.kod in ['5t49xm']                                         │
│                 │                           │ vého kĺbu                                     │                                                              │
│             331 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača prsta      │ vv.kod in ['5t7021']                                         │
│             331 │ vv.pocet*cena             │ Discízia šľachových pošiev ohýbača palca      │ vv.kod in ['5t7022']                                         │
│             331 │ vv.pocet*cena             │ Discízia šľachových pošiev prsta              │ vv.kod in ['5t7027']                                         │
│             331 │ vv.pocet*cena             │ Discízia šľachových pošiev palca              │ vv.kod in ['5t7028']                                         │
│             441 │ vv.pocet*cena             │ Primárna sutúra ohýbača prsta                 │ vv.kod in ['5t7051']                                         │
│             441 │ vv.pocet*cena             │ Primárna sutúra vystierača prsta              │ vv.kod in ['5t7054']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza ohýbača prsta                        │ vv.kod in ['5t7071']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza ohýbača palca                        │ vv.kod in ['5t7072']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza vystierača prsta                     │ vv.kod in ['5t7074']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza vystierača palca                     │ vv.kod in ['5t7075']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza šľachových pošiev prsta              │ vv.kod in ['5t7077']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza šľachových pošiev palca              │ vv.kod in ['5t7078']                                         │
│             309 │ vv.pocet*cena             │ Tenolýza šľachových pošiev dlane              │ vv.kod in ['5t7079']                                         │
│             392 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             392 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum          │ vv.kod in ['5t71110']                                        │
│             392 │ vv.pocet*cena             │ Prerušenie väzu retinaculum flexorum s epineu │ vv.kod in ['5t71111']                                        │
│                 │                           │ rolýzou n. medianus                           │                                                              │
│             392 │ vv.pocet*cena             │ Parciálna excízia retinaculum flexorum        │ vv.kod in ['5t7121']                                         │
│             287 │ vv.pocet*cena             │ Perkutánna fasciotómia jedného prsta          │ vv.kod in ['5t7211']                                         │
│             287 │ vv.pocet*cena             │ Perkutánna fasciotómia viac ako jedného prsta │ vv.kod in ['5t7212']                                         │
│             331 │ vv.pocet*cena             │ Parciálna fasciektómia izolovaná na dlani     │ vv.kod in ['5t7220']                                         │
│             331 │ vv.pocet*cena             │ Parciálna fasciektómia jedného alebo dvoch pr │ vv.kod in ['5t7223']                                         │
│                 │                           │ stov                                          │                                                              │
│             375 │ vv.pocet*cena             │ Totálna fasciektómia izolovaná na dlani       │ vv.kod in ['5t7230']                                         │
│             375 │ vv.pocet*cena             │ Totálna fasciektómia 3 a viac prstov          │ vv.kod in ['5t7234']                                         │
│             375 │ vv.pocet*cena             │ Fasciektómia jedného prsta s jednou neurolýzo │ vv.kod in ['5t7241']                                         │
│                 │                           │ u                                             │                                                              │
│             375 │ vv.pocet*cena             │ Fasciektómia viac prstov s jednou neurolýzou  │ vv.kod in ['5t7242']                                         │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) karpometakarpálneho kĺb │ vv.kod in ['5t7452']                                         │
│                 │                           │ u palca                                       │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálneho  │ vv.kod in ['5t7453']                                         │
│                 │                           │ kĺbu, jeden zákrok                            │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) metakarpofalangeálnych  │ vv.kod in ['5t7454']                                         │
│                 │                           │ kĺbov, viaceré zákroky                        │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálneho kĺbu │ vv.kod in ['5t7455']                                         │
│                 │                           │ ruky, jeden zákrok                            │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7456']                                         │
│                 │                           │ v jedného prsta ruky, viaceré zákroky         │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) interfalangeálnych kĺbo │ vv.kod in ['5t7457']                                         │
│                 │                           │ v viacerých prstov ruky, viaceré zákroky      │                                                              │
│             364 │ vv.pocet*cena             │ Uvoľnenie (artrolýza) ostatných kĺbov ruky    │ vv.kod in ['5t745x']                                         │
│             364 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t764']                                          │
│                 │                           │ ruky                                          │                                                              │
│             364 │ vv.pocet*cena             │ Jednotlivá artrodéza interfalangeálneho kĺbu  │ vv.kod in ['5t765']                                          │
│                 │                           │ ruky so spongioplastikou                      │                                                              │
│             364 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t766']                                          │
│                 │                           │ v ruky                                        │                                                              │
│             364 │ vv.pocet*cena             │ Viacpočetné artrodézy interfalangeálnych kĺbo │ vv.kod in ['5t767']                                          │
│                 │                           │ v ruky so spongioplastikou                    │                                                              │
│             364 │ vv.pocet*cena             │ Ostatné artrodézy kĺbov ruky                  │ vv.kod in ['5t76x']                                          │
│              66 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['5t790']                                          │
│             328 │ vv.pocet*cena             │ Incízia svalu priečne v oblasti ramena a lakť │ vv.kod in ['5t8012']                                         │
│                 │                           │ a                                             │                                                              │
│             328 │ vv.pocet*cena             │ Debridement šľachy v oblasti ramena a lakťa   │ vv.kod in ['5t80c2']                                         │
│             328 │ vv.pocet*cena             │ Ostatné incízie svalu, šľachy a fascie v obla │ vv.kod in ['5t80x2']                                         │
│                 │                           │ sti ramena a lakťa                            │                                                              │
│             328 │ vv.pocet*cena             │ Otvorená chirurgická tenotómia v oblasti rame │ vv.kod in ['5t8112']                                         │
│                 │                           │ na a lakťa                                    │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia pr │ vv.kod in ['5t815x']                                         │
│                 │                           │ iečna, ostatné                                │                                                              │
│             331 │ vv.pocet*cena             │ Otvorená chirurgická parciálna fasciotómia po │ vv.kod in ['5t818x']                                         │
│                 │                           │ zdĺžna, jeden segment, ostatné                │                                                              │
│             287 │ vv.pocet*cena             │ Perkutánna fasciotómia pozdĺžna, ostatné      │ vv.kod in ['5t81ax']                                         │
│             328 │ vv.pocet*cena             │ Parciálna excízia šľachy v oblasti ramena a l │ vv.kod in ['5t8202']                                         │
│                 │                           │ akťa                                          │                                                              │
│             328 │ vv.pocet*cena             │ Predĺženie šliach v oblasti ramena a lakťa    │ vv.kod in ['5t8402']                                         │
│             276 │ vv.pocet*cena             │ Transpozícia šliach, ostatné                  │ vv.kod in ['5t842x']                                         │
│             485 │ vv.pocet*cena             │ Reinzercia šľachy v oblasti predkolenia       │ vv.kod in ['5t8508']                                         │
│             441 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predlaktia   │ vv.kod in ['5t8513']                                         │
│             441 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti stehna a kol │ vv.kod in ['5t8517']                                         │
│                 │                           │ ena                                           │                                                              │
│             485 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti predkolenia  │ vv.kod in ['5t8518']                                         │
│             485 │ vv.pocet*cena             │ Primárna sutúra šľachy v oblasti nohy         │ vv.kod in ['5t8519']                                         │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti ramena a l │ vv.kod in ['5t8522']                                         │
│                 │                           │ akťa                                          │                                                              │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predlaktia │ vv.kod in ['5t8523']                                         │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti stehna a k │ vv.kod in ['5t8527']                                         │
│                 │                           │ olena                                         │                                                              │
│             485 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti predkoleni │ vv.kod in ['5t8528']                                         │
│                 │                           │ a                                             │                                                              │
│             485 │ vv.pocet*cena             │ Sekundárna sutúra šľachy v oblasti nohy       │ vv.kod in ['5t8529']                                         │
│             441 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8533']                                         │
│                 │                           │ dlaktia                                       │                                                              │
│             485 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti pre │ vv.kod in ['5t8538']                                         │
│                 │                           │ dkolenia                                      │                                                              │
│             441 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy v oblasti noh │ vv.kod in ['5t8539']                                         │
│                 │                           │ y                                             │                                                              │
│             441 │ vv.pocet*cena             │ Primárna sutúra šľachovej pošvy, ostatné      │ vv.kod in ['5t853x']                                         │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8543']                                         │
│                 │                           │ redlaktia                                     │                                                              │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti p │ vv.kod in ['5t8548']                                         │
│                 │                           │ redkolenia                                    │                                                              │
│             441 │ vv.pocet*cena             │ Sekundárna sutúra šľachovej pošvy v oblasti n │ vv.kod in ['5t8549']                                         │
│                 │                           │ ohy                                           │                                                              │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a axi │ vv.kod in ['5t8911']                                         │
│                 │                           │ ly                                            │                                                              │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti ramena a lak │ vv.kod in ['5t8912']                                         │
│                 │                           │ ťa                                            │                                                              │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predlaktia   │ vv.kod in ['5t8913']                                         │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti stehna a kol │ vv.kod in ['5t8917']                                         │
│                 │                           │ ena                                           │                                                              │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti predkolenia  │ vv.kod in ['5t8918']                                         │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy v oblasti nohy         │ vv.kod in ['5t8919']                                         │
│             364 │ vv.pocet*cena             │ Totálna resekcia burzy, ostatné               │ vv.kod in ['5t891x']                                         │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej o                                    │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              66 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['5t892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              66 │ vv.pocet*cena             │ Amputácia prsta ruky                          │ vv.kod in ['5t933']                                          │
│              66 │ vv.pocet*cena             │ Exartikulácia prsta ruky                      │ vv.kod in ['5t935']                                          │
│             309 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, jedna  │ vv.kod in ['5u1100']                                         │
│                 │                           │ lézia                                         │                                                              │
│             309 │ vv.pocet*cena             │ Excízia ihlou označenej lézie prsníka, viacpo │ vv.kod in ['5u1101']                                         │
│                 │                           │ četná lézia                                   │                                                              │
│             309 │ vv.pocet*cena             │ Excízia nádoru prsníka                        │ vv.kod in ['5u111']                                          │
│             309 │ vv.pocet*cena             │ Lumpektómia                                   │ vv.kod in ['5u112']                                          │
│             309 │ vv.pocet*cena             │ Mikroduktektómia prsníka                      │ vv.kod in ['5u114']                                          │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany                                     │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histo                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1440']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1444']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1445']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1446']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1447']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1448']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1449']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144a']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144b']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144d']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144e']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144f']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144g']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v144x']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1450']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1454']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1455']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1456']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1457']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1458']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1459']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145a']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145b']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145c']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145d']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145e']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145f']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145g']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v145x']                                         │
│                 │                           │ niva na koži a podkoží s transplantáciou aleb │                                                              │
│                 │                           │ o transpoz                                    │                                                              │
│             220 │ vv.pocet*cena             │ Totálna excízia nechta                        │ vv.kod in ['5v175']                                          │
│             220 │ vv.pocet*cena             │ Excízia poškodeného tkaniva nechtového lôžka  │ vv.kod in ['5v176']                                          │
│             220 │ vv.pocet*cena             │ Plastika nechta                               │ vv.kod in ['5v179']                                          │
│             220 │ vv.pocet*cena             │ Odstránenie nechtovej matrix                  │ vv.kod in ['5v17a']                                          │
│             375 │ vv.pocet*cena             │ Excízia sinus pilonidalis                     │ vv.kod in ['5v191']                                          │
│             375 │ vv.pocet*cena             │ Operačné odstránenie sinus pilonidalis, ostat │ vv.kod in ['5v193']                                          │
│                 │                           │ né                                            │                                                              │
│             375 │ vv.pocet*cena             │ Incízia sinus pilonidalis                     │ vv.kod in ['5v194']                                          │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2310']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti pery                                       │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2314']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ostat │                                                              │
│                 │                           │ ných častí                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2315']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti krku                                       │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2316']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena                                     │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2317']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ramena                                     │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2318']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predlak                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v2319']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti ruky                                       │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231a']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti hrudnej                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231b']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v brušn │                                                              │
│                 │                           │ ej oblasti                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231c']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v ingui │                                                              │
│                 │                           │ nálnej a g                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231d']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v glute │                                                              │
│                 │                           │ álnej obla                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231e']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti stehna                                     │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231f']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti predkol                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231g']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom v oblas │                                                              │
│                 │                           │ ti nohy (c                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, pl │ vv.kod in ['5v231x']                                         │
│                 │                           │ astika malej plochy rotovaným lalokom, ostatn │                                                              │
│                 │                           │ é                                             │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2320']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pe │                                                              │
│                 │                           │ ry                                            │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2324']                                         │
│                 │                           │ anspozičná plastika malej plochy v ostatných  │                                                              │
│                 │                           │ častiach h                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2325']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti kr │                                                              │
│                 │                           │ ku                                            │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2326']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a axi                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2327']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ra │                                                              │
│                 │                           │ mena a lak                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2328']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edlaktia                                      │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v2329']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti ru │                                                              │
│                 │                           │ ky                                            │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232a']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti hr │                                                              │
│                 │                           │ udnej sten                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232b']                                         │
│                 │                           │ anspozičná plastika malej plochy v brušnej ob │                                                              │
│                 │                           │ lasti                                         │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232c']                                         │
│                 │                           │ anspozičná plastika malej plochy v inguinálne │                                                              │
│                 │                           │ j a genitá                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232d']                                         │
│                 │                           │ anspozičná plastika malej plochy v gluteálnej │                                                              │
│                 │                           │ oblasti                                       │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232e']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti st │                                                              │
│                 │                           │ ehna a kol                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232f']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti pr │                                                              │
│                 │                           │ edkolenia                                     │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232g']                                         │
│                 │                           │ anspozičná plastika malej plochy v oblasti no │                                                              │
│                 │                           │ hy (chodid                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, tr │ vv.kod in ['5v232x']                                         │
│                 │                           │ anspozičná plastika malej plochy, ostatné     │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a0']                                         │
│                 │                           │ plastika malej plochy v oblasti pery          │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a4']                                         │
│                 │                           │ plastika malej plochy v ostatných častí hlavy │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a5']                                         │
│                 │                           │ plastika malej plochy v oblasti krku          │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a6']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a axil │                                                              │
│                 │                           │ y                                             │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a7']                                         │
│                 │                           │ plastika malej plochy v oblasti ramena a lakť │                                                              │
│                 │                           │ a                                             │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a8']                                         │
│                 │                           │ plastika malej plochy v oblasti predlaktia    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23a9']                                         │
│                 │                           │ plastika malej plochy v oblasti ruky          │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23aa']                                         │
│                 │                           │ plastika malej plochy v oblasti hrudnej steny │                                                              │
│                 │                           │ a chrbta                                      │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ab']                                         │
│                 │                           │ plastika malej plochy v brušnej oblasti       │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ac']                                         │
│                 │                           │ plastika malej plochy v inguinálnej a genitál │                                                              │
│                 │                           │ nej oblast                                    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ad']                                         │
│                 │                           │ plastika malej plochy v gluteálnej oblasti    │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ae']                                         │
│                 │                           │ plastika malej plochy v oblasti stehna a kole │                                                              │
│                 │                           │ na                                            │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23af']                                         │
│                 │                           │ plastika malej plochy v oblasti predkolenia   │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, W- │ vv.kod in ['5v23ag']                                         │
│                 │                           │ plastika malej plochy v oblasti nohy (chodidl │                                                              │
│                 │                           │ o)                                            │                                                              │
│             220 │ vv.pocet*cena             │ Lokálna laloková plastika kože a podkožia, os │ vv.kod in ['5v23xx']                                         │
│                 │                           │ tatné                                         │                                                              │
│             210 │ vv.pocet*cena             │ Excízia a exstirpácia hemangiómu na koži      │ vv.kod in ['5v482']                                          │
│             387 │ vv.pocet*cena             │ Laparoskopia bez otvorenia pneumoperitonea    │ vv.kod in ['5z1121']                                         │
│             242 │ vv.pocet*cena             │ Jednodňová ZS - Krytie defektov alebo korekci │ vv.kod in ['j0004']                                          │
│                 │                           │ a jazvy plastikou                             │                                                              │
│             276 │ vv.pocet*cena             │ Jednodňová ZS - Ošetrenie popáleniny v celkov │ vv.kod in ['j0005']                                          │
│                 │                           │ ej anestéze                                   │                                                              │
│             242 │ vv.pocet*cena             │ Biologická nekrektómia [Maggot therapy]       │ vv.kod in ['Kg210']                                          │
│             650 │ vv.pocet*cena             │ Prešitie varikozít na varikóznych žilách      │ vv.kod in ['Kl1901']                                         │
│             650 │ vv.pocet*cena             │ Lokálna excízia na varikóznych žilách         │ vv.kod in ['Kl1902']                                         │
│             650 │ vv.pocet*cena             │ Incízia varikozít na varikóznych žilách       │ vv.kod in ['Kl1903']                                         │
│             650 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['Kl19110']                                        │
│                 │                           │ nych žilách bez fasciotómie                   │                                                              │
│             650 │ vv.pocet*cena             │ Endoskopická ligatúra perforátorov na varikóz │ vv.kod in ['Kl19111']                                        │
│                 │                           │ nych žilách s fasciotómiou                    │                                                              │
│             650 │ vv.pocet*cena             │ Transkutánna ligatúra perforátorov na varikóz │ vv.kod in ['Kl1912']                                         │
│                 │                           │ nych žilách                                   │                                                              │
│             650 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['Kl1920']                                         │
│                 │                           │ magna                                         │                                                              │
│             650 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['Kl1921']                                         │
│                 │                           │ parva                                         │                                                              │
│             650 │ vv.pocet*cena             │ Crossektómia a parciálny stripping v. saphena │ vv.kod in ['Kl1922']                                         │
│                 │                           │ magna a parva                                 │                                                              │
│             650 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna      │ vv.kod in ['Kl1930']                                         │
│             650 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena parva      │ vv.kod in ['Kl1931']                                         │
│             650 │ vv.pocet*cena             │ Samostatná crossektómia v. saphena magna a pa │ vv.kod in ['Kl1932']                                         │
│                 │                           │ rva                                           │                                                              │
│             650 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna bez cros │ vv.kod in ['Kl1940']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             650 │ vv.pocet*cena             │ Odstránenie varixov v. saphena parva bez cros │ vv.kod in ['Kl1941']                                         │
│                 │                           │ sektómie                                      │                                                              │
│             650 │ vv.pocet*cena             │ Odstránenie varixov v. saphena magna a parva  │ vv.kod in ['Kl1942']                                         │
│                 │                           │ bez crossektómie                              │                                                              │
│             650 │ vv.pocet*cena             │ Odstránenie varixov nekmeňovej varikozity bez │ vv.kod in ['Kl1943']                                         │
│                 │                           │ crossektómie                                  │                                                              │
│             650 │ vv.pocet*cena             │ Odstránenie varixov bez crossektómie, ostatné │ vv.kod in ['Kl194x']                                         │
│             695 │ vv.pocet*cena             │ Termická ablácia VSM, VSP pomocou rádiofrekve │ vv.kod in ['Kl1951']                                         │
│                 │                           │ ncie, endovenózne pod sonografickou navigácio │                                                              │
│                 │                           │ u                                             │                                                              │
│             650 │ vv.pocet*cena             │ Endovenózna liečba perforátorov na varikóznyc │ vv.kod in ['Kl1955']                                         │
│                 │                           │ h žilách                                      │                                                              │
│             695 │ vv.pocet*cena             │ Rádioflekvenčná ablácia lokálnych varixov     │ vv.kod in ['Kl1957']                                         │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['Kn8100']                                         │
│                 │                           │ lastiky s vysokým podviazaním vaku hernie a č │                                                              │
│                 │                           │ iastočnou                                     │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['Kn8101']                                         │
│                 │                           │ lastiky s resekciou steny hydrokély           │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['Kn8102']                                         │
│                 │                           │ lastiky s funikulolýzou a dislokáciou semenní │                                                              │
│                 │                           │ ka                                            │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['Kn8103']                                         │
│                 │                           │ lastiky bez ďalších výkonov                   │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] bez p │ vv.kod in ['Kn810x']                                         │
│                 │                           │ lastiky, ostatné                              │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s pla │ vv.kod in ['Kn811']                                          │
│                 │                           │ stikou                                        │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s aut │ vv.kod in ['Kn812']                                          │
│                 │                           │ ológnym materiálom                            │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['Kn8130']                                         │
│                 │                           │ plastickým materiálom, laparotomicky          │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['Kn8132']                                         │
│                 │                           │ plastickým materiálom, endoskopicky, totálny  │                                                              │
│                 │                           │ extraperit                                    │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s alo │ vv.kod in ['Kn813x']                                         │
│                 │                           │ plastickým materiálom, ostatné                │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] s res │ vv.kod in ['Kn814']                                          │
│                 │                           │ ekciou čreva bez dodatočnej laparotómie       │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn8150']                                         │
│                 │                           │ ecidíve s plastikou bez funikulo-orchidolýzy  │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn8151']                                         │
│                 │                           │ ecidíve s plastikou s funikulo-orchidolýzou   │                                                              │
│             496 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn816']                                          │
│                 │                           │ ecidíve s autológnym materiálom               │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn8170']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, laparotom │                                                              │
│                 │                           │ icky                                          │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn8172']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, endoskopi │                                                              │
│                 │                           │ cky totáln                                    │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn817x']                                         │
│                 │                           │ ecidíve s aloplastickým materiálom, iný príst │                                                              │
│                 │                           │ up                                            │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn818']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, resekciou │                                                              │
│                 │                           │ čreva bez                                     │                                                              │
│             661 │ vv.pocet*cena             │ Uzavretie inguinálnej hernie [prietrže] pri r │ vv.kod in ['Kn81x']                                          │
│                 │                           │ ecidíve s aloplastickým materiálom, ostatné   │                                                              │
│             496 │ vv.pocet*cena             │ Resekcie (exostózy) os metatarsale I          │ vv.kod in ['Kt0800']                                         │
│             496 │ vv.pocet*cena             │ Resekcie (exostózy) článkov prstov nohy: digi │ vv.kod in ['Kt080a']                                         │
│                 │                           │ tus I                                         │                                                              │
│             496 │ vv.pocet*cena             │ Korektívna operácia mäkkých častí metatarzu a │ vv.kod in ['Kt0810']                                         │
│                 │                           │ článkov prstov nohy vo výške 1. metatarzofala │                                                              │
│                 │                           │ ngeálneho                                     │                                                              │
│             496 │ vv.pocet*cena             │ Osteotomia os metatarsale I                   │ vv.kod in ['Kt08201']                                        │
│             496 │ vv.pocet*cena             │ Osteotomia os metatarsale I, dvojitá osteotóm │ vv.kod in ['Kt08202']                                        │
│                 │                           │ ia                                            │                                                              │
│             496 │ vv.pocet*cena             │ Osteotomia článkov prstov nohy: digitus I     │ vv.kod in ['Kt0822a']                                        │
│             496 │ vv.pocet*cena             │ Artroplastika metatarzofalangeálneho kĺbu I   │ vv.kod in ['Kt0830']                                         │
│             496 │ vv.pocet*cena             │ Artrodéza priehlavku a stredonožia, 1 alebo 2 │ vv.kod in ['Kt3891']                                         │
│                 │                           │ kĺby                                          │                                                              │
│             496 │ vv.pocet*cena             │ Artrodézy metatarzofalangeálneho kĺbu palca n │ vv.kod in ['Kt38aa']                                         │
│                 │                           │ ohy                                           │                                                              │
│              83 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['Kt790']                                          │
│              83 │ vv.pocet*cena             │ Excízia gangliómu na ruke                     │ vv.kod in ['Kt790']                                          │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8920']                                         │
│                 │                           │ iách a burzách v oblasti hlavy a krku         │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8921']                                         │
│                 │                           │ iách a burzách v oblasti ramena a axily       │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8922']                                         │
│                 │                           │ iách a burzách v oblasti ramena a lakťa       │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8923']                                         │
│                 │                           │ iách a burzách v oblasti predlaktia           │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8924']                                         │
│                 │                           │ iách a burzách v oblasti hrudnej steny a chrb │                                                              │
│                 │                           │ ta                                            │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8925']                                         │
│                 │                           │ iách a burzách v oblasti brušnej steny        │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej o                                    │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8926']                                         │
│                 │                           │ iách a burzách v inguinálnej, genitálnej a gl │                                                              │
│                 │                           │ uteálnej o                                    │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8927']                                         │
│                 │                           │ iách a burzách v oblasti stehna a kolena      │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8928']                                         │
│                 │                           │ iách a burzách v oblasti predkolenia          │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt8929']                                         │
│                 │                           │ iách a burzách v oblasti nohy                 │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│              83 │ vv.pocet*cena             │ Resekcia gangliónu na svaloch, šľachách, fasc │ vv.kod in ['Kt892x']                                         │
│                 │                           │ iách a burzách, ostatné                       │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1500']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti p                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1504']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha o │                                                              │
│                 │                           │ statných č                                    │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1505']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti k                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1506']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti r                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1507']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti r                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1508']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti p                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv1509']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti r                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150a']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti h                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150b']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ brušnej o                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150c']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ inguináln                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150d']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ gluteálne                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150e']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti s                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150f']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti p                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150g']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha v │                                                              │
│                 │                           │ oblasti n                                     │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv150x']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, malá plocha,  │                                                              │
│                 │                           │ ostatné                                       │                                                              │
│             242 │ vv.pocet*cena             │ Chirurgické vyčistenie rany s odstránením cho │ vv.kod in ['Kv15xx']                                         │
│                 │                           │ rého tkaniva na koži a podkoží, ostatné       │                                                              │
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

