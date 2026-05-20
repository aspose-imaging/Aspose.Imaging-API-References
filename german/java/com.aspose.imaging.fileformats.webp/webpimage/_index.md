---
title: "WebPImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie WebP-Rasterbilder mit unserer API und nutzen Sie deren moderne Funktionen für verlustfreie und verlustbehaftete Kompression, um optimale Bildqualität bei reduzierter Dateigröße zu gewährleisten."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipulieren Sie WebP-Rasterbilder mit unserer API, nutzen Sie deren moderne Funktionen für verlustfreie und verlustbehaftete Kompression, um optimale Bildqualität bei reduzierten Dateigrößen zu gewährleisten. Handhaben Sie nahtlos erweiterte Dateiformate, Animationen und Alphakanäle, während Sie Dimensionen einfach aktualisieren, proportional skalieren, zuschneiden, drehen, Filter anwenden, Bildparameter anpassen und in andere Bildformate konvertieren, um eine vielseitige Web-Bildoptimierung zu ermöglichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einer bereitgestellten Stream-Quelle. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mithilfe eines Streams und angegebenen Ladeoptionen, um eine vielseitige Handhabung von WebP-Bilddaten zu ermöglichen. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einer bereitgestellten Dateiquelle. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) unter Verwendung einer Datei und angegebenen Ladeoptionen, um eine flexible Handhabung von WebP-Bilddaten zu ermöglichen. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einem bereitgestellten rasterImage-Objekt. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mithilfe eines rasterImage-Objekts und angegebenen Ladeoptionen, um eine flexible Handhabung von Bilddaten zu ermöglichen. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mit einem leeren Bild mit angegebenen Breiten- und Höhenmaßen. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mit einem leeren Bild und angegebenen Ladeoptionen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOptions()](#getOptions--) | Rufen Sie die mit der angegebenen Eigenschaft verbundenen Optionen ab oder ändern Sie sie, um eine fein abgestimmte Anpassung von Verhalten und Einstellungen zu ermöglichen. |
| [getPages()](#getPages--) | Greifen Sie auf die WebP-Blöcke im Bild zu, um eine detaillierte Untersuchung oder Manipulation der zugrunde liegenden Blockstruktur zu ermöglichen. |
| [getPageCount()](#getPageCount--) | Rufen Sie die Gesamtzahl der Seiten im angegebenen Dokument ab, um eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. |
| [getFileFormat()](#getFileFormat--) | Greifen Sie auf den Dateiformatwert zu, der dem Bild zugeordnet ist, und erhalten Sie Informationen über das Format, in dem das Bild gespeichert ist. |
| [hasAlpha()](#hasAlpha--) | Ermitteln Sie, ob das Bild einen Alphakanal enthält, was auf das Vorhandensein von Transparenzinformationen hinweist. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Fügen Sie dem Bild eine neue Seite hinzu, um dessen Inhalt zu erweitern und zusätzliche visuelle Elemente aufzunehmen. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Integrieren Sie einen neuen WebP-Block in das Bild, um dessen Inhalt zu bereichern und fortgeschrittene Bildmanipulation zu ermöglichen. |
| [clearBlocks()](#clearBlocks--) | Löschen Sie alle vorhandenen WebP-Blöcke aus dem Bild, um eine saubere Basis für nachfolgende Änderungen oder Ergänzungen zu schaffen. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Fügen Sie einen neuen WebP-Block an der angegebenen Position im Bild ein, um eine präzise Kontrolle über die Blocksequenz zu ermöglichen. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Entfernen Sie den angegebenen WebP-Block aus dem Bild, um eine effiziente Verwaltung der Bilddatenstruktur zu ermöglichen. |
| [getOriginalOptions()](#getOriginalOptions--) | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Drehen Sie das Bild um sein Zentrum um einen angegebenen Winkel, während Sie es proportional skalieren und angegebene Hintergrundfarbparameter anwenden. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Skalieren Sie das Bild, indem Sie seine Abmessungen anpassen und dabei das Seitenverhältnis beibehalten. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Passen Sie die Breite des Bildes proportional an, während Sie das Seitenverhältnis beibehalten. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Passen Sie die Höhe des Bildes proportional an, während Sie das Seitenverhältnis für eine konsistente Skalierung beibehalten. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Wenden Sie Drehung, Spiegelung oder beide Operationen ausschließlich auf den aktiven Frame im Bild an. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Führen Sie Dithering am aktuellen Bild durch, um Farbbänderungen zu reduzieren und die visuelle Qualität zu verbessern. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Zuschneiden des Bildes mit einem angegebenen Rechteckbereich, um unerwünschte Teile zu entfernen und den gewünschten Inhalt beizubehalten. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beschneiden Sie das Bild, indem Sie linke, rechte, obere und untere Verschiebungen anwenden, wodurch effektiv ein Interessensbereich im Bild ausgewählt wird. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Führen Sie eine Binarisierung des Bildes mit einem vordefinierten Schwellenwert durch, wodurch es in ein Binärbild umgewandelt wird, bei dem die Pixel basierend auf ihrer Intensität relativ zum Schwellenwert als Vordergrund oder Hintergrund klassifiziert werden. |
| [binarizeOtsu()](#binarizeOtsu--) | Führen Sie eine Binarisierung des Bildes mit Otsus Schwellenwertmethode durch, die den optimalen Schwellenwert automatisch anhand des Histogramms des Bildes bestimmt. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Wenden Sie eine Binarisierung des Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung an. |
| [grayscale()](#grayscale--) | Wenden Sie eine Binarisierung des Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung an. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Wenden Sie eine Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und die gewünschte Helligkeit sowie Farbbalance zu erreichen. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Führen Sie eine Gammakorrektur des Bildes mit einzelnen Koeffizienten für die Rot-, Grün- und Blaukanäle durch, um feine Anpassungen von Farbbalance und Kontrast zu ermöglichen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementieren Sie die `brightness`-Anpassung für das Bild, um die Gesamtlichtstärke zu ändern. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Verbessern Sie den Kontrast des [Image](../../com.aspose.imaging/image), indem Sie die Unterschiede zwischen hellen und dunklen Bereichen verstärken. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks, indem Sie einen festgelegten Bildverarbeitungsfilter anwenden, um den ausgewählten Bereich zu verbessern oder zu verändern. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändern Sie die Größe des Bildes gemäß den angegebenen Einstellungen, um eine präzise Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Laden Sie ein WebP‑Bild aus einer Datei.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Als PNG speichern
    // Beachten Sie, dass nur das aktive Bild in PNG gespeichert wird, da PNG kein Mehrseitenformat ist.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einer bereitgestellten Stream‑Quelle. Verwenden Sie diesen Konstruktor, um WebP‑Bildobjekte nahtlos direkt aus Streams zu erstellen, wodurch eine effiziente Handhabung und Manipulation von WebP‑Bilddaten in Ihrer Anwendung ermöglicht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Das Stream‑WebP‑Bild. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mithilfe eines Streams und festgelegter Ladeoptionen, um eine vielseitige Handhabung von WebP‑Bilddaten zu ermöglichen. Integrieren Sie diesen Konstruktor, um WebP‑Bildobjekte nahtlos aus Streams zu initialisieren und dabei die Ladeparameter nach Bedarf in Ihrer Anwendung anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Das Stream‑WebP‑Bild. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einer bereitgestellten Dateiquelle. Verwenden Sie diesen Konstruktor, um WebP‑Bildobjekte nahtlos direkt aus Dateien zu erstellen und den Vorgang des Ladens und Manipulierens von WebP‑Bilddaten in Ihrer Anwendung zu vereinfachen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad zur WebP‑Bilddatei |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mithilfe einer Datei und festgelegter Ladeoptionen, um eine flexible Handhabung von WebP‑Bilddaten zu ermöglichen. Verwenden Sie diesen Konstruktor, um WebP‑Bildobjekte nahtlos aus Dateien zu initialisieren und dabei die Ladeparameter gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad zur WebP‑Bilddatei |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), initialisiert aus einem bereitgestellten rasterImage‑Objekt. Dieser Konstruktor ermöglicht eine nahtlose Konvertierung von Rasterbildern in das WebP‑Format und unterstützt eine effiziente Handhabung und Manipulation von Bilddaten in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mithilfe eines rasterImage‑Objekts und festgelegter Ladeoptionen, um eine flexible Handhabung von Bilddaten zu ermöglichen. Verwenden Sie diesen Konstruktor, um WebP‑Bildobjekte nahtlos aus Rasterbildern zu initialisieren und dabei die Ladeparameter gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Instanziieren Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mit einem leeren Bild mit angegebenen Breiten‑ und Höhenmaßen. Dieser Konstruktor ermöglicht die Erstellung leerer WebP‑Bilder und bietet eine Grundlage für nachfolgende Bildmanipulationen und Inhaltserzeugung in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite |
| Höhe | int | Die Bildhöhe. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Die Optionen. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Erstellen Sie eine neue Instanz der Klasse [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) mit einem leeren Bild und festgelegten Ladeoptionen. Dieser Konstruktor ermöglicht die Initialisierung von WebP‑Bildern mit anpassbaren Ladeparametern und bietet Flexibilität bei der Bildgenerierung und -manipulation in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Bildbreite |
| Höhe | int | Die Bildhöhe. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Die Optionen. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Rufen Sie die mit der angegebenen Eigenschaft verbundenen Optionen ab oder ändern Sie sie, um eine feine Anpassung von Verhalten und Einstellungen zu ermöglichen. Verwenden Sie diese Eigenschaft, um konfigurierbare Parameter nahtlos zuzugreifen und zu manipulieren, wodurch eine vielseitige Steuerung und Optimierung der Funktionalität Ihrer Anwendung ermöglicht wird.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Greifen Sie auf die WebP‑Blöcke im Bild zu, um eine detaillierte Untersuchung oder Manipulation der zugrunde liegenden Blockstruktur zu ermöglichen. Nutzen Sie diese Eigenschaft, um einzelne Blöcke innerhalb der WebP‑Bilddaten zu analysieren oder zu ändern, wodurch fortgeschrittene Bildverarbeitungstechniken in Ihrer Anwendung unterstützt werden.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtzahl der Seiten im angegebenen Dokument ab, um eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. Integrieren Sie diese Funktion, um das Benutzererlebnis zu verbessern und nahtlosen Zugriff auf umfassende Dokumentstrukturen zu gewährleisten.

**Returns:**
int – die Seitenanzahl.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Greifen Sie auf den Dateiformatwert zu, der mit dem Bild verknüpft ist, und erhalten Sie Informationen über das Format, in dem das Bild gespeichert ist. Nutzen Sie diese Eigenschaft, um das Dateiformat des Bildes zu bestimmen, was Kompatibilitätsprüfungen und formatbezogene Verarbeitung in Ihrer Anwendung erleichtert.

**Returns:**
long – ein Wert des Dateiformats
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ermitteln Sie, ob das Bild einen Alphakanal enthält, was auf das Vorhandensein von Transparenzinformationen hinweist. Verwenden Sie diese Eigenschaft, um festzustellen, ob das Bild Transparenz aufweist, und ermöglichen Sie eine geeignete Handhabung und Verarbeitung von alpha‑bezogenen Vorgängen in Ihrer Anwendung.

**Returns:**
boolean – `true`, wenn ein Alpha‑Kanal vorhanden ist.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Hat der aktive TIFF‑Frame einen Alpha‑Kanal, wird das gesamte TIFF‑Bild als Alpha‑Kanal‑vorhanden betrachtet.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Fügen Sie dem Bild eine neue Seite hinzu, um dessen Inhalt zu erweitern und zusätzliche Bildelemente aufzunehmen. Integrieren Sie diese Methode, um ein dynamisches Seitenmanagement in Ihrer Anwendung zu ermöglichen und die nahtlose Erstellung sowie Erweiterung von mehrseitigen Dokumenten oder Bildern zu unterstützen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Die hinzuzufügende Seite. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Integrieren Sie einen neuen WebP-Block in das Bild, bereichern Sie dessen Inhalt und erleichtern Sie fortgeschrittene Bildmanipulationen. Verwenden Sie diese Methode, um die Struktur und Komplexität der WebP-Bilddaten in Ihrer Anwendung dynamisch zu verbessern, wodurch eine präzise Kontrolle und Optimierung der Bilddarstellung ermöglicht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Der hinzuzufügende WebP-Block. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Der Standardrahmen plus 36 + 36 zusätzliche Rahmen.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Erstellen Sie ein WebP-Bild mit 100x100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // Der erste Kreis ist rot
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Der zweite Kreis ist schwarz
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Erhöhen Sie schrittweise den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Erhöhen Sie schrittweise den Winkel des schwarzen Bogens und entfernen Sie den roten Bogen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // In einer WebP-Datei speichern
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Löschen Sie alle vorhandenen WebP-Blöcke aus dem Bild, um eine saubere Basis für nachfolgende Änderungen oder Ergänzungen zu schaffen. Verwenden Sie diese Methode, um die Blockstruktur in den WebP-Bilddaten effektiv zurückzusetzen und eine optimale Verwaltung und Organisation des Bildinhalts in Ihrer Anwendung sicherzustellen.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Fügen Sie einen neuen WebP-Block an dem angegebenen Index im Bild ein, um eine präzise Kontrolle über die Blocksequenz zu ermöglichen. Integrieren Sie diese Methode, um zusätzliche WebP-Blöcke nahtlos in die Bilddatenstruktur einzufügen und fortgeschrittene Bildverarbeitung sowie Optimierung in Ihrer Anwendung zu unterstützen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Das nullbasierte Element, an dem `block` eingefügt wird. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Der hinzuzufügende WebP-Block. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Entfernen Sie den angegebenen WebP-Block aus dem Bild, um eine effiziente Verwaltung der Bilddatenstruktur zu ermöglichen. Verwenden Sie diese Methode, um Bildverarbeitungsabläufe zu optimieren, indem Sie unnötige Blöcke oder Komponenten in Ihrer Anwendung entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Der zu entfernende Block. |

--------------------

Hinweis: Vergessen Sie nicht, `block` zu entsorgen, wenn Sie ihn nicht zu einem anderen WebPImage hinzufügen. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie an die [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) Methode als zweiten Parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Drehen Sie das Bild um sein Zentrum um einen angegebenen Winkel, während Sie es proportional skalieren und die angegebenen Hintergrundfarbparameter anwenden. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um präzise Transformationen mit anpassbaren Hintergrundfarben zu erreichen und eine optimale visuelle Darstellung in Ihrer Anwendung sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Skalieren Sie das Bild, passen Sie seine Abmessungen an und erhalten Sie dabei das Seitenverhältnis. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um Bilder dynamisch zu skalieren und verschiedenen Anzeige- oder Speicheranforderungen in Ihrer Anwendung gerecht zu werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Passen Sie die Breite des Bildes proportional an und erhalten Sie dabei das Seitenverhältnis. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um Bilder dynamisch mit konsistenten Proportionen zu skalieren und eine optimale Anzeige oder Speicherung in Ihrer Anwendung sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Passen Sie die Höhe des Bildes proportional an und erhalten Sie dabei das Seitenverhältnis für ein konsistentes Skalieren. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um Bilder dynamisch mit einheitlichen Proportionen zu skalieren und eine optimale Anzeige oder Speicherung in Ihrer Anwendung sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Wenden Sie Drehung, Spiegelung oder beide Operationen ausschließlich auf den aktiven Frame im Bild an. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um eine präzise Manipulation einzelner Frames zu erreichen und die Flexibilität sowie Kontrolle über Frame-Transformationen in Ihrer Anwendung zu erhöhen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Dreh‑/Spiegeltyp. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Führen Sie Dithering am aktuellen Bild durch, um Farbbänderungen zu reduzieren und die visuelle Qualität zu verbessern. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um sanftere Farbübergänge zu erzielen und das Gesamterscheinungsbild des Bildes in Ihrer Anwendung zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beschneiden Sie das Bild mithilfe eines angegebenen Rechteckbereichs, entfernen Sie unerwünschte Teile und behalten Sie den gewünschten Inhalt bei. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um bestimmte Interessensbereiche im Bild präzise zu extrahieren und zu fokussieren und so Klarheit und Komposition für verschiedene Anwendungen zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beschneiden Sie das Bild, indem Sie Verschiebungen nach links, rechts, oben und unten anwenden, um effektiv einen Interessensbereich im Bild auszuwählen. Nutzen Sie diese Methode, um gewünschte Bildteile dynamisch zu extrahieren und die Komposition sowie den Fokus gemäß den Anforderungen Ihrer Anwendung anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Führen Sie eine Binarisierung des Bildes mit einem vordefinierten Schwellenwert durch, indem Sie es in ein Binärbild umwandeln, bei dem Pixel basierend auf ihrer Intensität relativ zum Schwellenwert als Vordergrund oder Hintergrund klassifiziert werden. Integrieren Sie diese Methode in Ihren Bildverarbeitungsablauf, um Segmentierungs- und Merkmalextraktionsaufgaben zu erleichtern und die Genauigkeit sowie Effizienz nachfolgender Analysen in Ihrer Anwendung zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert (byte)255 zugewiesen, sonst 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Führen Sie die Binärisierung des Bildes mit der Otsu‑Schwellwertmethode durch und bestimmen Sie dabei automatisch den optimalen Schwellwert basierend auf dem Histogramm des Bildes. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um eine effektive Segmentierung und Merkmalsextraktion zu erreichen und die Genauigkeit sowie Zuverlässigkeit von Bildanalyseaufgaben in Ihrer Anwendung zu verbessern.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Wenden Sie die Binärisierung des Bildes mit Bradleys adaptivem Schwellwertalgorithmus und Integralbild‑Schwellwertbildung an. Diese Methode berechnet dynamisch lokale Schwellenwerte basierend auf der Nachbarschaft des Bildes, erhöht die Anpassungsfähigkeit an unterschiedliche Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende Verarbeitungsaufgaben in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Wenden Sie die Binärisierung des Bildes mit Bradleys adaptivem Schwellwertalgorithmus und Integralbild‑Schwellwertbildung an. Diese Methode berechnet dynamisch lokale Schwellenwerte basierend auf der Nachbarschaft des Bildes, erhöht die Anpassungsfähigkeit an unterschiedliche Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende Verarbeitungsaufgaben in Ihrer Anwendung.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Wenden Sie die Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und die gewünschte Helligkeit sowie Farbbalance zu erreichen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit nachfolgender Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Führen Sie die Gammakorrektur des Bildes mit einzelnen Koeffizienten für die Rot‑, Grün‑ und Blau‑Kanäle durch, um feine Anpassungen von Farbbalance und Kontrast zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um eine präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer Anwendung zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementieren Sie die `brightness`‑Anpassung für das Bild, um die Gesamthelligkeit zu verändern. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um die Sichtbarkeit zu erhöhen und die Bildqualität in Ihrer Anwendung zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Verbessern Sie den Kontrast des [Image](../../com.aspose.imaging/image), indem Sie die Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um die visuelle Klarheit und die Gesamtbildqualität in Ihrer Anwendung zu erhöhen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks, indem Sie einen festgelegten Bildverarbeitungsfilter anwenden, um den ausgewählten Bereich zu verbessern oder zu verändern. Integrieren Sie diese Methode in Ihren Bildbearbeitungs‑Workflow, um gezielte Verbesserungen oder Transformationen in Ihrer Anwendung zu erreichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skalieren Sie das Bild gemäß den angegebenen Einstellungen, um eine präzise Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um maßgeschneiderte Größenänderungsoperationen zu realisieren, die den spezifischen Anforderungen Ihrer Anwendung entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

