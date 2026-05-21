---
title: "BmpOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "API:et för BMP och DIB rasterbildformatets skapandealternativ ger utvecklare ett mångsidigt verktygssats för att generera anpassade Bitmap BMP och Device Independent Bitmap DIB-bilder."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

API:et för BMP och DIB rasterbildformatets skapandealternativ ger utvecklare ett mångsidigt verktygssats för att generera anpassade Bitmap (BMP) och Device Independent Bitmap (DIB)-bilder. Med detta API kan du exakt definiera bildegenskaper såsom bitar per pixel, komprimeringsnivå och komprimeringstyp, och anpassa utdata för att möta specifika krav. Detta funktionsrika API möjliggör för utvecklare att enkelt och flexibelt skapa högkvalitativa, anpassade rasterbilder för olika tillämpningar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Initierar en ny instans av klassen `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Initierar en ny instans av klassen `BmpOptions`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar eller anger antalet bildbitar per pixel. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Hämtar eller anger antalet bildbitar per pixel. |
| [getCompression()](#getCompression--) | Hämtar komprimeringstypen. |
| [setCompression(long value)](#setCompression-long-) | Anger komprimeringstypen. |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. I själva verket kommer bara en sida att rasteriseras eftersom BMP inte är ett flersidigt format.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Initierar en ny instans av klassen `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Initierar en ny instans av klassen `BmpOptions`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | BMP‑alternativen. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar eller anger antalet bildbitar per pixel.

**Returns:**
int - Bildens bitar per pixel-antal.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Hämtar eller anger antalet bildbitar per pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Antalet bildbitar per pixel. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Skapa BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Använd 8 bitar per pixel för att minska storleken på den genererade bilden.
    saveOptions.setBitsPerPixel(8);

    // Ange den närmaste 8-bitars färgpaletten som täcker det maximala antalet bildpixlar, så att en paletterad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Spara utan komprimering.
    // Du kan också använda RLE-8-komprimering för att minska storleken på den genererade bilden.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Ställ in horisontell och vertikal upplösning till 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Hämtar komprimeringstypen. Standardkomprimeringstypen är [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), som möjliggör att spara en [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med transparens.

Värde: Komprimeringstypen.

**Returns:**
long - komprimeringstypen.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Ställer in komprimeringstypen. Standardkomprimeringstypen är [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), som möjliggör att spara en [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) med transparens.

Värde: Komprimeringstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | komprimeringstypen. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Skapa BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Använd 8 bitar per pixel för att minska storleken på den genererade bilden.
    saveOptions.setBitsPerPixel(8);

    // Ange den närmaste 8-bitars färgpaletten som täcker det maximala antalet bildpixlar, så att en paletterad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Spara utan komprimering.
    // Du kan också använda RLE-8-komprimering för att minska storleken på den genererade bilden.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Ställ in horisontell och vertikal upplösning till 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard.
    // Om du vill ange sådant läge explicit, bör BmpOptions's Compression property sättas till BitmapCompression.Bitfields.
    // BitmapCompression.Bitfields-komprimeringsmetoden är standardkomprimeringsmetoden i BmpOptions.
    // Samma resultat av att exportera en Bmp-bild med transparens kan uppnås på någon av följande sätt.
    // Med implicita standardalternativ:
    pngImage.save(outputPathPng);
    // Med explicita standardalternativ:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specificera BitmapCompression.Bitfields-komprimeringsmetoden:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Läs in en PNG-bild från en fil.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP-bild sparas med transparensstöd som standard, vilket uppnås genom att använda BitmapCompression.Bitfields-komprimeringsmetoden.
    // För att spara en BMP-bild med Rgb-komprimeringsmetoden bör BmpOptions med Compression property satt till BitmapCompression.Rgb anges.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

