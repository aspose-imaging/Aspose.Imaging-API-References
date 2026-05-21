---
title: "JpegOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Skapa högkvalitativa JPEG-bilder enkelt med vårt API som erbjuder justerbara komprimeringsnivåer för att optimera lagringsstorlek utan att kompromissa med bildkvaliteten."
type: docs
weight: 26
url: /sv/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Skapa högkvalitativa JPEG-bilder enkelt med vårt API, som erbjuder justerbara komprimeringsnivåer för att optimera lagringsstorlek utan att kompromissa med bildkvaliteten. Dra nytta av stöd för olika komprimeringstyper, nästan förlustfri kodning, RGB- och CMYK-färgprofiler samt EXIF-, JFIF-bilddata och XMP-behållare, vilket säkerställer mångsidiga och anpassningsbara alternativ för dina bildskapande behov.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initierar en ny instans av `JpegOptions`-klassen. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Initierar en ny instans av `JpegOptions`-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Hämtar standardgränsen för minnesallokering. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Ställer in standardgränsen för minnesallokering. |
| [getJfif()](#getJfif--) | Hämtar jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Ställer in jfif. |
| [getComment()](#getComment--) | Hämtar jpeg-filkommentaren. |
| [setComment(String value)](#setComment-java.lang.String-) | Ställer in jpeg-filkommentaren. |
| [getExifData()](#getExifData--) | Hämtar Exif-datakontainer. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data. |
| [getJpegExifData()](#getJpegExifData--) | Hämta Exif-datakontainer. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Hämta eller ställ in Exif-datakontainer |
| [getCompressionType()](#getCompressionType--) | Hämtar komprimeringstypen. |
| [setCompressionType(int value)](#setCompressionType-int-) | Anger komprimeringstypen. |
| [getColorType()](#getColorType--) | Hämtar färgtypen för jpeg-bild. |
| [setColorType(int value)](#setColorType-int-) | Ställer in färgtypen för jpeg-bild. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Hämtar bitar per kanal för förlustfri jpeg-bild. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Ställer in bitar per kanal för förlustfri jpeg-bild. |
| [getQuality()](#getQuality--) | Hämtar bildkvalitet. |
| [setQuality(int value)](#setQuality-int-) | Ställer in bildkvalitet. |
| [getScaledQuality()](#getScaledQuality--) | Den skalade kvaliteten. |
| [getRdOptSettings()](#getRdOptSettings--) | Hämtar RD optimizer settings. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Ställer in RD optimizer settings. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Den destination RGB-färgprofilen för CMYK jpeg-bilder. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Den destination RGB-färgprofilen för CMYK jpeg-bilder. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Den destination CMYK-färgprofilen för CMYK jpeg-bilder. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Den destination CMYK-färgprofilen för CMYK jpeg-bilder. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Hämtar JPEG-LS difference bound för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Ställer in JPEG-LS difference bound för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Hämtar JPEG-LS interleave mode. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Ställer in JPEG-LS interleave mode. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Hämtar JPEG-LS preset parameters. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Ställer in JPEG-LS‑förinställningsparametrarna. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Hämtar de horisontella undersamplingsvärdena för varje komponent. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Ställer in de horisontella undersamplingsvärdena för varje komponent. |
| [getVerticalSampling()](#getVerticalSampling--) | Hämtar de vertikala undersamplingsvärdena för varje komponent. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Ställer in de vertikala undersamplingsvärdena för varje komponent. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Hämtar provrundningsläget för att anpassa ett 8‑bitarsvärde till ett n‑bitarsvärde. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Ställer in provrundningsläget för att anpassa ett 8‑bitarsvärde till ett n‑bitarsvärde. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Hämtar ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Ställer in ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| [getResolutionUnit()](#getResolutionUnit--) | Hämtar upplösningsenheten. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Ställer in upplösningsenheten. |

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


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportera endast de två första sidorna. I själva verket kommer bara en sida att rasteriseras eftersom JPEG inte är ett flersidigt format.
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

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initierar en ny instans av `JpegOptions`-klassen.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initierar en ny instans av `JpegOptions`-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG‑alternativen. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Hämtar standardgränsen för minnesallokering.

**Returns:**
int - Standardgränsen för minnesallokering.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Ställer in standardgränsen för minnesallokering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Standardgränsen för minnesallokering. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Hämtar jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Ställer in jfif.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Hämtar jpeg-filkommentaren.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ställer in jpeg-filkommentaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Hämtar Exif-datakontainer.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Ställer in Exif-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif‑data. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Hämta Exif-datakontainer.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Hämta eller ställ in Exif-datakontainer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Hämtar komprimeringstypen.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Anger komprimeringstypen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Skapa en JPEG‑bild på 100 × 100 px.
// Använd ytterligare alternativ för att ange de önskade bildparametrarna.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y‑, Cr‑ och Cb‑komponenterna enligt detta.
createOptions.setBitsPerChannel((byte) 8);

// Ange den progressiva komprimeringstypen.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.setQuality(100);

// Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Detta är ett standardalternativ för JPEG‑bilder.
// Två kromakomponenter (Cb och Cr) kan minskas i bandbredd, undersamplas och komprimeras.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fyll bilden med ett gråskaleförlopp
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Spara till en fil.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Hämtar färgtypen för jpeg-bild.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Skapa en JPEG‑bild på 100 × 100 px.
// Använd ytterligare alternativ för att ange de önskade bildparametrarna.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y‑, Cr‑ och Cb‑komponenterna enligt detta.
createOptions.setBitsPerChannel((byte) 8);

// Ange den progressiva komprimeringstypen.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.setQuality(100);

// Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Detta är ett standardalternativ för JPEG‑bilder.
// Två kromakomponenter (Cb och Cr) kan minskas i bandbredd, undersamplas och komprimeras.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fyll bilden med ett gråskaleförlopp
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Spara till en fil.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ställer in färgtypen för jpeg-bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Läs in en BMP-bild från en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Utför någon bildbehandling.

    // Använd ytterligare alternativ för att ange de önskade bildparametrarna.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.setBitsPerChannel((byte) 8);

    // Ange den progressiva komprimeringstypen.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.setQuality(100);

    // Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Använd en palett för att minska utdata storleken.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Hämtar bitar per kanal för förlustfri JPEG‑bild. Nu stöder vi från 2 till 8 bitar per kanal.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Ställer in bitar per kanal för förlustfri JPEG‑bild. Nu stöder vi från 2 till 8 bitar per kanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Skapa en JPEG‑bild på 100 × 100 px.
// Använd ytterligare alternativ för att ange de önskade bildparametrarna.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y‑, Cr‑ och Cb‑komponenterna enligt detta.
createOptions.setBitsPerChannel((byte) 8);

// Ange den progressiva komprimeringstypen.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.setQuality(100);

// Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Detta är ett standardalternativ för JPEG‑bilder.
// Två kromakomponenter (Cb och Cr) kan minskas i bandbredd, undersamplas och komprimeras.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fyll bilden med ett gråskaleförlopp
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Spara till en fil.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Hämtar bildkvalitet.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Ställer in bildkvalitet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Skapa en JPEG‑bild på 100 × 100 px.
// Använd ytterligare alternativ för att ange de önskade bildparametrarna.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y‑, Cr‑ och Cb‑komponenterna enligt detta.
createOptions.setBitsPerChannel((byte) 8);

// Ange den progressiva komprimeringstypen.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.setQuality(100);

// Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Detta är ett standardalternativ för JPEG‑bilder.
// Två kromakomponenter (Cb och Cr) kan minskas i bandbredd, undersamplas och komprimeras.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fyll bilden med ett gråskaleförlopp
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Spara till en fil.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Den skalade kvaliteten.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Hämtar RD optimizer settings.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Ställer in RD optimizer settings.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Inställningarna för RD‑optimeraren. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Destinations‑RGB‑färgprofilen för CMYK‑JPEG‑bilder. Använd för att spara bilder. Måste paras med CMYKColorProfile för korrekt färgkonvertering.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Destinations‑RGB‑färgprofilen för CMYK‑JPEG‑bilder. Använd för att spara bilder. Måste paras med CMYKColorProfile för korrekt färgkonvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Följande exempel läser in PNG och sparar det som CMYK-JPEG med en anpassad ICC-profil. Därefter läses CMYK-JPEG in och sparas tillbaka som PNG. Färgkonverteringen från RGB till CMYK och från CMYK till RGB utförs med hjälp av anpassade ICC-profiler.
``` java
String dir = "c:\\temp\\";

// Läs in PNG och spara det som CMYK-JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Använd anpassade ICC-profiler
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Läs in CMYK-JPEG och spara det som PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Använd anpassade ICC-profiler
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Destinations‑CMYK‑färgprofilen för CMYK‑JPEG‑bilder. Använd för att spara bilder. Måste paras med RGBColorProfile för korrekt färgkonvertering.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Destinations‑CMYK‑färgprofilen för CMYK‑JPEG‑bilder. Använd för att spara bilder. Måste paras med RGBColorProfile för korrekt färgkonvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Följande exempel läser in PNG och sparar det som CMYK-JPEG med en anpassad ICC-profil. Därefter läses CMYK-JPEG in och sparas tillbaka som PNG. Färgkonverteringen från RGB till CMYK och från CMYK till RGB utförs med hjälp av anpassade ICC-profiler.
``` java
String dir = "c:\\temp\\";

// Läs in PNG och spara det som CMYK-JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Använd anpassade ICC-profiler
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Läs in CMYK-JPEG och spara det som PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Använd anpassade ICC-profiler
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Hämtar JPEG-LS difference bound för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Ställer in JPEG-LS difference bound för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Hämtar JPEG-LS interleave mode.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Ställer in JPEG-LS interleave mode.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Hämtar JPEG-LS preset parameters.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Ställer in JPEG-LS‑förinställningsparametrarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Hämtar de horisontella undersamplingsvärdena för varje komponent.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Ställer in de horisontella undersamplingsvärdena för varje komponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Hämtar de vertikala undersamplingsvärdena för varje komponent.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Ställer in de vertikala undersamplingsvärdena för varje komponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Hämtar provavrundningsläget för att anpassa ett 8-bitarsvärde till ett n-bitarsvärde. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Ställer in provavrundningsläget för att anpassa ett 8-bitarsvärde till ett n-bitarsvärde. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Hämtar ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Ställer in ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Hämtar upplösningsenheten.

**Returns:**
byte - upplösningsenheten.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Skapa en JPEG‑bild på 100 × 100 px.
// Använd ytterligare alternativ för att ange de önskade bildparametrarna.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Antalet bitar per kanal är 8, 8, 8 för Y‑, Cr‑ och Cb‑komponenterna enligt detta.
createOptions.setBitsPerChannel((byte) 8);

// Ange den progressiva komprimeringstypen.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
createOptions.setQuality(100);

// Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Detta är ett standardalternativ för JPEG‑bilder.
// Två kromakomponenter (Cb och Cr) kan minskas i bandbredd, undersamplas och komprimeras.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fyll bilden med ett gråskaleförlopp
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Spara till en fil.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Ställer in upplösningsenheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte | upplösningsenheten. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Läs in en BMP-bild från en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Utför någon bildbehandling.

    // Använd ytterligare alternativ för att ange de önskade bildparametrarna.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.setBitsPerChannel((byte) 8);

    // Ange den progressiva komprimeringstypen.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.setQuality(100);

    // Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Använd en palett för att minska utdata storleken.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

