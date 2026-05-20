---
title: "Bild"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das Bild ist die Basisklasse für alle Bildtypen."
type: docs
weight: 56
url: /de/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

Das Bild ist die Basisklasse für alle Bildtypen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen `loadOptions` verwendet. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | Erstellt eine [RasterImage](../../com.aspose.imaging/rasterimage)-Instanz aus dem bereitgestellten Pixel‑Array. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien enthält. |
| [create(String[] files)](#create-java.lang.String---) | Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien enthält. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | Erstellt ein neues Bild mit den angegebenen Bildern als Seiten. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Liefert das Dateiformat. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL. |
| [load(String filePath)](#load-java.lang.String-) | Lädt ein neues Bild vom angegebenen Dateipfad oder URL. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | Lädt ein neues Bild vom angegebenen Stream. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Lädt ein neues Bild vom angegebenen Stream. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Lädt ein neues Bild vom angegebenen Stream. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Lädt ein neues Bild vom angegebenen Stream. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Liefert das Dateiformat. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Liefert eine proportionale Breite. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Liefert eine proportionale Höhe. |
| [removeMetadata()](#removeMetadata--) | Entfernt Metadaten. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und den Typ [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) implementiert. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getBounds()](#getBounds--) | Liefert die Bildgrenzen. |
| [getContainer()](#getContainer--) | Liefert den `Image`-Container. |
| [getPalette()](#getPalette--) | Liefert die Farbpalette. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Setzt die Farbpalette. |
| [isUsePalette()](#isUsePalette--) | Liefert einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| [getSize()](#getSize--) | Liefert die Bildgröße. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Liefert den Unterbrechungsmonitor. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | Setzt den Unterbrechungsmonitor. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Liefert einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Liefert einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [getFileFormat()](#getFileFormat--) | Rufen Sie den Dateiformatwert einfach mit dieser benutzerfreundlichen Eigenschaft ab. |
| [getBackgroundColor()](#getBackgroundColor--) | Liefert oder setzt einen Wert für die Hintergrundfarbe. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Liefert oder setzt einen Wert für die Hintergrundfarbe. |
| [getMetadata()](#getMetadata--) | Ermittelt die Metadaten des Bildes. |
| [getExifData()](#getExifData--) | Liefert die Exif-Daten. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt die Exif-Daten. |
| [getXmpData()](#getXmpData--) | Liefert die Xmp-Daten. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Setzt die Xmp-Daten. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | Ruft die Informationen des Fortschritt-Event-Handlers ab. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Ruft die Informationen des Fortschritt-Event-Handlers ab. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Ändert die Größe des Bildes. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe des Bildes. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Größe des Bildes. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Ruft die Standardoptionen ab. |
| [getOriginalOptions()](#getOriginalOptions--) | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Ändert die Breite proportional. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Ändert die Höhe proportional. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändert die Breite proportional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändert die Höhe proportional. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Breite proportional. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Höhe proportional. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [rotate(float angle)](#rotate-float-) | Bild um die Mitte drehen. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet das angegebene Rechteck zu. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Bild mit Verschiebungen zuschneiden. |
| [save()](#save--) | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(String filePath)](#save-java.lang.String-) | Speichert das Bild am angegebenen Speicherort. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | Konvertiert zu aps. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der BmpOptions‑Instanz angegeben ist. Mehrere Eigenschaften der BmpOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.
``` java
// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von BmpOptions, indem Sie die Create‑Methode aufrufen
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Führen Sie einige Bildverarbeitungen durch

    // Speichern Sie alle Änderungen
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |

**Returns:**
boolescher Wert – `true`, wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// Verwenden Sie einen absoluten Pfad zur Datei
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
boolescher Wert – `true`, wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem geladen werden soll. |

**Returns:**
boolescher Wert – `true`, wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// Verwenden Sie einen Dateistream
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// Die folgenden Daten sind kein gültiger Bild-Stream, daher gibt CanLoad `false` zurück.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen `loadOptions` verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem geladen werden soll. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
boolescher Wert – `true`, wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Bildoptionen. |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der BmpOptions‑Instanz angegeben ist. Mehrere Eigenschaften der BmpOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.
``` java
// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von BmpOptions, indem Sie die Create‑Methode aufrufen
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Führen Sie einige Bildverarbeitungen durch

    // Speichern Sie alle Änderungen
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


Erstellt eine [RasterImage](../../com.aspose.imaging/rasterimage)-Instanz aus dem bereitgestellten Pixel-Array. Validiert, dass die angegebene Breite und Höhe den Abmessungen der Pixeldaten entsprechen. Diese Methode kann nur verwendet werden, wenn die Bibliothek im lizenzierten Modus ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen, die zum Erstellen des [RasterImage](../../com.aspose.imaging/rasterimage) verwendet werden. |
| width | int | Die Breite des [RasterImage](../../com.aspose.imaging/rasterimage). |
| height | int | Die Höhe des [RasterImage](../../com.aspose.imaging/rasterimage). |
| Pixel | int[] | Das Array von Pixelwerten, das zum Befüllen des Bildes verwendet wird. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


Erstellt ein neues Bild, das die angegebenen Bilder als Seiten verwendet

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Die Bilder. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


Erstellt die angegebenen Mehrseiten‑Erstellungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | Die Optionen für die Mehrseitenerstellung. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateien | java.lang.String[] | Die Dateien. |
| throwExceptionOnLoadError | boolean | wenn auf `true` gesetzt [throw exception on load error]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


Erstellt das Mehrseiten‑Bild, das die angegebenen Dateien enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dateien | java.lang.String[] | Die Dateien. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Erstellt ein neues Bild mit den angegebenen Bildern als Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Die Bilder. |
| disposeImages | boolean | wenn auf `true` gesetzt [dispose images]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Liefert das Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad. |

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden kann. Verwenden Sie eine der Überladungen der CanLoad-Methode, um zu bestimmen, ob die Datei geladen werden kann. |

**Returns:**
long - Das ermittelte Dateiformat.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// Verwenden Sie einen absoluten Pfad zur Datei
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Eine Zeichenkettenrepräsentation des Dateiformats.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Lädt ein neues Bild vom angegebenen Dateipfad oder von einer URL. Wenn `filePath` ein Dateipfad ist, öffnet die Methode einfach die Datei. Wenn `filePath` eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad oder die URL, von der das Bild geladen werden soll. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Lädt ein neues Bild vom angegebenen Dateipfad oder von einer URL. Wenn `filePath` ein Dateipfad ist, öffnet die Methode einfach die Datei. Wenn `filePath` eine URL ist, lädt die Methode die Datei herunter, speichert sie temporär und öffnet sie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad oder die URL, von der das Bild geladen werden soll. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
Dieses Beispiel demonstriert das Laden einer vorhandenen Image-Datei in eine Instanz von com.aspose.imaging.Image unter Verwendung des angegebenen Dateipfads.
``` java
// Erstelle eine Image-Instanz und initialisiere sie mit einer vorhandenen Bilddatei vom Speicherort auf der Festplatte.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Führe einige Bildverarbeitungen durch.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Lädt ein neues Bild vom angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, von der das Bild geladen werden soll. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Lädt ein neues Bild vom angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, von der das Bild geladen werden soll. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Lädt ein neues Bild vom angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem das Bild geladen wird. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Lädt ein neues Bild vom angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem das Bild geladen wird. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// Erstelle eine Instanz von FileInputStream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // Erstelle eine Instanz der Image-Klasse und lade eine vorhandene Datei über das FileStream-Objekt, indem du die Load-Methode aufrufst
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // Führe einige Bildverarbeitungen durch.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Liefert das Dateiformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stream | java.io.InputStream | Der Stream. |

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden kann. Verwende eine der Überladungen der CanLoad-Methode, um zu bestimmen, ob der Stream geladen werden kann. |

**Returns:**
long - Das ermittelte Dateiformat.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

``` java

// Die Hilfsklasse, die im nachfolgenden Hauptbeispiel verwendet wird.
class Utils {
    // Die Hilfsmethode, um eine Zeichenkettenrepräsentation des Dateiformats zu erhalten.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

String dir = "c:\\temp\\";

// Verwenden Sie einen Dateistream
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Die folgenden Daten sind kein gültiger Bild-Stream, daher gibt GetFileFormat FileFormat.Undefined zurück.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Die Ausgabe könnte so aussehen:
// Das Dateiformat ist BMP
// Das Dateiformat ist UNDEFINED
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Liefert das Rechteck, das zum aktuellen Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| Breite | int | Die Objektbreite. |
| Höhe | int | Die Objekthöhe. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Liefert das Rechteck, das zum aktuellen Bild passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das ein passendes Rechteck ermittelt werden soll. |
| Pixel | int[] | Die 32‑Bit‑ARGB‑Pixel. |
| Breite | int | Die Objektbreite. |
| Höhe | int | Die Objekthöhe. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Liefert eine proportionale Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| newHeight | int | Die neue Höhe. |

**Returns:**
int – Die proportionale Breite.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Liefert eine proportionale Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |
| newWidth | int | Die neue Breite. |

**Returns:**
int – Die proportionale Höhe.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Entfernt Metadaten.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und den Typ [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Die Metadaten. |

**Returns:**
boolean – true, wenn die [Image](../../com.aspose.imaging/image)-Instanz den Typ [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) unterstützt und implementiert; andernfalls false.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Liefert die Bildgrenzen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Liefert den `Image`-Container.

Wert: Der `Image`‑Container.

Wenn diese Eigenschaft nicht null ist, weist das darauf hin, dass das Bild in einem anderen Bild enthalten ist.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Liefert die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Liefert einen Wert, der angibt, ob die Bildpalette verwendet wird.

Wert: `true`, wenn die Palette im Bild verwendet wird; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob die Bildpalette verwendet wird.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


Liefert die Bildgröße.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Seiten: 2
//Die aktive Seitennummer:    1
//Die erste Seitennummer:     1
//Die letzte Seitennummer:      2
//--------------------------------------------------
//Seitennummer:     1
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
//--------------------------------------------------
//Seitennummer:     2
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
```

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Liefert den Unterbrechungsmonitor.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Setzt den Unterbrechungsmonitor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | Der Interrupt-Monitor. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Returns:**
int - der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert.

Wert: Der Hinweis zur Puffergröße in Megabyte. Ein nicht‑positiver Wert bedeutet keine Speicherbeschränkung für interne Puffer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Liefert einen Wert, der angibt, ob die Palette automatisch angepasst wird.

**Returns:**
boolean - `true`, wenn die automatische Anpassung der Palette aktiviert ist; andernfalls `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn die automatische Anpassung der Palette aktiviert ist; andernfalls `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Liefert einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie den Dateiformatwert einfach über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf Informationen zum Dateiformat benötigen.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liefert oder setzt einen Wert für die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Liefert oder setzt einen Wert für die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Ermittelt die Metadaten des Bildes.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Liefert die Exif-Daten.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Setzt die Exif-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | die Exif‑Daten. |

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Liefert die Xmp-Daten.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


Setzt die Xmp-Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | die Xmp‑Daten. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


Ruft die Informationen des Fortschritt-Event-Handlers ab.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Ruft die Informationen des Fortschritt-Event-Handlers ab.

Wert: Die Informationen zum Fortschritts‑Event‑Handler.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die zu verwendenden Speicheroptionen. |

**Returns:**
boolean - `true`, wenn das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann; andernfalls `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // Bestimmen Sie, ob das Bild im Jpeg-Format gespeichert werden kann
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Skaliert das Bild. Der Standard [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
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


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskierungs‑Exportoptionen
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Verwenden Sie GraphCut‑Clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Die Hintergrundfarbe wird transparent sein.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Reduzierung der Bildgröße zur Beschleunigung des Segmentierungsprozesses.
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ermitteln der Vordergrundmaske.
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Vergrößern Sie die Größe der Maske auf die Größe des Originalbildes.
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Anwenden der Maske auf das Originalbild, um einen Vordergrundabschnitt zu erhalten.
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

``` java
// EPS-Bild laden.
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Bild skalieren mit der Mitchell-Kubik-Interpolationsmethode.
    image.resize(400, 400, ResizeType.Mitchell);

    // Bild in das PNG-Format exportieren.
    image.save("ExportResult.png", new PngOptions());
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |


**Example: This example loads an image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

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
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

``` java
// EPS-Bild laden.
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Interpolationsmodus festlegen.
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Filtertyp festlegen.
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Legt die Farbvergleichsmethode fest.
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Farbquantisierungsmethode festlegen.
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Bild skalieren mit erweiterten Skalierungseinstellungen.
    image.resize(400, 400, resizeSettings);

    // Bild in das PNG-Format exportieren.
    image.save("ExportResult.png", new PngOptions());
}
```

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
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Skaliert die Breite proportional. Der Standard [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Skaliert die Höhe proportional. Der Standard [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) wird verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Breite angegeben, die Höhe wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändert die Höhe proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Höhe angegeben, die Breite wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskierungs‑Exportoptionen
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// Verwenden Sie GraphCut‑Clustering.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Die Hintergrundfarbe wird transparent sein.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Reduzierung der Bildgröße zur Beschleunigung des Segmentierungsprozesses.
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // Erstellen Sie eine Instanz der Klasse ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente) auf.
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ermitteln der Vordergrundmaske.
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Vergrößern Sie die Größe der Maske auf die Größe des Originalbildes.
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Anwenden der Maske auf das Originalbild, um einen Vordergrundabschnitt zu erhalten.
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Bildskalierungseinstellungen. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Ändert die Höhe proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Bildskalierungseinstellungen. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Typ der Drehungsumkehr. |


**Example: This example demonstrates the use of Rotate operation on an image.**
Dieses Beispiel demonstriert die Verwendung der Rotate-Operation auf einem Bild. Das Beispiel lädt eine vorhandene Bilddatei von einem Speicherort und führt die Rotate-Operation auf dem Bild gemäß dem Wert des Enums com.aspose.imaging.RotateFlipType aus.
``` java
// Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Bilddatei über den Dateipfad.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Drehen Sie das Bild um 180 Grad um die X-Achse.
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Schneidet das angegebene Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |


**Example: The following example crops a raster image.**
Das folgende Beispiel schneidet ein Rasterbild zu. Der Zuschnittbereich wird über com.aspose.imaging.Rectangle angegeben.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Schneiden Sie das Bild zu. Der Zuschnittsbereich ist der rechteckige zentrale Bereich des Bildes.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // Speichern Sie das zugeschnittene Bild als PNG
    image.save(dir + "sample.Crop.png");
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Bild mit Verschiebungen zuschneiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |


**Example: The following example crops a raster image.**
Das folgende Beispiel schneidet ein Rasterbild zu. Der Zuschnittbereich wird über die Ränder Links, Oben, Rechts, Unten angegeben.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Erneut zuschneiden. Setzen Sie einen Rand von 10 % der Bildgröße.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Speichern Sie das zugeschnittene Bild als PNG.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


Speichert die Bilddaten in den zugrunde liegenden Stream.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // In ein Schwarz-Weiß-Bild konvertieren
    bmpImage.binarizeOtsu();

    // Am selben Ort mit den Standardoptionen speichern.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Eine Palette enthält in diesem Fall nur zwei Farben: Schwarz und Weiß.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.setBitsPerPixel(1);

    // An einem anderen Ort mit den angegebenen Optionen speichern.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Das gesamte Bild in einen Speicherstream speichern
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // Den zentralen Teil des Bildes in einen Speicherstream speichern
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Bytes: 1662
//Die Größe des zentralen Bildteils in Bytes: 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert das Bild am angegebenen Speicherort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, unter dem das Bild gespeichert werden soll. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen. |


**Example: This example shows the simple steps to Save an Image.**
Dieses Beispiel zeigt die einfachen Schritte zum Speichern eines Bildes. Um diesen Vorgang zu demonstrieren, laden wir eine vorhandene Datei von einem Speicherort und speichern das Bild im PSD-Format.
``` java
// Eine vorhandene Datei von der Festplatte laden.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Das Bild als PSD unter dem Dateipfad mit den Standard-PsdOptions-Einstellungen speichern.
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Speichern Sie die obere Bildhälfte in einer PNG-Datei.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, in die die Bilddaten gespeichert werden. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Optionen. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Datei | java.io.RandomAccessFile | Die Datei, in die die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Der Stream, in den die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Speicheroptionen. |


**Example: This example shows the process of saving an Image to memory buffer.**
Dieses Beispiel zeigt den Vorgang, ein Bild in einen Speicherpuffer zu speichern. Um diesen Vorgang zu demonstrieren, lädt das Beispiel eine vorhandene Datei von einem Speicherort und speichert das Bild im PSD-Format.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //Speichern Sie das Bild in einen PSD‑Speicherstream mit den Standard‑PsdOptions‑Einstellungen.
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | Der Stream, in den die Bilddaten gespeichert werden. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Speicheroptionen. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // Speichern Sie die obere Bildhälfte in einen Dateistream.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


Konvertiert zu aps.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Bildoptionen. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Beschneidungsrechteck. |
| pageNumber | int[] | Die Seitennummer. |

**Returns:**
java.io.InputStream - Der serialisierte Stream
