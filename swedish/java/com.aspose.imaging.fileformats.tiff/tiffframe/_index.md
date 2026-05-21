---
title: "TiffFrame"
second_title: "Aspose.Imaging för Java API-referens"
description: "TIFF-ramen."
type: docs
weight: 12
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class TiffFrame extends RasterCachedImage
```

TIFF-ramen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffFrame(InputStream stream)](#TiffFrame-java.io.InputStream-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(InputStream stream, TiffOptions options)](#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(String path)](#TiffFrame-java.lang.String-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(String path, TiffOptions options)](#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(RasterImage image)](#TiffFrame-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(RasterImage image, TiffOptions options)](#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-) | Initierar en ny instans av klassen `TiffFrame`. |
| [TiffFrame(TiffOptions options, int width, int height)](#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-) | Initierar en ny instans av klassen `TiffFrame`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar ett värde för bakgrundsfärgen. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Ställer in ett värde för bakgrundsfärgen. |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getFrameOptions()](#getFrameOptions--) | Hämtar alternativ för att skapa ramen. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ställer in den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Hämtar den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Ställer in den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [getPathResources()](#getPathResources--) | Hämtar sökvägsresurserna. |
| [setPathResources(List<PathResource> value)](#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--) | Ställer in sökvägsresurserna. |
| [removeMetadata()](#removeMetadata--) | Tar bort metadata för denna bildinstans genom att sätta detta IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) och `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) värden till `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Hämtar alternativen baserat på de ursprungliga filinställningarna. |
| [alignResolutions()](#alignResolutions--) | Hjälpmetod för att göra horisontella och vertikala upplösningar lika. |
| [copyFrame(TiffFrame tiffFrame)](#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Kopierar hela ramen (duplicerar). |
| [createFrameFrom(TiffFrame tiffFrame, TiffOptions options)](#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-) | Skapar ramen från angiven `tiffFrame` med de angivna `options`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändrar storlek på bilden. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Roterar, vänder eller roterar och vänder bilden. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotera bilden kring centrum. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär bilden. |

## Example: This example shows how to create a TIFF image from scratch and save it to a file.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Ställ in byteordning Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Ställ in LZW-komprimering.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Ställ in färgmodellen RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Alla färgkomponenter kommer att lagras i ett enda plan.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Skapa en TIFF-ram på 100x100 px.
// Observera att du inte behöver avyttra en ram explicit om den är inkluderad i TiffImage.
// När behållaren avyttras kommer alla ramar att avyttras automatiskt.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Fyll hela ramen med den blå-gula gradienten.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Skapa en TIFF-bild.
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


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda en bild från och initiera bildramens pixel- och palettdata med. |

### TiffFrame(InputStream stream, TiffOptions options) {#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(InputStream stream, TiffOptions options)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Alternativen att använda för den nyss skapade ramen. |

### TiffFrame(String path) {#TiffFrame-java.lang.String-}
```
public TiffFrame(String path)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att ladda en bild från och initiera bildramens pixel- och palettdata med. |

### TiffFrame(String path, TiffOptions options) {#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(String path, TiffOptions options)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Sökvägen att ladda en bild från och initiera bildramens pixel- och palettdata med. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Alternativen att använda för den nyss skapade ramen. |

### TiffFrame(RasterImage image) {#TiffFrame-com.aspose.imaging.RasterImage-}
```
public TiffFrame(RasterImage image)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden att initiera bildramens pixel- och palettdata med. |

### TiffFrame(RasterImage image, TiffOptions options) {#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(RasterImage image, TiffOptions options)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden att initiera bildramens pixel- och palettdata med. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Alternativen att använda för den nyss skapade ramen. |

### TiffFrame(TiffOptions options, int width, int height) {#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-}
```
public TiffFrame(TiffOptions options, int width, int height)
```


Initierar en ny instans av klassen `TiffFrame`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Ramalternativen. |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar ett värde för bakgrundsfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ställer in ett värde för bakgrundsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

**Returns:**
boolean - `true` om denna instans har alfa; annars `false`.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Om den aktiva TIFF-ramen har alfakanal, anses hela TIFF-bilden ha alfakanal.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

**Returns:**
int - Bildens bitar per pixel-antal.
### getFrameOptions() {#getFrameOptions--}
```
public TiffOptions getFrameOptions()
```


Hämtar alternativ för att skapa ramen.

**Returns:**
[TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

**Returns:**
int - Bildens höjd.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

**Returns:**
int - Bildens bredd.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämtar den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`.

**Returns:**
double - Den horisontella upplösningen.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Ladda en TIFF-bild från en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Hämta horisontell och vertikal upplösning för TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
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


Ställer in den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Den horisontella upplösningen. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`.

**Returns:**
double - Den vertikala upplösningen.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Ladda en TIFF-bild från en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Hämta horisontell och vertikal upplösning för TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
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


Ställer in den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Den vertikala upplösningen. |

### getPathResources() {#getPathResources--}
```
public List<PathResource> getPathResources()
```


Hämtar sökvägsresurserna.

Värde: Sökvägsresurserna.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> - sökvägsresurserna.

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
Följande exempel visar hur man modifierar redan befintliga Clipping Paths. Till exempel kan du behålla endast en Clipping Path i bilden.
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


Ställer in sökvägsresurserna.

Värde: Sökvägsresurserna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> | sökvägsresurserna. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Tar bort metadata för denna bildinstans genom att sätta detta IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) och `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) värden till `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Får alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av metoden [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), kommer en PNG-bild med 8 bitar per pixel att produceras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem till metoden [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) som den andra parametern.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### alignResolutions() {#alignResolutions--}
```
public void alignResolutions()
```


Hjälpmetod för att göra horisontella och vertikala upplösningar lika.

### copyFrame(TiffFrame tiffFrame) {#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public static TiffFrame copyFrame(TiffFrame tiffFrame)
```


Kopierar hela ramen (duplicerar).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Tiff-ramen att kopiera. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly copied tiff frame.
### createFrameFrom(TiffFrame tiffFrame, TiffOptions options) {#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-}
```
public static TiffFrame createFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```


Skapar ramen från specificerad `tiffFrame` med de specificerade `options`. Pixeldata bevaras men konverteras till önskat format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Tiff-ramen att skapa från. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | De nya alternativen att använda. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly created frame.

**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte tillfällig filkälla.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Den linjära gradienten från bildens övre vänstra till nedre högra hörn.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fyll den aktiva ramen med en linjär gradientpensel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gråskalaalternativ
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Skapa en gråskalig kopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Lägg till den nyss skapade ramen till TIFF-bilden.
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


Ändrar storlek på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| resizeType | int | Typen av storleksändring. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Roterar, vänder eller roterar och vänder bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | int | Rotations- och vändningstypen. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | om den är inställd på `true` kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beskär bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |

