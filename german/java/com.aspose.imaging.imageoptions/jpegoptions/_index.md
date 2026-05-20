---
title: "JpegOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie mühelos hochwertige JPEG-Bilder mit unserer API, die einstellbare Komprimierungsstufen bietet, um die Speichergröße zu optimieren, ohne die Bildqualität zu beeinträchtigen."
type: docs
weight: 26
url: /de/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Erstellen Sie mühelos hochwertige JPEG-Bilder mit unserer API, die einstellbare Komprimierungsstufen bietet, um die Speichergröße zu optimieren, ohne die Bildqualität zu beeinträchtigen. Profitieren Sie von der Unterstützung verschiedener Kompressionstypen, nahezu verlustfreier Kodierung, RGB- und CMYK-Farbprofile sowie EXIF-, JFIF-Bilddaten und XMP-Containern, die vielseitige und anpassbare Optionen für Ihre Bildgenerierungsanforderungen gewährleisten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initialisiert eine neue Instanz der Klasse `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Initialisiert eine neue Instanz der Klasse `JpegOptions`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Liefert das standardmäßige Speicherzuweisungs-Limit. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Setzt das Standard‑Speicherzuweisungs‑Limit. |
| [getJfif()](#getJfif--) | Liest das jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Setzt das jfif. |
| [getComment()](#getComment--) | Liest den JPEG-Dateikommentar. |
| [setComment(String value)](#setComment-java.lang.String-) | Setzt den JPEG-Dateikommentar. |
| [getExifData()](#getExifData--) | Liest den Exif‑Datencontainer. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt Exif‑Daten. |
| [getJpegExifData()](#getJpegExifData--) | Lese den Exif‑Datencontainer. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Lese oder setze den Exif‑Datencontainer |
| [getCompressionType()](#getCompressionType--) | Ruft den Komprimierungstyp ab. |
| [setCompressionType(int value)](#setCompressionType-int-) | Legt den Komprimierungstyp fest. |
| [getColorType()](#getColorType--) | Liest den Farbtyp für JPEG‑Bild. |
| [setColorType(int value)](#setColorType-int-) | Setzt den Farbtyp für JPEG‑Bild. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Liest Bits pro Kanal für verlustfreies JPEG‑Bild. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Setzt Bits pro Kanal für verlustfreies JPEG‑Bild. |
| [getQuality()](#getQuality--) | Liest die Bildqualität. |
| [setQuality(int value)](#setQuality-int-) | Setzt die Bildqualität. |
| [getScaledQuality()](#getScaledQuality--) | Die skalierte Qualität. |
| [getRdOptSettings()](#getRdOptSettings--) | Liest die RD‑Optimizer‑Einstellungen. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Setzt die RD‑Optimizer‑Einstellungen. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Liest die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Setzt die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Liest den JPEG‑LS‑Interleavemodus. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Setzt den JPEG‑LS‑Interleavemodus. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Liest die JPEG‑LS‑Voreinstellungsparameter. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Legt die JPEG-LS-Voreinstellungsparameter fest. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Liest die horizontalen Subsamplings für jede Komponente. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Legt die horizontalen Subsamplings für jede Komponente fest. |
| [getVerticalSampling()](#getVerticalSampling--) | Liest die vertikalen Subsamplings für jede Komponente. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Legt die vertikalen Subsamplings für jede Komponente fest. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Liest den Probenrundungsmodus, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Legt den Probenrundungsmodus fest, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Liest einen Wert, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alphakanal vorhanden ist. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Legt einen Wert fest, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alphakanal vorhanden ist. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest die Auflösungseinheit. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Legt die Auflösungseinheit fest. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions‑Namespace für Exportzwecke. Ein Bild vom Typ Gif wird in eine Instanz von Image geladen und anschließend in mehrere Formate exportiert.
``` java
String dir = "c:\\temp\\";

//Laden Sie ein vorhandenes Bild (vom Typ Gif) in eine Instanz der Image‑Klasse.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportieren Sie in das BMP-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportieren Sie in das JPEG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportieren Sie in das PNG-Dateiformat mit den Standardoptionen.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportieren Sie in das TIFF-Dateiformat mit den Standardoptionen.
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

    // Exportiere nur die ersten beiden Seiten. Tatsächlich wird nur eine Seite gerastert, weil JPEG kein Mehrseitiges Format ist.
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


