---
title: "PngOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstellen Sie hochwertige Portable Network Graphics PNG Rasterbilder mühelos mit unserer API, die anpassbare Optionen für Kompressionsstufen, Bits‑pro‑Pixel‑Tiefen und Alpha‑Bits bietet."
type: docs
weight: 38
url: /de/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Erstellen Sie hochwertige Portable Network Graphics (PNG) Rasterbilder mühelos mit unserer API, die anpassbare Optionen für Kompressionsstufen, Bits‑pro‑Pixel‑Tiefen und Alpha‑Bits bietet. Verarbeiten Sie nahtlos XMP‑Metadaten‑Container, gewährleisten Sie eine umfassende Bildmetadatenverwaltung und ermöglichen Sie es Ihnen, PNG‑Bilder exakt nach Ihren Vorgaben mühelos anzupassen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initialisiert eine neue Instanz der `PngOptions` Klasse. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Initialisiert eine neue Instanz der `PngOptions` Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | Der Standard-Komprimierungsgrad. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorType()](#getColorType--) | Gibt den Typ der Farbe zurück. |
| [setColorType(int value)](#setColorType-int-) | Setzt den Typ der Farbe. |
| [getProgressive()](#getProgressive--) | Ermittelt einen Wert, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Legt einen Wert fest, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist. |
| [getFilterType()](#getFilterType--) | Ermittelt den Filtertyp, der beim Speichern von PNG-Dateien verwendet wird. |
| [setFilterType(int value)](#setFilterType-int-) | Legt den Filtertyp fest, der beim Speichern von PNG-Dateien verwendet wird. |
| [getCompressionLevel()](#getCompressionLevel--) | Ermittelt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Legt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fest. |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Ermittelt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Legt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fest. |
| [getBitDepth()](#getBitDepth--) | Ermittelt die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Legt die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16 fest. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportiere nur die ersten beiden Seiten. Tatsächlich wird nur eine Seite gerastert, da PNG kein Mehrseitiges Format ist.
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


Initialisiert eine neue Instanz der `PngOptions` Klasse.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initialisiert eine neue Instanz der `PngOptions` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Die PNG-Optionen. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


Der Standard-Komprimierungsgrad.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Gibt den Typ der Farbe zurück.

Wert: Der Typ der Farbe.

**Returns:**
int – der Typ der Farbe.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Setzt den Typ der Farbe.

Wert: Der Typ der Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Typ der Farbe. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Lädt PNG-Bild
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Indizierten Farbtyp verwenden
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maximale Kompression verwenden
    options.setCompressionLevel(9);
    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Die Größe der Ausgabedatei sollte deutlich reduziert werden
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
// Sie können ein Bild eines beliebigen unterstützten Formats aus einer Datei oder einem Stream laden.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das Bild mit dem blau-transparenten Farbverlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Verwenden Sie progressives Laden.
    saveOptions.setProgressive(true);

    // Setzen Sie die horizontale und vertikale Auflösung auf 96 Pixel pro Zoll.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Jedes Pixel ist ein (Rot, Grün, Blau)-Tripel, gefolgt von Alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Setzen Sie den maximalen Komprimierungsgrad.
    saveOptions.setCompressionLevel(9);

    // Dies ist die beste Kompression, aber die langsamste Ausführungszeit.
    // Adaptives Filtern bedeutet, dass der Speicherprozess für jede Datenzeile den am besten geeigneten Filter auswählt.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setBitDepth((byte) 8);

    // In einer Datei speichern.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Ermittelt einen Wert, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist.

Wert: `` wenn progressiv; andernfalls ``.

**Returns:**
boolescher Wert – ein Wert, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Legt einen Wert fest, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist.

Wert: `` wenn progressiv; andernfalls ``.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | ein Wert, der angibt, ob ein [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) progressiv ist. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Lädt PNG-Bild
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Indizierten Farbtyp verwenden
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maximale Kompression verwenden
    options.setCompressionLevel(9);
    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Die Größe der Ausgabedatei sollte deutlich reduziert werden
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// Die Anzahl der Bits pro Farbkanal
createOptions.setBitDepth((byte) 8);

// Jedes Pixel ist ein (Rot, Grün, Blau)-Tripel, gefolgt von der Alpha-Komponente.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// Der maximale Komprimierungsgrad.
createOptions.setCompressionLevel(9);

// Die Verwendung von Filtern ermöglicht es, kontinuierliche tonale Bilder effektiver zu komprimieren.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Progressives Laden verwenden
createOptions.setProgressive(true);

// Erstellen Sie ein PNG‑Bild mit benutzerdefinierten Parametern.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das Bild mit einem halbtransparenten Farbverlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // In einer Datei speichern.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Ermittelt den Filtertyp, der beim Speichern von PNG-Dateien verwendet wird.

**Returns:**
int – der während des PNG‑Dateispeichervorgangs verwendete Filtertyp.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Legt den Filtertyp fest, der beim Speichern von PNG-Dateien verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der während des PNG‑Dateispeichervorgangs verwendete Filtertyp. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Hilfsklasse
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

// Hier ist das Hauptbeispiel.
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
        // Legen Sie einen Filtertyp fest
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

//Die Ausgabe könnte so aussehen:
//Der Filtertyp ist None, die Ausgabebildgröße beträgt 116845 Byte.
//Der Filtertyp ist Up, die Ausgabebildgröße beträgt 86360 Byte.
//Der Filtertyp ist Sub, die Ausgabebildgröße beträgt 94907 Byte.
//Der Filtertyp ist Paeth, die Ausgabebildgröße beträgt 86403 Byte.
//Der Filtertyp ist Avg, die Ausgabebildgröße beträgt 89956 Byte.
//Der Filtertyp ist Adaptive, die Ausgabebildgröße beträgt 97248 Byte.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Ermittelt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int – das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Komprimierungslevel.
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Legt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Komprimierungslevel. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Lädt PNG-Bild
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Indizierten Farbtyp verwenden
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Maximale Kompression verwenden
    options.setCompressionLevel(9);
    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// Die Größe der Ausgabedatei sollte deutlich reduziert werden
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
// Sie können ein Bild eines beliebigen unterstützten Formats aus einer Datei oder einem Stream laden.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das Bild mit dem blau-transparenten Farbverlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Verwenden Sie progressives Laden.
    saveOptions.setProgressive(true);

    // Setzen Sie die horizontale und vertikale Auflösung auf 96 Pixel pro Zoll.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Jedes Pixel ist ein (Rot, Grün, Blau)-Tripel, gefolgt von Alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Setzen Sie den maximalen Komprimierungsgrad.
    saveOptions.setCompressionLevel(9);

    // Dies ist die beste Kompression, aber die langsamste Ausführungszeit.
    // Adaptives Filtern bedeutet, dass der Speicherprozess für jede Datenzeile den am besten geeigneten Filter auswählt.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setBitDepth((byte) 8);

    // In einer Datei speichern.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Ermittelt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int – das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Komprimierungslevel.
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Legt den Komprimierungsgrad des [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage)-Komprimierungslevel. |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Ermittelt die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16.

Beachten Sie die folgenden Grenzen:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte – die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Legt die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16 fest.

Beachten Sie die folgenden Grenzen:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | die Bit-Tiefenwerte im Bereich von 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
// Sie können ein Bild eines beliebigen unterstützten Formats aus einer Datei oder einem Stream laden.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das Bild mit dem blau-transparenten Farbverlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Verwenden Sie progressives Laden.
    saveOptions.setProgressive(true);

    // Setzen Sie die horizontale und vertikale Auflösung auf 96 Pixel pro Zoll.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Jedes Pixel ist ein (Rot, Grün, Blau)-Tripel, gefolgt von Alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Setzen Sie den maximalen Komprimierungsgrad.
    saveOptions.setCompressionLevel(9);

    // Dies ist die beste Kompression, aber die langsamste Ausführungszeit.
    // Adaptives Filtern bedeutet, dass der Speicherprozess für jede Datenzeile den am besten geeigneten Filter auswählt.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setBitDepth((byte) 8);

    // In einer Datei speichern.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

