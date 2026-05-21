---
title: "ApngImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Animated PNG (Animated Portable Network Graphics) bildfilformat är en mångsidig lösning för utvecklare som vill integrera animerat innehåll i sina applikationer."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

API:et för Animated PNG (Animated Portable Network Graphics) bildfilformat är en mångsidig lösning för utvecklare som vill integrera animerat innehåll i dina applikationer. Detta API erbjuder omfattande kontroll över raminställningar, vilket gör det möjligt för användare att definiera ram‑specifika parametrar, inklusive slinganlängd och PNG‑filinställningar. Med detta funktionsrika verktyg kan du enkelt hantera och optimera visningen av APNG‑bilder, importera och exportera bilder, vilket förbättrar de dynamiska och interaktiva aspekterna av dina applikationer.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Börja arbeta med klassen [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) genom att initiera en ny instans enkelt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Få snabbt åtkomst till information om filformatet med denna praktiska egenskap. |
| [getPageCount()](#getPageCount--) | Hämta det totala antalet sidor i din bildfil enkelt med denna egenskap. |
| [getPages()](#getPages--) | Få enkelt åtkomst till sidorna i din bild med denna praktiska egenskap. |
| [getNumPlays()](#getNumPlays--) | Kontrollera enkelt antalet gånger din animation loopar med denna mångsidiga egenskap. |
| [setNumPlays(int value)](#setNumPlays-int-) | Kontrollera enkelt antalet gånger din animation loopar med denna mångsidiga egenskap. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Justera enkelt standardramens varaktighet för att skapa nya ramar med denna flexibla egenskap. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Justera enkelt standardramens varaktighet för att skapa nya ramar med denna flexibla egenskap. |
| [getInterlaced()](#getInterlaced--) | Bestäm snabbt om detta [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-objekt är interlaced med denna praktiska egenskap. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämta alternativ baserade på de ursprungliga filinställningarna enkelt med denna intuitiva metod. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Hämta standardalternativen enkelt med denna enkla metod. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Få snabbt datum och tid för när resursbilden senast ändrades med denna användarvänliga metod. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Lägg till en ny sida i bilden enkelt med denna intuitiva metod. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Utöka enkelt din ramkollektion genom att lägga till en ny ram i slutet med denna intuitiva metod. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Utöka din ramkollektion sömlöst genom att lägga till en ny ram till den med denna intuitiva metod. |
| [insertFrame(int index)](#insertFrame-int-) | Infoga enkelt en ny ram i din ramkollektion på den angivna platsen med denna intuitiva metod. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Infogar en ny ram i den egna ramkollektionen på det angivna indexet. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Infogar en ny ram i den egna ramkollektionen på det angivna indexet. |
| [popFrameAt(int index)](#popFrameAt-int-) | Ta bort och hämta ramen på det angivna indexet från din ramkollektion med denna intuitiva metod. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Ta bort ramen på det angivna indexet från din ramkollektion sömlöst med denna metod. |
| [removeAllFrames()](#removeAllFrames--) | Rensa din ramkollektion genom att ta bort alla ramar med denna intuitiva metod. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Ställ in den angivna rasterbilden som standardbild för den aktuella animationen enkelt med denna metod. |
| [resetDefaultImage()](#resetDefaultImage--) | Ta bort en tidigare angiven standardbild med den här intuitiva metoden. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exportera till APNG-animation med obegränsade animationscykler som standard
    image.save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Ställa in standardramens varaktighet
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Börja arbeta med klassen [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) genom att initiera en ny instans utan ansträngning. Perfekt för utvecklare som vill börja använda ApngImage‑objekt snabbt och effektivt i sina projekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Alternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Få snabbt åtkomst till information om filformatet med den här praktiska egenskapen. Idealisk för utvecklare som enkelt behöver hämta detaljer om formatet på sina Apng‑filer.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Hämta det totala antalet sidor i din bildfil utan ansträngning med den här egenskapen. Idealisk för utvecklare som behöver snabb åtkomst till sidantalet.

Värde: Sidantalet.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Få utan ansträngning åtkomst till bildens sidor med den här praktiska egenskapen. Perfekt för utvecklare som söker snabb och enkel åtkomst till enskilda sidor för manipulation.

Värde: Sidorna.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Styr antalet gånger din animation loopar utan ansträngning med den här mångsidiga egenskapen. Perfekt för utvecklare som vill ha exakt kontroll över animationsbeteendet, med stöd för oändlig looping när värdet är 0.

Värde: Antalet gånger att loopa.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Styr antalet gånger din animation loopar utan ansträngning med den här mångsidiga egenskapen. Perfekt för utvecklare som vill ha exakt kontroll över animationsbeteendet, med stöd för oändlig looping när värdet är 0.

Värde: Antalet gånger att loopa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Justera enkelt standardramens varaktighet för att skapa nya ramar med den här flexibla egenskapen. Perfekt för utvecklare som vill anpassa ramtidpunkter effektivt i sina animationer.

Värde: Standardramens varaktighet i millisekunder.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Justera enkelt standardramens varaktighet för att skapa nya ramar med den här flexibla egenskapen. Perfekt för utvecklare som vill anpassa ramtidpunkter effektivt i sina animationer.

Värde: Standardramens varaktighet i millisekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Bestäm snabbt om detta [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-objekt är interlaced med den här praktiska egenskapen. Idealisk för utvecklare som enkelt behöver kontrollera interlacing‑statusen för PNG‑bilder.

Värde: `true` om interlaced; annars `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Hämta alternativ baserade på originalfilens inställningar utan ansträngning med den här intuitiva metoden. Perfekt för utvecklare som vill komma åt och använda inställningar som matchar originalfilens egenskaper. Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av metoden [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), kommer en PNG‑utdata med 8‑bit per pixel att skapas. För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till metoden [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Hämta standardalternativen utan ansträngning med den här enkla metoden. Idealisk för utvecklare som vill ha snabb åtkomst till standardinställningarna för Apng‑bilder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | java.lang.Object[] | Argumenten. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Få snabbt datum och tid för när resursbilden senast ändrades med den här användarvänliga metoden. Idealisk för utvecklare som behöver spåra förändringar och hantera resurser effektivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useDefault | boolean | om den är satt till `true` använder informationen från FileInfo som standardvärde. |

**Returns:**
java.util.Date - Datum och tid då resursbilden senast ändrades.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Lägg till en ny sida i bilden utan ansträngning med den här intuitiva metoden. Perfekt för utvecklare som vill utöka innehållet i sina bildfiler dynamiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Sidan att lägga till. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Lägg enkelt till en ny ram i slutet av din ramkollektion med den här enkla metoden. Idealisk för utvecklare som vill utöka sin ramkollektion dynamiskt för animationer med fler‑ram‑bilder. En ny ram skapas enligt storleken på den aktuella bilden.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Utöka din ramkollektion utan ansträngning genom att lägga till en ny ram i slutet med den här intuitiva metoden. Perfekt för utvecklare som vill förbättra sina animationer av fler‑ram‑bilder dynamiskt. Innehållet i den nya ramen fylls från den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Ramens bild. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Utöka din ramkollektion sömlöst genom att lägga till en ny ram med den här intuitiva metoden. Idealisk för utvecklare som vill berika sina animationer av fler‑ram‑bilder. Innehållet i den nya ramen fylls från den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Ramens bild. |
| frameTime | long | Ramens varaktighet i millisekunder. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Infoga utan ansträngning en ny ram i din ramkollektion på den angivna platsen med den här intuitiva metoden. Idealisk för utvecklare som vill ha exakt kontroll över ramarnas placering i sina animationer av fler‑ram‑bilder. En ny ram skapas enligt storleken på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Infogar en ny ram i den egna ramkollektionen på det angivna indexet. Innehållet i den nya ramen fylls från den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Ramens bild. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Infogar en ny ram i den egna ramkollektionen på det angivna indexet. Innehållet i den nya ramen fylls från den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Ramens bild. |
| frameTime | long | Ramens varaktighet i millisekunder. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Ta bort och hämta ramen på det angivna indexet från din ramkollektion med den här intuitiva metoden. Perfekt för utvecklare som vill ha effektiv hantering av ramar i sina animationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Ta bort ramen på det angivna indexet från din ramkollektion sömlöst med den här metoden. Perfekt för utvecklare som vill ha förenklad hantering av ramar i sina fler‑ram‑bilder. Den ram som ska tas bort kommer att avyttras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Rensa din bildramsamling genom att ta bort alla ramar med den här intuitiva metoden. Perfekt för utvecklare som vill återställa eller uppdatera sina animationer.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Ställ in den angivna rasterbilden som standardbild för den aktuella animationen enkelt med den här metoden. Perfekt för utvecklare som vill anpassa standardbilden i sina animationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Ta bort en tidigare inställd standardbild med den här intuitiva metoden. Perfekt för utvecklare som vill återställa eller rensa standardbilden i sin animation. Efter detta blir standardbilden den första ramen i den egna bildramsamlingen (den kan inte tas bort med den här metoden).

