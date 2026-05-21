---
title: "GifOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för Graphical Interchange Format GIF rasterbildfilsskapande erbjuder utvecklare omfattande alternativ för att generera GIF-bilder med exakt kontroll."
type: docs
weight: 22
url: /sv/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

API:et för Graphical Interchange Format (GIF) rasterbildfilsskapande erbjuder utvecklare omfattande alternativ för att generera GIF-bilder med exakt kontroll. Med funktioner för att ställa in bakgrundsfärg, färgpalett, upplösning, interlaced‑typ, transparent färg, XMP‑metadata‑behållare och bildkomprimering säkerställer detta API flexibilitet och effektivitet vid skapandet av optimerade och visuellt tilltalande GIF-filer som är anpassade efter specifika applikationskrav.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initierar en ny instans av klassen `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Initierar en ny instans av klassen `GifOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas. |
| [getLoopsCount()](#getLoopsCount--) | Hämtar antalet slingor (Standard 1 slinga) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Anger antalet slingor (Standard 1 slinga) |
| [getColorResolution()](#getColorResolution--) | Hämtar eller anger GIF-färgupplösningen. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Hämtar eller anger GIF-färgupplösningen. |
| [isPaletteSorted()](#isPaletteSorted--) | Hämtar eller anger ett värde som indikerar om palettposter är sorterade. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Hämtar eller anger ett värde som indikerar om palettposter är sorterade. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Hämtar eller anger GIF-pixelns bildförhållande. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Hämtar eller anger GIF-pixelns bildförhållande. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Hämtar eller anger GIF-bakgrundsfärgens index. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Hämtar eller anger GIF-bakgrundsfärgens index. |
| [hasTrailer()](#hasTrailer--) | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
| [getInterlaced()](#getInterlaced--) | True om bilden ska vara interlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True om bilden ska vara interlaced. |
| [getMaxDiff()](#getMaxDiff--) | Hämtar eller anger den maximalt tillåtna pixelskillnaden. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Hämtar eller anger den maximalt tillåtna pixelskillnaden. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Anger bakgrundsfärgen. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om en GIF-bild har transparent färg. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Ställer in ett värde som indikerar om en GIF-bild har transparent färg. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Detta exempel demonstrerar användningen av olika klasser från SaveOptions‑namnutrymmet för exportändamål. En bild av typen Gif laddas in i en instans av Image och exporteras sedan till flera format.
``` java
String dir = "c:\\temp\\";

//Läs in en befintlig bild (av typen Gif) i en instans av Image‑klassen
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportera till BMP‑filformat med standardalternativen
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportera till JPEG‑filformat med standardalternativen
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportera till PNG‑filformat med standardalternativen
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportera till TIFF‑filformat med standardalternativen
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som animerade ramar i den exporterade GIF-filen.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initierar en ny instans av klassen `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initierar en ny instans av klassen `GifOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | GIF-alternativen. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas.

**Returns:**
boolean - `true` om palettkorrigering tillämpas; annars `false`.

Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen). Analysprocessen tar lite tid men den exporterade bilden får den bäst matchande färgpaletten och resultatet blir visuellt bättre.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | `true` om palettkorrigering tillämpas; annars `false`. |

Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen). Analysprocessen tar lite tid men den exporterade bilden får den bäst matchande färgpaletten och resultatet blir visuellt bättre. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fyll hela bilden med den blå-gula gradienten.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Antalet bitar som krävs för att lagra en färg, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras
    // för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen)
    saveOptions.setDoPaletteCorrection(true);

    // Läs in en GIF-bild på ett progressivt sätt.
    // En interlaced GIF visar inte sina skanningslinjer linjärt från topp till botten, utan omordnar dem
    // så GIF:ens innehåll blir tydligt redan innan den är färdigladdad.
    saveOptions.setInterlaced(true);

    // Spara som en förlustfri GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Ställ in maximal tillåten pixelavvikelse. Om den är större än noll används förlustkomprimering.
    // Det rekommenderade värdet för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.
    saveOptions.setMaxDiff(80);

    // Spara som en förlustkomprimerad GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Utdata kan se ut så här:
//Storleken på den förlustfria GIF:en: 212816 byte.
//Storleken på den förlustkomprimerade GIF:en: 89726 byte.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Hämtar antalet slingor (Standard 1 slinga)

Värde: Antalet slingor.

**Returns:**
int - antalet slingor (Standard 1 slinga)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Anger antalet slingor (Standard 1 slinga)

Värde: Antalet slingor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | antalet slingor (Standard 1 slinga) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Hämtar eller anger GIF-färgupplösningen.

**Returns:**
byte - Färglösningen.

Färglösning - Antalet bitar per primärfärg som är tillgängliga i originalbilden, minus 1. Detta värde representerar storleken på hela paletten från vilken färgerna i grafiken valdes, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, så hade paletten i originalbilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör sättas för att indikera rikedom i den ursprungliga paletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Hämtar eller anger GIF-färgupplösningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte | Färglösningen. |

Färglösning - Antalet bitar per primärfärg som är tillgängliga i originalbilden, minus 1. Detta värde representerar storleken på hela paletten från vilken färgerna i grafiken valdes, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, så hade paletten i originalbilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör sättas för att indikera rikedom i den ursprungliga paletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fyll hela bilden med den blå-gula gradienten.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Antalet bitar som krävs för att lagra en färg, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras
    // för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen)
    saveOptions.setDoPaletteCorrection(true);

    // Läs in en GIF-bild på ett progressivt sätt.
    // En interlaced GIF visar inte sina skanningslinjer linjärt från topp till botten, utan omordnar dem
    // så GIF:ens innehåll blir tydligt redan innan den är färdigladdad.
    saveOptions.setInterlaced(true);

    // Spara som en förlustfri GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Ställ in maximal tillåten pixelavvikelse. Om den är större än noll används förlustkomprimering.
    // Det rekommenderade värdet för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.
    saveOptions.setMaxDiff(80);

    // Spara som en förlustkomprimerad GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Utdata kan se ut så här:
//Storleken på den förlustfria GIF:en: 212816 byte.
//Storleken på den förlustkomprimerade GIF:en: 89726 byte.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Hämtar eller anger ett värde som indikerar om palettposter är sorterade.

**Returns:**
boolean - `true` om palettposter är sorterade; annars `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Hämtar eller anger ett värde som indikerar om palettposter är sorterade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om palettposter är sorterade; annars `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Hämtar eller anger GIF-pixelns bildförhållande.

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av bildförhållandet för pixeln i originalbilden. Om fältets värde inte är 0, beräknas denna approximation av bildförhållandet enligt formeln: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio definieras som kvoten av pixelns bredd över dess höjd. Värdeintervallet i detta fält tillåter specificering av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64. Värden : 0 - Ingen information om bildförhållande ges. 1..255 - Värde som används i beräkningen.

**Returns:**
byte - GIF:s pixelaspectförhållande.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Hämtar eller anger GIF-pixelns bildförhållande.

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av bildförhållandet för pixeln i originalbilden. Om fältets värde inte är 0, beräknas denna approximation av bildförhållandet enligt formeln: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio definieras som kvoten av pixelns bredd över dess höjd. Värdeintervallet i detta fält tillåter specificering av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64. Värden : 0 - Ingen information om bildförhållande ges. 1..255 - Värde som används i beräkningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | GIF:s pixelaspectförhållande. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Hämtar eller anger GIF-bakgrundsfärgens index.

**Returns:**
byte - GIF:s bakgrundsfärgindex.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Hämtar eller anger GIF-bakgrundsfärgens index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | GIF:s bakgrundsfärgindex. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Hämtar eller anger ett värde som indikerar om GIF har trailer.

**Returns:**
boolean - `true` om GIF har trailer; annars `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Hämtar eller anger ett värde som indikerar om GIF har trailer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om GIF har trailer; annars `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True om bilden ska vara interlaced.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True om bilden ska vara interlaced.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fyll hela bilden med den blå-gula gradienten.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Antalet bitar som krävs för att lagra en färg, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras
    // för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen)
    saveOptions.setDoPaletteCorrection(true);

    // Läs in en GIF-bild på ett progressivt sätt.
    // En interlaced GIF visar inte sina skanningslinjer linjärt från topp till botten, utan omordnar dem
    // så GIF:ens innehåll blir tydligt redan innan den är färdigladdad.
    saveOptions.setInterlaced(true);

    // Spara som en förlustfri GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Ställ in maximal tillåten pixelavvikelse. Om den är större än noll används förlustkomprimering.
    // Det rekommenderade värdet för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.
    saveOptions.setMaxDiff(80);

    // Spara som en förlustkomprimerad GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Utdata kan se ut så här:
//Storleken på den förlustfria GIF:en: 212816 byte.
//Storleken på den förlustkomprimerade GIF:en: 89726 byte.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Hämtar eller anger den maximalt tillåtna pixelskillnaden. Om den är större än noll används förlustkomprimering. Rekommenderat värde för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung. Det fungerar bäst när bara liten förlust introduceras, och på grund av begränsningar i komprimeringsalgoritmen ger mycket höga förlustnivåer inte lika stor vinst. Intervallet av tillåtna värden är [0, 1000].

**Returns:**
int - Intervallet av tillåtna värden.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Hämtar eller anger den maximalt tillåtna pixelskillnaden. Om den är större än noll används förlustkomprimering. Rekommenderat värde för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung. Det fungerar bäst när bara liten förlust introduceras, och på grund av begränsningar i komprimeringsalgoritmen ger mycket höga förlustnivåer inte lika stor vinst. Intervallet av tillåtna värden är [0, 1000].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Intervallet av tillåtna värden. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fyll hela bilden med den blå-gula gradienten.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Antalet bitar som krävs för att lagra en färg, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettkorrigering innebär att när en bild exporteras till GIF kommer källbildens färger att analyseras
    // för att bygga den bäst matchande paletten (om bildens Palett inte finns eller inte anges i alternativen)
    saveOptions.setDoPaletteCorrection(true);

    // Läs in en GIF-bild på ett progressivt sätt.
    // En interlaced GIF visar inte sina skanningslinjer linjärt från topp till botten, utan omordnar dem
    // så GIF:ens innehåll blir tydligt redan innan den är färdigladdad.
    saveOptions.setInterlaced(true);

    // Spara som en förlustfri GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Ställ in maximal tillåten pixelavvikelse. Om den är större än noll används förlustkomprimering.
    // Det rekommenderade värdet för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.
    saveOptions.setMaxDiff(80);

    // Spara som en förlustkomprimerad GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Utdata kan se ut så här:
//Storleken på den förlustfria GIF:en: 212816 byte.
//Storleken på den förlustkomprimerade GIF:en: 89726 byte.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Hämtar bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Anger bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | bakgrundsfärgen. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om en GIF-bild har transparent färg. Om returvärdet är `null` åsidosätts denna egenskap av källbildens kontext.

**Returns:**
java.lang.Boolean - ett värde som indikerar om en GIF-bild har transparent färg.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Anger ett värde som indikerar om en GIF-bild har transparent färg. Om returvärdet är `null` åsidosätts denna egenskap av källbildens kontext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Boolean | ett värde som indikerar om en GIF-bild har transparent färg. |

