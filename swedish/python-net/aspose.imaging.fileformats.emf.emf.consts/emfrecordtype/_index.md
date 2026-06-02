---
title: "EmfRecordType uppräkning"
type: docs
weight: 290
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

Den RecordType enumeration definierar värden som unikt identifierar EMF‑poster.<br/>            Dessa värden tillhandahålls i fältet Type för varje post.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EMR_ABORTPATH | Denna post avbryter en sökvägsparentes eller förkastar sökvägen från en sluten sökvägsparentes. |
| EMR_ALPHABLEND | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel,<br/>             inklusive alfa‑transparentdata, enligt en angiven blandningsoperation. |
| EMR_ANGLEARC | Denna post definierar ett linjesegment av en båge. Linjesegmentet ritas från den <br/>            aktuella positionen till början av bågen. Bågen ritas längs omkretsen <br/>            av en cirkel med given radie och centrum. Bågens längd definieras av de <br/>            angivna start‑ och svev‑vinklarna. |
| EMR_ARC | Denna post definierar en elliptisk båge. |
| EMR_ARCTO | Denna post definierar en elliptisk båge. Den återställer den aktuella positionen till <br/>            bågens slutpunkt. |
| EMR_BEGINPATH | Denna post öppnar en sökvägsparentes i uppspelningsenhetens kontext. |
| EMR_BITBLT | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinations<br/>             rektangel, eventuellt i kombination med ett penselmönster, enligt en angiven rasteroperation. |
| EMR_CHORD | Denna post definierar en kord (ett område avgränsat av skärningspunkten mellan en ellips <br/>            och ett linjesegment, kallat en sekant). Korden avgränsas med den aktuella <br/>            pennan och fylls med den aktuella penseln. |
| EMR_CLOSEFIGURE | Denna post stänger en öppen figur i en sökväg. |
| EMR_COLORCORRECTPALETTE | Denna post specificerar hur man korrigerar posterna i ett logiskt palettobjekt med hjälp av Windows <br/>            Color System (WCS) 1.0‑värden. |
| EMR_COLORMATCHTOTARGETW | Denna post anger huruvida färgmatchning ska utföras med en färgprofil som är specificerad i en fil med ett namn bestående av Unicode-tecken. |
| EMR_COMMENT | Denna post specificerar godtycklig privat data. |
| EMR_CREATEBRUSHINDIRECT | Denna post definierar en logisk pensel för figurfyllning i grafikoperationer. |
| EMR_CREATECOLORSPACE | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av ASCII-tecken |
| EMR_CREATECOLORSPACEW | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av Unicode-tecken |
| EMR_CREATEDIBPATTERNBRUSHPT | Denna post definierar en logisk pensel som har mönstret specificerat av DIB. |
| EMR_CREATEMONOBRUSH | Denna post definierar en logisk pensel med det specificerade bitmap-mönstret. Bitmapen kan<br/>             vara en enhetsoberoende bitmap (DIB) sektion bitmap eller så kan den vara en enhetsberoende bitmap. |
| EMR_CREATEPALETTE | Denna post definierar ett LogPalette-objekt. |
| EMR_CREATEPEN | Denna post definierar en logisk penna som har den specificerade stilen, bredden och färgen. <br/>            Pennan kan därefter väljas in i uppspelningsenhetens kontext och användas för att rita linjer och kurvor. |
| EMR_DELETECOLORSPACE | Denna post tar bort ett logiskt färgrymdsobjekt. Observera att ett EMR_DELETEOBJECT‑post BÖR <br/>            användas i stället för EMR_DELETECOLORSPACE för att ta bort ett logiskt färgrymdsobjekt |
| EMR_DELETEOBJECT | Denna post tar bort ett grafikobjekt och rensar dess index i EMF-objektabellen. <br/>            Om det borttagna objektet är valt i uppspelningsenhetens kontext, måste standardobjektet <br/>            för den kontextens egenskap ÅTERSTÄLLAS. |
| EMR_DRAWESCAPE | Denna post överför godtycklig information till drivrutinen. Avsikten är att informationen <br/>            ska leda till att ritning utförs. |
| EMR_ELLIPSE | Denna post definierar en ellips. Ellipsens centrum är centrum för den <br/>            angivna omgivande rektangeln. Ellipsen kontureras med den aktuella pennan och <br/>            fylls med den aktuella penseln. |
| EMR_ENDPATH | Denna post stänger en sökvägsparentes och väljer den sökväg som definierats av parentesen <br/>            i uppspelningsenhetens kontext. |
| EMR_EOF | Denna post indikerar slutet på metafilen. |
| EMR_EXCLUDECLIPRECT | Denna post definierar ett nytt beskärningsområde som består av det befintliga beskärningsområdet <br/>            minus den angivna rektangeln. |
| EMR_EXTCREATEFONTINDIRECTW | Denna post definierar ett logiskt teckensnitt som har de angivna egenskaperna. Teckensnittet <br/>            kan därefter väljas som det aktuella teckensnittet för uppspelningsenhetens kontext. |
| EMR_EXTCREATEPEN | Denna post definierar en logisk kosmetisk eller geometrisk penna som har den angivna stilen, <br/>            bredden och penselattributen. |
| EMR_EXTESCAPE | Denna post överför godtycklig information till drivrutinen. Avsikten är att informationen <br/>            inte ska leda till någon ritning. |
| EMR_EXTFLOODFILL | Denna post fyller ett område på displayytan med den aktuella penseln. |
| EMR_EXTSELECTCLIPRGN | Denna post kombinerar det angivna området med det aktuella beskärningsområdet med hjälp av den <br/>            angivna metoden. |
| EMR_EXTTEXTOUTA | Denna post ritar en ASCII-textsträng med det aktuella teckensnittet och textfärgerna. Obs <br/>            EMR_EXTTEXTOUTA SKA emuleras med ett EMR_EXTTEXTOUTW‑record (avsnitt 2.3.5.8).  <br/>            Detta kräver att ASCII‑textsträngen i EmrText‑objektet konverteras till Unicode UTF16‑LE‑kodning. |
| EMR_EXTTEXTOUTW | Denna post ritar en Unicode‑textsträng med det aktuella teckensnittet och textfärgerna. |
| EMR_FILLPATH | Denna post stänger alla öppna figurer i den aktuella sökvägen och fyller sökvägens inre <br/>            genom att använda den aktuella penseln och polygon‑fyllningsläget. |
| EMR_FILLRGN | Denna post fyller det angivna området genom att använda den angivna penseln. |
| EMR_FLATTENPATH | Denna post omvandlar alla kurvor i den valda vägen till uppspelningsenhetens <br/>            kontext, och gör varje kurva till en sekvens av linjer. |
| EMR_FORCEUFIMAPPING | Denna post tvingar teckensnittsmapparen att matcha teckensnitt baserat på deras UniversalFontId i <br/>            företräde framför deras LogFont‑information. |
| EMR_FRAMERGN | Denna post ritar en ram runt det angivna området med den angivna penseln. |
| EMR_GLSBOUNDEDRECORD | Denna post specificerar en OpenGL‑funktion med en avgränsande rektangel för utdata. |
| EMR_GLSRECORD | Denna post specificerar en OpenGL‑funktion. |
| EMR_GRADIENTFILL | Denna post specificerar fyllning av rektanglar eller trianglar med färggradienter |
| EMR_HEADER | Denna post definierar början av metafilen och specificerar dess egenskaper; dess innehåll, <br/>            inklusive dimensionerna på den inbäddade bilden; antalet poster i metafilen; och <br/>            upplösningen på den enhet där den inbäddade bilden skapades. Dessa värden möjliggör att metafilen blir enhetsoberoende. |
| EMR_INTERSECTCLIPRECT | Denna post definierar ett nytt beskärningsområde från skärningspunkten mellan det aktuella beskärnings‑<br/>            området och den angivna rektangeln. |
| EMR_INVERTRGN | Denna post inverterar färgerna i det angivna området. |
| EMR_LINETO | Denna post definierar en linje från den aktuella positionen upp till, men utan att inkludera,<br/>             den angivna punkten. Den återställer den aktuella positionen till den angivna punkten. |
| EMR_MASKBLT | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinations‑<br/>             rektangel, eventuellt i kombination med ett penselmönster och med tillämpning av en <br/>            färgmask‑bitmap, enligt angivna förgrunds‑ och bakgrundsrasteroperationer. |
| EMR_MODIFYWORLDTRANSFORM | Denna post omdefinierar världstransformationen för uppspelningsenhetens kontext med det angivna läget. |
| EMR_MOVETOEX | Detta register definierar koordinaterna för den nya aktuella positionen, i logiska enheter. |
| EMR_NAMEDESCAPE | Detta register överför godtycklig information till den angivna namngivna drivrutinen. |
| EMR_OFFSETCLIPRGN | Detta register omdefinierar klippningsområdet för uppspelningsenhetens kontext med de angivna förskjutningarna. |
| EMR_PAINTRGN | Detta register målar det angivna området genom att använda penseln som för närvarande är vald i <br/>            uppspelningsenhetens kontext. |
| EMR_PIE | Detta register definierar en pajformad kil som begränsas av skärningspunkten mellan en ellips <br/>            och två radier. Pajen kontureras med den aktuella pennan och fylls med den aktuella penseln. |
| EMR_PIXELFORMAT | Detta register specificerar pixelformatet som ska användas för grafikoperationer |
| EMR_PLGBLT | Detta register specificerar en blocköverföring av pixlar från en källbitmap till ett destinations‑parallellogram, med tillämpning av en färgmask‑bitmap. |
| EMR_POLYBEZIER | Detta register definierar en eller flera Bézier-kurvor. Kubiska Bézier-kurvor definieras med<br/>            specificerade ändpunkter och kontrollpunkter, och ritas med den aktuella pennan. |
| EMR_POLYBEZIER16 | Detta register definierar en eller flera Bézier-kurvor. Kurvorna ritas med den aktuella pennan. |
| EMR_POLYBEZIERTO | Detta register definierar en eller flera Bézier-kurvor baserade på den aktuella positionen. |
| EMR_POLYBEZIERTO16 | Detta register definierar en eller flera Bézier-kurvor baserat på den aktuella positionen. |
| EMR_POLYDRAW | Detta register definierar en uppsättning linjesegment och Bézier-kurvor. |
| EMR_POLYDRAW16 | Detta register definierar en uppsättning linjesegment och Bézier-kurvor. |
| EMR_POLYGON | Detta register definierar en polygon bestående av två eller fler hörn som är förbundna med raka <br/>            linjer. Polygonen avgränsas med den aktuella pennan och fylls med den aktuella penseln <br/>            och polygonens fyllningsläge. Polygonen stängs automatiskt genom att rita en linje från den sista hörnet till den första. |
| EMR_POLYGON16 | Detta register definierar en polygon bestående av två eller fler hörn som är förbundna med raka linjer. <br/>            Polygonen avgränsas med den aktuella pennan och fylls med den aktuella penseln och polygonens<br/>             fyllningsläge. Polygonen stängs automatiskt genom att rita en linje från den sista hörnet till den första. |
| EMR_POLYLINE | Detta register definierar en serie av linjesegment genom att ansluta punkterna i den angivna <br/>            arrayen. |
| EMR_POLYLINE16 | Detta register definierar en serie av linjesegment genom att ansluta punkterna i den angivna arrayen. |
| EMR_POLYLINETO | Detta register definierar en eller flera raka linjer baserade på den aktuella positionen. <br/>            En linje ritas från den aktuella positionen till den första punkt som anges i fältet points <br/>            med hjälp av den aktuella pennan. För varje ytterligare linje utförs ritning från slutpunkten <br/>            för den föregående linjen till nästa punkt som anges av points. |
| EMR_POLYLINETO16 | Detta register definierar en eller flera raka linjer baserade på den aktuella positionen.<br/>             En linje ritas från den aktuella positionen till den första punkt som anges i fältet Points <br/>            med hjälp av den aktuella pennan. För varje ytterligare linje utförs ritning från <br/>            slutpunkten för den föregående linjen till nästa punkt som anges av Points. |
| EMR_POLYPOLYGON | Detta register definierar en serie av slutna polygoner. Varje polygon avgränsas med den <br/>            aktuella pennan och fylls med den aktuella penseln och polygonens fyllningsläge. Polygonerna som definieras av detta register kan överlappa. |
| EMR_POLYPOLYGON16 | Detta register definierar en serie av slutna polygoner. Varje polygon avgränsas med den <br/>            aktuella pennan och fylls med den aktuella penseln och polygonens fyllningsläge. Polygonerna<br/>             som anges av detta register kan överlappa. |
| EMR_POLYPOLYLINE | Detta register definierar flera serier av anslutna linjesegment. Linjesegmenten är <br/>            ritade med den aktuella pennan. Figurerna som bildas av segmenten är inte fyllda. D<br/>            en aktuella positionen används varken eller uppdateras av detta register. |
| EMR_POLYPOLYLINE16 | Detta register definierar flera serier av anslutna linjesegment. |
| EMR_POLYTEXTOUTA | Detta register ritar en eller flera ASCII-textsträngar med den aktuella teckensnittet och textfärgerna.<br/>             Observera att EMR_POLYTEXTOUTA BÖR emuleras med en serie av EMR_EXTTEXTOUTW-register, ett per sträng |
| EMR_POLYTEXTOUTW | Detta register ritar en eller flera Unicode-textsträngar med den aktuella teckensnittet och textfärgerna.<br/>            Observera att EMR_POLYTEXTOUTW BÖR emuleras med en serie av EMR_EXTTEXTOUTW-register, ett per sträng |
| EMR_REALIZEPALETTE | Detta register mappar poster från den aktuella logiska paletten till systempaletten. |
| EMR_RECTANGLE | Denna post definierar en rektangel. Rektangeln avgränsas genom att använda den aktuella <br/>            pennan och fylls genom att använda den aktuella penseln. |
| EMR_RESIZEPALETTE | Denna post ökar eller minskar storleken på en logisk palett. |
| EMR_RESTOREDC | Denna post återställer uppspelningsenhetens kontext till det angivna sparade tillståndet. <br/>            Uppspelningsenhetens kontext återställs genom att poppa tillståndsinformation från en stack av <br/>            sparade enhetskontexter som skapats av tidigare EMR_SAVEDC (avsnitt 2.3.11) poster. |
| EMR_ROUNDRECT | Denna post definierar en rektangel med avrundade hörn. Rektangeln avgränsas <br/>            genom att använda den aktuella pennan och fylls genom att använda den aktuella penseln. |
| EMR_SAVEDC | Denna post sparar det aktuella tillståndet för uppspelningsenhetens kontext genom att kopiera data <br/>            som beskriver valda objekt och grafiklägen—inklusive bitmap, pensel, palett, <br/>            teckensnitt, penna, region, ritläge och kartläggningsläge till en stack av sparade enhetskontexter. |
| EMR_SCALEVIEWPORTEXTEX | Denna post omdefinierar viewporten för uppspelningsenhetens kontext med hjälp av förhållandena <br/>            som bildas av de angivna multiplikanderna och divisorarna. |
| EMR_SCALEWINDOWEXTEX | Denna post omdefinierar fönstret för uppspelningsenhetens kontext med hjälp av förhållandena som bildas <br/>            av de angivna multiplikanderna och divisorarna. |
| EMR_SELECTCLIPPATH | Denna post definierar den aktuella vägen som ett urklippsområde för uppspelningsenhetens <br/>            kontext, och kombinerar det nya området med eventuella befintliga urklippsområden med hjälp av det angivna läget. |
| EMR_SELECTOBJECT | Denna post lägger till ett objekt i uppspelningsenhetens kontext, identifierat genom dess <br/>            index i EMF Object Table (avsnitt 3.1.1.1). |
| EMR_SELECTPALETTE | Denna post lägger till ett LogPalette-objekt (avsnitt 2.2.17) i uppspelningsenhetens <br/>            kontext, identifierat genom dess index i EMF Object Table. |
| EMR_SETARCDIRECTION | Denna post definierar ritningsriktningen som ska användas för båg- och rektangel<br/>             operationer. |
| EMR_SETBKCOLOR | Denna post definierar bakgrundsfärgen. |
| EMR_SETBKMODE | Denna post definierar bakgrundsblandningsläget för uppspelningsenhetens kontext. Bakgrundsblandnings<br/>             läget används med text, skuggade penslar och pennstilar som inte är solida linjer. |
| EMR_SETBRUSHORGEX | Denna post definierar ursprunget för den aktuella penseln. |
| EMR_SETCOLORADJUSTMENT | Denna post definierar färgjusteringsvärdena för uppspelningsenhetens kontext med de angivna värdena. |
| EMR_SETCOLORSPACE | Denna post definierar det aktuella logiska färgrymdsobjektet för grafikoperationer. |
| EMR_SETDIBITSTODEVICE | Denna post specificerar en blocköverföring av pixlar från angivna skanningslinjer i en käll‑bitmap<br/>             till en destinationsrektangel. |
| EMR_SETICMMODE | Denna post specificerar läget för Image Color Management (ICM) för grafikoperationer. |
| EMR_SETICMPROFILEA | Denna post specificerar en färgprofil i en fil med ett namn bestående av ASCII‑tecken,<br/>             för grafikoutput. |
| EMR_SETICMPROFILEW | Denna post specificerar en färgprofil i en fil med ett namn bestående av Unicode‑tecken,<br/>             för grafikoutput |
| EMR_SETLAYOUT | Denna post specificerar den ordning i vilken text och grafik ritas |
| EMR_SETLINKEDUFIS | Denna post anger UniversalFontIds för länkade typsnitt som ska användas under teckenuppslagning. |
| EMR_SETMAPMODE | Denna post definierar kartläggningsläget för uppspelningsenhetens kontext. Kartläggningsläget<br/>             definierar måttenheten som används för att omvandla sidrymdsenheter till enhetsrymdsenheter,<br/>             och definierar även enhetens x‑axel och y‑axel orientering. |
| EMR_SETMAPPERFLAGS | Denna post specificerar parametrarna för processen att matcha logiska typsnitt med fysiska <br/>            typsnitt, vilket utförs av typsnittsmapparen. |
| EMR_SETMETARGN | Denna post korsar den aktuella klippningsregionen för uppspelningsenhetens kontext med den <br/>            aktuella meta‑regionen och sparar den kombinerade regionen som den nya meta‑regionen. Klippningsregionen återställs till en null‑region. |
| EMR_SETMITERLIMIT | Detta register definierar gränsen för längden på miter-fogar för uppspelnings <br/>            enhetssammanhang. |
| EMR_SETPALETTEENTRIES | Detta register definierar RGB (röd-grön-blå) färgvärden i ett intervall av poster <br/>            i ett LogPalette-objekt. |
| EMR_SETPIXELV | Detta register definierar färgen på pixeln vid de angivna logiska koordinaterna. |
| EMR_SETPOLYFILLMODE | Detta register definierar polygonens fyllningsläge. |
| EMR_SETROP2 | Detta register definierar binärt rasteroperationsläge. |
| EMR_SETSTRETCHBLTMODE | Detta register definierar bitmapens sträckningsläge. |
| EMR_SETTEXTALIGN | Detta register definierar textjustering. |
| EMR_SETTEXTCOLOR | Detta register definierar den aktuella textfärgen. |
| EMR_SETTEXTJUSTIFICATION | Detta register specificerar mängden extra utrymme som ska läggas till brytningstecken för justering<br/>             ändamål. |
| EMR_SETVIEWPORTEXTEX | Detta register definierar viewportens omfattning. |
| EMR_SETVIEWPORTORGEX | Detta register definierar viewportens ursprung. |
| EMR_SETWINDOWEXTEX | Detta register definierar fönstrets omfattning. |
| EMR_SETWINDOWORGEX | Denna post definierar fönstrets ursprung. |
| EMR_SETWORLDTRANSFORM | Denna post definierar en tvådimensionell linjär transformation mellan världsrummet och <br/>            sidutrymmet (för mer information, se [MSDN-WRLDPGSPC]) för uppspelningsenhetens kontext. <br/>            Denna transformation kan användas för att skala, rotera, skeva eller översätta grafikoutput. |
| EMR_SMALLTEXTOUT | Denna post skriver ut en sträng. |
| EMR_STRETCHBLT | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinations<br/>             rektangel, eventuellt i kombination med ett borstermönster, enligt en specificerad raster<br/>             operation, som sträcker eller komprimerar utdata för att passa destinationens dimensioner, om nödvändigt. |
| EMR_STRETCHDIBITS | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinations <br/>            rektangel, eventuellt i kombination med ett borstermönster, enligt en specificerad rasteroperation, <br/>            som sträcker eller komprimerar utdata för att passa destinationens dimensioner, om nödvändigt. |
| EMR_STROKEANDFILLPATH | Denna post stänger alla öppna figurer i en bana, ritar konturen av banan med <br/>            den aktuella pennan, och fyller dess inre med den aktuella penseln. |
| EMR_STROKEPATH | Denna post renderar den specificerade banan genom att använda den aktuella pennan. |
| EMR_TRANSPARENTBLT | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel,<br/>             där en specificerad färg behandlas som transparent, och som sträcker eller komprimerar utdata för att passa destinationens dimensioner, om nödvändigt. |
| EMR_WIDENPATH | Denna post omdefinierar den aktuella banan som det område som skulle målas om banan <br/>            ritas med den penna som för närvarande är vald i uppspelningsenhetens kontext. |
