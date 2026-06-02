---
title: "MultiPageOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Basisklasse für Formate, die mehrere Seiten unterstützen"
type: docs
weight: 30
url: /de/java/com.aspose.imaging.imageoptions/multipageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Basisklasse für Formate, die mehrere Seiten unterstützen
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.imaging.IntRange---) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.imaging.IntRange-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der Klasse `MultiPageOptions`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPages()](#getPages--) | Liest oder legt die Seiten fest. |
| [setPages(int[] value)](#setPages-int---) | Liest oder legt die Seiten fest. |
| [getPageTitles()](#getPageTitles--) | Liest oder legt die Seitentitel fest. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Liest oder legt die Seitentitel fest. |
| [getTimeInterval()](#getTimeInterval--) | Liest das Zeitintervall. |
| [setTimeInterval(TimeInterval value)](#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-) | Legt das Zeitintervall fest. |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Liest die Seitenrasterisierungsoptionen. |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---) | Legt die Seitenrasterisierungsoptionen fest. |
| [getExportArea()](#getExportArea--) | Liest oder legt den Exportbereich fest. |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.imaging.Rectangle-) | Liest oder legt den Exportbereich fest. |
| [getMode()](#getMode--) | Liest oder legt den Modus fest. |
| [setMode(int value)](#setMode-int-) | Liest oder legt den Modus fest. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Liest oder legt die Namen der Ausgabelayer fest (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Liest oder legt die Namen der Ausgabelayer fest (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| [getMergeLayers()](#getMergeLayers--) | Liest einen Wert, der angibt, ob [merge layers]. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Legt einen Wert fest, der angibt, ob [merge layers]. |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.imaging.IntRange---) | Initialisiert die Seiten aus dem Bereichsarray. |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seiten | int[] | Die Seiten. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seiten | int[] | Das Array von Seiten. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Exportbereich. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Die Seitentitel. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Die Seitentitel. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Exportbereich. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.imaging.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Der `IntRange`. |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange---com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Der `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Exportbereich. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.imaging.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Der `IntRange`. |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.imaging.IntRange-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.imaging/intrange) | Der `IntRange`. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Exportbereich. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | int | Der Seitenindex. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.imaging.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Initialisiert eine neue Instanz der Klasse `MultiPageOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | int | Der Seitenindex. |
| exportArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Exportbereich. |

### getPages() {#getPages--}
```
public int[] getPages()
```


Liest oder legt die Seiten fest.

Wert: Die Seiten.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Liest oder legt die Seiten fest.

Wert: Die Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Hinweis: Wenn das Bild farbig ist, wird es automatisch gemäß der untenstehenden Option in ein B/W-Format konvertiert:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Standardmäßig werden alle Seiten im Ausgabetiff gespeichert, aber der gewünschte Satz von Seiten kann explizit angegeben werden.
        // Nur die erste und die zweite Seite werden exportiert.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Seitentitel festlegen.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Als TIFF speichern
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Liest oder legt die Seitentitel fest.

Wert: Die Seitentitel.

**Returns:**
java.lang.String[]
### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Liest oder legt die Seitentitel fest.

Wert: Die Seitentitel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |


**Example: This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        com.aspose.imaging.imageoptions.TiffOptions saveOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Hinweis: Wenn das Bild farbig ist, wird es automatisch gemäß der untenstehenden Option in ein B/W-Format konvertiert:
        saveOptions.setBitsPerSample(new int[]{1});

        saveOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.DjvuMultiPageOptions());

        // Standardmäßig werden alle Seiten im Ausgabetiff gespeichert, aber der gewünschte Satz von Seiten kann explizit angegeben werden.
        // Nur die erste und die zweite Seite werden exportiert.
        saveOptions.getMultiPageOptions().setPages(new int[]{0, 1});

        // Seitentitel festlegen.
        saveOptions.getMultiPageOptions().setPageTitles(new String[]{"The First Page", "The Second Page"});

        // Als TIFF speichern
        djvuImage.save(dir + "sample.tif", saveOptions);
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}
```

### getTimeInterval() {#getTimeInterval--}
```
public final TimeInterval getTimeInterval()
```


Liest das Zeitintervall.

Wert: Das Zeitintervall.

**Returns:**
[TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) - the time interval.
### setTimeInterval(TimeInterval value) {#setTimeInterval-com.aspose.imaging.imageoptions.TimeInterval-}
```
public final void setTimeInterval(TimeInterval value)
```


Legt das Zeitintervall fest.

Wert: Das Zeitintervall.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.imaging.imageoptions/timeinterval) | das Zeitintervall. |

### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Liest die Seitenrasterisierungsoptionen.

**Returns:**
com.aspose.imaging.imageoptions.VectorRasterizationOptions[] - die Seitenrasterisierungsoptionen.
### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Legt die Seitenrasterisierungsoptionen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | die Seitenrasterisierungsoptionen. |

### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Liest oder legt den Exportbereich fest.

Wert: Der Exportbereich.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setExportArea(Rectangle value) {#setExportArea-com.aspose.imaging.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Liest oder legt den Exportbereich fest.

Wert: Der Exportbereich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getMode() {#getMode--}
```
public int getMode()
```


Liest oder legt den Modus fest.

Wert: Der Modus.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Liest oder legt den Modus fest.

Wert: Der Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Liest oder legt die Namen der Ausgabelayer fest (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd)

Wert: Die Namen der Ausgabelayer.

**Returns:**
java.lang.String[]
### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Liest oder legt die Namen der Ausgabelayer fest (funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd)

Wert: Die Namen der Ausgabelayer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] |  |

### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Liest einen Wert, der angibt, ob [merge layers].

Wert: `true` wenn [merge layers]; sonst `false`.

**Returns:**
boolean - ein Wert, der angibt, ob [merge layers].
### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Legt einen Wert fest, der angibt, ob [merge layers].

Wert: `true` wenn [merge layers]; sonst `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [merge layers]. |

### initPages(IntRange[] ranges) {#initPages-com.aspose.imaging.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Initialisiert die Seiten aus dem Bereichsarray.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.imaging/intrange) | Die Bereiche. |

