                                                                      ====================
                                                                      Cenník ped. urologia
                                                                      ====================

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
│              55 │ vv.pocet*cena             │ Perkutánna biopsia penisu s použitím zobrazov │ vv.kod in ['12o203']                                         │
│                 │                           │ acích metód                                   │                                                              │
│              55 │ vv.pocet*cena             │ Perkutánna (ihlová) biopsia penisu            │ vv.kod in ['12p103']                                         │
│              55 │ vv.pocet*cena             │ Biopsia s incíziou glans penis                │ vv.kod in ['13p010']                                         │
│             309 │ vv.pocet*cena             │ Diagnostická ureteroskopia                    │ vv.kod in ['14o01']                                          │
│              68 │ vv.pocet*cena             │ Diagnostická uretrocystoskopia                │ vv.kod in ['14o02']                                          │
│              68 │ vv.pocet*cena             │ Diagnostická uretrocystoskopia, stómický prís │ vv.kod in ['14o111']                                         │
│                 │                           │ tup                                           │                                                              │
│             309 │ vv.pocet*cena             │ Ureterorenoskopia                             │ vv.kod in ['14o301']                                         │
│              68 │ vv.pocet*cena             │ Cystoskopia                                   │ vv.kod in ['14o302']                                         │
│             331 │ vv.pocet*cena             │ Odstránenie konkrementu z obličky dezintegrác │ vv.kod in ['5o1336']                                         │
│                 │                           │ iou [litotripsia], ureterorenoskopicky        │                                                              │
│             309 │ vv.pocet*cena             │ Sondáž močovodu, transuretrálne antegrádne    │ vv.kod in ['5o242a']                                         │
│             309 │ vv.pocet*cena             │ Sondáž močovodu, transuretrálne retrográdne   │ vv.kod in ['5o242r']                                         │
│             331 │ vv.pocet*cena             │ Ureterotómia a odstránenie konkrementu pre ur │ vv.kod in ['5o2566']                                         │
│                 │                           │ eterolitiázu [litotripsia], ureterorenoskopic │                                                              │
│                 │                           │ ky                                            │                                                              │
│             220 │ vv.pocet*cena             │ Optická uretrotómia                           │ vv.kod in ['5o4111']                                         │
│             220 │ vv.pocet*cena             │ Transuretrálna incízia chorého tkaniva močove │ vv.kod in ['5o4301']                                         │
│                 │                           │ j rúry, vnútorná uretrotómia pod optickou kon │                                                              │
│                 │                           │ trolou                                        │                                                              │
│             242 │ vv.pocet*cena             │ Plastická meatotómia močovej rúry, meatoplast │ vv.kod in ['5o441']                                          │
│                 │                           │ ika                                           │                                                              │
│             242 │ vv.pocet*cena             │ Meatotómia                                    │ vv.kod in ['5o442']                                          │
│              55 │ vv.pocet*cena             │ Divulzia močovej rúry                         │ vv.kod in ['5o499']                                          │
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
│             242 │ vv.pocet*cena             │ Plastická rekonštrukcia hypospádie u muža, os │ vv.kod in ['5p55x']                                          │
│                 │                           │ tatné                                         │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c3201']                                         │
│                 │                           │ vou vlnou v močovode                          │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c3202']                                         │
│                 │                           │ vou vlnou v obličke                           │                                                              │
│             463 │ vv.pocet*cena             │ Litotripsia konkrementu extrakorporálnou rázo │ vv.kod in ['8c320x']                                         │
│                 │                           │ vou vlnou v iných orgánoch                    │                                                              │
│             463 │ vv.pocet*cena             │ Extrakorporálna litotripsia                   │ vv.kod in ['8c323']                                          │
│             231 │ vv.pocet*cena             │ Odstránenie bradavíc alebo porovnateľných kož │ vv.kod in ['8z211']                                          │
│                 │                           │ ných zmien                                    │                                                              │
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
│             220 │ vv.pocet*cena             │ Excízia karunkuly chorého tkaniva močovej rúr │ vv.kod in ['5o4201']                                         │
│                 │                           │ y                                             │                                                              │
│             387 │ vv.pocet*cena             │ Operácia hydrokély semenného povrazca         │ vv.kod in ['5p4030']                                         │
│             387 │ vv.pocet*cena             │ Operácia hydrokély testis                     │ vv.kod in ['5p4031']                                         │
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

