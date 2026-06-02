---
title: "EmfRecordType"
second_title: "Aspose.Imaging för Java API-referens"
description: "RecordType‑uppräkningen definierar värden som unikt identifierar EMF‑poster."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

RecordType‑uppräkningen definierar värden som unikt identifierar EMF‑poster. Dessa värden tillhandahålls i fältet Type för varje post.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Denna post definierar början av metafilen och specificerar dess egenskaper; dess innehåll, inklusive dimensionerna för den inbäddade bilden; antalet poster i metafilen; och upplösningen på enheten där den inbäddade bilden skapades. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Denna post definierar en eller flera Bézier-kurvor. |
| [EMR_POLYGON](#EMR-POLYGON) | Denna post definierar en polygon bestående av två eller fler hörn som är sammankopplade med raka linjer. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna arrayen. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Denna post definierar en eller flera Bézier-kurvor baserade på den aktuella positionen. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Denna post definierar en eller flera raka linjer baserade på den aktuella positionen. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Denna post definierar flera serier av sammankopplade linjesegment. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Denna post definierar en serie av slutna polygoner. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Denna post definierar fönstrets omfattning. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Denna post definierar fönstrets ursprung. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Denna post definierar viewportens omfattning. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Denna post definierar viewportens ursprung. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Denna post definierar ursprunget för den aktuella penseln. |
| [EMR_EOF](#EMR-EOF) | Denna post indikerar slutet på metafilen. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Denna post definierar färgen på pixeln vid de angivna logiska koordinaterna. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Denna post specificerar parametrar för processen att matcha logiska typsnitt mot fysiska typsnitt, vilket utförs av typsnittsmapparen. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Denna post definierar kartläggningsläget för uppspelningsenhetens kontext. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Denna post definierar bakgrundsblandningsläget för uppspelningsenhetens kontext. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Denna post definierar polygonfyllningsläget. |
| [EMR_SETROP2](#EMR-SETROP2) | Denna post definierar binärt rasteroperationsläge. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Denna post definierar bitmapsträckningsläge. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Denna post definierar textjustering. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Denna post definierar färgjusteringsvärdena för uppspelningsenhetens kontext med de angivna värdena. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Denna post definierar den aktuella textfärgen. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Denna post definierar bakgrundsfärgen. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Denna post omdefinierar klippningsregionen för uppspelningsenhetens kontext med de angivna förskjutningarna. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Denna post definierar koordinaterna för den nya aktuella positionen, i logiska enheter. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Denna post skär den aktuella klippningsregionen för uppspelningsenhetens kontext med den aktuella metaregionen och sparar den kombinerade regionen som den nya metaregionen. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Denna post definierar en ny klippningsregion som består av den befintliga klippningsregionen minus den angivna rektangeln. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Denna post definierar en ny klippningsregion från skärningen mellan den aktuella klippningsregionen och den angivna rektangeln. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Denna post omdefinierar visningsområdet för uppspelningsenhetens kontext med de förhållanden som bildas av de angivna multiplikatorerna och divisorena. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Denna post omdefinierar fönstret för uppspelningsenhetens kontext med de förhållanden som bildas av de angivna multiplikatorerna och divisorena. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Denna post sparar det aktuella tillståndet för uppspelningsenhetens kontext genom att kopiera data som beskriver valda objekt och grafiklägen—inklusive bitmap, pensel, palett, teckensnitt, penna, region, ritläge och kartläggningsläge—till en stack av sparade enhetssammanhang. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Denna post återställer uppspelningsenhetens kontext till det angivna sparade tillståndet. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Denna post definierar en tvådimensionell linjär transformation mellan världsrummet och sidrymmet (för mer information, se [MSDN-WRLDPGSPC]) för uppspelningsenhetens kontext. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Denna post omdefinierar världstransformationen för uppspelningsenhetens kontext med det angivna läget. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Denna post lägger till ett objekt i uppspelningsenhetens kontext, identifierat genom dess index i EMF-objektstabellen (avsnitt 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Denna post definierar en logisk penna som har den angivna stilen, bredden och färgen. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Denna post definierar en logisk pensel för figurutfyllnad i grafikoperationer. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Denna post raderar ett grafikobjekt och rensar dess index i EMF-objektstabellen. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Denna post definierar ett linjesegment av en båge. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Denna post definierar en ellips. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Denna post definierar en rektangel. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Denna post definierar en rektangel med avrundade hörn. |
| [EMR_ARC](#EMR-ARC) | Denna post definierar en elliptisk båge. |
| [EMR_CHORD](#EMR-CHORD) | Denna post definierar en kord (ett område avgränsat av skärningen mellan en ellips och ett linjesegment, kallad en sekant). |
| [EMR_PIE](#EMR-PIE) | Denna post definierar en pajformad kil avgränsad av skärningen mellan en ellips och två radier. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Denna post lägger till ett LogPalette‑objekt (avsnitt 2.2.17) till uppspelningsenhetens kontext och identifierar det med dess index i EMF‑objektabellen. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Denna post definierar ett LogPalette‑objekt. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Denna post definierar RGB‑ (röd-grön-blå) färgvärden i ett intervall av poster i ett LogPalette‑objekt. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Denna post ökar eller minskar storleken på en logisk palett. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Denna post mappar poster från den aktuella logiska paletten till systempaletten. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Denna post fyller ett område på displayytan med den aktuella penseln. |
| [EMR_LINETO](#EMR-LINETO) | Denna post definierar en linje från den aktuella positionen upp till, men utan att inkludera, den angivna punkten. |
| [EMR_ARCTO](#EMR-ARCTO) | Denna post definierar en elliptisk båge. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Denna post definierar en uppsättning linjesegment och Bézier‑kurvor. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Denna post definierar ritningsriktningen som ska användas för båg‑ och rektangeloperationer. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Denna post definierar gränsen för längden på snedställda fogar för uppspelningsenhetens kontext. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Denna post öppnar en sökvägsparentes i uppspelningsenhetens kontext. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Denna post stänger en sökvägsparentes och väljer den sökväg som definierats av parentesen i uppspelningsenhetens kontext. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Denna post stänger en öppen figur i en sökväg. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Denna post stänger eventuella öppna figurer i den aktuella sökvägen och fyller sökvägens inre genom att använda den aktuella penseln och polygonfyllningsläget. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Denna post stänger eventuella öppna figurer i en sökväg, ritar konturen av sökvägen med den aktuella pennan och fyller dess inre med den aktuella penseln. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Denna post renderar den angivna sökvägen med den aktuella pennan. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Denna post transformerar varje kurva i den valda sökvägen till uppspelningsenhetens kontext, och omvandlar varje kurva till en sekvens av linjer. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Denna post omdefinierar den aktuella sökvägen som det område som skulle målas om sökvägen kontureras med den penna som för närvarande är vald i uppspelningsenhetens kontext. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Denna post definierar den aktuella sökvägen som ett beskärningsområde för uppspelningsenhetens kontext, och kombinerar det nya området med eventuella befintliga beskärningsområden med det angivna läget. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Denna post avbryter en sökvägsparentes eller kastar bort sökvägen från en stängd sökvägsparentes. |
| [EMR_COMMENT](#EMR-COMMENT) | Denna post specificerar godtyckliga privata data. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Denna post fyller det angivna området med den angivna penseln. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Denna post ritar en ram runt det angivna området med den angivna penseln. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Denna post inverterar färgerna i det angivna området. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Denna post målar det angivna området med den pensel som för närvarande är vald i uppspelningsenhetens kontext. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Denna post kombinerar det angivna området med det aktuella beskärningsområdet med det angivna läget. |
| [EMR_BITBLT](#EMR-BITBLT) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation, med sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster och med applicering av en färgmaskbitmap, enligt specificerade förgrunds- och bakgrundsrasteroperationer. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till ett destinationsparallellogram, med applicering av en färgmaskbitmap. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Denna post specificerar en blocköverföring av pixlar från angivna skanningslinjer i en källbitmap till en destinationsrektangel. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation, med sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Denna post definierar ett logiskt teckensnitt som har de specificerade egenskaperna. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Denna post ritar en ASCII-textsträng med det aktuella teckensnittet och textfärgerna. Observera att EMR\_EXTTEXTOUTA SKALL emuleras med ett EMR\_EXTTEXTOUTW‑record (avsnitt 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Denna post ritar en Unicode-textsträng med det aktuella teckensnittet och textfärgerna. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Denna post definierar en eller flera Bézier-kurvor. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Denna post definierar en polygon bestående av två eller fler hörn som är sammankopplade med raka linjer. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna arrayen. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Denna post definierar en eller flera Bézier-kurvor baserade på den aktuella positionen. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Denna post definierar en eller flera raka linjer baserade på den aktuella positionen. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Denna post definierar flera serier av sammankopplade linjesegment. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Denna post definierar en serie av slutna polygoner. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Denna post definierar en uppsättning linjesegment och Bézier‑kurvor. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Denna post definierar en logisk pensel med det specificerade bitmapmönstret. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Denna post definierar en logisk pensel som har mönstret specificerat av DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Denna post definierar en logisk kosmetisk eller geometrisk penna som har den specificerade stilen, bredden och penselattributen. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Denna post ritar en eller flera ASCII-textsträngar med det aktuella teckensnittet och textfärgerna. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Denna post ritar en eller flera Unicode-textsträngar med det aktuella teckensnittet och textfärgerna. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Denna post specificerar läget för Image Color Management (ICM) för grafikoperationer. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av ASCII-tecken. |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Denna post definierar det aktuella logiska färgrymdsobjektet för grafikoperationer. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Denna post tar bort ett logiskt färgrymdsobjekt. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Denna post specificerar en OpenGL-funktion. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Denna post specificerar en OpenGL-funktion med en avgränsande rektangel för utdata. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Denna post specificerar pixelformatet att använda för grafikoperationer. |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Denna post överför godtycklig information till drivrutinen. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Denna post överför godtycklig information till drivrutinen. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Denna post skriver ut en sträng. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Denna post tvingar teckensnittsmapparen att matcha teckensnitt baserat på deras UniversalFontId i förtur framför deras LogFont‑information. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Denna post överför godtycklig information till den angivna namngivna drivrutinen. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Denna post specificerar hur man korrigerar posterna i ett logiskt palettobjekt med hjälp av Windows Color System (WCS) 1.0‑värden. |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Denna post specificerar en färgprofil i en fil med ett namn bestående av ASCII‑tecken, för grafikoutput. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Denna post specificerar en färgprofil i en fil med ett namn bestående av Unicode‑tecken, för grafikoutput. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, inklusive alfa‑transparentdata, enligt en specificerad blandningsoperation. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Denna post specificerar den ordning i vilken text och grafik ritas. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, där en specificerad färg behandlas som transparent, och utdata sträcks eller komprimeras för att passa destinationens dimensioner, om nödvändigt. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Denna post specificerar fyllning av rektanglar eller trianglar med färggradienter. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Denna post anger UniversalFontIds för länkade typsnitt som ska användas vid teckenuppslagning. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Denna post specificerar mängden extra utrymme som ska läggas till brytningstecken för justeringsändamål. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Denna post specificerar huruvida färgmatchning ska utföras med en färgprofil som är specificerad i en fil med ett namn bestående av Unicode‑tecken. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av Unicode‑tecken. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Denna post definierar början av metafilen och specificerar dess egenskaper; dess innehåll, inklusive dimensionerna för den inbäddade bilden; antalet poster i metafilen; och upplösningen på den enhet där den inbäddade bilden skapades. Dessa värden möjliggör att metafilen blir enhetsoberoende.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Denna post definierar en eller flera Bézierkurvor. Kubiska Bézierkurvor definieras med angivna ändpunkter och kontrollpunkter, och ritas med den aktuella pennan.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Denna post definierar en polygon bestående av två eller fler hörn som är förbundna med raka linjer. Polygonen kontureras med den aktuella pennan och fylls med den aktuella penseln och polygonens fyllningsläge. Polygonen stängs automatiskt genom att rita en linje från det sista hörnet till det första.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna arrayen.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Denna post definierar en eller flera Bézier-kurvor baserade på den aktuella positionen.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Denna post definierar en eller flera raka linjer baserade på den aktuella positionen. En linje ritas från den aktuella positionen till den första punkt som anges i fältet points med den aktuella pennan. För varje ytterligare linje utförs ritning från slutpunkten för den föregående linjen till nästa punkt som anges i points.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Denna post definierar flera serier av sammankopplade linjesegment. Linjesegmenten ritas med den aktuella pennan. Figurerna som bildas av segmenten fylls inte. Den aktuella positionen används inte och uppdateras inte av denna post.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Denna post definierar en serie av slutna polygoner. Varje polygon kontureras med den aktuella pennan och fylls med den aktuella penseln och polygonens fyllningsläge. Polygonerna som definieras av denna post kan överlappa.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Denna post definierar fönstrets omfattning.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Denna post definierar fönstrets ursprung.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Denna post definierar viewportens omfattning.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Denna post definierar viewportens ursprung.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Denna post definierar ursprunget för den aktuella penseln.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Denna post indikerar slutet på metafilen.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Denna post definierar färgen på pixeln vid de angivna logiska koordinaterna.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Denna post specificerar parametrar för processen att matcha logiska typsnitt mot fysiska typsnitt, vilket utförs av typsnittsmapparen.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Denna post definierar kartläggningsläget för uppspelningsenhetens kontext. Kartläggningsläget definierar måttenheten som används för att omvandla sidrymdsenheter till enhetsrymdsenheter, och definierar även orienteringen för enhetens x‑axel och y‑axel.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Denna post definierar bakgrundsblandningsläget för uppspelningsenhetens kontext. Bakgrundsblandningsläget används med text, skuggade penslar och pennstilar som inte är solida linjer.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Denna post definierar polygonfyllningsläget.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Denna post definierar binärt rasteroperationsläge.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Denna post definierar bitmapsträckningsläge.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Denna post definierar textjustering.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Denna post definierar färgjusteringsvärdena för uppspelningsenhetens kontext med de angivna värdena.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Denna post definierar den aktuella textfärgen.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Denna post definierar bakgrundsfärgen.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Denna post omdefinierar klippningsregionen för uppspelningsenhetens kontext med de angivna förskjutningarna.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Denna post definierar koordinaterna för den nya aktuella positionen, i logiska enheter.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Denna post skär av den aktuella klippningsregionen för uppspelningsenhetens kontext med den aktuella meta‑regionen och sparar den kombinerade regionen som den nya meta‑regionen. Klippningsregionen återställs till en null‑region.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Denna post definierar en ny klippningsregion som består av den befintliga klippningsregionen minus den angivna rektangeln.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Denna post definierar en ny klippningsregion från skärningen mellan den aktuella klippningsregionen och den angivna rektangeln.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Denna post omdefinierar visningsområdet för uppspelningsenhetens kontext med de förhållanden som bildas av de angivna multiplikatorerna och divisorena.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Denna post omdefinierar fönstret för uppspelningsenhetens kontext med de förhållanden som bildas av de angivna multiplikatorerna och divisorena.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Denna post sparar det aktuella tillståndet för uppspelningsenhetens kontext genom att kopiera data som beskriver valda objekt och grafiklägen—inklusive bitmap, pensel, palett, teckensnitt, penna, region, ritläge och kartläggningsläge—till en stack av sparade enhetssammanhang.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Denna post återställer uppspelningsenhetens kontext till det specificerade sparade tillståndet. Uppspelningsenhetens kontext återställs genom att poppa tillståndsinformation från en stack med sparade enhetskontexter som skapats av tidigare EMR\_SAVEDC‑poster (avsnitt 2.3.11).

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Denna post definierar en tvådimensionell linjär transformation mellan världsrymd och sidrymd (för mer information, se [MSDN-WRLDPGSPC]) för uppspelningsenhetens kontext. Denna transformation kan användas för att skala, rotera, skeva eller translera grafikoutput.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Denna post omdefinierar världstransformationen för uppspelningsenhetens kontext med det angivna läget.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Denna post lägger till ett objekt i uppspelningsenhetens kontext, identifierat genom dess index i EMF-objektstabellen (avsnitt 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Denna post definierar en logisk penna som har den specificerade stilen, bredden och färgen. Pennan kan därefter väljas in i uppspelningsenhetens kontext och användas för att rita linjer och kurvor.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Denna post definierar en logisk pensel för figurutfyllnad i grafikoperationer.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Denna post raderar ett grafikobjekt och rensar dess index i EMF‑objektabellen. Om det raderade objektet är valt i uppspelningsenhetens kontext, måste standardobjektet för den kontextegenskapen återställas.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Denna post definierar ett linjesegment av en båge. Linjesegmentet ritas från den aktuella positionen till början av bågen. Bågen ritas längs omkretsen av en cirkel med given radie och centrum. Bågens längd definieras av de angivna start‑ och svev‑vinklarna.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Denna post definierar en ellips. Ellipsens centrum är centrum för den angivna begränsande rektangeln. Ellipsen kontureras med den aktuella pennan och fylls med den aktuella penseln.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Denna post definierar en rektangel. Rektangeln kontureras med den aktuella pennan och fylls med den aktuella penseln.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Denna post definierar en rektangel med rundade hörn. Rektangeln kontureras med den aktuella pennan och fylls med den aktuella penseln.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Denna post definierar en elliptisk båge.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Denna post definierar en kord (ett område avgränsat av skärningen mellan en ellips och ett linjesegment, kallat en sekant). Korden kontureras med den aktuella pennan och fylls med den aktuella penseln.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Denna post definierar en pajformad kil avgränsad av skärningen mellan en ellips och två radier. Pajen kontureras med den aktuella pennan och fylls med den aktuella penseln.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Denna post lägger till ett LogPalette‑objekt (avsnitt 2.2.17) till uppspelningsenhetens kontext och identifierar det med dess index i EMF‑objektabellen.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Denna post definierar ett LogPalette‑objekt.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Denna post definierar RGB‑ (röd-grön-blå) färgvärden i ett intervall av poster i ett LogPalette‑objekt.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Denna post ökar eller minskar storleken på en logisk palett.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Denna post mappar poster från den aktuella logiska paletten till systempaletten.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Denna post fyller ett område på displayytan med den aktuella penseln.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Denna post definierar en linje från den aktuella positionen upp till, men utan att inkludera, den angivna punkten. Den återställer den aktuella positionen till den angivna punkten.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Denna post definierar en elliptisk båge. Den återställer den aktuella positionen till bågens slutpunkt.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Denna post definierar en uppsättning linjesegment och Bézier‑kurvor.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Denna post definierar ritningsriktningen som ska användas för båg‑ och rektangeloperationer.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Denna post definierar gränsen för längden på snedställda fogar för uppspelningsenhetens kontext.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Denna post öppnar en sökvägsparentes i uppspelningsenhetens kontext.

--------------------

När en sökvägsparentes är öppen kan ett program börja bearbeta poster för att definiera de punkter som ligger i sökvägen. Ett program MÅSTE stänga en öppen sökvägsparentes genom att bearbeta EMR\_ENDPATH-posten. När ett program bearbetar EMR\_BEGINPATH-posten MÅSTE alla tidigare sökvägar kasseras från uppspelningsenhetens kontext.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Denna post stänger en sökvägsparentes och väljer den sökväg som definierats av parentesen i uppspelningsenhetens kontext.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Denna post stänger en öppen figur i en sökväg.

--------------------

Bearbetning av EMR\_CLOSEFIGURE-posten MÅSTE stänga figuren genom att rita en linje från den aktuella positionen till figurens första punkt, och sedan MÅSTE den ansluta linjerna med hjälp av linjesammanslagningsstilen. Om en figur stängs genom att bearbeta EMR\_LINETO-posten istället för EMR\_CLOSEFIGURE-posten används ändkapslar för att skapa hörnet istället för en sammanslagning. EMR\_LINETO specificeras i avsnitt 2.3.5.13. EMR\_CLOSEFIGURE-posten BÖR endast användas om det finns en öppen sökvägsparentes i uppspelningsenhetens kontext. En figur i en sökväg är öppen såvida den inte uttryckligen stängs genom att bearbeta denna post. Obs: En figur kan vara öppen även om den aktuella punkten och figurens startpunkt är samma. Efter bearbetning av EMR\_CLOSEFIGURE-posten MÅSTE tillägg av en linje eller kurva till sökvägen starta en ny figur.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Denna post stänger eventuella öppna figurer i den aktuella sökvägen och fyller sökvägens inre genom att använda den aktuella penseln och polygonfyllningsläget.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Denna post stänger eventuella öppna figurer i en sökväg, ritar konturen av sökvägen med den aktuella pennan och fyller dess inre med den aktuella penseln.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Denna post renderar den angivna sökvägen med den aktuella pennan.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Denna post transformerar varje kurva i den valda sökvägen till uppspelningsenhetens kontext, och omvandlar varje kurva till en sekvens av linjer.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Denna post omdefinierar den aktuella sökvägen som det område som skulle målas om sökvägen kontureras med den penna som för närvarande är vald i uppspelningsenhetens kontext.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Denna post definierar den aktuella sökvägen som ett beskärningsområde för uppspelningsenhetens kontext, och kombinerar det nya området med eventuella befintliga beskärningsområden med det angivna läget.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Denna post avbryter en sökvägsparentes eller kastar bort sökvägen från en stängd sökvägsparentes.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Denna post specificerar godtyckliga privata data.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Denna post fyller det angivna området med den angivna penseln.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Denna post ritar en ram runt det angivna området med den angivna penseln.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Denna post inverterar färgerna i det angivna området.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Denna post målar det angivna området med den pensel som för närvarande är vald i uppspelningsenhetens kontext.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Denna post kombinerar det angivna området med det aktuella beskärningsområdet med det angivna läget.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation, med sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster och med applicering av en färgmaskbitmap, enligt specificerade förgrunds- och bakgrundsrasteroperationer.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till ett destinationsparallellogram, med applicering av en färgmaskbitmap.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Denna post specificerar en blocköverföring av pixlar från angivna skanningslinjer i en källbitmap till en destinationsrektangel.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, eventuellt i kombination med ett penselmönster, enligt en specificerad rasteroperation, med sträckning eller komprimering av utdata för att passa destinationens dimensioner, om nödvändigt.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Denna post definierar ett logiskt teckensnitt som har de angivna egenskaperna. Teckensnittet kan därefter väljas som det aktuella teckensnittet för uppspelningsenhetens kontext.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Denna post ritar en ASCII-textsträng med det aktuella teckensnittet och textfärgerna. Obs: EMR\_EXTTEXTOUTA BÖR emuleras med en EMR\_EXTTEXTOUTW-post (avsnitt 2.3.5.8). Detta kräver att ASCII-textsträngen i EmrText-objektet konverteras till Unicode UTF16-LE-kodning.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Denna post ritar en Unicode-textsträng med det aktuella teckensnittet och textfärgerna.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Denna post definierar en eller flera Bézier-kurvor. Kurvorna ritas med den aktuella pennan.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Denna post definierar en polygon bestående av två eller fler hörn som är förbundna med raka linjer. Polygonen kontureras med den aktuella pennan och fylls med den aktuella penseln och polygonens fyllningsläge. Polygonen stängs automatiskt genom att rita en linje från det sista hörnet till det första.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Denna post definierar en serie linjesegment genom att koppla ihop punkterna i den angivna arrayen.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Denna post definierar en eller flera Bézier-kurvor baserade på den aktuella positionen.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Denna post definierar en eller flera raka linjer baserade på den aktuella positionen. En linje ritas från den aktuella positionen till den första punkten som anges i Points-fältet med den aktuella pennan. För varje ytterligare linje utförs ritning från slutpunkten för den föregående linjen till nästa punkt som anges i Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Denna post definierar flera serier av sammankopplade linjesegment.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Denna post definierar en serie av slutna polygoner. Varje polygon kontureras med den aktuella pennan och fylls med den aktuella penseln samt polygonens fyllnadsläge. Polygonerna som specificeras av denna post kan överlappa.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Denna post definierar en uppsättning linjesegment och Bézier‑kurvor.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Denna post definierar en logisk pensel med det angivna bitmapmönstret. Bitmapen kan vara en enhetsoberoende bitmap (DIB) sektion bitmap eller en enhetsberoende bitmap.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Denna post definierar en logisk pensel som har mönstret specificerat av DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Denna post definierar en logisk kosmetisk eller geometrisk penna som har den specificerade stilen, bredden och penselattributen.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Denna post ritar en eller flera ASCII-textsträngar med det aktuella teckensnittet och textfärgerna. Obs: EMR\_POLYTEXTOUTA BÖR emuleras med en serie av EMR\_EXTTEXTOUTW-poster, en per sträng.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Denna post ritar en eller flera Unicode-textsträngar med det aktuella teckensnittet och textfärgerna. Obs: EMR\_POLYTEXTOUTW BÖR emuleras med en serie av EMR\_EXTTEXTOUTW-poster, en per sträng.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Denna post specificerar läget för Image Color Management (ICM) för grafikoperationer.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av ASCII-tecken.

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Denna post definierar det aktuella logiska färgrymdsobjektet för grafikoperationer.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Denna post raderar ett logiskt färgrymdsobjekt. Obs: En EMR\_DELETEOBJECT-post BÖR användas istället för EMR\_DELETECOLORSPACE för att radera ett logiskt färgrymdsobjekt.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Denna post specificerar en OpenGL-funktion.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Denna post specificerar en OpenGL-funktion med en avgränsande rektangel för utdata.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Denna post specificerar pixelformatet att använda för grafikoperationer.

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Denna post överför godtycklig information till drivrutinen. Avsikten är att informationen ska resultera i att ritning utförs.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Denna post överför godtycklig information till drivrutinen. Avsikten är att informationen inte ska resultera i att ritning utförs.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Denna post skriver ut en sträng.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Denna post tvingar teckensnittsmapparen att matcha teckensnitt baserat på deras UniversalFontId i förtur framför deras LogFont‑information.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Denna post överför godtycklig information till den angivna namngivna drivrutinen.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Denna post specificerar hur man korrigerar posterna i ett logiskt palettobjekt med hjälp av Windows Color System (WCS) 1.0‑värden.

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Denna post specificerar en färgprofil i en fil med ett namn bestående av ASCII‑tecken, för grafikoutput.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Denna post specificerar en färgprofil i en fil med ett namn bestående av Unicode‑tecken, för grafikoutput.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, inklusive alfa‑transparentdata, enligt en specificerad blandningsoperation.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Denna post specificerar den ordning i vilken text och grafik ritas.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Denna post specificerar en blocköverföring av pixlar från en källbitmap till en destinationsrektangel, där en specificerad färg behandlas som transparent, och utdata sträcks eller komprimeras för att passa destinationens dimensioner, om nödvändigt.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Denna post specificerar fyllning av rektanglar eller trianglar med färggradienter.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Denna post anger UniversalFontIds för länkade typsnitt som ska användas vid teckenuppslagning.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Denna post specificerar mängden extra utrymme som ska läggas till brytningstecken för justeringsändamål.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Denna post specificerar huruvida färgmatchning ska utföras med en färgprofil som är specificerad i en fil med ett namn bestående av Unicode‑tecken.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Denna post skapar ett logiskt färgrymdsobjekt från en färgprofil med ett namn bestående av Unicode‑tecken.

