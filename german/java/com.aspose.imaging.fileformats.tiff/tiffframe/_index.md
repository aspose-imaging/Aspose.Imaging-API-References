---
title: "TiffFrame"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der TIFF‑Frame."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class TiffFrame extends RasterCachedImage
```

Der TIFF‑Frame.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffFrame(InputStream stream)](#TiffFrame-java.io.InputStream-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(InputStream stream, TiffOptions options)](#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(String path)](#TiffFrame-java.lang.String-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(String path, TiffOptions options)](#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(RasterImage image)](#TiffFrame-com.aspose.imaging.RasterImage-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(RasterImage image, TiffOptions options)](#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
| [TiffFrame(TiffOptions options, int width, int height)](#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-) | Initialisiert eine neue Instanz der `TiffFrame`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Liest einen Wert für die Hintergrundfarbe. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt einen Wert für die Hintergrundfarbe. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getFrameOptions()](#getFrameOptions--) | Ruft die Optionen zur Erstellung des Frames ab. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Ruft die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll ab. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [getVerticalResolution()](#getVerticalResolution--) | Ruft die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll ab. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [getPathResources()](#getPathResources--) | Ruft die Pfadressourcen ab. |
| [setPathResources(List<PathResource> value)](#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--) | Setzt die Pfadressourcen. |
| [removeMetadata()](#removeMetadata--) | Entfernt die Metadaten dieser Bildinstanz, indem die IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) und `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) Werte auf `null` gesetzt werden. |
| [getOriginalOptions()](#getOriginalOptions--) | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. |
| [alignResolutions()](#alignResolutions--) | Hilfsmethode, um horizontale und vertikale Auflösungen gleich zu machen. |
| [copyFrame(TiffFrame tiffFrame)](#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Kopiert den gesamten Frame (Duplikate). |
| [createFrameFrom(TiffFrame tiffFrame, TiffOptions options)](#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-) | Erstellt den Frame aus dem angegebenen `tiffFrame` unter Verwendung der angegebenen `options`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe des Bildes. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Bild um die Mitte drehen. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Zuschneiden des Bildes. |

## Example: This example shows how to create a TIFF image from scratch and save it to a file.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Setzt 8 Bit für jede Farbkomponente.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Setzt die Byte-Reihenfolge Big Endian (Motorola).
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Setzt die LZW-Kompression.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Setzt das RGB-Farbmodell.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Erstelle einen TIFF-Frame von 100 × 100 px.
// Beachten Sie, dass Sie einen Frame nicht explizit freigeben müssen, wenn er in TiffImage eingebunden ist.
// Wenn der Container freigegeben wird, werden alle Frames automatisch freigegeben.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Füllt den gesamten Frame mit dem blau-gelben Verlauf.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Erstelle ein TIFF-Bild.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### TiffFrame(InputStream stream) {#TiffFrame-java.io.InputStream-}
```
public TiffFrame(InputStream stream)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |

### TiffFrame(InputStream stream, TiffOptions options) {#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(InputStream stream, TiffOptions options)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Optionen, die für das neu erstellte Frame verwendet werden sollen. |

### TiffFrame(String path) {#TiffFrame-java.lang.String-}
```
public TiffFrame(String path)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |

### TiffFrame(String path, TiffOptions options) {#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(String path, TiffOptions options)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad, aus dem ein Bild geladen wird, und mit dem Frame-Pixel- und Palettendaten initialisiert wird. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Optionen, die für das neu erstellte Frame verwendet werden sollen. |

### TiffFrame(RasterImage image) {#TiffFrame-com.aspose.imaging.RasterImage-}
```
public TiffFrame(RasterImage image)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Frame-Pixel- und Palettendaten initialisiert werden. |

### TiffFrame(RasterImage image, TiffOptions options) {#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(RasterImage image, TiffOptions options)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Bild, mit dem Frame-Pixel- und Palettendaten initialisiert werden. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Optionen, die für das neu erstellte Frame verwendet werden sollen. |

### TiffFrame(TiffOptions options, int width, int height) {#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-}
```
public TiffFrame(TiffOptions options, int width, int height)
```


Initialisiert eine neue Instanz der `TiffFrame`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die Frame-Optionen. |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest einen Wert für die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt einen Wert für die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

**Returns:**
boolean - `true`, wenn diese Instanz Alpha hat; andernfalls `false`.

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

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getFrameOptions() {#getFrameOptions--}
```
public TiffOptions getFrameOptions()
```


Ruft die Optionen zur Erstellung des Frames ab.

**Returns:**
[TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

**Returns:**
int - Die Bildhöhe.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

**Returns:**
int - Die Bildbreite.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Ruft die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll ab.

**Returns:**
double - Die horizontale Auflösung.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Lade ein TIFF-Bild aus einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Erhalte die horizontale und vertikale Auflösung des TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Die horizontale Auflösung. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ruft die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll ab.

**Returns:**
double - Die vertikale Auflösung.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Lade ein TIFF-Bild aus einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Erhalte die horizontale und vertikale Auflösung des TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Die vertikale Auflösung. |

### getPathResources() {#getPathResources--}
```
public List<PathResource> getPathResources()
```


Ruft die Pfadressourcen ab.

Wert: Die Pfadressourcen.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> - die Pfadressourcen.

**Example: The following example shows how to retrieve paths from TIFF image and display their names in the console.**

``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    for (PathResource path : image.getActiveFrame().getPathResources())
    {
        System.out.println(path.getName());
    }
}
```


**Example: The following example shows how to modify already existing Clipping Paths.**
Das folgende Beispiel zeigt, wie bereits vorhandene Clipping Paths geändert werden können. Zum Beispiel können Sie nur einen Clipping Path im Bild behalten.
``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    List<PathResource> paths = image.getActiveFrame().getPathResources();
    image.getActiveFrame().setPathResources(Collections.singletonList(paths.get(0)));
    image.save();
}
```


**Example: Transfer Clipping Paths during export from TIFF to PSD image.**

``` java
try (Image image = Image.load("Sample.tif"))
{
    image.save("SampleWithPaths.psd", new PsdOptions());
}
```


**Example: Create Clipping Path manually.**

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Sample.tif"))
    {
        PathResource res = new PathResource();
        res.setBlockId((short) 2000);                                                  // Block Id according to Photoshop specification
        res.setName("My Clipping Path");                                               // Path name
        res.setRecords(createRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)); // Create path records using coordinates
                    
        image.getActiveFrame().setPathResources(Collections.singletonList(res));

        image.save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> createRecords(float ... coordinates)
{
    List<VectorPathRecord>  records = createBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    LengthRecord lr = new LengthRecord(); // LengthRecord required by Photoshop specification
    lr.setOpen(false);                    // Lets create closed path
    lr.setRecordCount(records.size());    // Record count in the path
                
    records.add(0, lr);

    return records;
}

private static List<VectorPathRecord> createBezierRecords(float[] coordinates)
{
    List<VectorPathRecord> l = new LinkedList<VectorPathRecord>();
                
    for (int index = 0; index < coordinates.length - 1; index += 2)
    {
        PointF pt = new PointF(coordinates[index], coordinates[index + 1]);
        BezierKnotRecord br = new BezierKnotRecord();
        br.setPathPoints(new PointF[] {pt, pt, pt});
        l.add(br);
    }
                    
    return l;
}

```

### setPathResources(List<PathResource> value) {#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--}
```
public void setPathResources(List<PathResource> value)
```


Setzt die Pfadressourcen.

Wert: Die Pfadressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> | die Pfadressourcen. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Entfernt die Metadaten dieser Bildinstanz, indem die IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) und `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) Werte auf `null` gesetzt werden.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie an die [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) Methode als zweiten Parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### alignResolutions() {#alignResolutions--}
```
public void alignResolutions()
```


Hilfsmethode, um horizontale und vertikale Auflösungen gleich zu machen.

### copyFrame(TiffFrame tiffFrame) {#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public static TiffFrame copyFrame(TiffFrame tiffFrame)
```


Kopiert den gesamten Frame (Duplikate).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der tiff Frame zum Kopieren. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly copied tiff frame.
### createFrameFrom(TiffFrame tiffFrame, TiffOptions options) {#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-}
```
public static TiffFrame createFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```


Erstellt das Frame aus dem angegebenen `tiffFrame` unter Verwendung der angegebenen `options`. Die Pixeldaten werden erhalten, aber in das gewünschte Format konvertiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Der tiff Frame, aus dem erstellt werden soll. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Die neuen Optionen, die verwendet werden sollen. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly created frame.

**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Erstelle eine permanente, nicht temporäre Dateiquelle.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fülle das aktive Frame mit einem linearen Farbverlauf-Pinsel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Graustufen-Optionen
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Erstelle eine Graustufenkopie des aktiven Frames.
    // Die Pixeldaten werden erhalten, aber in das gewünschte Format konvertiert.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Füge das neu erstellte Frame zum TIFF-Bild hinzu.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Rotations‑Umkehrtyp. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Zuschneiden des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

