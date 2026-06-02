---
title: "GifOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für die Erstellung von Rasterbilddateien im Graphical Interchange Format GIF bietet Entwicklern umfassende Optionen zur Erzeugung von GIF-Bildern mit präziser Kontrolle."
type: docs
weight: 22
url: /de/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Die API für die Erstellung von Rasterbilddateien im Graphical Interchange Format (GIF) bietet Entwicklern umfassende Optionen zur Erzeugung von GIF-Bildern mit präziser Kontrolle. Mit Funktionen zum Festlegen von Hintergrundfarbe, Farbpalette, Auflösung, Interlaced-Typ, transparenter Farbe, XMP-Metadatencontainer und Bildkompression gewährleistet diese API Flexibilität und Effizienz bei der Erstellung optimierter und visuell ansprechender GIFs, die auf spezifische Anwendungsanforderungen zugeschnitten sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialisiert eine neue Instanz der `GifOptions`-Klasse. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Initialisiert eine neue Instanz der `GifOptions`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird. |
| [getLoopsCount()](#getLoopsCount--) | Liest die Schleifenanzahl (Standard 1 Schleife) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Setzt die Schleifenanzahl (Standard 1 Schleife) |
| [getColorResolution()](#getColorResolution--) | Liest oder setzt die GIF-Farbauflösung. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Liest oder setzt die GIF-Farbauflösung. |
| [isPaletteSorted()](#isPaletteSorted--) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Liest oder setzt das Seitenverhältnis der GIF-Pixel. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Liest oder setzt das Seitenverhältnis der GIF-Pixel. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Liest oder setzt den Index der GIF-Hintergrundfarbe. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Liest oder setzt den Index der GIF-Hintergrundfarbe. |
| [hasTrailer()](#hasTrailer--) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
| [getInterlaced()](#getInterlaced--) | Wahr, wenn das Bild interlaced sein soll. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Wahr, wenn das Bild interlaced sein soll. |
| [getMaxDiff()](#getMaxDiff--) | Liest oder setzt die maximal zulässige Pixeldifferenz. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Liest oder setzt die maximal zulässige Pixeldifferenz. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest die Hintergrundfarbe. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt die Hintergrundfarbe. |
| [hasTransparentColor()](#hasTransparentColor--) | Ermittelt einen Wert, der angibt, ob ein GIF‑Bild eine transparente Farbe hat. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Legt einen Wert fest, der angibt, ob ein GIF‑Bild eine transparente Farbe hat. |

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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportiere nur die ersten beiden Seiten. Diese Seiten werden als animierte Frames im Ausgabegif dargestellt.
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


Initialisiert eine neue Instanz der `GifOptions`-Klasse.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initialisiert eine neue Instanz der `GifOptions`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | Die GIF‑Optionen. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird.

**Returns:**
boolean - `true`, wenn Palettenkorrektur angewendet wird; andernfalls `false`.

Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden, um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang dauert etwas, jedoch wird das Ausgabebild die bestpassende Farbpalette besitzen und das Ergebnis ist visuell besser.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | boolean | `true`, wenn Palettenkorrektur angewendet wird; andernfalls `false`. |

Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden, um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang dauert etwas, jedoch wird das Ausgabebild die bestpassende Farbpalette besitzen und das Ergebnis ist visuell besser. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Die Anzahl der Bits, die zum Speichern einer Farbe benötigt werden, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden
    // um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist)
    saveOptions.setDoPaletteCorrection(true);

    // Lade ein GIF‑Bild progressiv.
    // Ein interlaced GIF zeigt seine Scanlinien nicht linear von oben nach unten an, sondern ordnet sie um
    // so wird der Inhalt des GIFs bereits sichtbar, bevor es vollständig geladen ist.
    saveOptions.setInterlaced(true);

    // Als verlustfreies GIF speichern.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Lege die maximal zulässige Pixeldifferenz fest. Ist sie größer als Null, wird eine verlustbehaftete Kompression verwendet.
    // Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark.
    saveOptions.setMaxDiff(80);

    // Als verlustbehaftetes GIF speichern.
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

//Die Ausgabe könnte so aussehen:
//Größe des verlustfreien GIFs: 212816 Byte.
//Größe des verlustbehafteten GIFs: 89726 Byte.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Liest die Schleifenanzahl (Standard 1 Schleife)

Wert: Die Schleifenanzahl.

**Returns:**
int - die Schleifenanzahl (Standard 1 Schleife)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Setzt die Schleifenanzahl (Standard 1 Schleife)

Wert: Die Schleifenanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Schleifenanzahl (Standard 1 Schleife) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Liest oder setzt die GIF-Farbauflösung.

**Returns:**
byte - die Farbauflösung.

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben in der Grafik ausgewählt wurden, nicht die tatsächlich in der Grafik verwendete Farbanzahl. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Bildgenerierung. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Liest oder setzt die GIF-Farbauflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte | Die Farbauflösung. |

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben in der Grafik ausgewählt wurden, nicht die tatsächlich in der Grafik verwendete Farbanzahl. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Bildgenerierung. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Die Anzahl der Bits, die zum Speichern einer Farbe benötigt werden, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden
    // um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist)
    saveOptions.setDoPaletteCorrection(true);

    // Lade ein GIF‑Bild progressiv.
    // Ein interlaced GIF zeigt seine Scanlinien nicht linear von oben nach unten an, sondern ordnet sie um
    // so wird der Inhalt des GIFs bereits sichtbar, bevor es vollständig geladen ist.
    saveOptions.setInterlaced(true);

    // Als verlustfreies GIF speichern.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Lege die maximal zulässige Pixeldifferenz fest. Ist sie größer als Null, wird eine verlustbehaftete Kompression verwendet.
    // Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark.
    saveOptions.setMaxDiff(80);

    // Als verlustbehaftetes GIF speichern.
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

//Die Ausgabe könnte so aussehen:
//Größe des verlustfreien GIFs: 212816 Byte.
//Größe des verlustbehafteten GIFs: 89726 Byte.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind.

**Returns:**
boolean - `true` wenn Paletteneinträge sortiert sind; andernfalls `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn Paletteneinträge sortiert sind; andernfalls `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Liest oder setzt das Seitenverhältnis der GIF-Pixel.

Pixel-Seitenverhältnis – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Seitenverhältnis = (Pixel-Seitenverhältnis + 15) / 64. Das Pixel-Seitenverhältnis ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Informationen zum Seitenverhältnis angegeben. 1..255 – Wert, der in der Berechnung verwendet wird.

**Returns:**
byte - Das GIF-Pixel-Seitenverhältnis.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Liest oder setzt das Seitenverhältnis der GIF-Pixel.

Pixel-Seitenverhältnis – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Seitenverhältnis = (Pixel-Seitenverhältnis + 15) / 64. Das Pixel-Seitenverhältnis ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Informationen zum Seitenverhältnis angegeben. 1..255 – Wert, der in der Berechnung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Das GIF-Pixel-Seitenverhältnis. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Liest oder setzt den Index der GIF-Hintergrundfarbe.

**Returns:**
byte - Der GIF-Hintergrundfarbindex.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Liest oder setzt den Index der GIF-Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Der GIF-Hintergrundfarbindex. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat.

**Returns:**
boolean - `true` wenn das GIF einen Trailer hat; andernfalls `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn das GIF einen Trailer hat; andernfalls `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Wahr, wenn das Bild interlaced sein soll.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Wahr, wenn das Bild interlaced sein soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Die Anzahl der Bits, die zum Speichern einer Farbe benötigt werden, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden
    // um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist)
    saveOptions.setDoPaletteCorrection(true);

    // Lade ein GIF‑Bild progressiv.
    // Ein interlaced GIF zeigt seine Scanlinien nicht linear von oben nach unten an, sondern ordnet sie um
    // so wird der Inhalt des GIFs bereits sichtbar, bevor es vollständig geladen ist.
    saveOptions.setInterlaced(true);

    // Als verlustfreies GIF speichern.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Lege die maximal zulässige Pixeldifferenz fest. Ist sie größer als Null, wird eine verlustbehaftete Kompression verwendet.
    // Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark.
    saveOptions.setMaxDiff(80);

    // Als verlustbehaftetes GIF speichern.
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

//Die Ausgabe könnte so aussehen:
//Größe des verlustfreien GIFs: 212816 Byte.
//Größe des verlustbehafteten GIFs: 89726 Byte.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Liest oder setzt die maximal zulässige Pixeldifferenz. Wenn sie größer als null ist, wird verlustbehaftete Kompression verwendet. Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 steht für sehr leichte Kompression, 200 für starke Kompression. Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus bringen sehr hohe Verluststufen nicht so viel Gewinn. Der zulässige Wertebereich ist [0, 1000].

**Returns:**
int - Der zulässige Wertebereich.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Liest oder setzt die maximal zulässige Pixeldifferenz. Wenn sie größer als null ist, wird verlustbehaftete Kompression verwendet. Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 steht für sehr leichte Kompression, 200 für starke Kompression. Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus bringen sehr hohe Verluststufen nicht so viel Gewinn. Der zulässige Wertebereich ist [0, 1000].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der zulässige Wertebereich. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fülle das gesamte Bild mit dem blau‑gelben Verlauf.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Die Anzahl der Bits, die zum Speichern einer Farbe benötigt werden, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden
    // um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist)
    saveOptions.setDoPaletteCorrection(true);

    // Lade ein GIF‑Bild progressiv.
    // Ein interlaced GIF zeigt seine Scanlinien nicht linear von oben nach unten an, sondern ordnet sie um
    // so wird der Inhalt des GIFs bereits sichtbar, bevor es vollständig geladen ist.
    saveOptions.setInterlaced(true);

    // Als verlustfreies GIF speichern.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Lege die maximal zulässige Pixeldifferenz fest. Ist sie größer als Null, wird eine verlustbehaftete Kompression verwendet.
    // Der empfohlene Wert für optimale verlustbehaftete Kompression beträgt 80. 30 ist eine sehr leichte Kompression, 200 ist stark.
    saveOptions.setMaxDiff(80);

    // Als verlustbehaftetes GIF speichern.
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

//Die Ausgabe könnte so aussehen:
//Größe des verlustfreien GIFs: 212816 Byte.
//Größe des verlustbehafteten GIFs: 89726 Byte.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Liest die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Setzt die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | die Hintergrundfarbe. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Liefert einen Wert, der angibt, ob ein GIF-Bild eine transparente Farbe hat. Wenn der Rückgabewert `null` ist, wird diese Eigenschaft vom Kontext des Quellbildes überschrieben.

**Returns:**
java.lang.Boolean - ein Wert, der angibt, ob ein GIF-Bild eine transparente Farbe hat.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Setzt einen Wert, der angibt, ob ein GIF-Bild eine transparente Farbe hat. Wenn der Rückgabewert `null` ist, wird diese Eigenschaft vom Kontext des Quellbildes überschrieben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Boolean | ein Wert, der angibt, ob ein GIF-Bild eine transparente Farbe hat. |

