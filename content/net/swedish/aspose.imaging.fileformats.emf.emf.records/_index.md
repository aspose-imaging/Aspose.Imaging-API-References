---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging för .NET API-referens
description: Namnutrymmet innehåller typer MS-EMF Enhanced Metafile Format. 2.3 EMF Records
type: docs
weight: 360
url: /sv/aspose.imaging.fileformats.emf.emf.records/
---
Namnutrymmet innehåller typer [MS-EMF]: Enhanced Metafile Format. 2.3 EMF Records

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Denna post avbryter en sökvägsparentes eller kasserar sökvägen från en stängd sökvägsparentes. |
| [EmfAlphaBlend](./emfalphablend) | EMR_ALPHABLEND-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, inklusive alfatransparensdata, enligt en specificerad blandningsoperation. |
| [EmfAngleArc](./emfanglearc) | EMR_ANGLEARC-posten specificerar ett linjesegment av en båge. Linjesegmentet ritas från den aktuella positionen till början av bågen. Bågen ritas längs omkretsen av en cirkel med given radie och centrum. Längden på bågen definieras av de givna start- och svepvinklarna |
| [EmfArc](./emfarc) | EMR_ARC-posten anger en elliptisk båge. |
| [EmfArcTo](./emfarcto) | EMR_ARCTO-posten specificerar en elliptisk båge. Den återställer den aktuella positionen till bågens slutpunkt. |
| [EmfBeginPath](./emfbeginpath) | Den här posten öppnar en sökvägsparentes i den aktuella uppspelningsenhetens kontext. När en sökvägsparentes är öppen kan en applikation börja bearbeta poster för att definiera punkterna som ligger i sökvägen. En applikation MÅSTE stänga en öppen sökvägsparentes genom att bearbeta EMR_ENDPATH record. När en applikation bearbetar EMR_BEGINPATH-posten MÅSTE alla tidigare sökvägar kasseras från uppspelningsenhetskontexten. |
| [EmfBitBlt](./emfbitblt) | EMR_BITBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett borstmönster, enligt en specificerad rasteroperation. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | Bitmappsposttyperna utför blocköverföringar av bitmappsbilder. |
| [EmfChord](./emfchord) | EMR_CHORD-posten specificerar ett ackord, vilket är ett område som begränsas av skärningspunkten mellan en ellips och ett linjesegment, som kallas en sekant. Ackordet beskrivs med hjälp av den aktuella pennan och fylls med hjälp av den aktuella penseln. |
| [EmfClippingRecordType](./emfclippingrecordtype) | Urklippsposttyperna anger och hanterar urklippsregioner. Obs EMR_SETMETARGN-posten anger inga parametrar. |
| [EmfCloseFigure](./emfclosefigure) | Denna post stänger en öppen figur i en bana. Bearbetning av EMR_CLOSEFIGURE-posten MÅSTE stänga figuren genom att rita en line från den aktuella positionen till den första punkten i figuren, och sedan MÅSTE den ansluta linjerna genom att använda linjekopplingsstilen. Om en figur stängs genom att bearbeta EMR_LINETO-posten istället för EMR_CLOSEFIGURE-posten, används ändkapslar för att skapa hörnet istället för en join.EMR_LINETO specificeras i avsnitt 2.3.5.13. Den enda posten som EMR_CLOSHOULD används om det finns en EMR_CLOSHOULD öppen sökväg hakparentes i uppspelningsenhetens sammanhang. En figur i en sökväg är öppen om den inte uttryckligen stängs genom att bearbeta denna post. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | EMR_COLORCORRECTPALETTE-posten anger hur man korrigerar inmatningarna för ett logiskt palette -objekt med hjälp av WCS 1.0-värden. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | EMR_COLORMATCHTOTargetW-posten anger om färgmatchning ska utföras med en color -profil som anges i en fil med ett namn som består av Unicode-tecken. |
| [EmfComment](./emfcomment) | EMR_COMMENT-posten innehåller godtyckliga privata data. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | EMR_COMMENT_BEGINGROUP-posten anger början av en grupp ritningsposter. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | EMR_COMMENT_EMFPLUS-posten innehåller inbäddade EMF+-poster. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | EMR_COMMENT_EMFSPOOL-posten innehåller inbäddade EMFSPOOL-poster. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup) | EMR_COMMENT_ENDGROUP-posten anger slutet på en grupp ritningsposter. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | EMR_COMMENT_MULTIFORMATS-posten anger en bild i flera grafikformat. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | EMR_COMMENT_PUBLIC-posttyperna anger tillägg till EMF-bearbetning. |
| [EmfCommentRecordType](./emfcommentrecordtype) | Kommentarposttyperna definierar format för att specificera godtyckliga privata data, bädda in poster i andra metafilformat och lägga till nya eller speciella kommandon. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | EMR_COMMENT_WINDOWS_METAFILE-posten anger en bild i en inbäddad WMF-metafil. |
| [EmfControlRecordType](./emfcontrolrecordtype) | Kontrollposttyperna definierar början och slutet av en EMF-metafil och egenskaperna för metafilen. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | EMR_CREATEBRUSHINDIRECT-posten definierar en logisk pensel för grafikoperationer. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | EMR_CREATECOLORSPACE-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett -namn som består av ASCII-tecken. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | EMR_CREATECOLORSPACEW-posten skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn som består av Unicode-tecken. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | EMR_CREATEDIBPATTERNBRUSHPT-posten definierar en mönsterpensel för grafikoperationer. Mönstret specificeras av en DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | EMR_CREATEMONOBRUSH-posten definierar en monokrom mönsterpensel för grafikoperationer. Mönstret specificeras av en monokrom DIB. |
| [EmfCreatePalette](./emfcreatepalette) | EMR_CREATEPALETTE-posten definierar en logisk palett för grafikoperationer. |
| [EmfCreatePen](./emfcreatepen) | EMR_CREATEPEN-posten definierar en logisk penna för grafikoperationer. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | EMR_DELETECOLORSPACE-posten tar bort ett logiskt färgrymdsobjekt. |
| [EmfDeleteObject](./emfdeleteobject) | EMR_DELETEOBJECT-posten tar bort ett grafikobjekt, vilket specificeras av dess index i EMF-objekttabellen (avsnitt 3.1.1.1). |
| [EmfDrawEscape](./emfdrawescape) | EMR_DRAWESCAPE-posten skickar godtycklig information till en skrivardrivrutin. Avsikten är att informationen ska resultera i att ritningen görs. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | Ritningsposttyperna utför grafikritning. |
| [EmfEllipse](./emfellipse) | EMR_ELLIPSE-posten anger en ellips. Ellipsens mitt är mitten av den angivna gränsrektangeln. Ellipsen kontureras med hjälp av den aktuella pennan och fylls med den aktuella borsten. |
| [EmfEndPath](./emfendpath) | Denna post stänger en sökvägsparentes och väljer den sökväg som definieras av hakparentesen in i uppspelningsenhetens sammanhang. |
| [EmfEof](./emfeof) | EMR_EOF-posten indikerar slutet av metafilen och anger en palett. |
| [EmfEscapeRecordType](./emfescaperecordtype) | Escape-posttyperna kör skrivardrivrutinens funktioner. |
| [EmfExcludeClipRect](./emfexcludecliprect) | EMR_EXCLUDECLIPRECT-posten anger ett nytt klippområde som består av det befintliga klippområdet minus den angivna rektangeln. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | EMR_EXTCREATEFONTINDIRECTW-posten definierar ett logiskt teckensnitt för grafikoperationer. |
| [EmfExtCreatePen](./emfextcreatepen) | EMR_EXTCREATEPEN-posten definierar en utökad logisk penna för grafikoperationer. An valfri DIB kan anges för att användas som linjestil. |
| [EmfExtEscape](./emfextescape) | EMR_EXTESCAPE-posten skickar godtycklig information till en skrivardrivrutin. Avsikten är att informationen inte kommer att resultera i att ritningen görs. |
| [EmfExtFloodFill](./emfextfloodfill) | EMR_EXTFLOODFILL-posten fyller ett område av visningsytan med den aktuella borsten |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | EMR_EXTSELECTCLIPRGN-posten kombinerar den angivna regionen med den aktuella klippregionen med det angivna läget. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta) | EMR_EXTTEXTOUTA-posten ritar en ASCII-textsträng med nuvarande teckensnitt och textfärger. |
| [EmfExtTextOutW](./emfexttextoutw) | EMR_EXTTEXTOUTW-posten ritar en ASCII-textsträng med nuvarande teckensnitt och textfärger. |
| [EmfFillPath](./emffillpath) | EMR_FILLPATH-posten stänger alla öppna figurer i den aktuella banan och fyller banans inre med med det aktuella borst- och polygonfyllningsläget. |
| [EmfFillRgn](./emffillrgn) | EMR_FILLRGN-posten fyller den angivna regionen genom att använda den angivna penseln. |
| [EmfFlatternPath](./emfflatternpath) | Denna post omvandlar alla kurvor i den valda banan till uppspelningsenhet -kontexten; varje kurva MÅSTE omvandlas till en rad rader. |
| [EmfForceUfiMapping](./emfforceufimapping) | EMR_FORCEUFIMAPPING-posten tvingar teckensnittsmapparen att matcha teckensnitt baserat på deras UniversalFontId framför deras LogFont-information (avsnitt 2.2.13). |
| [EmfFrameRgn](./emfframergn) | EMR_FRAMERGN-posten ritar en kant runt det angivna området med den angivna penseln. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | EMR_GLSBOUNDEDRECORD-posten anger en OpenGL-funktion med en begränsningsrektangel för utdata. |
| [EmfGlsRecord](./emfglsrecord) | EMR_GLSRECORD-posten anger en OpenGL-funktion. |
| [EmfGradientFill](./emfgradientfill) | EMR_GRADIENTFILL-posten specificerar fyllningsrektanglar eller trianglar med färggradienter. |
| [EmfIntersectClipRect](./emfintersectcliprect) | EMR_INTERSECTCLIPRECT-posten specificerar ett nytt klippområde från skärningspunkten mellan den nuvarande klippningsregionen och den angivna rektangeln. Obs Fält som inte beskrivs i detta avsnitt specificeras i avsnitt 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn) | EMR_INVERTRGN-posten inverterar färgerna i det angivna området. |
| [EmfLineTo](./emflineto) | EMR_LINETO-posten specificerar en linje från den aktuella positionen upp till, men inte inklusive, den specificerade punkten. Den återställer den aktuella positionen till den specificerade punkten. |
| [EmfMaskBlt](./emfmaskblt) | EMR_MASKBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett penselmönster och med applicering av en färgmask bitmapp, enligt specificerade förgrunds- och bakgrundsrasteroperationer. |
| [EmfMetafileHeader](./emfmetafileheader) | EMR_HEADER-posttyperna definierar startpunkterna för EMF-metafiler och anger egenskaperna för enheten på vilken bilden i metafilen skapades. Informationen i rubrikposten gör det möjligt för EMF-metafiler att vara oberoende av någon specifik utenhet. Värdet i fältet Storlek kan användas för att skilja mellan de olika EMR_HEADER-posttyperna som listats tidigare i detta avsnitt. Det finns tre möjliga headers: Bashuvudet, som är EmfMetafileHeader-posten. Den fasta delen av denna rubrik är 88 byte, och den innehåller ett Header-objekt. Det första tilläggshuvudet, som är EmfMetafileHeaderExtension1-posten._The-s00 en del av denna rubrik är 100 byte, och den innehåller ett Header-objekt och ett HeaderExtension1-objekt (avsnitt 2.2.10). Det andra tilläggshuvudet, som är EmfMetafileHeaderExtension2-posten. Delen med fast storlek av denna rubrik är, 108 bytes och det innehåller ett Header-objekt, ett HeaderExtension1-objekt och ett HeaderExtension2-objekt (avsnitt 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | EmfMetafileHeaderExtension1-posten är rubrikposten som används i det första tillägget till EMF-metafiler. Efter fältet EmfHeaderExtension1 är de återstående fälten valfria och kan finnas i valfri ordning. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | EmfMetafileHeaderExtension2-posten är rubrikposten som används i det andra tillägget till EMF metafiler. Efter fältet EmfHeaderExtension2 är de återstående fälten valfria och kan finnas i valfri ordning. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | EMR_MODIFYWORLDTRANSFORM-posten ändrar det aktuella världsutrymmet till sidutrymme transformation i uppspelningsenhetskontexten. |
| [EmfMoveToEx](./emfmovetoex) | EMR_MOVETOEX-posten anger koordinater för den nya aktuella positionen, i logiska enheter. |
| [EmfNamedEscape](./emfnamedescape) | MR_NAMEDESCAPE-posten skickar godtycklig information till en angiven skrivardrivrutin. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | Posttyperna för objektskapande skapar grafikobjekt. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | Objektmanipuleringsposttyperna hanterar och ändrar grafikobjekt. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | EMR_OFFSETCLIPRGN-posten flyttar det aktuella klippområdet i uppspelningsenhetskontexten med de angivna förskjutningarna. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | OpenGL-posttyperna anger OpenGL-funktioner. |
| [EmfPaintRgn](./emfpaintrgn) | EMR_PAINTRGN-posten målar den angivna regionen genom att använda penseln som för närvarande är vald i uppspelningsenhetskontexten. |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | Posttyperna för sökvägsparentes anger och manipulerar sökvägar inom sökvägsparenteser. Obs! Ingen av posterna för sökvägsparentes anger parametrar. |
| [EmfPie](./emfpie) | EMR_PIE-posten specificerar en pajformad kil som begränsas av skärningspunkten mellan en ellips och två radialer. Pajen kontureras med hjälp av den aktuella pennan och fylls med den aktuella penseln. |
| [EmfPixelFormat](./emfpixelformat) | EMR_PIXELFORMAT-posten anger pixelformatet som ska användas för grafikoperationer. |
| [EmfPlgBlt](./emfplgblt) | EMR_PLGBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till ett mål parallellogram, med tillämpning av en färgmaskbitmapp. |
| [EmfPolyBezier](./emfpolybezier) | EMR_POLYBEZIER-posten specificerar en eller flera Bezier-kurvor. |
| [EmfPolyBezier16](./emfpolybezier16) | EMR_POLYBEZIER16-posten specificerar en eller flera Bezier-kurvor. Kurvorna ritas med den nuvarande pennan. |
| [EmfPolyBezierTo](./emfpolybezierto) | EMR_POLYBEZIERTO-posten specificerar en eller flera Bezier-kurvor baserat på den aktuella positionen. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | EMR_POLYBEZIERTO16-posten specificerar en eller flera Bezier-kurvor baserat på den aktuella positionen. |
| [EmfPolyDraw](./emfpolydraw) | EMR_POLYDRAW-posten specificerar en uppsättning linjesegment och Bezier-kurvor. |
| [EmfPolyDraw16](./emfpolydraw16) | EMR_POLYDRAW16-posten specificerar en uppsättning linjesegment och Bezier-kurvor. |
| [EmfPolygon](./emfpolygon) | EMR_POLYGON-posten anger en polygon som består av två eller flera hörn sammankopplade med raka linjer. |
| [EmfPolygon16](./emfpolygon16) | EMR_POLYGON16-posten specificerar en polygon som består av två eller flera hörn sammankopplade med räta linjer. Polygonen skisseras genom att använda den aktuella pennan och fylls med den aktuella penseln och polygonfyllningsläget. Polygonen stängs automatiskt genom att dra en linje från den sista hörn till den första. |
| [EmfPolyline](./emfpolyline) | EMR_POLYLINE-posten specificerar en serie linjesegment genom att koppla ihop punkterna i den specificerade arrayen. |
| [EmfPolyline16](./emfpolyline16) | EMR_POLYLINE16-posten specificerar en serie linjesegment genom att ansluta punkterna i den specificerade arrayen. |
| [EmfPolylineTo](./emfpolylineto) | EMR_POLYLINETO-posten specificerar en eller flera räta linjer baserat på den aktuella positionen. |
| [EmfPolylineTo16](./emfpolylineto16) | EMR_POLYLINETO16-posten specificerar en eller flera räta linjer baserat på den aktuella positionen. En linje dras från den aktuella positionen till den första punkten som anges av aPoints-fältet med hjälp av den aktuella pennan. För varje ytterligare linje ritas från slutpunkten för föregående -linje till nästa punkt som specificeras av aPoints. |
| [EmfPolyPolygon](./emfpolypolygon) | EMR_POLYPOLYGON-posten anger en serie slutna polygoner. |
| [EmfPolyPolygon16](./emfpolypolygon16) | EMR_POLYPOLYGON16-posten specificerar en serie slutna polygoner. Varje polygon är skisserad med den aktuella pennan och fylld med det aktuella borst- och polygonfyllningsläget. Polygonerna som ritas av denna post kan överlappa varandra. |
| [EmfPolyPolyline](./emfpolypolyline) | EMR_POLYPOLYLINE-posten specificerar flera serier av anslutna linjesegment. |
| [EmfPolyPolyline16](./emfpolypolyline16) | EMR_POLYPOLYLINE16-posten specificerar flera serier av anslutna linjesegment. |
| [EmfPolyTextOutA](./emfpolytextouta) | EMR_POLYTEXTOUTA-posten ritar en eller flera ASCII-textsträngar med nuvarande teckensnitt och textfärger. |
| [EmfPolyTextOutW](./emfpolytextoutw) | EMR_POLYTEXTOUTW-posten ritar en eller flera Unicode-textsträngar med nuvarande teckensnitt och textfärger. |
| [EmfRealizePalette](./emfrealizepalette) | Denna post mappar palettposter från current LogPalette-objektet (avsnitt 2.2.17) till system_palette. Denna EMF-post specificerar inga parametrar. |
| [EmfRecord](./emfrecord) | Basklass för EMF-poster Alla EMF-poster MÅSTE ha en längd som är en multipel av 4 byte. Detta avbildas i de generiska strukturerna för de föregående EMF-posttyperna genom att inkludera AlignmentPadding fields där så är lämpligt i ändarna av dessa strukturer. Innehållet i AlignmentPadding fields MÅSTE alltid ignoreras. För korthetens skull visas inte dessa fält i varje enskild EMF -postdefinition. |
| [EmfRectangle](./emfrectangle) | EMR_RECTANGLE-posten ritar en rektangel. Rektangeln skisseras genom att använda den aktuella pennan och fylls med den aktuella penseln. |
| [EmfResizePalette](./emfresizepalette) | EMR_RESIZEPALETTE-posten ökar eller minskar storleken på ett befintligt LogPalette-objekt (avsnitt 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | EMR_RESTOREDC-posten återställer uppspelningsenhetskontexten till det angivna tillståndet. Uppspelningsenhetskontexten återställs genom att tillståndsinformationen öppnas från en stack som skapades av tidigare EMR_SAVEDC-poster (avsnitt 2.3.11). |
| [EmfRop4](./emfrop4) | En kvartär rasteroperation, som specificerar ternära rasteroperationer för förgrunds- och bakgrundsfärgerna i en bitmapp. Dessa värden definierar hur färgdata för källrektangeln ska kombineras med färgdata för destinationsrektangeln. |
| [EmfRoundRect](./emfroundrect) | EMR_ROUNDRECT-posten anger en rektangel med rundade hörn. Rektangeln är konturerad med hjälp av den aktuella pennan och fylls med den aktuella penseln. |
| [EmfSaveDc](./emfsavedc) | Sparar det aktuella tillståndet för uppspelningsenhetskontext på en hög med tillstånd som sparats av föregående EMR_SAVEDC -poster, om några. Tillståndet består av grafikegenskaper och objekt, inklusive den för närvarande valda bitmappen, pensel, palett, teckensnitt, penna och region. An EMR_RESTOREDC-post används för att återställa tillståndet. Denna EMF-post specificerar inga parametrar. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | EMR_SCALEVIEWPORTEXTEX-posten specificerar visningsporten för en enhetskontext genom att använda -förhållandena som bildas av de angivna multiplikanderna och divisorerna. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | EMR_SCALEWINDOWEXTEX-posten specificerar fönstret för en uppspelningsenhetskontext med med hjälp av förhållanden som bildas av de angivna multiplikanderna och divisorerna. |
| [EmfSelectClipPath](./emfselectclippath) | EMR_SELECTCLIPPATH-posten anger den aktuella sökvägen som en urklippsregion för en uppspelnings- enhetskontext, kombinerar den nya regionen med vilken befintlig urklippsregion som helst med det angivna läget. |
| [EmfSelectObject](./emfselectobject) | EMR_SELECTOBJECT-posten lägger till ett grafikobjekt till den aktuella metafiluppspelningskontexten device . Objektet specificeras antingen av dess index i EMF-objekttabellen (avsnitt 3.1.1.1) eller av dess värde från StockObject-uppräkningen (avsnitt 2.1.31). |
| [EmfSelectPalette](./emfselectpalette) | EMR_SELECTPALETTE-posten anger en logisk palett för uppspelningsenhetens sammanhang. |
| [EmfSetArcDirection](./emfsetarcdirection) | EMR_SETARCDIRECTION-posten anger ritriktningen som ska användas för båge- och rektangelutgång. |
| [EmfSetBkColor](./emfsetbkcolor) | EMR_SETBKCOLOR-posten anger bakgrundsfärgen. |
| [EmfSetBkMode](./emfsetbkmode) | EMR_SETBKMODE-posten anger bakgrundsblandningsläget för uppspelningsenhetens sammanhang. Bakgrundsblandningsläget används med text, streckade penslar och pennstilar som inte är heldragna linjer. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | EMR_SETBRUSHORGEX-posten anger ursprunget för den aktuella borsten. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | EMR_SETCOLORADJUSTMENT-posten anger färgjusteringsegenskaper i playback enhetskontext. |
| [EmfSetColorSpace](./emfsetcolorspace) | EMR_SETCOLORSPACE-posten definierar det aktuella logiska färgrymdsobjektet för grafikoperationer. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | EMR_SETDIBITSTODEVICE-posten specificerar en blocköverföring av pixlar från specificerade skanningslinjer av en källbitmapp till en destinationsrektangel. |
| [EmfSetIcmMode](./emfseticmmode) | EMR_SETICMMODE-posten anger läget för bildfärghantering (ICM) för grafikoperationer. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | EMR_SETICMPROFILEA-posten anger en färgprofil i en fil med ett namn som består av ASCII tecken, för grafikutdata. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | EMR_SETICMPROFILEW-posten anger en färgprofil i en fil med ett namn bestående av Unicode-tecken, för grafikutdata. |
| [EmfSetLayout](./emfsetlayout) | EMR_SETLAYOUT-posten anger i vilken ordning text och grafik ritas. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | EMR_SETLINKEDUFIS-posten ställer in UniversalFontIds (avsnitt 2.2.27) för de länkade typsnitten för att användas under teckensökning. |
| [EmfSetMapMode](./emfsetmapmode) | EMR_SETMAPMODE-posten specificerar mappningsläget för uppspelningsenhetskontexten. Mappningsläget anger måttenheten som används för att omvandla sidutrymmesenheter till enhetsutrymmesenheter, och anger även orienteringen för enhetens x-axel och y-axel. |
| [EmfSetMapperFlags](./emfsetmapperflags) | EMR_SETMAPPERFLAGS-posten anger parametrar för processen för matchning av logiska teckensnitt till fysiska teckensnitt, vilket utförs av teckensnittsmapparen. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter ställer in den aktuella metaregionen med den aktuella klippningsregionen för att bilda en ny metaregion för uppspelningsenhetskontexten. Den nuvarande urklippsregionen SKA återställas till null. Denna EMF-post specificerar inga parametrar. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | EMR_SETMITERLIMIT-posten anger gränsen för längden på geringskopplingar för uppspelningsenhetskontexten. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | EMR_SETPALETTEENTRIES-posten definierar RGB-färgvärden i ett intervall av poster för ett existerande LogPalette-objekt (avsnitt 2.2.17). |
| [EmfSetPixelV](./emfsetpixelv) | EMR_SETPIXELV-posten definierar färgen på pixeln vid de angivna logiska koordinaterna. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | EMR_SETPOLYFILLMODE-posten definierar polygonfyllningsläge. |
| [EmfSetRop2](./emfsetrop2) | EMR_SETROP2-posten definierar ett binärt rasterdriftsläge. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | EMR_SETSTRETCHBLTMODE-posten anger bitmappsträckningsläge. |
| [EmfSetTextAlign](./emfsettextalign) | EMR_SETTEXTALIGN-posten anger textjustering. |
| [EmfSetTextColor](./emfsettextcolor) | EMR_SETTEXTCOLOR-posten definierar den aktuella textfärgen. |
| [EmfSetTextJustification](./emfsettextjustification) | EMR_SETTEXTJUSTIFICATION-posten anger mängden extra utrymme som ska läggas till break tecken för textjustering. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | EMR_SETVIEWPORTEXTEX-posten definierar visningsportens omfattning. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | EMR_SETVIEWPORTORGEX-posten definierar visningsportens ursprung. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | EMR_SETWINDOWEXTEX-posten definierar fönstrets utsträckning. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | EMR_SETWINDOWORGEX-posten definierar fönstrets ursprung. |
| [EmfSetWorldTransform](./emfsetworldtransform) | EMR_SETWORLDTRANSFORM-posten anger en transformation för den aktuella transformationen av världsutrymme till sidutrymme i uppspelningsenhetskontexten. |
| [EmfSmallTextOut](./emfsmalltextout) | EMR_SMALLTEXTOUT-posten matar ut en sträng. |
| [EmfStateRecordType](./emfstaterecordtype) | Statusposttyperna anger och hanterar grafikegenskaper som definierar tillståndet för uppspelningsenhetskontexten. |
| [EmfStretchBlt](./emfstretchblt) | EMR_STRETCHBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, valfritt i kombination med ett penselmönster, enligt en specificerad raster -operation, sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt . |
| [EmfStretchDiBits](./emfstretchdibits) | EMR_STRETCHDIBITS-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, valfritt i kombination med ett penselmönster, enligt en specificerad raster operation, sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändig. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | EMR_STROKEANDFILLPATH-posten stänger alla öppna figurer i en bana, stryker konturerna av -banan med hjälp av den aktuella pennan och fyller dess inre med den aktuella penseln. |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH klass |
| [EmfTransformRecordType](./emftransformrecordtype) | Transformeringsposttyperna specificerar och modifierar världsutrymme till sidutrymmestransformeringar. |
| [EmfTransparentBlt](./emftransparentblt) | EMR_TRANSPARENTBLT-posten specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, behandlar en specificerad färg som transparent, sträcker ut eller komprimerar utdata för att passa dimensionerna på destinationen, om nödvändigt |
| [EmfVertexData](./emfvertexdata) | Objekt som specificerar hörn för antingen rektanglar eller trianglar och färgerna som motsvarar dem. |
| [EmfWidenPath](./emfwidenpath) | Den här posten omdefinierar den aktuella banan som det område som skulle målas om path ritades med den penna som för närvarande är vald i uppspelningsenhetens sammanhang. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
