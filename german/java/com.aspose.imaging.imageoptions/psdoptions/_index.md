---
title: "PsdOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Erstelle Photoshop‑Dokument‑PSD‑Bilder mit unserer API, die vielseitige Optionen mit verschiedenen Formatversionen, Komprimierungsmethoden, Farbmodi und Bit‑Anzahlen pro Farbkanal bietet."
type: docs
weight: 40
url: /de/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Erstelle Photoshop‑Dokument‑(PSD)‑Bilder mit unserer API, die vielseitige Optionen mit verschiedenen Formatversionen, Komprimierungsmethoden, Farbmodi und Bit‑Anzahlen pro Farbkanal bietet. Verarbeite nahtlos XMP‑Metadaten‑Container und stelle eine umfassende Bildverarbeitung sicher, indem du die Leistungsfähigkeit der PSD‑Formatfunktionen wie Bildebenen, Ebenenmasken und Dateiinformationen nutzt, um deine Designs anzupassen und kreativ zu gestalten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initialisiert eine neue Instanz der `PsdOptions`‑Klasse. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Initialisiert eine neue Instanz der `PsdOptions`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Lese oder setze den XMP‑Datencontainer |
| [getVersion()](#getVersion--) | Liest oder setzt die PSD‑Dateiversion. |
| [setVersion(int value)](#setVersion-int-) | Liest oder setzt die PSD‑Dateiversion. |
| [getCompressionMethod()](#getCompressionMethod--) | Liest oder setzt die PSD‑Komprimierungsmethode. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Liest oder setzt die PSD‑Komprimierungsmethode. |
| [getPsdVersion()](#getPsdVersion--) | Liest die Dateiformatversion. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Setzt die Dateiformatversion. |
| [getColorMode()](#getColorMode--) | Liest oder setzt den PSD‑Farbmodus. |
| [setColorMode(short value)](#setColorMode-short-) | Liest oder setzt den PSD‑Farbmodus. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Liest oder setzt die Bit‑Anzahl pro Farbkanal. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Liest oder setzt die Bit‑Anzahl pro Farbkanal. |
| [getChannelsCount()](#getChannelsCount--) | Liest die Anzahl der Farbkanäle. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Setzt die Anzahl der Farbkanäle. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Liest einen Wert, der angibt, ob – die globale Text‑Engine‑Ressource entfernt werden soll – verwendet wird für einige textbasierte PSD‑Dateien, und zwar nur dann, wenn sie nach der Verarbeitung in Adobe Photoshop nicht geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Text‑Ebenen). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Setzt einen Wert, der angibt, ob – die globale Text‑Engine‑Ressource entfernt werden soll – verwendet wird für einige textbasierte PSD‑Dateien, und zwar nur dann, wenn sie nach der Verarbeitung in Adobe Photoshop nicht geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Text‑Ebenen). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Liest einen Wert, der angibt, ob [Bildvorschau‑Daten aktualisieren] – eine Option, die zur maximalen Kompatibilität mit anderen PSD‑Betrachtern verwendet wird. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Setzt einen Wert, der angibt, ob [Bildvorschau‑Daten aktualisieren] – eine Option, die zur maximalen Kompatibilität mit anderen PSD‑Betrachtern verwendet wird. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Liest die PSD‑Vektorisierungsoptionen. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Legt die PSD-Vektorisierungsoptionen fest. |

## Example: This example demonstrates the use of Aspose.
Dieses Beispiel demonstriert die Verwendung der Aspose.Imaging for Java API, um Bilder in das PSD-Format zu konvertieren. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und speichert es anschließend wieder im PSD-Format.
``` java

// Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Erstellen Sie eine Instanz der PsdOptions-Klasse.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Setzen Sie die CompressionMethod auf RLE.
    // Hinweis: Eine weitere unterstützte CompressionMethod ist CompressionMethod.RAW [Keine Kompression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Setzen Sie den ColorMode auf GrayScale.
    // Hinweis: Weitere unterstützte ColorModes sind ColorModes.Bitmap und ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Speichern Sie das Bild auf dem Datenträger mit den bereitgestellten PsdOptions-Einstellungen.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportieren Sie nur die ersten beiden Seiten. Diese Seiten werden als Ebenen im ausgegebenen PSD dargestellt.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initialisiert eine neue Instanz der `PsdOptions`‑Klasse.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initialisiert eine neue Instanz der `PsdOptions`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Die Optionen. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Lese oder setze den XMP‑Datencontainer

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Liest oder setzt die PSD‑Dateiversion.

Wert: Die PSD-Dateiversion.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Liest oder setzt die PSD‑Dateiversion.

Wert: Die PSD-Dateiversion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definieren Sie einen linearen blau-transparenten Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das PNG-Bild mit dem linearen blau-transparenten Verlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Die folgenden Optionen werden verwendet, um das PNG-Bild im PSD-Format zu speichern.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Die Anzahl der Kanäle. Ein Kanal für jede Farbkomponente R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Der Farbmodus
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Keine Kompression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversion ist 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Die RLE-Kompression ermöglicht es, die Größe des Ausgabebildes zu reduzieren.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Die Ausgabe könnte so aussehen:
    // Die Größe des PSD-Bildes mit RAW-Kompression: 40090.
    // Die Größe des PSD-Bildes mit RLE-Kompression: 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Liest oder setzt die PSD‑Komprimierungsmethode.

Wert: Die Kompressionsmethode.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Liest oder setzt die PSD‑Komprimierungsmethode.

Wert: Die Kompressionsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |


**Example: This example demonstrates the use of Aspose.**
Dieses Beispiel demonstriert die Verwendung der Aspose.Imaging for Java API, um Bilder in das PSD-Format zu konvertieren. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und speichert es anschließend wieder im PSD-Format.
``` java

// Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Erstellen Sie eine Instanz der PsdOptions-Klasse.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Setzen Sie die CompressionMethod auf RLE.
    // Hinweis: Eine weitere unterstützte CompressionMethod ist CompressionMethod.RAW [Keine Kompression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Setzen Sie den ColorMode auf GrayScale.
    // Hinweis: Weitere unterstützte ColorModes sind ColorModes.Bitmap und ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Speichern Sie das Bild auf dem Datenträger mit den bereitgestellten PsdOptions-Einstellungen.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Ermittelt die Dateiformatversion. Sie kann PSD oder PSB sein.

Wert: Die Dateiformatversion.

**Returns:**
byte - die Dateiformatversion.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Legt die Dateiformatversion fest. Sie kann PSD oder PSB sein.

Wert: Die Dateiformatversion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | die Dateiformatversion. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Liest oder setzt den PSD‑Farbmodus.

Wert: Der Farbmodus.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Liest oder setzt den PSD‑Farbmodus.

Wert: Der Farbmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |


**Example: This example demonstrates the use of Aspose.**
Dieses Beispiel demonstriert die Verwendung der Aspose.Imaging for Java API, um Bilder in das PSD-Format zu konvertieren. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und speichert es anschließend wieder im PSD-Format.
``` java

// Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Erstellen Sie eine Instanz der PsdOptions-Klasse.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Setzen Sie die CompressionMethod auf RLE.
    // Hinweis: Eine weitere unterstützte CompressionMethod ist CompressionMethod.RAW [Keine Kompression].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Setzen Sie den ColorMode auf GrayScale.
    // Hinweis: Weitere unterstützte ColorModes sind ColorModes.Bitmap und ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Speichern Sie das Bild auf dem Datenträger mit den bereitgestellten PsdOptions-Einstellungen.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Liest oder setzt die Bit‑Anzahl pro Farbkanal.

Wert: Die Bitanzahl pro Farbkanal.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Liest oder setzt die Bit‑Anzahl pro Farbkanal.

Wert: Die Bitanzahl pro Farbkanal.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definieren Sie einen linearen blau-transparenten Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das PNG-Bild mit dem linearen blau-transparenten Verlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Die folgenden Optionen werden verwendet, um das PNG-Bild im PSD-Format zu speichern.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Die Anzahl der Kanäle. Ein Kanal für jede Farbkomponente R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Der Farbmodus
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Keine Kompression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversion ist 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Die RLE-Kompression ermöglicht es, die Größe des Ausgabebildes zu reduzieren.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Die Ausgabe könnte so aussehen:
    // Die Größe des PSD-Bildes mit RAW-Kompression: 40090.
    // Die Größe des PSD-Bildes mit RLE-Kompression: 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Liest die Anzahl der Farbkanäle.

**Returns:**
short - Die Anzahl der Farbkanäle.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Setzt die Anzahl der Farbkanäle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short | Die Anzahl der Farbkanäle. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein PNG-Bild mit 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Definieren Sie einen linearen blau-transparenten Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Füllen Sie das PNG-Bild mit dem linearen blau-transparenten Verlauf.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Die folgenden Optionen werden verwendet, um das PNG-Bild im PSD-Format zu speichern.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Die Anzahl der Bits pro Kanal.
    saveOptions.setChannelBitsCount((byte) 8);

    // Die Anzahl der Kanäle. Ein Kanal für jede Farbkomponente R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // Der Farbmodus
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Keine Kompression.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Standardversion ist 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // Die RLE-Kompression ermöglicht es, die Größe des Ausgabebildes zu reduzieren.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Die Ausgabe könnte so aussehen:
    // Die Größe des PSD-Bildes mit RAW-Kompression: 40090.
    // Die Größe des PSD-Bildes mit RLE-Kompression: 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Holt einen Wert, der angibt, ob - Die globale Text‑Engine‑Ressource entfernen - Wird für einige textbasierte PSD‑Dateien verwendet, und zwar nur in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Text‑Ebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Dokument Folgendes ausführen: Menü "Text" -> "Fehlende Schriften verarbeiten". Nach diesem Vorgang wird der gesamte Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang zu einigen endgültigen Layoutänderungen führen kann.

**Returns:**
boolean - `true` wenn [remove global text engine resource]; andernfalls `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Setzt einen Wert, der angibt, ob - Die globale Text‑Engine‑Ressource entfernen - Wird für einige textbasierte PSD‑Dateien verwendet, und zwar nur in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten‑Text‑Ebenen). Nach der Verwendung dieser Option muss der Benutzer im geöffneten Photoshop‑Dokument Folgendes ausführen: Menü "Text" -> "Fehlende Schriften verarbeiten". Nach diesem Vorgang wird der gesamte Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang zu einigen endgültigen Layoutänderungen führen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn [remove global text engine resource]; andernfalls `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Liest einen Wert, der angibt, ob [Bildvorschau‑Daten aktualisieren] – eine Option, die zur maximalen Kompatibilität mit anderen PSD‑Betrachtern verwendet wird.

**Returns:**
boolean - `true` wenn [refresh image preview data]; andernfalls `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Setzt einen Wert, der angibt, ob [Bildvorschau‑Daten aktualisieren] – eine Option, die zur maximalen Kompatibilität mit anderen PSD‑Betrachtern verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn [refresh image preview data]; andernfalls `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Liest die PSD‑Vektorisierungsoptionen.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Legt die PSD-Vektorisierungsoptionen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | die PSD-Vektorisierungsoptionen. |

