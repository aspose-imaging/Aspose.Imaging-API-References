---
title: "Jpeg2000Image"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie JPEG2000‑JP2‑Bilddateien effizient mit unserer API, die eine Reihe von Bits‑pro‑Pixel‑Tiefen unterstützt und eine nahtlose Verarbeitung von XMP‑Metadaten mit wesentlichen Bildinformationen ermöglicht."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Manipulieren Sie JPEG2000‑(JP2)‑Bilddateien effizient mit unserer API, die eine Reihe von Bits‑pro‑Pixel‑Tiefen unterstützt und eine nahtlose Verarbeitung von XMP‑Metadaten mit wesentlichen Bildinformationen ermöglicht. Mit Funktionen für verlustfreie Kompression stellen Sie optimale Bildqualität sicher, während die Dateiintegrität erhalten bleibt, und ermöglichen es Ihnen, JP2‑Bilder mühelos exakt nach Ihren Vorgaben anzupassen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Beginnen Sie mit der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie eine neue Instanz mit dem Pfad zu dem Bild, das Sie laden möchten, initialisieren. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Starten Sie einfach mit der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie eine neue Instanz erstellen, die sowohl den Dateipfad als auch den gewünschten Bits‑pro‑Pixel‑Parameter enthält. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Initialisieren Sie einfach eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie ein Stream‑Objekt bereitstellen. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Initialisieren Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) mit einem Stream zum Laden des Bildes sowie Bits‑pro‑Pixel‑Parametern. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Erstellen Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) und geben Sie die Parameter für Breite und Höhe an. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Instanziieren Sie ein neues [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-Objekt und geben Sie die Parameter für Breite, Höhe und Bildoptionen an. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Erstellen Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) mit Parametern für Breite, Höhe und Bitanzahl. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Instanziieren Sie eine neue Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) mit einem Rasterbild. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Initialisieren Sie eine neue [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-Instanz mit einem Rasterbild und Bits‑pro‑Pixel‑Parametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie das Format der Bilddatei ab. |
| [getRawDataFormat()](#getRawDataFormat--) | Diese Eigenschaft ruft das Rohdatenformat des Bildes ab. |
| [getRawLineSize()](#getRawLineSize--) | Diese Eigenschaft ruft die Größe einer einzelnen Zeile Rohbilddaten in Bytes ab. |
| [getWidth()](#getWidth--) | Diese Eigenschaft gibt die Breite des Bildes in Pixeln zurück. |
| [getHeight()](#getHeight--) | Diese Eigenschaft ermittelt die Höhe des Bildes in Pixeln. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Diese Eigenschaft gibt die Farbtiefe des Bildes zurück, gemessen in Bits pro Pixel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Diese Eigenschaft ermöglicht das Abrufen oder Ändern der horizontalen Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Diese Eigenschaft ermöglicht das Abrufen oder Ändern der horizontalen Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Diese Eigenschaft bietet Zugriff auf die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Diese Eigenschaft bietet Zugriff auf die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). |
| [getComments()](#getComments--) | Diese Eigenschaft ermöglicht das Abrufen oder Aktualisieren der mit dem Bild verknüpften Kommentare. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Diese Eigenschaft ermöglicht das Abrufen oder Aktualisieren der mit dem Bild verknüpften Kommentare. |
| [getCodec()](#getCodec--) | Diese Eigenschaft ruft den mit dem Bild verknüpften JPEG2000-Codec ab. |
| [getOriginalOptions()](#getOriginalOptions--) | Rufen Sie die Bildoptionen basierend auf den ursprünglichen Dateieinstellungen ab. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Laden Sie ein JPEG2000-Bild.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Als PNG speichern
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Beginnen Sie mit der Arbeit mit der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie eine neue Instanz mit dem Pfad zu dem Bild, das Sie laden möchten, initialisieren. Dieser Konstruktor ermöglicht einfachen Zugriff auf JPEG2000-Bilder und vereinfacht den Vorgang des Ladens und Handhabens von Bilddateien. Durch Angabe des Dateipfads können Sie schnell mit der Verarbeitung und Manipulation von JPEG2000-Bildern in Ihrer Anwendung beginnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Starten Sie einfach mit der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie eine neue Instanz sowohl mit dem Dateipfad als auch mit dem gewünschten Bits‑pro‑Pixel‑Parameter erstellen. Dieser Konstruktor ermöglicht eine Feinabstimmung des Bildladevorgangs und stellt die Kompatibilität mit verschiedenen Bildformaten und Qualitätseinstellungen sicher. Mit dieser Flexibilität können Sie JPEG2000-Bilder effizient verwalten und nach Ihren spezifischen Anforderungen manipulieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden |
| bitsPerPixel | int | Die Bits pro Pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Initialisieren Sie einfach eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), indem Sie ein Stream‑Objekt bereitstellen. Dieser Konstruktor vereinfacht das Laden von JPEG2000-Bildern direkt aus Streams und bietet Flexibilität sowie Komfort beim Umgang mit Bilddaten aus verschiedenen Quellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Initialisieren Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) mit einem Stream zum Laden des Bildes sowie Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor bietet Flexibilität, indem er Ihnen ermöglicht, sowohl die Bilddatenquelle als auch die gewünschten Bits pro Pixel anzugeben, und so eine feinere Kontrolle über den Bildladevorgang ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, von dem das Bild geladen und die Pixel‑ und Palettendaten initialisiert werden. |
| bitsPerPixel | int | Die Bits pro Pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Erstellen Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) und geben Sie die Parameter für Breite und Höhe an. Dieser Konstruktor ermöglicht das Initialisieren eines JPEG2000-Bildes mit spezifischen Abmessungen, was in Szenarien nützlich ist, in denen Sie programmgesteuert ein Bild einer bestimmten Größe erzeugen müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite |
| Höhe | int | Die Bildhöhe |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Instanziieren Sie ein neues [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-Objekt und geben Sie die Parameter für Breite, Höhe und Bildoptionen an. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-Bildern mit spezifischen Abmessungen und zusätzlichen Optionen und bietet Flexibilität bei der Bildgenerierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite |
| Höhe | int | Die Bildhöhe |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Die Optionen. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Erstellen Sie eine neue Instanz der Klasse [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) mit Parametern für Breite, Höhe und Bitanzahl. Dieser Konstruktor ermöglicht die Erstellung von JPEG2000-Bildern mit spezifischen Abmessungen und Bit‑Tiefen und bietet Flexibilität für verschiedene Bildgebungsanforderungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite |
| Höhe | int | Die Bildhöhe |
| bitsCount | int | Die Bitanzahl. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Instanziieren Sie eine neue [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-Klasse mit einem Rasterbild. Dieser Konstruktor erleichtert die Erstellung eines JPEG2000-Bildes aus einem bestehenden Rasterbild und ermöglicht nahtlose Integration und Konvertierung zwischen verschiedenen Bildformaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Initialisieren Sie eine neue [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image)-Instanz mit einem Rasterbild und Bits‑pro‑Pixel‑Parametern. Dieser Konstruktor ermöglicht eine präzise Kontrolle über die Qualität und Größe des resultierenden JPEG2000‑Bildes, was ihn ideal für Szenarien macht, in denen Anpassungen entscheidend sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Pixel‑ und Palettendaten initialisiert werden sollen. |
| bitsPerPixel | int | Die Bits pro Pixel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie das Format der Bilddatei ab. Diese Eigenschaft liefert Informationen über das Dateiformat des Bildes. Verwenden Sie diese Eigenschaft, um das Format der Bilddatei programmgesteuert zu bestimmen, wodurch eine geeignete Handhabung und Verarbeitung basierend auf dem Dateiformat ermöglicht wird.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Diese Eigenschaft ruft das Rohdatenformat des Bildes ab. Sie liefert Informationen darüber, wie die Pixeldaten im Speicher abgelegt sind. Verwenden Sie diese Eigenschaft, um das zugrunde liegende Datenformat des Bildes zu verstehen, was für verschiedene Bildverarbeitungsoperationen wie Farbkonvertierung, Kompression oder Dekompression entscheidend sein kann.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Diese Eigenschaft ermittelt die Größe einer einzelnen Zeile von Rohbilddaten in Bytes. Sie gibt an, wie viel Speicher eine einzelne Pixelreihe im Rohdatenformat des Bildes belegt. Das Verständnis der Rohzeilengröße ist für Aufgaben wie Speicherzuweisung, Datenmanipulation und Bildverarbeitungsalgorithmen, die auf einzelnen Bildzeilen operieren, unerlässlich.

**Returns:**
int - Die Rohzeilengröße in Bytes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Diese Eigenschaft gibt die Breite des Bildes in Pixeln zurück. Sie liefert eine grundlegende Information über die Abmessungen des Bildes, die für verschiedene Bildverarbeitungsaufgaben wie Skalierung, Zuschneiden und Rendering entscheidend ist.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Diese Eigenschaft ruft die Höhe des Bildes in Pixeln ab. Sie stellt eine wesentliche Information zum Verständnis der vertikalen Abmessungen des Bildes dar und unterstützt verschiedene Bildbearbeitungsaufgaben wie Skalierung, Zuschneiden und Rendering. Der Zugriff auf diese Eigenschaft ermöglicht es Benutzern, die vertikale Größe des Bildes zu ermitteln, wodurch ein präzises Layout und eine genaue Anzeige in Anwendungen gewährleistet werden.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Diese Eigenschaft gibt die Farbtiefe des Bildes zurück, gemessen in Bits pro Pixel (bpp). Sie gibt an, wie viel Farbinformation in jedem Pixel des Bildes gespeichert ist. Das Verständnis der Bildtiefe ist entscheidend für die Bestimmung der Farbtreue und Bildqualität. Mit diesen Informationen können Benutzer das Detailniveau und die Farbreichtum des Bildes einschätzen.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Diese Eigenschaft ermöglicht das Abrufen oder Ändern der horizontalen Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). Die Anpassung dieser Auflösung kann die Größe und Qualität des Bildes beim Druck oder der Anzeige beeinflussen. Durch das Festlegen der horizontalen Auflösung können Benutzer das Bild für bestimmte Ausgabegeräte oder Anwendungen optimieren und so die bestmöglichen visuellen Ergebnisse erzielen.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Abrufen der horizontalen und vertikalen Auflösung des Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 72.0
// Die vertikale Auflösung, in Pixel pro Zoll: 72.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 72.0
// Die vertikale Auflösung, in Pixel pro Zoll: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Diese Eigenschaft ermöglicht das Abrufen oder Ändern der horizontalen Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). Die Anpassung dieser Auflösung kann die Größe und Qualität des Bildes beim Druck oder der Anzeige beeinflussen. Durch das Festlegen der horizontalen Auflösung können Benutzer das Bild für bestimmte Ausgabegeräte oder Anwendungen optimieren und so die bestmöglichen visuellen Ergebnisse erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Diese Eigenschaft bietet Zugriff auf die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). Das Ändern dieser Auflösung kann die Qualität und Größe des Bildes beim Druck oder der Anzeige beeinflussen. Durch die Anpassung der vertikalen Auflösung können Benutzer das Bild für verschiedene Ausgabegeräte oder Anwendungen optimieren und so ein optimales visuelles Rendering gewährleisten.

**Returns:**
double - Die vertikale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Abrufen der horizontalen und vertikalen Auflösung des Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 72.0
// Die vertikale Auflösung, in Pixel pro Zoll: 72.0
// Auflösungswerte auf 96 dpi setzen
// Die horizontale Auflösung, in Pixel pro Zoll: 72.0
// Die vertikale Auflösung, in Pixel pro Zoll: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Diese Eigenschaft bietet Zugriff auf die vertikale Auflösung des [RasterImage](../../com.aspose.imaging/rasterimage), gemessen in Pixel pro Zoll (PPI). Das Ändern dieser Auflösung kann die Qualität und Größe des Bildes beim Druck oder der Anzeige beeinflussen. Durch die Anpassung der vertikalen Auflösung können Benutzer das Bild für verschiedene Ausgabegeräte oder Anwendungen optimieren und so ein optimales visuelles Rendering gewährleisten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Diese Eigenschaft ermöglicht das Abrufen oder Aktualisieren der Kommentare, die dem Bild zugeordnet sind. Kommentare liefern zusätzliche Informationen zum Bildinhalt, wie Anmerkungen, Beschreibungen oder Metadaten. Das Ändern dieser Kommentare kann nützlich sein, um Bilder zu organisieren und zu kategorisieren sowie wichtige Details an Betrachter oder Benutzer zu übermitteln.

**Returns:**
java.lang.String[] - Die Kommentare.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Diese Eigenschaft ermöglicht das Abrufen oder Aktualisieren der Kommentare, die dem Bild zugeordnet sind. Kommentare liefern zusätzliche Informationen zum Bildinhalt, wie Anmerkungen, Beschreibungen oder Metadaten. Das Ändern dieser Kommentare kann nützlich sein, um Bilder zu organisieren und zu kategorisieren sowie wichtige Details an Betrachter oder Benutzer zu übermitteln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String[] | Die Kommentare. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Diese Eigenschaft ruft den JPEG2000‑Codec ab, der dem Bild zugeordnet ist. Der JPEG2000‑Codec ist für das Kodieren und Dekodieren der Bilddaten im JPEG2000‑Format verantwortlich und bietet eine effiziente Kompression bei gleichzeitig hoher Bildqualität. Der Zugriff auf diesen Codec kann nützlich sein, um fortgeschrittene Bildverarbeitungsoperationen durchzuführen oder die Kompressionseinstellungen des Bildes an spezifische Anforderungen anzupassen.

**Returns:**
int - Der Codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Rufen Sie die Bildoptionen basierend auf den ursprünglichen Dateieinstellungen ab. Diese Methode ist nützlich, um die Farbtiefe und andere Parameter des Originalbildes beizubehalten, wodurch Konsistenz gewährleistet und die Integrität der Bilddaten erhalten bleibt. Der Zugriff auf diese Optionen erleichtert die nahtlose Handhabung und Verarbeitung des Bildes, während seine ursprünglichen Eigenschaften erhalten bleiben. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) Methode.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
