---
title: "PngImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Bearbeiten Sie Portable Network Graphics (PNG) Rasterbilder mit unserer vielseitigen API, die Unterstützung für Komprimierungsstufen und verschiedene Farbtiefen einschließlich Graustufen, indizierter Farbe, TrueColor und Alphakanälen bietet."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Bearbeiten Sie Portable Network Graphics (PNG) Rasterbilder mit unserer vielseitigen API, die Unterstützung für Komprimierungsstufen und verschiedene Farbtiefen einschließlich Graustufen, indizierter Farbe, TrueColor und Alphakanälen bietet. Verarbeiten Sie nahtlos XMP-Metadaten, wodurch eine umfassende Bildmetadatenverwaltung ermöglicht wird, während Sie PNG-Bilder einfach laden, vielfältige Manipulationen durchführen, Filter anwenden und Bilder in andere Dateiformate konvertieren, um optimale Vielseitigkeit und Anpassbarkeit zu erreichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Initialisieren Sie ein neues Objekt der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem Sie die Parameter für Breite und Höhe angeben. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) unter Verwendung des Pfadparameters, um den Speicherort der zu ladenden Bilddatei anzugeben. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem ein Rasterbild als Parameter übergeben wird. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Initialisiert eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem der Pfad zur Bilddatei und der Farbtyp angegeben werden. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem ein Rasterbild und ein Farbtyp angegeben werden. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem sie mit einem Stream initialisiert wird. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Instanziieren Sie eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) und geben Sie die gewünschten Parameter für Breite, Höhe und Farbtyp an. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Initialisieren Sie eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) und integrieren Sie PNG-Optionen zusammen mit den Parametern für Breite und Höhe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie den Bits‑pro‑Pixel‑Wert des Bildes ab. |
| [getHeight()](#getHeight--) | Ermitteln Sie die Höhe des Bildes in Pixeln. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Rufen Sie die horizontale Auflösung des Bildes ab oder ändern Sie sie. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Rufen Sie die horizontale Auflösung des Bildes ab oder ändern Sie sie. |
| [getFileFormat()](#getFileFormat--) | Gibt das Format der mit der Bildinstanz verknüpften Datei zurück. |
| [getRawDataFormat()](#getRawDataFormat--) | Greift auf das Rohdatenformat des Bildes zu. |
| [getVerticalResolution()](#getVerticalResolution--) | Stellt Zugriff auf die vertikale Auflösung des Bildes bereit. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Stellt Zugriff auf die vertikale Auflösung des Bildes bereit. |
| [getWidth()](#getWidth--) | Ermöglicht das Abrufen der Breite des Bildes in Pixeln und liefert wesentliche Informationen über seine Abmessungen. |
| [hasTransparentColor()](#hasTransparentColor--) | Gibt einen booleschen Wert zurück, der angibt, ob das Bild eine transparente Farbe enthält. |
| [hasAlpha()](#hasAlpha--) | Gibt einen booleschen Wert zurück, der angibt, ob das Bild einen Alphakanal hat, der seine Transparenz bestimmt. |
| [getTransparentColor()](#getTransparentColor--) | Ruft die transparente Farbe des Bildes ab, falls vorhanden. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gibt einen booleschen Wert zurück, der angibt, ob das Bild eine transparente Farbe enthält. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Ändert die transparente Farbe des Bildes, falls vorhanden. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Ruft einen booleschen Wert ab, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [getBackgroundColor()](#getBackgroundColor--) | Ruft die Hintergrundfarbe des Bildes ab, falls angegeben. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ruft einen booleschen Wert ab, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Ruft die Hintergrundfarbe des Bildes ab, falls angegeben. |
| [getInterlaced()](#getInterlaced--) | Ruft einen booleschen Wert ab, der angibt, ob das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) interlaced ist, was bestimmt, ob die Bilddaten progressiv gespeichert werden, um schnelleres Laden oder Übertragen zu ermöglichen. |
| [isInterlaced()](#isInterlaced--) | Liest einen Wert, der angibt, ob diese Bildinstanz interlaced ist. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ruft die Standardoptionen ab. |
| [getOriginalOptions()](#getOriginalOptions--) | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Lade ein PNG‑Bild aus einer Datei.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Transformieren Sie das Bild in eine Graustufen-Darstellung
    pngImage.grayscale();

    // In einer Datei speichern.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Initialisieren Sie ein neues Objekt der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) durch Angabe der Breiten- und Höhenparameter. Dieser Konstruktor vereinfacht die Erstellung von PNG-Bildern, indem er Entwicklern ermöglicht, die Abmessungen direkt anzugeben, und erleichtert die effiziente Verwaltung von PNG-Bilddaten innerhalb ihrer Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Konstruiert eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) mithilfe des Pfadparameters, um den Speicherort der zu ladenden Bilddatei anzugeben. Dieser Konstruktor ermöglicht es Entwicklern, PNG-Bilder bequem aus einer Datei zu erstellen, und vereinfacht den Umgang mit PNG-Bildern in ihren Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad zum Laden eines Bildes. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) indem ein Rasterbild als Parameter übergeben wird. Dieser Konstruktor erlaubt Entwicklern, ein PNG-Bildobjekt direkt mit einem vorhandenen Rasterbild zu initialisieren und streamlinet den Prozess der Arbeit mit PNG-Bildern in ihren Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Initialisiert eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem der Pfad zur Bilddatei und der Farbtyp angegeben werden. Dieser Konstruktor ermöglicht die bequeme Erstellung von PNG-Bildern aus Dateien mit unterschiedlichen Farbtypen und bietet Flexibilität beim Umgang mit verschiedenen Bildformaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad zum Laden eines Bildes. |
| colorType | int | Der Farbtyp. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem ein Rasterbild und ein Farbtyp angegeben werden. Dieser Konstruktor ermöglicht Entwicklern, Rasterbilder direkt in das PNG-Format zu konvertieren, während der gewünschte Farbtyp festgelegt wird, und bietet Flexibilität bei der Farbdarstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| colorType | int | Der Farbtyp. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Erstellt eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem sie mit einem Stream initialisiert wird. Dieser Konstruktor erlaubt Entwicklern, PNG-Bilder direkt aus einem Stream zu laden und bietet Flexibilität beim Abrufen von Bildern aus verschiedenen Quellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream zum Laden eines Bildes. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Instanziieren Sie eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem Sie die gewünschten Breiten-, Höhen- und Farbtyp-Parameter angeben. Dieser Konstruktor ermöglicht die schnelle Erstellung von PNG-Bildern mit maßgeschneiderten Abmessungen und Farbkombinationen und erleichtert die effiziente Bildgenerierung für verschiedene Anwendungen und Workflows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| colorType | int | Der Farbtyp. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Initialisieren Sie eine neue Instanz der Klasse [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), indem Sie PNG-Optionen zusammen mit Breiten- und Höhenparametern einbinden. Dieser Konstruktor befähigt Entwickler, PNG-Bilder mit anpassbaren Einstellungen und Abmessungen zu erstellen und bietet Flexibilität bei der Bildgenerierung für unterschiedliche Anwendungsfälle.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Die PNG-Optionen. |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie den Bits‑pro‑Pixel‑Wert des Bildes ab. Diese Eigenschaft liefert wichtige Informationen zur Farbtiefe des Bildes und ermöglicht Entwicklern, das Detailniveau und die Farbgenauigkeit der Bilddaten zu verstehen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermitteln Sie die Höhe des Bildes in Pixeln. Diese Eigenschaft gibt die vertikale Dimension des Bildes zurück und ermöglicht Entwicklern, die Größe in Pixeln entlang der vertikalen Achse zu bestimmen.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Rufen Sie die horizontale Auflösung des Bildes ab oder ändern Sie sie. Diese Eigenschaft gibt die Anzahl der Pixel pro Zoll entlang der horizontalen Achse des Bildes an. Das Anpassen dieser Auflösung kann die physische Größe des Bildes beim Drucken oder Anzeigen beeinflussen.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Erhalten Sie die horizontale und vertikale Auflösung des PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die horizontale Auflösung, in Pixel pro Zoll: 96.0
//Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Rufen Sie die horizontale Auflösung des Bildes ab oder ändern Sie sie. Diese Eigenschaft gibt die Anzahl der Pixel pro Zoll entlang der horizontalen Achse des Bildes an. Das Anpassen dieser Auflösung kann die physische Größe des Bildes beim Drucken oder Anzeigen beeinflussen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft das Format der mit der Bildinstanz verknüpften Datei ab. Diese Eigenschaft liefert wesentliche Informationen zum Dateityp und ermöglicht eine effiziente Handhabung und Verarbeitung basierend auf den spezifischen Formatanforderungen.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Greift auf das Rohdatenformat des Bildes zu. Diese Eigenschaft gibt Aufschluss darüber, wie die Bilddaten intern strukturiert sind, was für fortgeschrittene Bildverarbeitungsaufgaben oder Formatkonvertierungen nützlich sein kann.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// Die zu ladenden PNG-Bilder.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bietet Zugriff auf die vertikale Auflösung des Bildes. Entwickler können diese Eigenschaft verwenden, um die Auflösungseinstellung abzurufen oder zu ändern, die die Anzahl der Pixel pro Zoll (PPI) entlang der vertikalen Achse des Bildes angibt.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Erhalten Sie die horizontale und vertikale Auflösung des PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die horizontale Auflösung, in Pixel pro Zoll: 96.0
//Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bietet Zugriff auf die vertikale Auflösung des Bildes. Entwickler können diese Eigenschaft verwenden, um die Auflösungseinstellung abzurufen oder zu ändern, die die Anzahl der Pixel pro Zoll (PPI) entlang der vertikalen Achse des Bildes angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermöglicht das Abrufen der Breite des Bildes in Pixeln und liefert wesentliche Informationen über seine Abmessungen. Diese Eigenschaft wird von Entwicklern häufig verwendet, um die Bildbreite zu bestimmen, sodass sie verschiedene Operationen basierend auf der Größe durchführen können.

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gibt einen booleschen Wert zurück, der angibt, ob das Bild eine transparente Farbe enthält. Diese Eigenschaft ist entscheidend für Anwendungen, die Transparenz verarbeiten müssen, und ermöglicht Entwicklern zu bestimmen, ob eine zusätzliche Verarbeitung erforderlich ist, um transparente Bereiche im Bild zu handhaben.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen booleschen Wert zurück, der angibt, ob das Bild einen Alpha-Kanal hat, der seine Transparenz bestimmt. Diese Eigenschaft ist nützlich für Anwendungen, die Transparenz handhaben müssen, und ermöglicht Entwicklern zu bestimmen, ob zusätzliche Verarbeitung erforderlich ist, um transparente Bereiche im Bild zu behandeln.

**Returns:**
boolean - `true`, wenn diese Instanz Alpha hat; andernfalls `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Hilfsklasse
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

// Alle unterstützten PNG-Farbtypen abrufen.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// Die Ausgabe sieht folgendermaßen aus:
// Ein Graustufen-PNG-Bild unterstützt keinen Alpha-Kanal
// Ein Truecolor-PNG-Bild unterstützt keinen Alpha-Kanal
// Ein IndexedColor-PNG-Bild unterstützt keinen Alpha-Kanal
// Ein GrayscaleWithAlpha-PNG-Bild unterstützt einen Alpha-Kanal
// Ein TruecolorWithAlpha-PNG-Bild unterstützt einen Alpha-Kanal
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Ruft die transparente Farbe des Bildes ab, falls sie vorhanden ist. Diese Eigenschaft ist wertvoll für Anwendungen, die eine präzise Handhabung transparenter Bereiche innerhalb von Bildern erfordern, und ermöglicht Entwicklern den Zugriff auf und die Manipulation der verwendeten spezifischen transparenten Farbe.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Gibt einen booleschen Wert zurück, der angibt, ob das Bild eine transparente Farbe enthält. Diese Eigenschaft ist entscheidend für Anwendungen, die Transparenz verarbeiten müssen, und ermöglicht Entwicklern zu bestimmen, ob eine zusätzliche Verarbeitung erforderlich ist, um transparente Bereiche im Bild zu handhaben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Erstelle ein TrueColor-PNG-Bild mit 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alle roten Pixel werden als vollständig transparent betrachtet.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alle transparenten Pixel erhalten eine Hintergrundfarbe.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fülle das gesamte Bild mit weißer Farbe.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fülle das obere linke Viertel des Bildes mit der transparenten Farbe.
    // Dadurch wird das obere linke Viertel in der Hintergrundfarbe eingefärbt.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Ändert die transparente Farbe des Bildes, falls sie vorhanden ist. Diese Eigenschaft ist wertvoll für Anwendungen, die eine präzise Handhabung transparenter Bereiche innerhalb von Bildern erfordern, und ermöglicht Entwicklern den Zugriff auf und die Manipulation der verwendeten spezifischen transparenten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Erstelle ein TrueColor-PNG-Bild mit 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alle roten Pixel werden als vollständig transparent betrachtet.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alle transparenten Pixel erhalten eine Hintergrundfarbe.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fülle das gesamte Bild mit weißer Farbe.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fülle das obere linke Viertel des Bildes mit der transparenten Farbe.
    // Dadurch wird das obere linke Viertel in der Hintergrundfarbe eingefärbt.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Ruft einen booleschen Wert ab, der angibt, ob das Bild eine Hintergrundfarbe hat. Diese Eigenschaft ist nützlich für Anwendungen, die bestimmen müssen, ob ein Bild eine Hintergrundfarbe enthält, was für verschiedene Verarbeitungsaufgaben wie Compositing, Rendering oder Export wichtig sein kann.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ruft die Hintergrundfarbe des Bildes ab, falls eine angegeben ist. Diese Eigenschaft ist hilfreich für Anwendungen, die die Hintergrundfarbe eines Bildes identifizieren und ggf. manipulieren müssen.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ruft einen booleschen Wert ab, der angibt, ob das Bild eine Hintergrundfarbe hat. Diese Eigenschaft ist nützlich für Anwendungen, die bestimmen müssen, ob ein Bild eine Hintergrundfarbe enthält, was für verschiedene Verarbeitungsaufgaben wie Compositing, Rendering oder Export wichtig sein kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Erstelle ein TrueColor-PNG-Bild mit 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alle roten Pixel werden als vollständig transparent betrachtet.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alle transparenten Pixel erhalten eine Hintergrundfarbe.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fülle das gesamte Bild mit weißer Farbe.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fülle das obere linke Viertel des Bildes mit der transparenten Farbe.
    // Dadurch wird das obere linke Viertel in der Hintergrundfarbe eingefärbt.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ruft die Hintergrundfarbe des Bildes ab, falls eine angegeben ist. Diese Eigenschaft ist hilfreich für Anwendungen, die die Hintergrundfarbe eines Bildes identifizieren und ggf. manipulieren müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Erstelle ein TrueColor-PNG-Bild mit 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Alle roten Pixel werden als vollständig transparent betrachtet.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Alle transparenten Pixel erhalten eine Hintergrundfarbe.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fülle das gesamte Bild mit weißer Farbe.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fülle das obere linke Viertel des Bildes mit der transparenten Farbe.
    // Dadurch wird das obere linke Viertel in der Hintergrundfarbe eingefärbt.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Ruft einen booleschen Wert ab, der angibt, ob das [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) interlaced ist, was bestimmt, ob die Bilddaten progressiv gespeichert werden, um schnelleres Laden oder Übertragen zu ermöglichen.

**Returns:**
boolean - `true`, wenn interlaced; sonst `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Liest einen Wert, der angibt, ob diese Bildinstanz interlaced ist.

Wert: `true`, wenn diese Bildinstanz interlaced ist; sonst `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Bildinstanz interlaced ist.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Ruft die Standardoptionen ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | java.lang.Object[] | Die Argumente. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Holt die Optionen basierend auf den Einstellungen der Originaldatei. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der `DataStreamSupporter.Save(string)`‑Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie an die `Image.Save(string, ImageOptionsBase)`‑Methode als zweiten Parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
