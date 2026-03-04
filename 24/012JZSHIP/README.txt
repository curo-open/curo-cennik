                                                                        ===============
                                                                        Cenník urologia
                                                                        ===============

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
│             111 │ vv.pocet*cena             │ Transuretrálna biopsia močového mechúra       │ vv.kod in ['12o012']                                         │
│             154 │ vv.pocet*cena             │ Perkutánna biopsia prostaty s použitím zobraz │ vv.kod in ['12o201']                                         │
│                 │                           │ ovacích metód                                 │                                                              │
│              55 │ vv.pocet*cena             │ Perkutánna biopsia penisu s použitím zobrazov │ vv.kod in ['12o203']                                         │
│                 │                           │ acích metód                                   │                                                              │
│             154 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia prostaty          │ vv.kod in ['12p101']                                         │
│              55 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia penisu            │ vv.kod in ['12p103']                                         │
│             154 │ vv.pocet*cena             │ Ihlová biopsia prostaty transrektálne, menej  │ vv.kod in ['12p3001']                                        │
│                 │                           │ ako 20 vzoriek                                │                                                              │
│             154 │ vv.pocet*cena             │ Ihlová biopsia prostaty transrektálne, 20 a v │ vv.kod in ['12p3002']                                        │
│                 │                           │ iac vzoriek                                   │                                                              │
│              55 │ vv.pocet*cena             │ Biopsia s incíziou glans penis                │ vv.kod in ['13p010']                                         │
│             309 │ vv.pocet*cena             │ Diagnostická ureteroskopia                    │ vv.kod in ['14o01']                                          │
│              68 │ vv.pocet*cena             │ Diagnostická uretrocystoskopia                │ vv.kod in ['14o02']                                          │
│              68 │ vv.pocet*cena             │ Diagnostická uretrocystoskopia, stómický prís │ vv.kod in ['14o111']                                         │
│                 │                           │ tup                                           │                                                              │
│             309 │ vv.pocet*cena             │ Ureterorenoskopia                             │ vv.kod in ['14o301']                                         │
│              68 │ vv.pocet*cena             │ Cystoskopia                                   │ vv.kod in ['14o302']                                         │
│             166 │ vv.pocet*cena             │ Nefrostómia punkčná                           │ vv.kod in ['5o1310']                                         │
│             331 │ vv.pocet*cena             │ Nefrostómia perkutánne                        │ vv.kod in ['5o1312']                                         │
│             331 │ vv.pocet*cena             │ Nefrostómia transplantovanej obličky, perkutá │ vv.kod in ['5o1313']                                         │
│                 │                           │ nne                                           │                                                              │
│             331 │ vv.pocet*cena             │ Odstránenie konkrementu z obličky dezintegrác │ vv.kod in ['5o1336']                                         │
│                 │                           │ iou [litotripsia], ureterorenoskopicky        │                                                              │
│             309 │ vv.pocet*cena             │ Sondáž močovodu, transuretrálne antegrádne    │ vv.kod in ['5o242a']                                         │
│             309 │ vv.pocet*cena             │ Sondáž močovodu, transuretrálne retrográdne   │ vv.kod in ['5o242r']                                         │
│             319 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['5o243r1']                                        │
│                 │                           │ u, transuretrálne retrográdne                 │                                                              │
│             319 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['5o243r2']                                        │
│                 │                           │ transuretrálne retrográdne                    │                                                              │
│             319 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['5o246r1']                                        │
│                 │                           │ u, perkutánne - transrenálne retrográdne      │                                                              │
│             319 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['5o246r2']                                        │
│                 │                           │ perkutánne-transrenálne retrográdne           │                                                              │
│             319 │ vv.pocet*cena             │ Odstránenie stentu z močovodu, retrográdne    │ vv.kod in ['5o247r']                                         │
│             331 │ vv.pocet*cena             │ Ureterotómia a odstránenie konkrementu pre ur │ vv.kod in ['5o2566']                                         │
│                 │                           │ eterolitiázu [litotripsia], ureterorenoskopic │                                                              │
│                 │                           │ ky                                            │                                                              │
│             220 │ vv.pocet*cena             │ Optická uretrotómia                           │ vv.kod in ['5o4111']                                         │
│             220 │ vv.pocet*cena             │ Transuretrálna incízia chorého tkaniva močove │ vv.kod in ['5o4301']                                         │
│                 │                           │ j rúry, vnútorná uretrotómia pod optickou kon │                                                              │
│                 │                           │ trolou                                        │                                                              │
│              55 │ vv.pocet*cena             │ Divulzia močovej rúry                         │ vv.kod in ['5o499']                                          │
│             408 │ vv.pocet*cena             │ Transvaginálna závesná operácia s použitím al │ vv.kod in ['5o9321']                                         │
│                 │                           │ oplastického materiálu bezťahová vaginálna pá │                                                              │
│                 │                           │ ska [TVT] alebo transobturatórna páska [TOT]  │                                                              │
│             377 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie, inguinálna  │ vv.kod in ['5p3010']                                         │
│                 │                           │ retencia semenníka                            │                                                              │
│             377 │ vv.pocet*cena             │ Orchiektómia bez epididymektómie skrotálne    │ vv.kod in ['5p3012']                                         │
│             377 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou, inguinálna r │ vv.kod in ['5p3020']                                         │
│                 │                           │ etencia semenníka                             │                                                              │
│             377 │ vv.pocet*cena             │ Orchiektómia s epididymektómiou skrotálne     │ vv.kod in ['5p3022']                                         │
│             377 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3050']                                         │
│                 │                           │ níka, inguinálne                              │                                                              │
│             377 │ vv.pocet*cena             │ Odstránenie zostávajúceho (solitárneho) semen │ vv.kod in ['5p3052']                                         │
│                 │                           │ níka, skrotálne                               │                                                              │
│             331 │ vv.pocet*cena             │ Orchiopexia s funikulolýzou                   │ vv.kod in ['5p311']                                          │
│             331 │ vv.pocet*cena             │ Orchiopexia skrotálne                         │ vv.kod in ['5p312']                                          │
│             331 │ vv.pocet*cena             │ Orchiopexia, ostatné                          │ vv.kod in ['5p31x']                                          │
│             387 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4020']                                         │
│                 │                           │ epny, inguinálne                              │                                                              │
│             387 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4021']                                         │
│                 │                           │ epny, otvorene mikrochirurgicky               │                                                              │
│             387 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4023']                                         │
│                 │                           │ epny, lumbálne                                │                                                              │
│             387 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['5p4024']                                         │
│                 │                           │ epny, laparoskopicky                          │                                                              │
│             364 │ vv.pocet*cena             │ Excízia cysty v oblasti nadsemenníka          │ vv.kod in ['5p411']                                          │
│             309 │ vv.pocet*cena             │ Parciálna epididymektómia                     │ vv.kod in ['5p421']                                          │
│             309 │ vv.pocet*cena             │ Totálna epididymektómia                       │ vv.kod in ['5p422']                                          │
│             309 │ vv.pocet*cena             │ Epididymektómia, ostatné                      │ vv.kod in ['5p42x']                                          │
│             309 │ vv.pocet*cena             │ Sklerotizácia semenovodu                      │ vv.kod in ['5p451']                                          │
│             309 │ vv.pocet*cena             │ Ligatúra semenovodu                           │ vv.kod in ['5p452']                                          │
│             309 │ vv.pocet*cena             │ Resekcia semenovodu [vazoresekcia]            │ vv.kod in ['5p453']                                          │
│             309 │ vv.pocet*cena             │ Deštrukcia, ligatúra a resekcia semenovodu, o │ vv.kod in ['5p45x']                                          │
│                 │                           │ statné                                        │                                                              │
│             231 │ vv.pocet*cena             │ Frenulotómia predkožky                        │ vv.kod in ['5p501']                                          │
│             298 │ vv.pocet*cena             │ Dorzálne preťatie predkožky                   │ vv.kod in ['5p502']                                          │
│             298 │ vv.pocet*cena             │ Cirkumcízia                                   │ vv.kod in ['5p503']                                          │
│             231 │ vv.pocet*cena             │ Frenuloplastika a plastika predkožky          │ vv.kod in ['5p504']                                          │
│             188 │ vv.pocet*cena             │ Krvavá repozícia na predkožke pre parafimózu  │ vv.kod in ['5p5051']                                         │
│                 │                           │ v celkovej anestézii                          │                                                              │
│             188 │ vv.pocet*cena             │ Nekrvavá repozícia na predkožke pre parafimóz │ vv.kod in ['5p5052']                                         │
│                 │                           │ u v celkovej anestézii                        │                                                              │
│             188 │ vv.pocet*cena             │ Uvoľnenie prepuciálnych zrastov na predkožke  │ vv.kod in ['5p506']                                          │
│                 │                           │ [synechiolýza]                                │                                                              │
│             188 │ vv.pocet*cena             │ Operácie na predkožke, ostatné                │ vv.kod in ['5p509']                                          │
│             231 │ vv.pocet*cena             │ Lokálna excízia chorého tkaniva penisu        │ vv.kod in ['5p511']                                          │
│             231 │ vv.pocet*cena             │ Lokálna deštrukcia chorého tkaniva penisu     │ vv.kod in ['5p512']                                          │
│             231 │ vv.pocet*cena             │ Lokálna excízia a deštrukcia chorého tkaniva  │ vv.kod in ['5p51x']                                          │
│                 │                           │ penisu, ostatné                               │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1300']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti pery                             │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1304']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny ostatných častí hlavy                      │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1305']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti krku                             │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1306']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a axily                   │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1307']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ramena a lakťa                   │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1308']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predlaktia                       │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1309']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti ruky                             │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130a']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti hrudnej steny a chrbta           │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130b']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v brušnej oblasti                          │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130d']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v gluteálnej oblasti                       │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130e']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti stehna a kolena                  │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130f']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti predkolenia                      │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130g']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny v oblasti nohy (chodidlo)                  │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v130x']                                         │
│                 │                           │ na koži a podkoží bez primárneho uzavretia ra │                                                              │
│                 │                           │ ny, ostatné                                   │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1310']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti pery                                │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1314']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ ostatných častí hlavy                         │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1315']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti krku                                │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1316']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a axily                      │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1317']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ramena a lakťa                      │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1318']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predlaktia                          │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v1319']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti ruky                                │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131a']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti hrudnej steny a chrbta              │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131b']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v brušnej oblasti                             │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131d']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v gluteálnej oblasti                          │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131e']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti stehna a kolena                     │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131f']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti predkolenia                         │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131g']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ v oblasti nohy (chodidlo)                     │                                                              │
│              55 │ vv.pocet*cena             │ Lokálne operačné odstránenie chorého tkaniva  │ vv.kod in ['5v131x']                                         │
│                 │                           │ na koži a podkoží s primárnym uzavretím rany  │                                                              │
│                 │                           │ , ostatné                                     │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1400']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti pery                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1404']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany ostatných častí hlavy                 │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1405']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti krku                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1406']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a axily              │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1407']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ramena a lakťa              │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1408']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predlaktia                  │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1409']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti ruky                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti hrudnej steny a chrbta      │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v brušnej oblasti                     │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v gluteálnej oblasti                  │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti stehna a kolena             │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti predkolenia                 │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany v oblasti nohy (chodidlo)             │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v140x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany, ostatné                              │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1410']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ ery                                           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1414']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované ostatných č │                                                              │
│                 │                           │ astí hlavy                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1415']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti k │                                                              │
│                 │                           │ rku                                           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1416']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a axily                                 │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1417']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ amena a lakťa                                 │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1418']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redlaktia                                     │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1419']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti r │                                                              │
│                 │                           │ uky                                           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141a']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti h │                                                              │
│                 │                           │ rudnej steny a chrbta                         │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141b']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v brušnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141c']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v inguináln │                                                              │
│                 │                           │ ej a genitálnej oblasti                       │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141d']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v gluteálne │                                                              │
│                 │                           │ j oblasti                                     │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141e']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti s │                                                              │
│                 │                           │ tehna a kolena                                │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141f']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti p │                                                              │
│                 │                           │ redkolenia                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141g']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované v oblasti n │                                                              │
│                 │                           │ ohy (chodidlo)                                │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v141x']                                         │
│                 │                           │ niva na koži a podkoží bez primárneho uzavret │                                                              │
│                 │                           │ ia rany histologicky kontrolované, ostatné    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1420']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti pery                      │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1424']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany ostatných častí hlavy               │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1425']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti krku                      │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1426']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a axily            │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1427']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ramena a lakťa            │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1428']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predlaktia                │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1429']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti ruky                      │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti hrudnej steny a chrbta    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142b']                                         │
│                 │                           │ niva na koži a podkoží s  s primárnym uzavret │                                                              │
│                 │                           │ ím rany rany v buršnej oblasti                │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v gluteálnej oblasti                │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti stehna a kolena           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti predkolenia               │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany v oblasti nohy (chodidlo)           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v142x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany rany, ostatné                            │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1430']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pery │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1434']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované ostatných čast │                                                              │
│                 │                           │ í hlavy                                       │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1435']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti krku │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1436']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a axily                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1437']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti rame │                                                              │
│                 │                           │ na a lakťa                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1438']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ laktia                                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v1439']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti ruky │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143a']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti hrud │                                                              │
│                 │                           │ nej steny a chrbta                            │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143b']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v brušnej obla │                                                              │
│                 │                           │ sti                                           │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143d']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v gluteálnej o │                                                              │
│                 │                           │ blasti                                        │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143e']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti steh │                                                              │
│                 │                           │ na a kolena                                   │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143f']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti pred │                                                              │
│                 │                           │ kolenia                                       │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143g']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované v oblasti nohy │                                                              │
│                 │                           │ (chodidlo)                                    │                                                              │
│              55 │ vv.pocet*cena             │ Radikálne a rozsiahle odstránenie chorého tka │ vv.kod in ['5v143x']                                         │
│                 │                           │ niva na koži a podkoží s primárnym uzavretím  │                                                              │
│                 │                           │ rany histologicky kontrolované, ostatné       │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c3201']                                         │
│                 │                           │ vou vlnou v močovode                          │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c3202']                                         │
│                 │                           │ vou vlnou v obličke                           │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c320x']                                         │
│                 │                           │ vou vlnou v iných orgánoch                    │                                                              │
│             463 │ vv.pocet*cena             │ Extrakorporálna litotripsia                   │ vv.kod in ['8c323']                                          │
│             166 │ vv.pocet*cena             │ Perkutánna terapeutická punkcia a aspirácia o │ vv.kod in ['8f3041']                                         │
│                 │                           │ bličkovej panvičky                            │                                                              │
│             231 │ vv.pocet*cena             │ Odstránenie bradavíc alebo porovnateľných kož │ vv.kod in ['8z211']                                          │
│                 │                           │ ných zmien                                    │                                                              │
│             387 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['ko243r1']                                        │
│                 │                           │ u, transuretrálne retrográdne                 │                                                              │
│             387 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['ko243r2']                                        │
│                 │                           │ transuretrálne retrográdne                    │                                                              │
│             387 │ vv.pocet*cena             │ Zavedenie trvalého kovového stentu do močovod │ vv.kod in ['ko246r1']                                        │
│                 │                           │ u, perkutánne - transrenálne retrográdne      │                                                              │
│             387 │ vv.pocet*cena             │ Zavedenie iného trvalého stentu do močovodu,  │ vv.kod in ['ko246r2']                                        │
│                 │                           │ perkutánne-transrenálne retrográdne           │                                                              │
│             387 │ vv.pocet*cena             │ Odstránenie stentu z močovodu, retrográdne    │ vv.kod in ['ko247r']                                         │
│             387 │ vv.pocet*cena             │ Implantácia double pigtailu do močových ciest │ vv.kod in ['ko29a']                                          │
│             387 │ vv.pocet*cena             │ Implantácia stentu do močových ciest          │ vv.kod in ['ko29b']                                          │
│             408 │ vv.pocet*cena             │ Orchiopexia s funikulolýzou                   │ vv.kod in ['kp311']                                          │
│             408 │ vv.pocet*cena             │ Orchiopexia skrotálne                         │ vv.kod in ['kp312']                                          │
│             408 │ vv.pocet*cena             │ Orchiopexia, ostatné                          │ vv.kod in ['kp31x']                                          │
│             518 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['kp4020']                                         │
│                 │                           │ epny, inguinálne                              │                                                              │
│             518 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['kp4021']                                         │
│                 │                           │ epny, otvorene mikrochirurgicky               │                                                              │
│             518 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['kp4023']                                         │
│                 │                           │ epny, lumbálne                                │                                                              │
│             518 │ vv.pocet*cena             │ Resekcia testikulárnej žily a testikulárnej t │ vv.kod in ['kp4024']                                         │
│                 │                           │ epny, laparoskopicky                          │                                                              │
│             419 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['kp403']                                          │
│             419 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['kp404']                                          │
│             319 │ vv.pocet*cena             │ Implantácia double pigtailu do močových ciest │ vv.kod in ['5o29d3']                                         │
│             319 │ vv.pocet*cena             │ Implantácia stentu do močových ciest          │ vv.kod in ['5o29d4']                                         │
│             220 │ vv.pocet*cena             │ Excízia karunkuly chorého tkaniva močovej rúr │ vv.kod in ['5o4201']                                         │
│                 │                           │ y                                             │                                                              │
│             552 │ vv.pocet*cena             │ Transuretrálna endoresekcia tkaniva prostaty, │ vv.kod in ['5p14c']                                          │
│                 │                           │ intersticiálna laserová deštrukcia            │                                                              │
│             552 │ vv.pocet*cena             │ Transuretrálna endoresekcia tkaniva prostaty, │ vv.kod in ['5p14d']                                          │
│                 │                           │ vizuálne kontrolovaná laserová ablácia [VLAP] │                                                              │
│             552 │ vv.pocet*cena             │ Transuretrálna endoresekcia tkaniva prostaty, │ vv.kod in ['5p14e']                                          │
│                 │                           │ laserová vaporizácia prostaty                 │                                                              │
│             552 │ vv.pocet*cena             │ Transuretrálna endoresekcia tkaniva prostaty, │ vv.kod in ['5p14f']                                          │
│                 │                           │ laserová deštrukcia iná                       │                                                              │
│             387 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['5p4030']                                         │
│             387 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['5p4031']                                         │
│             331 │ vv.pocet*cena             │ Výmena nefrostomického katétra                │ vv.kod in ['8d130']                                          │
│             377 │ vv.pocet*cena             │ Radikálna orchiektómia s epididymektómiou a o │ vv.kod in ['5p3071']                                         │
│                 │                           │ dstránením "spermatic cord"                   │                                                              │
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

