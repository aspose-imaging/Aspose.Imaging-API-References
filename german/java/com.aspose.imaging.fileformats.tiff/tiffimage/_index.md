---
title: "TiffImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Verarbeiten Sie Tagged Image File Format (TIFF) Rasterbilder mit unserer API, die umfassende Unterstützung für verschiedene Auflösungen und erweiterte Bearbeitungsfunktionen wie EXIF‑Datenmanipulation und Alphakanäle bietet."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Verarbeiten Sie Tagged Image File Format (TIFF) Rasterbilder mit unserer API, die umfassende Unterstützung für verschiedene Auflösungen und erweiterte Bearbeitungsfunktionen wie EXIF‑Datenmanipulation und Alphakanäle bietet. Normalisieren Sie Winkel für gescannte Bilder, skalieren Sie, wandeln Sie in Graustufen um und wenden Sie mühelos Filter, Gammakorrekturen und Bildparameter‑Anpassungen an. Handhaben Sie nahtlos mehrseitige TIFF‑Dateien, erstellen Sie Grafikpfade, fügen Sie Formen hinzu und speichern Sie Bilder mühelos in verschiedenen Formaten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Initialisieren Sie ein neues Objekt der Klasse [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) und geben Sie den Frame‑Parameter an. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Erstellen Sie eine neue Instanz der Klasse [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) und übergeben Sie eine Liste von Frames als Parameter. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie den Dateiformatwert ab, der dem Bild zugeordnet ist. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Geben Sie an, ob Komponenten eine Vormultiplikation benötigen, um eine effiziente Handhabung visueller Elemente zu gewährleisten. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Geben Sie an, ob Komponenten eine Vormultiplikation benötigen, um eine effiziente Handhabung visueller Elemente zu gewährleisten. |
| [getByteOrder()](#getByteOrder--) | Schalten Sie die Byte‑Reihenfolge für TIFF‑Dateien nahtlos um und gewährleisten Sie eine präzise Kontrolle über die Dateninterpretation. |
| [setByteOrder(int value)](#setByteOrder-int-) | Schalten Sie die Byte‑Reihenfolge für TIFF‑Dateien nahtlos um und gewährleisten Sie eine präzise Kontrolle über die Dateninterpretation. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Rufen Sie die horizontale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll ab, um präzise Anpassungen und Rendering‑Funktionen zu ermöglichen. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ändert die horizontale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll und ermöglicht präzise Anpassungen sowie Rendering‑Funktionen. |
| [getVerticalResolution()](#getVerticalResolution--) | Greifen Sie auf die vertikale Auflösung des bezeichneten [Image](../../com.aspose.imaging/image) in Pixel pro Zoll zu, um präzise Anpassungen und Rendering‑Optimierungen zu ermöglichen. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Greifen Sie auf die vertikale Auflösung des bezeichneten [Image](../../com.aspose.imaging/image) in Pixel pro Zoll zu, um präzise Anpassungen und Rendering‑Optimierungen zu ermöglichen. |
| [getActiveFrame()](#getActiveFrame--) | Verwalten Sie den aktiven Frame nahtlos, um eine dynamische Navigation und Manipulation im vorgesehenen Kontext zu ermöglichen. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Verwalten Sie den aktiven Frame nahtlos, um eine dynamische Navigation und Manipulation im vorgesehenen Kontext zu ermöglichen. |
| [getFrames()](#getFrames--) | Rufen Sie ein Array von [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-Instanzen ab, um umfassenden Zugriff und Manipulation einzelner Frames im TIFF‑Bild zu ermöglichen. |
| [getPageCount()](#getPageCount--) | Rufen Sie die Gesamtzahl der Seiten im angegebenen Dokument ab, um eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. |
| [getPages()](#getPages--) | Greifen Sie nahtlos auf die Seiten des Dokuments zu, um eine dynamische Navigation und Manipulation innerhalb der Inhaltsstruktur zu ermöglichen. |
| [hasAlpha()](#hasAlpha--) | Bestimmen Sie, ob das Bild einen Alphakanal besitzt, um wichtige Informationen für Rendering‑ und Compositing‑Operationen zu erhalten. |
| [removeMetadata()](#removeMetadata--) | Entfernt die Metadaten dieser Bildinstanz, indem dieser `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) Wert auf `null` gesetzt wird. |
| [getOriginalOptions()](#getOriginalOptions--) | Rufen Sie Optionen ab, die aus den ursprünglichen Dateieinstellungen abgeleitet sind, um die nahtlose Bewahrung wichtiger Parameter wie Bit‑Tiefe und anderer wesentlicher Attribute des Originalbildes zu ermöglichen. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Fügen Sie nahtlos eine neue Seite in das bestehende Bild ein und erweitern Sie dessen Inhalt und Vielseitigkeit. |
| [alignResolutions()](#alignResolutions--) | Implementieren Sie die Hilfsmethode AlignResolutions, um horizontale und vertikale Auflösungen zu synchronisieren und Einheitlichkeit in den Bildabmessungen sicherzustellen. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Legt die Auflösung für das angegebene [RasterImage](../../com.aspose.imaging/rasterimage) fest und ermöglicht eine präzise Kontrolle über das Rendering und die Anzeigeeigenschaften des Bildes. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Verwenden Sie die Methode NormalizeAngle, die speziell für gescannte Textdokumente entwickelt wurde, um schiefe Scans zu korrigieren und eine genaue Ausrichtung sicherzustellen. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Integrieren Sie den angegebenen Rahmen nahtlos in das Bild, wodurch dessen Inhalt und Vielseitigkeit erweitert werden. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Fügen Sie die Rahmen aus dem angegebenen Bild nahtlos in den aktuellen Rahmen ein, konsolidieren deren Inhalt und erhöhen die gestalterische Flexibilität. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Integrieren Sie das Array von Rahmen nahtlos in das Bild, wodurch dessen Inhalt und Vielseitigkeit bereichert werden. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Fügen Sie den neuen Rahmen an dem angegebenen Index innerhalb der Rahmenfolge ein, um eine präzise Kontrolle über die Anordnung der Rahmen zu gewährleisten. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Ersetzen Sie den Rahmen an der festgelegten Position durch einen anderen Rahmen nahtlos, um ein dynamisches Rahmenmanagement innerhalb der Bildsequenz zu ermöglichen. |
| [removeFrame(int index)](#removeFrame-int-) | Entfernen Sie mühelos den durch seinen Index identifizierten Rahmen aus der Bildsequenz, um das Rahmenmanagement in Ihrer Anwendung zu optimieren. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Entfernen Sie den angegebenen Rahmen effizient aus der Bildsequenz, um ein schlankes Rahmenmanagement in Ihrer Anwendung zu ermöglichen. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis erhalten bleibt, während die Abmessungen angepasst werden. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Passen Sie die Breite des Bildes an, während das Seitenverhältnis beibehalten wird, um eine proportionale Größenänderung für eine optimale visuelle Darstellung sicherzustellen. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Führen Sie eine proportionale Anpassung der Bildhöhe durch, wobei das Seitenverhältnis erhalten bleibt, um eine konsistente visuelle Integrität zu gewährleisten. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Führen Sie Rotation, Spiegelung oder eine Kombination beider Operationen ausschließlich am aktiven Rahmen durch. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Wenden Sie Dithering auf das aktuelle Bild an, um dessen visuelle Qualität zu verbessern und Farbband-Artefakte zu reduzieren. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beschneiden Sie das Bild mithilfe eines angegebenen rechteckigen Bereichs, um eine präzise Auswahl des gewünschten Inhalts zu ermöglichen. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Beschneiden Sie das Bild, indem Sie Verschiebungen nach links, rechts, oben und unten angeben. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Wenden Sie die Binarisierung auf das Bild mit einem vordefinierten Schwellenwert an, wodurch es in ein Binärbild mit klaren Vorder- und Hintergrundbereichen umgewandelt wird. |
| [binarizeOtsu()](#binarizeOtsu--) | Verwenden Sie die Otsu‑Schwellenwertbestimmung, um das Bild zu binarisieren, wobei der optimale Schwellenwert automatisch anhand des Histogramms des Bildes ermittelt wird. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Implementieren Sie die Binarisierung des Bildes mithilfe von Bradleys adaptivem Schwellenwertalgorithmus mit Integralbild‑Schwellenwertbestimmung. |
| [grayscale()](#grayscale--) | Konvertieren Sie das Bild in seine Graustufen‑Darstellung, wodurch es zu einem einkanaligen Bild wird, bei dem jeder Pixel die Intensität repräsentiert. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Wenden Sie die Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und die gewünschte Farbbalance zu erreichen. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Führen Sie die Gammakorrektur am Bild unter Verwendung einzelner Koeffizienten für die Rot-, Grün- und Blaukanäle durch, um feine Anpassungen von Farbbalance und Kontrast zu ermöglichen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implementieren Sie die `brightness`-Anpassung für das Bild, um die Gesamtlichtstärke zu ändern. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Verbessern Sie den Kontrast der [Image](../../com.aspose.imaging/image)-Instanz, um die Unterschiede zwischen hellen und dunklen Bereichen zu verstärken. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtern Sie den Inhalt innerhalb des angegebenen Rechtecks, indem Sie einen festgelegten Bildverarbeitungsfilter anwenden, um den ausgewählten Bereich zu verbessern oder zu verändern. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Passen Sie die Größe des Bildes anhand der angegebenen Einstellungen an, um eine präzise Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Erstellen Sie den GraphicsPath mithilfe von PathResources aus einem TIFF-Bild
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Zeichnen Sie eine rote Linie und speichern Sie das Bild
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Erstellen Sie eine rechteckige Figure für den GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Erstellen Sie den GraphicsPath mithilfe unserer Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Setzen Sie PathResources mithilfe des GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Speichern Sie das Bild
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Initialisieren Sie ein neues Objekt der Klasse [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) und geben Sie den Frame-Parameter an. Dieser Konstruktor erleichtert die Erstellung einer TiffImage-Instanz, sodass Entwickler den zu ladenden oder zu verarbeitenden Frame angeben können, und optimiert die Aufgaben der Tiff-Bildverarbeitung in ihren Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der TIFF-Frame, mit dem das Bild initialisiert wird. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Erstellen Sie eine neue Instanz der Klasse [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) und übergeben Sie eine Liste von Frames als Parameter. Dieser Konstruktor ermöglicht die Initialisierung eines TiffImage-Objekts mit mehreren Frames und erleichtert die effiziente Handhabung und Verarbeitung von TIFF-Bildsequenzen in Softwareanwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Die Frames. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie den Dateiformatwert ab, der dem Bild zugeordnet ist. Diese Eigenschaft ist ein kritischer Aspekt der Metadatenabfrage für Bilder und ermöglicht es Softwareanwendungen, das Format der Bilddaten effizient zu identifizieren und zu interpretieren.

**Returns:**
long – ein Wert des Dateiformats
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Gibt an, ob Komponenten eine Vormultiplikation benötigen, um eine effiziente Handhabung visueller Elemente zu gewährleisten. Verbessern Sie Renderprozesse, indem Sie diese Eigenschaft umschalten, und optimieren Sie Grafik-Workflows für eine bessere Leistung.

**Returns:**
boolean – `true`, wenn Komponenten vormultipiziert werden müssen; andernfalls `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Gibt an, ob Komponenten eine Vormultiplikation benötigen, um eine effiziente Handhabung visueller Elemente zu gewährleisten. Verbessern Sie Renderprozesse, indem Sie diese Eigenschaft umschalten, und optimieren Sie Grafik-Workflows für eine bessere Leistung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn Komponenten vormultipiziert werden müssen; andernfalls `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Pixel für das gesamte Bild speichern.
    image.savePixels(image.getBounds(), colors);

    // Die Pixel werden im Originalbild in nicht vormultiplizierter Form gespeichert.
    // Die entsprechende Option muss explizit angegeben werden, um vormultiplizierte Farbkomponenten zu erhalten.
    // Die vormultiplizierten Farbkomponenten werden mit den Formeln berechnet:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//Die Ausgabe sieht folgendermaßen aus:
//Ursprüngliche Farbe: Color [A=127, R=255, G=0, B=0]
//Vormultiplizierte Farbe: Color [A=127, R=127, G=0, B=0]
//Ursprüngliche Farbe: Color [A=127, R=0, G=255, B=0]
//Vormultiplizierte Farbe: Color [A=127, R=0, G=127, B=0]
//Ursprüngliche Farbe: Color [A=127, R=0, G=0, B=255]
//Vormultiplizierte Farbe: Color [A=127, R=0, G=0, B=127]
//Ursprüngliche Farbe: Color [A=127, R=255, G=255, B=0]
//Vormultiplizierte Farbe: Color [A=127, R=127, G=127, B=0]
//Ursprüngliche Farbe: Color [A=127, R=255, G=0, B=255]
//Vormultiplizierte Farbe: Color [A=127, R=127, G=0, B=127]
//Originalfarbe: Color [A=127, R=0, G=255, B=255]
//Vormultiplizierte Farbe: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Schalten Sie die Byte-Reihenfolge für TIFF-Dateien nahtlos um und gewährleisten Sie eine präzise Kontrolle über die Dateninterpretation. Ermöglichen Sie Ihren Anwendungen die Flexibilität, sich an unterschiedliche Dateispezifikationen anzupassen, und verbessern Sie damit die Kompatibilität und Effizienz bei der Datenverarbeitung.

**Returns:**
int – Die TIFF-Byte-Reihenfolge.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Schalten Sie die Byte-Reihenfolge für TIFF-Dateien nahtlos um und gewährleisten Sie eine präzise Kontrolle über die Dateninterpretation. Ermöglichen Sie Ihren Anwendungen die Flexibilität, sich an unterschiedliche Dateispezifikationen anzupassen, und verbessern Sie damit die Kompatibilität und Effizienz bei der Datenverarbeitung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die TIFF-Byte-Reihenfolge. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Rufen Sie die horizontale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll ab, um präzise Anpassungen und Rendering‑Funktionen zu ermöglichen. Greifen Sie mühelos auf wesentliche Bildmetadaten zu und unterstützen Sie optimierte Bildverarbeitungs‑Workflows für verbesserte Benutzererlebnisse.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ermitteln Sie die horizontale und vertikale Auflösung des TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Ändert die horizontale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll, um präzise Anpassungen und Rendering‑Funktionen zu ermöglichen. Greifen Sie mühelos auf wesentliche Bildmetadaten zu und unterstützen Sie optimierte Bildverarbeitungs‑Workflows für verbesserte Benutzererlebnisse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Greifen Sie auf die vertikale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll zu, um präzise Anpassungen und Rendering‑Optimierungen zu ermöglichen. Nutzen Sie wesentliche Bilddaten mühelos, um Bildverarbeitungs‑Workflows zu optimieren und in Ihren Anwendungen eine hervorragende Qualität und Leistung sicherzustellen.

**Returns:**
double - Die vertikale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ermitteln Sie die horizontale und vertikale Auflösung des TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Greifen Sie auf die vertikale Auflösung des angegebenen [Image](../../com.aspose.imaging/image) in Pixel pro Zoll zu, um präzise Anpassungen und Rendering‑Optimierungen zu ermöglichen. Nutzen Sie wesentliche Bilddaten mühelos, um Bildverarbeitungs‑Workflows zu optimieren und in Ihren Anwendungen eine hervorragende Qualität und Leistung sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Verwalten Sie den aktiven Frame nahtlos und ermöglichen Sie eine dynamische Navigation sowie Manipulation im jeweiligen Kontext. Ermöglichen Sie Ihrer Anwendung eine effiziente Interaktion mit Multimedia‑Inhalten, um die Benutzerbindung und Produktivität zu steigern.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Verwalten Sie den aktiven Frame nahtlos und ermöglichen Sie eine dynamische Navigation sowie Manipulation im jeweiligen Kontext. Ermöglichen Sie Ihrer Anwendung eine effiziente Interaktion mit Multimedia‑Inhalten, um die Benutzerbindung und Produktivität zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Aktiver Frame. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Rufen Sie ein Array von [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-Instanzen ab, um umfassenden Zugriff und Manipulation einzelner Frames im TIFF‑Bild zu ermöglichen. Nutzen Sie die Möglichkeiten dieses Arrays, um Bildverarbeitungs‑Workflows zu optimieren und eine präzise Kontrolle sowie Optimierung des visuellen Inhalts sicherzustellen.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] – das [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe)-Array.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtzahl der Seiten im angegebenen Dokument ab, um eine effiziente Navigation und Verwaltung von mehrseitigem Inhalt zu ermöglichen. Integrieren Sie diese Funktion, um das Benutzererlebnis zu verbessern und nahtlosen Zugriff auf umfassende Dokumentstrukturen zu gewährleisten.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Greifen Sie nahtlos auf die Seiten des Dokuments zu und ermöglichen Sie eine dynamische Navigation sowie Manipulation innerhalb der Inhaltsstruktur. Statten Sie Ihre Anwendung mit effizientem Zugriff auf einzelne Seiten aus, um die Dokumentenverarbeitung zu optimieren und die Benutzerinteraktion zu verbessern.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestimmen Sie, ob das Bild einen Alpha‑Kanal besitzt, um wichtige Informationen für Rendering‑ und Kompositionsvorgänge zu erhalten. Integrieren Sie diese Funktion, um visuelle Verarbeitungs‑Workflows zu optimieren und eine genaue Darstellung sowie Manipulation transparenter Elemente sicherzustellen.

**Returns:**
boolean – `true`, wenn ein Alpha‑Kanal vorhanden ist.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Hat der aktive TIFF‑Frame einen Alpha‑Kanal, wird das gesamte TIFF‑Bild als Alpha‑Kanal‑vorhanden betrachtet.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Entfernt die Metadaten dieser Bildinstanz, indem dieser `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) Wert auf `null` gesetzt wird.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Rufen Sie Optionen ab, die aus den ursprünglichen Dateieinstellungen abgeleitet sind, um eine nahtlose Bewahrung wichtiger Parameter wie Bit‑Tiefe und anderer wesentlicher Attribute des Originalbildes zu ermöglichen. Verwenden Sie diese Methode, um Treue und Konsistenz bei Bildverarbeitungsaufgaben zu erhalten und optimale Ergebnisse ohne unnötige Änderungen sicherzustellen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der Methode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG‑Bild mit 1 Bit pro Pixel zu speichern, nutzen Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie als zweiten Parameter an die Methode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) zu übergeben.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Integrieren Sie eine neue Seite nahtlos in das bestehende Bild, erweitern Sie dessen Inhalt und Vielseitigkeit. Nutzen Sie diese Methode, um die Dokumentenzusammensetzung und -verwaltung zu verbessern und eine effiziente Handhabung von mehrseitigen Bildern in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Die hinzuzufügende Seite. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implementieren Sie die Hilfsmethode AlignResolutions, um horizontale und vertikale Auflösungen zu synchronisieren und damit Einheitlichkeit in den Bildabmessungen zu gewährleisten. Diese Funktionalität erleichtert optimierte Bildverarbeitungs‑Workflows, indem sie Auflösungsparameter harmonisiert und die visuelle Qualität sowie Konsistenz über verschiedene Plattformen und Geräte hinweg optimiert.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Legt die Auflösung für das angegebene [RasterImage](../../com.aspose.imaging/rasterimage) fest und ermöglicht damit eine präzise Kontrolle über Bildrendering und Anzeigeeigenschaften. Integrieren Sie diese Funktion, um die visuelle Ausgabe zu optimieren und die Kompatibilität mit verschiedenen Ausgabegeräten und Plattformen sicherzustellen, wodurch das gesamte Benutzererlebnis verbessert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | Die vertikale Auflösung in Punkten pro Zoll (dpi) des [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Ermitteln Sie die horizontale und vertikale Auflösung des TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die horizontale Auflösung, in Pixel pro Zoll: 96.0
// Die vertikale Auflösung, in Pixel pro Zoll: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Verwenden Sie die speziell für gescannte Textdokumente entwickelte Methode NormalizeAngle, um verzerrte Scans zu korrigieren und eine genaue Ausrichtung sicherzustellen. Integrieren Sie diese Funktion nahtlos in Ihre Textverarbeitungs‑Workflows, um die Lesbarkeit und Qualität von Dokumenten zu verbessern und die Gesamteffizienz bei Texterkennung und Analyseaufgaben zu steigern. Diese Methode nutzt die Methoden [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) und [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Integrieren Sie den angegebenen Frame nahtlos in das Bild, erweitern Sie dessen Inhalt und Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Mehrfach‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der hinzuzufügende Frame. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Fügen Sie die Frames des angegebenen Bildes nahtlos in den aktuellen Frame ein, konsolidieren Sie deren Inhalt und erhöhen Sie die Flexibilität der Komposition. Integrieren Sie diese Methode, um die Frame‑Verwaltung und -Manipulation in Ihrer Anwendung zu optimieren und eine effiziente Handhabung von Mehrfach‑Frame‑Bildern zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | Das Quellbild. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integrieren Sie das Array von Frames nahtlos in das Bild, bereichern Sie dessen Inhalt und Vielseitigkeit. Nutzen Sie diese Methode, um die Bildkomposition und -verwaltung zu verbessern und eine effiziente Handhabung von Mehrfach‑Frame‑Bildern in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Das hinzuzufügende Frame‑Array |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Fügen Sie den neuen Frame an dem angegebenen Index innerhalb der Frame‑Sequenz ein, um eine präzise Kontrolle über die Anordnung der Frames zu gewährleisten. Verwenden Sie diese Methode, um Frame‑Sequenzen effektiv zu verwalten und eine dynamische Manipulation sowie Organisation von Bildinhalten in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der Index des `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der einzufügende Frame. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Ersetzen Sie den Frame an der vorgesehenen Position nahtlos durch einen anderen Frame, um eine dynamische Frame‑Verwaltung innerhalb der Bildsequenz zu ermöglichen. Integrieren Sie diese Methode, um Flexibilität und Präzision bei der Frame‑Manipulation zu erhöhen und eine optimale Organisation sowie Darstellung von Bildinhalten in Ihrer Anwendung sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Die nullbasierte Frame‑Position. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der zu ersetzende Frame. |

Hinweis: Vergessen Sie nicht, den Frame zu entsorgen/schließen, wenn Sie ihn nicht zu einem anderen TiffImage hinzufügen. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Entfernen Sie mühelos den anhand seines Index identifizierten Frame aus der Bildsequenz und vereinfachen Sie die Frame‑Verwaltung in Ihrer Anwendung. Integrieren Sie diese Funktion, um Effizienz und Präzision bei der Frame‑Manipulation zu steigern und eine nahtlose Organisation sowie Darstellung von Bildinhalten zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | index | int | Index des zu entfernenden Frames. |

--------------------

Hinweis: Vergessen Sie nicht, den Frame zu entsorgen, wenn Sie ihn nicht zu einem anderen TiffImage hinzufügen. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Entfernen Sie den angegebenen Frame effizient aus der Bildsequenz, um eine optimierte Frame‑Verwaltung in Ihrer Anwendung zu ermöglichen. Integrieren Sie diese Funktion, um Präzision und Flexibilität bei der Frame‑Manipulation zu erhöhen und eine nahtlose Organisation sowie Darstellung von Bildinhalten sicherzustellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der zu entfernende Frame. |

--------------------

Hinweis: Vergessen Sie nicht, den Frame zu entsorgen, wenn Sie ihn nicht zu einem anderen TiffImage hinzufügen. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Führen Sie eine proportionale Größenänderung des Bildes durch, wobei das Seitenverhältnis beibehalten und die Abmessungen angepasst werden. Verwenden Sie diese Methode, um Bilder in Ihrer Anwendung dynamisch zu skalieren und eine konsistente visuelle Darstellung der Inhaltsintegrität sicherzustellen. Die proportionale Größenänderung passt jeden Frame gemäß dem Verhältnis von `newWidth`/width und `newHeight`/height an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Passen Sie die Breite des Bildes an, während Sie das Seitenverhältnis beibehalten, um eine proportionale Größenänderung für eine optimale visuelle Darstellung sicherzustellen. Nutzen Sie diese Methode, um Bilder dynamisch in Ihrer Anwendung zu skalieren und eine konsistente sowie ästhetisch ansprechende Darstellung in verschiedenen Anzeigeumgebungen zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein TIFF‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Breite angegeben, die Höhe wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Führen Sie eine proportionale Anpassung der Bildhöhe durch und erhalten Sie das Seitenverhältnis für eine konsistente visuelle Integrität. Verwenden Sie diese Methode, um Bilder dynamisch in Ihrer Anwendung zu skalieren und eine optimale Anzeige auf verschiedenen Plattformen und Geräten zu gewährleisten, ohne die Inhaltsqualität zu beeinträchtigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein TIFF‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Höhe angegeben, die Breite wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Führen Sie eine Rotation, Spiegelung oder eine Kombination beider Operationen ausschließlich am aktiven Frame durch. Diese Methode ermöglicht eine präzise Manipulation einzelner Frames innerhalb der Bildsequenz und erhöht die Flexibilität bei der Bildbearbeitung und -komposition in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Rotations‑ und Spiegelungstyp. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Dies ist eine Hilfsklasse.
class Utils {
    // Gibt eine Zeichenkettenrepräsentation des Rotations‑Flip‑Typs zurück.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Drehen, spiegeln und in die Ausgabedatei speichern.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Wenden Sie Dithering auf das aktuelle Bild an, um die visuelle Qualität zu verbessern und Farbbanding-Artefakte zu reduzieren. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um sanftere Farbübergänge zu gewährleisten, was zu einer verbesserten Gesamtdarstellung und Klarheit des Bildes führt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Führen Sie Schwellenwert-Dithering mit einer 4‑Bit-Farbpalette durch, die 16 Farben enthält.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Führen Sie Floyd-Dithering mit einer 1‑Bit-Farbpalette durch, die nur 2 Farben enthält – Schwarz und Weiß.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beschneiden Sie das Bild mit einem angegebenen rechteckigen Bereich, um eine präzise Auswahl des gewünschten Inhalts zu ermöglichen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um unerwünschte Bereiche effizient zu entfernen und sich auf wesentliche Details zu konzentrieren, wodurch die Gesamtklarheit und Komposition des Bildes verbessert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |


**Example: The following example crops a TIFF image.**
Das folgende Beispiel schneidet ein TIFF‑Bild zu. Der Beschneidungsbereich wird über Aspose.Imaging.Rectangle angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Schneiden Sie das Bild zu. Der Zuschnittsbereich ist der rechteckige zentrale Bereich des Bildes.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Speichern Sie das zugeschnittene Bild als PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beschneiden Sie das Bild, indem Sie Verschiebungen nach links, rechts, oben und unten angeben. Diese Methode ermöglicht eine präzise Auswahl des gewünschten Bildausschnitts, erleichtert das effiziente Entfernen unerwünschter Bereiche und das Fokussieren auf wesentliche Inhalte. Integrieren Sie diese Funktionalität in Ihre Bildverarbeitungspipeline, um bei Bedarf Klarheit und Komposition in Ihrer Anwendung zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |


**Example: The following example crops a TIFF image.**
Das folgende Beispiel schneidet ein TIFF‑Bild zu. Der Beschneidungsbereich wird über die Ränder Links, Oben, Rechts, Unten angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Erneut zuschneiden. Setzen Sie einen Rand von 10 % der Bildgröße.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Speichern Sie das zugeschnittene Bild als PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Wenden Sie die Binärisierung auf das Bild mit einem vordefinierten Schwellenwert an, um es in ein Binärbild mit klaren Vorder‑ und Hintergrundbereichen zu konvertieren. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um Segmentierungs‑ und Merkmalsextraktionsaufgaben zu erleichtern und die Genauigkeit sowie Effizienz der Bildanalyse in Ihrer Anwendung zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
Das folgende Beispiel binarisiert ein TIFF‑Bild mit dem vordefinierten Schwellenwert. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisieren Sie das Bild mit einem Schwellenwert von 127.
    // Wenn der entsprechende Grauwert eines Pixels größer als 127 ist, wird ihm der Wert 255 zugewiesen, sonst 0.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Nutzen Sie die Otsu‑Schwellenwertbestimmung, um das Bild zu binarisieren, wobei der optimale Schwellenwert automatisch anhand des Histogramms des Bildes ermittelt wird. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um eine effektive Segmentierung und Merkmalsextraktion zu erreichen und die Genauigkeit sowie Zuverlässigkeit von Bildanalyseaufgaben in Ihrer Anwendung zu verbessern.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
Das folgende Beispiel binarisiert ein TIFF‑Bild mit Otsu‑Schwellenwertbestimmung. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisieren Sie das Bild mit Otsu‑Schwellenwertverfahren.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Implementieren Sie die Binärisierung des Bildes mit Bradleys adaptivem Schwellenwertalgorithmus und Integralbild‑Schwellenwertbestimmung. Dieser Ansatz berechnet dynamisch lokale Schwellenwerte basierend auf der Nachbarschaft des Bildes, erhöht die Anpassungsfähigkeit an unterschiedliche Lichtverhältnisse und sorgt für eine robuste Segmentierung für nachfolgende Verarbeitungsaufgaben in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
Das folgende Beispiel binarisiert ein TIFF‑Bild mit Bradleys adaptivem Schwellenwertalgorithmus und der angegebenen Fenstergröße. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binarisieren Sie das Bild mit einem Helligkeitsunterschied von 5. Die Helligkeit ist die Differenz zwischen einem Pixel und dem Durchschnitt eines 10 × 10‑Pixel‑Fensters, das um diesen Pixel zentriert ist.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Konvertieren Sie das Bild in seine Graustufen‑Darstellung, indem Sie es in ein ein‑Kanal‑Bild umwandeln, bei dem jeder Pixel die Intensität repräsentiert. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um die Analyse zu vereinfachen und die Kompatibilität mit graustufenbasierten Algorithmen zu erhöhen, was verschiedene Computer‑Vision‑ und Bildanalyse‑Aufgaben in Ihrer Anwendung erleichtert.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
Das folgende Beispiel wandelt ein farbiges TIFF‑Bild in seine Graustufen‑Darstellung um. Graustufen‑Bilder bestehen ausschließlich aus Grautönen und enthalten nur Intensitätsinformationen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Wenden Sie eine Gammakorrektur auf das Bild an, um die Pixelintensitäten anzupassen und das gewünschte Farbgleichgewicht zu erreichen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um die visuelle Qualität zu verbessern und die Genauigkeit nachfolgender Analyse‑ oder Anzeigeaufgaben in Ihrer Anwendung zu erhöhen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Setzen Sie den Gamma-Koeffizienten für Rot-, Grün- und Blaukanäle.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Führen Sie eine Gammakorrektur des Bildes mit einzelnen Koeffizienten für die Rot‑, Grün‑ und Blaukanäle durch, um feine Anpassungen des Farbgleichgewichts und des Kontrasts zu ermöglichen. Integrieren Sie diese Methode in Ihre Bildverarbeitungspipeline, um eine präzise Kontrolle über die Farbdarstellung zu erreichen und die visuelle Treue in Ihrer Anwendung zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Setzen Sie individuelle Gamma-Koeffizienten für die Rot-, Grün- und Blaukanäle.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementieren Sie die `brightness`‑Anpassung für das Bild, um die Gesamthelligkeit zu verändern. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um die Sichtbarkeit zu erhöhen und die Bildqualität in Ihrer Anwendung zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Legen Sie den Helligkeitswert fest. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Verbessern Sie den Kontrast der [Image](../../com.aspose.imaging/image)‑Instanz, indem Sie die Unterschiede zwischen hellen und dunklen Bereichen verstärken. Integrieren Sie diese Funktionalität, um die visuelle Klarheit und die Gesamtqualität des Bildes in Ihrer Anwendung zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Legen Sie den Kontrastwert fest. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

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


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Passen Sie die Größe des Bildes anhand der angegebenen Einstellungen an, um eine präzise Kontrolle über Abmessungen, Seitenverhältnis und Skalierungsverhalten zu ermöglichen. Integrieren Sie diese Methode in Ihren Bildverarbeitungs‑Workflow, um benutzerdefinierte Skalierungsoperationen zu erzielen, die auf die spezifischen Anforderungen Ihrer Anwendung zugeschnitten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Der adaptive Algorithmus basierend auf gewichteter und gemischter rationaler Funktion sowie Lanczos‑3‑Interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Der kleine rechteckige Filter
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Die Anzahl der Farben in der Palette.
resizeSettings.setEntriesCount(256);

// Die Farbquantisierung wird nicht verwendet
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Die euklidische Methode
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Als PNG speichern
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

