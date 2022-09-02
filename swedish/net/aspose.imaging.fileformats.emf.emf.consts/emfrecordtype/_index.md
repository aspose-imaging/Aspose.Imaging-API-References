---
title: EmfRecordType
second_title: Aspose.Imaging för .NET API-referens
description: Uppräkningen RecordType definierar värden som unikt identifierar EMF-poster. Dessa värden finns i fältet Typ för varje post.
type: docs
weight: 2820
url: /sv/net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

Uppräkningen RecordType definierar värden som unikt identifierar EMF-poster. Dessa värden finns i fältet Typ för varje post.

```csharp
public enum EmfRecordType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| EMR_HEADER | `1` | Denna post definierar starten av metafilen och specificerar dess egenskaper; dess innehåll, inklusive dimensionerna för den inbäddade bilden; antalet poster i metafilen; och upplösningen för enheten på vilken den inbäddade bilden skapades. Dessa värden gör det möjligt för metafilen att vara enhetsoberoende. |
| EMR_POLYBEZIER | `2` | Denna post definierar en eller flera Bezier-kurvor. Cubic Bezier-kurvor definieras med specificerade slutpunkter och kontrollpunkter, och ströks med den aktuella pennan. |
| EMR_POLYGON | `3` | Denna post definierar en polygon som består av två eller flera hörn förbundna med raka linjer. Polygonen skisseras genom att använda den aktuella pennan och fylls med den aktuella penseln och polygonfyllningsläget. Polygonen stängs automatiskt genom att dra en linje från den sista hörn till den första. |
| EMR_POLYLINE | `4` | Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna arrayen. |
| EMR_POLYBEZIERTO | `5` | Denna post definierar en eller flera Bezier-kurvor baserat på den aktuella positionen. |
| EMR_POLYLINETO | `6` | Denna post definierar en eller flera raka linjer baserat på den aktuella positionen. En linje dras från den aktuella positionen till den första punkten som anges av punktfältet med hjälp av den aktuella pennan. För varje ytterligare linje ritas från slutpunkten på föregående linje till nästa punkt specificerad av punkter. |
| EMR_POLYPOLYLINE | `7` | Denna post definierar flera serier av anslutna linjesegment. Linjesegmenten ritas med hjälp av den aktuella pennan. Siffrorna som bildas av segmenten är inte ifyllda. T den aktuella positionen varken används eller uppdateras av denna post. |
| EMR_POLYPOLYGON | `8` | Denna post definierar en serie slutna polygoner. Varje polygon är skisserad med hjälp av nuvarande penna och fylls med det aktuella borst- och polygonfyllningsläget. Polygonerna som definieras av denna post kan överlappa. |
| EMR_SETWINDOWEXTEX | `9` | Denna post definierar fönstrets utsträckning. |
| EMR_SETWINDOWORGEX | `10` | Denna post definierar fönstrets ursprung. |
| EMR_SETVIEWPORTEXTEX | `11` | Denna post definierar visningsportens omfattning. |
| EMR_SETVIEWPORTORGEX | `12` | Denna post definierar visningsportens ursprung. |
| EMR_SETBRUSHORGEX | `13` | Denna post definierar ursprunget för den aktuella borsten. |
| EMR_EOF | `14` | Denna post indikerar slutet på metafilen. |
| EMR_SETPIXELV | `15` | Denna post definierar färgen på pixeln vid de angivna logiska koordinaterna. |
| EMR_SETMAPPERFLAGS | `16` | Denna post specificerar parametrar för processen att matcha logiska teckensnitt med fysiska -teckensnitt, vilket utförs av teckensnittsmapparen. |
| EMR_SETMAPMODE | `17` | Denna post definierar mappningsläget för uppspelningsenhetens sammanhang. Mappningsläget definierar måttenheten som används för att omvandla sidutrymmesenheter till enhetsutrymmesenheter, och definierar även orienteringen för enhetens x-axel och y-axel. |
| EMR_SETBKMODE | `18` | Denna post definierar bakgrundsblandningsläget för uppspelningsenhetens sammanhang. Bakgrundsläget mix används med text, streckade penslar och pennstilar som inte är heldragna linjer. |
| EMR_SETPOLYFILLMODE | `19` | Denna post definierar polygonfyllningsläge. |
| EMR_SETROP2 | `20` | Denna post definierar binärt rasterdriftsläge. |
| EMR_SETSTRETCHBLTMODE | `21` | Den här posten definierar bitmappsträckningsläge. |
| EMR_SETTEXTALIGN | `22` | Den här posten definierar textjustering. |
| EMR_SETCOLORADJUSTMENT | `23` | Denna post definierar färgjusteringsvärdena för uppspelningsenhetskontexten med de angivna värdena. |
| EMR_SETTEXTCOLOR | `24` | Denna post definierar den aktuella textfärgen. |
| EMR_SETBKCOLOR | `25` | Den här posten definierar bakgrundsfärgen. |
| EMR_OFFSETCLIPRGN | `26` | Den här posten omdefinierar klippområdet för uppspelningsenhetskontexten med de angivna förskjutningarna. |
| EMR_MOVETOEX | `27` | Denna post definierar koordinaterna för den nya aktuella positionen, i logiska enheter. |
| EMR_SETMETARGN | `28` | Denna post skär den aktuella klippningsregionen för uppspelningsenhetskontexten med den aktuella metaregionen och sparar den kombinerade regionen som den nya metaregionen. Klippningsområdet återställs till ett nollområde. |
| EMR_EXCLUDECLIPRECT | `29` | Den här posten definierar ett nytt klippområde som består av det befintliga klippområdet minus den angivna rektangeln. |
| EMR_INTERSECTCLIPRECT | `30` | Den här posten definierar ett nytt klippområde från skärningspunkten mellan det aktuella klippområdet och den angivna rektangeln. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Denna post omdefinierar visningsporten för uppspelningsenhetskontexten med hjälp av förhållandena som bildas av de angivna multiplikanderna och divisorerna. |
| EMR_SCALEWINDOWEXTEX | `32` | Den här posten omdefinierar fönstret för uppspelningsenhetskontexten med hjälp av förhållanden som bildas av de angivna multiplikanderna och divisorerna. |
| EMR_SAVEDC | `33` | Den här posten sparar det aktuella tillståndet för uppspelningsenhetskontexten genom att kopiera data som beskriver valda objekt och grafiska lägen – inklusive bitmapp, pensel, palett, -teckensnitt, penna, region, ritläge och mappningsläge – till en stapel med sparade enhetskontexter. |
| EMR_RESTOREDC | `34` | Denna post återställer uppspelningsenhetens kontext till det angivna sparade tillståndet. Uppspelningsenhetskontexten återställs genom att tillståndsinformation öppnas från en stapel med sparade enhetskontexter skapade av tidigare EMR_SAVEDC (avsnitt 2.3.11) poster. |
| EMR_SETWORLDTRANSFORM | `35` | Denna post definierar en tvådimensionell linjär transformation mellan världsrymden och sidutrymme (för mer information, se [MSDN-WRLDPGSPC]) för uppspelningsenhetskontexten. Denna transformation kan användas för att skala, rotera, klippa eller översätta grafikutdata. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Denna post omdefinierar världstransformationen för uppspelningsenhetskontexten med det angivna läget. |
| EMR_SELECTOBJECT | `37` | Den här posten lägger till ett objekt i uppspelningsenhetskontexten och identifierar det med dess -index i EMF-objekttabellen (avsnitt 3.1.1.1). |
| EMR_CREATEPEN | `38` | Denna post definierar en logisk penna som har den specificerade stilen, bredden och färgen. Pennan kan sedan väljas in i uppspelningsenhetens sammanhang och användas för att rita linjer och kurvor. |
| EMR_CREATEBRUSHINDIRECT | `39` | Denna post definierar en logisk pensel för figurfyllning i grafikoperationer. |
| EMR_DELETEOBJECT | `40` | Denna post tar bort ett grafikobjekt och rensar dess index i EMF-objekttabellen. Om det borttagna objektet väljs i uppspelningsenhetskontexten, MÅSTE standardobjektet för den kontextegenskapen återställas. |
| EMR_ANGLEARC | `41` | Denna post definierar ett linjesegment av en båge. Linjesegmentet ritas från den aktuella positionen till början av bågen. Bågen ritas längs omkretsen av en cirkel med den givna radien och mitten. Längden på bågen definieras av de givna start- och svepvinklarna. |
| EMR_ELLIPSE | `42` | Denna post definierar en ellips. Mitten av ellipsen är mitten av den specificerade begränsningsrektangeln. Ellipsen kontureras med hjälp av den aktuella pennan och fylls med hjälp av den aktuella borsten. |
| EMR_RECTANGLE | `43` | Denna post definierar en rektangel. Rektangeln skisseras med hjälp av den nuvarande -pennan och fylls med den aktuella penseln. |
| EMR_ROUNDRECT | `44` | Denna post definierar en rektangel med rundade hörn. Rektangeln är konturerad med hjälp av den aktuella pennan och fylls med den aktuella penseln. |
| EMR_ARC | `45` | Denna post definierar en elliptisk båge. |
| EMR_CHORD | `46` | Denna post definierar ett ackord (ett område som begränsas av skärningspunkten mellan en ellips och ett linjesegment, som kallas en sekant). Ackordet skisseras med hjälp av den nuvarande -pennan och fylls med den aktuella penseln. |
| EMR_PIE | `47` | Denna post definierar en pajformad kil som begränsas av skärningspunkten mellan en ellips och två radialer. Pajen kontureras med hjälp av den aktuella pennan och fylls med den aktuella penseln. |
| EMR_SELECTPALETTE | `48` | Den här posten lägger till ett LogPalette-objekt (avsnitt 2.2.17) till uppspelningsenhetens -kontext och identifierar det genom dess index i EMF-objekttabellen. |
| EMR_CREATEPALETTE | `49` | Denna post definierar ett LogPalette-objekt. |
| EMR_SETPALETTEENTRIES | `50` | Den här posten definierar RGB (röd-grön-blå) färgvärden i ett intervall av poster i ett LogPalette-objekt. |
| EMR_RESIZEPALETTE | `51` | Denna post ökar eller minskar storleken på en logisk palett. |
| EMR_REALIZEPALETTE | `52` | Denna post mappar poster från den aktuella logiska paletten till systempaletten. |
| EMR_EXTFLOODFILL | `53` | Denna post fyller ett område av visningsytan med den aktuella penseln. |
| EMR_LINETO | `54` | Denna post definierar en linje från den aktuella positionen till, men inte inklusive, den angivna punkten. Den återställer den aktuella positionen till den angivna punkten. |
| EMR_ARCTO | `55` | Denna post definierar en elliptisk båge. Den återställer den aktuella positionen till slutpunkten för bågen. |
| EMR_POLYDRAW | `56` | Denna post definierar en uppsättning linjesegment och Bezier-kurvor. |
| EMR_SETARCDIRECTION | `57` | Denna post definierar ritriktningen som ska användas för båge- och rektangel -operationer. |
| EMR_SETMITERLIMIT | `58` | Den här posten definierar gränsen för längden på geringskopplingar för uppspelningen enhetskontext. |
| EMR_BEGINPATH | `59` | Den här posten öppnar en sökvägsparentes i uppspelningsenhetens sammanhang. |
| EMR_ENDPATH | `60` | Den här posten stänger en sökvägsparentes och väljer den sökväg som definieras av hakparentesen till uppspelningsenhetskontexten. |
| EMR_CLOSEFIGURE | `61` | Denna post stänger en öppen figur i en bana. |
| EMR_FILLPATH | `62` | Den här posten stänger alla öppna figurer i den aktuella banan och fyller banans inre genom att använda det aktuella borst- och polygonfyllningsläget. |
| EMR_STROKEANDFILLPATH | `63` | Den här posten stänger alla öppna figurer i en bana, strök konturerna av banan med med den aktuella pennan och fyller dess inre med den aktuella penseln. |
| EMR_STROKEPATH | `64` | Denna post återger den angivna sökvägen med hjälp av den aktuella pennan. |
| EMR_FLATTENPATH | `65` | Den här posten omvandlar valfri kurva i banan som är vald till uppspelningsenhetens -kontext, och gör varje kurva till en sekvens av linjer. |
| EMR_WIDENPATH | `66` | Den här posten omdefinierar den aktuella banan som det område som skulle målas om banan ströks med den penna som för närvarande är vald i uppspelningsenhetens sammanhang. |
| EMR_SELECTCLIPPATH | `67` | Den här posten definierar den aktuella sökvägen som en urklippsregion för uppspelningsenhetens kontext, kombinerar den nya regionen med vilken befintlig klippregion som helst med det angivna läget. |
| EMR_ABORTPATH | `68` | Denna post avbryter en sökvägsparentes eller kasserar sökvägen från en stängd sökvägsparentes. |
| EMR_COMMENT | `70` | Denna post specificerar godtyckliga privata data. |
| EMR_FILLRGN | `71` | Denna post fyller den angivna regionen genom att använda den angivna penseln. |
| EMR_FRAMERGN | `72` | Den här posten ritar en kant runt det angivna området med den angivna penseln. |
| EMR_INVERTRGN | `73` | Denna post inverterar färgerna i det angivna området. |
| EMR_PAINTRGN | `74` | Den här posten målar den angivna regionen genom att använda penseln som för närvarande är vald i uppspelningsenhetens sammanhang. |
| EMR_EXTSELECTCLIPRGN | `75` | Denna post kombinerar den angivna regionen med den aktuella klippregionen med specificerat läge. |
| EMR_BITBLT | `76` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett borstmönster, enligt en specificerad rasteroperation. |
| EMR_STRETCHBLT | `77` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett penselmönster, enligt en specificerad raster operation, sträckning eller komprimering av utdata för att passa dimensionerna på destinationen, om nödvändigt. |
| EMR_MASKBLT | `78` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett penselmönster och med applicering av en färgmaskbitmapp, enligt specificerade förgrunds- och bakgrundsrasteroperationer. |
| EMR_PLGBLT | `79` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till ett mål parallellogram, med tillämpning av en färgmaskbitmapp. |
| EMR_SETDIBITSTODEVICE | `80` | Denna post specificerar en blocköverföring av pixlar från specificerade skanningslinjer i en source bitmapp till en destinationsrektangel. |
| EMR_STRETCHDIBITS | `81` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destination rektangel, valfritt i kombination med ett penselmönster, enligt en specificerad rasteroperation, sträcker ut eller komprimerar utdata för att passa destinationens dimensioner, om nödvändigt . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Denna post definierar ett logiskt teckensnitt som har de angivna egenskaperna. Teckensnittet kan sedan väljas som aktuellt teckensnitt för uppspelningsenhetens sammanhang. |
| EMR_EXTTEXTOUTA | `83` | Denna post ritar en ASCII-textsträng med nuvarande teckensnitt och textfärger. Notera att EMR_EXTTEXTOUTA BÖR emuleras med en EMR_EXTTEXTOUTW-post (avsnitt 2.3.5.8). Detta kräver att ASCII-textsträngen i EmrText-objektet konverteras till Unicode UTF16-LE-kodning. |
| EMR_EXTTEXTOUTW | `84` | Denna post ritar en Unicode-textsträng med det aktuella teckensnittet och textfärgerna. |
| EMR_POLYBEZIER16 | `85` | Denna post definierar en eller flera Bezier-kurvor. Kurvorna ritas med den aktuella pennan. |
| EMR_POLYGON16 | `86` | Denna post definierar en polygon som består av två eller flera hörn sammankopplade med räta linjer. Polygonen beskrivs genom att använda den aktuella pennan och fylls med den aktuella penseln och polygon fyllningsläget. Polygonen stängs automatiskt genom att dra en linje från den sista hörn till den första. |
| EMR_POLYLINE16 | `87` | Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna matrisen. |
| EMR_POLYBEZIERTO16 | `88` | Denna post definierar en eller flera Bezier-kurvor baserat på den aktuella positionen. |
| EMR_POLYLINETO16 | `89` | Denna post definierar en eller flera räta linjer baserat på den aktuella positionen. En linje dras från den aktuella positionen till den första punkten som specificeras av fältet Points med hjälp av den aktuella pennan. För varje ytterligare linje ritas från slutpunkten på föregående linje till nästa punkt som specificeras av Points. |
| EMR_POLYPOLYLINE16 | `90` | Denna post definierar flera serier av anslutna linjesegment. |
| EMR_POLYPOLYGON16 | `91` | Denna post definierar en serie slutna polygoner. Varje polygon skisseras genom att använda den aktuella pennan och fylls genom att använda det aktuella borst- och polygonfyllningsläget. Polygonerna som anges av denna post kan överlappa. |
| EMR_POLYDRAW16 | `92` | Denna post definierar en uppsättning linjesegment och Bezier-kurvor. |
| EMR_CREATEMONOBRUSH | `93` | Denna post definierar en logisk pensel med det angivna bitmappsmönstret. Bitmappen kan vara en enhetsoberoende bitmappsbitmapp (DIB) bitmapp eller den kan vara en enhetsberoende bitmapp. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Den här posten definierar en logisk pensel som har mönstret som specificeras av DIB. |
| EMR_EXTCREATEPEN | `95` | Den här posten definierar en logisk kosmetisk eller geometrisk penna som har den specificerade stilen, bredd och penselattribut. |
| EMR_POLYTEXTOUTA | `96` | Denna post ritar en eller flera ASCII-textsträngar med nuvarande teckensnitt och textfärger. Obs EMR_POLYTEXTOUTA BÖR emuleras med en serie EMR_EXTTEXTOUTW-poster, en per sträng |
| EMR_POLYTEXTOUTW | `97` | Denna post ritar en eller flera Unicode-textsträngar med nuvarande teckensnitt och textfärger. Obs EMR_POLYTEXTOUTW BÖR emuleras med en serie EMR_EXTTEXTOUTW-poster, en per sträng |
| EMR_SETICMMODE | `98` | Den här posten anger läget för bildfärghantering (ICM) för grafikoperationer. |
| EMR_CREATECOLORSPACE | `99` | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn som består av ASCII-tecken |
| EMR_SETCOLORSPACE | `100` | Denna post definierar det aktuella logiska färgrymdsobjektet för grafikoperationer. |
| EMR_DELETECOLORSPACE | `101` | Denna post tar bort ett logiskt färgrymdsobjekt. Obs! En EMR_DELETEOBJECT-post SKA användas istället för EMR_DELETECOLORSPACE för att ta bort ett logiskt färgrymdsobjekt |
| EMR_GLSRECORD | `102` | Denna post specificerar en OpenGL-funktion. |
| EMR_GLSBOUNDEDRECORD | `103` | Denna post specificerar en OpenGL-funktion med en avgränsande rektangel för utdata. |
| EMR_PIXELFORMAT | `104` | Denna post anger pixelformatet som ska användas för grafikoperationer |
| EMR_DRAWESCAPE | `105` | Denna post skickar godtycklig information till föraren. Avsikten är att informationen ska resultera i att ritningen görs. |
| EMR_EXTESCAPE | `106` | Denna post skickar godtycklig information till föraren. Avsikten är att informationen inte ska resultera i att ritning görs. |
| EMR_SMALLTEXTOUT | `108` | Denna post matar ut en sträng. |
| EMR_FORCEUFIMAPPING | `109` | Denna post tvingar teckensnittsmapparen att matcha teckensnitt baserat på deras UniversalFontId i -inställning med deras LogFont-information. |
| EMR_NAMEDESCAPE | `110` | Denna post skickar godtycklig information till den givna namngivna föraren. |
| EMR_COLORCORRECTPALETTE | `111` | Den här posten anger hur man korrigerar posterna för ett logiskt palettobjekt med Windows Color System (WCS) 1.0 values |
| EMR_SETICMPROFILEA | `112` | Denna post specificerar en färgprofil i en fil med ett namn som består av ASCII-tecken, för grafikutdata. |
| EMR_SETICMPROFILEW | `113` | Denna post specificerar en färgprofil i en fil med ett namn som består av Unicode-tecken, för grafikutgång |
| EMR_ALPHABLEND | `114` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, inklusive alfatransparensdata, enligt en specificerad blandningsoperation. |
| EMR_SETLAYOUT | `115` | Denna post anger i vilken ordning text och grafik ritas |
| EMR_TRANSPARENTBLT | `116` | Denna post specificerar en blocköverföring av pixlar från en källbitmapp till en destinationsrektangel, behandlar en specificerad färg som transparent, sträcker ut eller komprimerar utdata för att passa dimensionerna på destinationen, om nödvändigt |
| EMR_GRADIENTFILL | `118` | Denna post specificerar fyllningsrektanglar eller trianglar med gradienter av color |
| EMR_SETLINKEDUFIS | `119` | Denna post ställer in UniversalFontIds för länkade teckensnitt som ska användas under teckensökning. |
| EMR_SETTEXTJUSTIFICATION | `120` | Den här posten anger mängden extra utrymme som ska läggas till för bryttecken för justification ändamål. |
| EMR_COLORMATCHTOTARGETW | `121` | Den här posten anger om färgmatchning ska utföras med en färgprofil som anges i en fil med ett namn som består av Unicode-tecken. |
| EMR_CREATECOLORSPACEW | `122` | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn som består av Unicode-tecken |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
