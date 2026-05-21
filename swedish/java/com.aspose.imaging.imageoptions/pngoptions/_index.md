---
title: "PngOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa högkvalitativa Portable Network Graphics PNG-rasterbilder enkelt med vårt API som erbjuder anpassningsbara alternativ för komprimeringsnivåer, bitar per pixel, djup och alfabitar."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Skapa högkvalitativa Portable Network Graphics (PNG) rasterbilder enkelt med vårt API, som erbjuder anpassningsbara alternativ för komprimeringsnivåer, bitar per pixel, djup och alfabitar. Bearbeta sömlöst XMP-metadata‑behållare, vilket säkerställer omfattande bildmetadatahantering, och ger dig möjlighet att skräddarsy PNG-bilder exakt efter dina specifikationer med lätthet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initierar en ny instans av klassen `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Initierar en ny instans av klassen `PngOptions`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Standardkomprimeringsnivån. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorType()](#getColorType--) | Hämtar färgens typ. |
| [setColorType(int value)](#setColorType-int-) | Ställer in färgens typ. |
| [getProgressive()](#getProgressive--) | Hämtar ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Ställer in ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv. |
| [getFilterType()](#getFilterType--) | Hämtar filtertypen som används under PNG-filsparningsprocessen. |
| [setFilterType(int value)](#setFilterType-int-) | Ställer in filtertypen som används under PNG-filsparningsprocessen. |
| [getCompressionLevel()](#getCompressionLevel--) | Hämtar [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Ställer in [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Hämtar [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Ställer in [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |
| [getBitDepth()](#getBitDepth--) | Hämtar bitdjupsvärdena i intervallet 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Ställer in bitdjupsvärdena i intervallet 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. Faktiskt kommer bara en sida att rasteriseras eftersom PNG inte är ett flersidigt format.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Initierar en ny instans av klassen `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initierar en ny instans av klassen `PngOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG-alternativen. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Standardkomprimeringsnivån.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Hämtar färgens typ.

Värde: Färgens typ.

**Returns:**
int – färgens typ.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Ställer in färgens typ.

Värde: Färgens typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | färgens typ. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Läser in png-bild        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Använd indexerad färgtyp
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Använd maximal kompression
    options.setCompressionLevel(9);
    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Utdatafilens storlek bör minskas avsevärt
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
// Du kan också läsa in en bild av vilket stödformat som helst från en fil eller en ström.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll bilden med den blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Använd progressiv inläsning.
    saveOptions.setProgressive(true);

    // Ställ in horisontell och vertikal upplösning till 96 pixlar per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Varje pixel är en (röd, grön, blå) trippel följd av alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Ställ in den maximala komprimeringsnivån.
    saveOptions.setCompressionLevel(9);

    // Detta är den bästa komprimeringen, men den långsammaste exekveringstiden.
    // Adaptiv filtrering betyder att sparprocessen kommer att välja det mest lämpliga filtret för varje datarad.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Antalet bitar per kanal.
    saveOptions.setBitDepth((byte) 8);

    // Spara till en fil.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Hämtar ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv.

Värde: `` om progressiv; annars ``.

**Returns:**
boolean - ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Ställer in ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv.

Värde: `` om progressiv; annars ``.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om en [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) är progressiv. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Läser in png-bild        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Använd indexerad färgtyp
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Använd maximal kompression
    options.setCompressionLevel(9);
    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Utdatafilens storlek bör minskas avsevärt
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Antalet bitar per färgkanal
createOptions.setBitDepth((byte) 8);

// Varje pixel är en (röd, grön, blå) trippel följd av alfakomponenten.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Den maximala komprimeringsnivån.
createOptions.setCompressionLevel(9);

// Användning av filter gör det möjligt att komprimera kontinuerliga tonbilder mer effektivt.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Använd progressiv inläsning
createOptions.setProgressive(true);

// Skapa en PNG-bild med anpassade parametrar.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll bilden med en halvtransparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Spara till en fil.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Hämtar filtertypen som används under PNG-filsparningsprocessen.

**Returns:**
int – filtertypen som används under png-filens sparprocess.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Ställer in filtertypen som används under PNG-filsparningsprocessen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | filtertypen som används under png-filens sparprocess. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Hjälparklass
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Här är huvudexemplet
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Ange en filtertyp
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//Utdata kan se ut så här:
//Filtertypen är None, utdatafilens storlek är 116845 byte.
//Filtertypen är Up, utdatafilens storlek är 86360 byte.
//Filtertypen är Sub, utdatafilens storlek är 94907 byte.
//Filtertypen är Paeth, utdatafilens storlek är 86403 byte.
//Filtertypen är Avg, utdatafilens storlek är 89956 byte.
//Filtertypen är Adaptive, utdatafilens storlek är 97248 byte.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Hämtar [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.

**Returns:**
int – [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Ställer in [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Läser in png-bild        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Använd indexerad färgtyp
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Använd maximal kompression
    options.setCompressionLevel(9);
    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Utdatafilens storlek bör minskas avsevärt
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
// Du kan också läsa in en bild av vilket stödformat som helst från en fil eller en ström.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll bilden med den blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Använd progressiv inläsning.
    saveOptions.setProgressive(true);

    // Ställ in horisontell och vertikal upplösning till 96 pixlar per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Varje pixel är en (röd, grön, blå) trippel följd av alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Ställ in den maximala komprimeringsnivån.
    saveOptions.setCompressionLevel(9);

    // Detta är den bästa komprimeringen, men den långsammaste exekveringstiden.
    // Adaptiv filtrering betyder att sparprocessen kommer att välja det mest lämpliga filtret för varje datarad.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Antalet bitar per kanal.
    saveOptions.setBitDepth((byte) 8);

    // Spara till en fil.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Hämtar [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.

**Returns:**
int – [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Ställer in [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) komprimeringsnivå. |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Hämtar bitdjupsvärdena i intervallet 1, 2, 4, 8, 16.

Observera följande begränsningar:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte – bitdjupsvärdena i intervallet 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Ställer in bitdjupsvärdena i intervallet 1, 2, 4, 8, 16.

Observera följande begränsningar:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | bitdjupsvärdena i intervallet 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
// Du kan också läsa in en bild av vilket stödformat som helst från en fil eller en ström.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fyll bilden med den blå-genomskinliga gradienten.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Använd progressiv inläsning.
    saveOptions.setProgressive(true);

    // Ställ in horisontell och vertikal upplösning till 96 pixlar per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Varje pixel är en (röd, grön, blå) trippel följd av alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Ställ in den maximala komprimeringsnivån.
    saveOptions.setCompressionLevel(9);

    // Detta är den bästa komprimeringen, men den långsammaste exekveringstiden.
    // Adaptiv filtrering betyder att sparprocessen kommer att välja det mest lämpliga filtret för varje datarad.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Antalet bitar per kanal.
    saveOptions.setBitDepth((byte) 8);

    // Spara till en fil.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