Initialisiert eine neue Instanz der Klasse `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initialisiert eine neue Instanz der Klasse `JpegOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Die JPEG-Optionen. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Liefert das standardmäßige Speicherzuweisungs-Limit.

**Returns:**
int – Das standardmäßige Speicherzuweisungs-Limit.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Setzt das Standard‑Speicherzuweisungs‑Limit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das standardmäßige Speicherzuweisungs-Limit. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Liest das jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Setzt das jfif.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Liest den JPEG-Dateikommentar.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Setzt den JPEG-Dateikommentar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Liest den Exif‑Datencontainer.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Setzt Exif‑Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif-Daten. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Lese den Exif‑Datencontainer.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Lese oder setze den Exif‑Datencontainer

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Ruft den Komprimierungstyp ab.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Legt den Komprimierungstyp fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Erstelle ein JPEG-Bild von 100 × 100 px.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Die Bitanzahl pro Kanal beträgt für die Y-, Cr- und Cb-Komponenten jeweils 8, 8, 8.
createOptions.setBitsPerChannel((byte) 8);

// Legen Sie den progressiven Kompressionstyp fest.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
createOptions.setQuality(100);

// Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, subsampelt und komprimiert werden.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fülle das Bild mit einem Graustufen‑Verlauf
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // In einer Datei speichern.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Liest den Farbtyp für JPEG‑Bild.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Erstelle ein JPEG-Bild von 100 × 100 px.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Die Bitanzahl pro Kanal beträgt für die Y-, Cr- und Cb-Komponenten jeweils 8, 8, 8.
createOptions.setBitsPerChannel((byte) 8);

// Legen Sie den progressiven Kompressionstyp fest.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
createOptions.setQuality(100);

// Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, subsampelt und komprimiert werden.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fülle das Bild mit einem Graustufen‑Verlauf
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // In einer Datei speichern.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Setzt den Farbtyp für JPEG‑Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Führe einige Bildverarbeitungen durch.

    // Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Die Anzahl der Bits pro Kanal beträgt 8.
    // Wenn eine Palette verwendet wird, wird der Farbindex in den Bilddaten gespeichert anstelle der Farbe selbst.
    saveOptions.setBitsPerChannel((byte) 8);

    // Legen Sie den progressiven Kompressionstyp fest.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
    saveOptions.setQuality(100);

    // Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Wenn das Quellbild farbig ist, wird es in Graustufen konvertiert.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Verwenden Sie eine Palette, um die Ausgabengröße zu reduzieren.
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


Liest Bits pro Kanal für verlustfreie JPEG-Bilder. Jetzt unterstützen wir 2 bis 8 Bits pro Kanal.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Legt Bits pro Kanal für verlustfreie JPEG-Bilder fest. Jetzt unterstützen wir 2 bis 8 Bits pro Kanal.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Erstelle ein JPEG-Bild von 100 × 100 px.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Die Bitanzahl pro Kanal beträgt für die Y-, Cr- und Cb-Komponenten jeweils 8, 8, 8.
createOptions.setBitsPerChannel((byte) 8);

// Legen Sie den progressiven Kompressionstyp fest.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
createOptions.setQuality(100);

// Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, subsampelt und komprimiert werden.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fülle das Bild mit einem Graustufen‑Verlauf
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // In einer Datei speichern.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Liest die Bildqualität.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Setzt die Bildqualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Erstelle ein JPEG-Bild von 100 × 100 px.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Die Bitanzahl pro Kanal beträgt für die Y-, Cr- und Cb-Komponenten jeweils 8, 8, 8.
createOptions.setBitsPerChannel((byte) 8);

// Legen Sie den progressiven Kompressionstyp fest.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
createOptions.setQuality(100);

// Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, subsampelt und komprimiert werden.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fülle das Bild mit einem Graustufen‑Verlauf
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // In einer Datei speichern.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Die skalierte Qualität.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Liest die RD‑Optimizer‑Einstellungen.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Setzt die RD‑Optimizer‑Einstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Die RD-Optimierer-Einstellungen. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden zum Speichern von Bildern. Muss zusammen mit CMYKColorProfile für korrekte Farbumwandlung verwendet werden.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden zum Speichern von Bildern. Muss zusammen mit CMYKColorProfile für korrekte Farbumwandlung verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Das folgende Beispiel lädt ein PNG und speichert es als CMYK‑JPEG unter Verwendung eines benutzerdefinierten ICC‑Profils. Anschließend wird das CMYK‑JPEG geladen und wieder als PNG gespeichert. Die Farbumwandlung von RGB zu CMYK und von CMYK zu RGB erfolgt mithilfe benutzerdefinierter ICC‑Profile.
``` java
String dir = "c:\\temp\\";

// PNG laden und als CMYK‑JPEG speichern
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Benutzerdefinierte ICC‑Profile verwenden
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

// CMYK‑JPEG laden und als PNG speichern
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Benutzerdefinierte ICC‑Profile verwenden
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


Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden zum Speichern von Bildern. Muss zusammen mit RGBColorProfile für korrekte Farbumwandlung verwendet werden.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. Verwenden zum Speichern von Bildern. Muss zusammen mit RGBColorProfile für korrekte Farbumwandlung verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Das folgende Beispiel lädt ein PNG und speichert es als CMYK‑JPEG unter Verwendung eines benutzerdefinierten ICC‑Profils. Anschließend wird das CMYK‑JPEG geladen und wieder als PNG gespeichert. Die Farbumwandlung von RGB zu CMYK und von CMYK zu RGB erfolgt mithilfe benutzerdefinierter ICC‑Profile.
``` java
String dir = "c:\\temp\\";

// PNG laden und als CMYK‑JPEG speichern
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Benutzerdefinierte ICC‑Profile verwenden
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

// CMYK‑JPEG laden und als PNG speichern
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Benutzerdefinierte ICC‑Profile verwenden
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


Liest die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Setzt die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Liest den JPEG‑LS‑Interleavemodus.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Setzt den JPEG‑LS‑Interleavemodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Liest die JPEG‑LS‑Voreinstellungsparameter.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Legt die JPEG-LS-Voreinstellungsparameter fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Liest die horizontalen Subsamplings für jede Komponente.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Legt die horizontalen Subsamplings für jede Komponente fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Liest die vertikalen Subsamplings für jede Komponente.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Legt die vertikalen Subsamplings für jede Komponente fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Ruft den Sample‑Rundungsmodus ab, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Setzt den Sample‑Rundungsmodus, um einen 8‑Bit‑Wert an einen n‑Bit‑Wert anzupassen. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Liest einen Wert, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alphakanal vorhanden ist.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Legt einen Wert fest, der angibt, ob Rot-, Grün- und Blaukomponenten mit einer Hintergrundfarbe gemischt werden sollen, falls ein Alphakanal vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Liest die Auflösungseinheit.

**Returns:**
byte – die Auflösungseinheit.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Erstelle ein JPEG-Bild von 100 × 100 px.
// Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Die Bitanzahl pro Kanal beträgt für die Y-, Cr- und Cb-Komponenten jeweils 8, 8, 8.
createOptions.setBitsPerChannel((byte) 8);

// Legen Sie den progressiven Kompressionstyp fest.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
createOptions.setQuality(100);

// Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Dies ist eine Standardoption für JPEG-Bilder.
// Zwei Chroma-Komponenten (Cb und Cr) können bandbreitenreduziert, subsampelt und komprimiert werden.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fülle das Bild mit einem Graustufen‑Verlauf
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // In einer Datei speichern.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Legt die Auflösungseinheit fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | die Auflösungseinheit. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Führe einige Bildverarbeitungen durch.

    // Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Die Anzahl der Bits pro Kanal beträgt 8.
    // Wenn eine Palette verwendet wird, wird der Farbindex in den Bilddaten gespeichert anstelle der Farbe selbst.
    saveOptions.setBitsPerChannel((byte) 8);

    // Legen Sie den progressiven Kompressionstyp fest.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
    saveOptions.setQuality(100);

    // Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Wenn das Quellbild farbig ist, wird es in Graustufen konvertiert.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Verwenden Sie eine Palette, um die Ausgabengröße zu reduzieren.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

