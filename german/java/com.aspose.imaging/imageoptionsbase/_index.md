---
title: "ImageOptionsBase"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Basisoptionen für Bilder."
type: docs
weight: 62
url: /de/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Die Basisoptionen für Bilder.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Gibt einen Wert zurück, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Ein Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen. |
| [getXmpData()](#getXmpData--) | Ruft den XMP-Metadatencontainer ab. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Setzt den XMP-Metadatencontainer. |
| [getExifData()](#getExifData--) | Liefert die Exif-Daten. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Setzt die Exif-Daten. |
| [getSource()](#getSource--) | Ruft die Quelle ab, in der das Bild erstellt wird. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Ruft die Quelle ab oder setzt sie, in der das Bild erstellt wird. |
| [getPalette()](#getPalette--) | Liefert die Farbpalette. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Setzt die Farbpalette. |
| [getResolutionSettings()](#getResolutionSettings--) | Ruft die Auflösungseinstellungen ab. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Setzt die Auflösungseinstellungen. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Ruft die Vektor-Rasterisierungsoptionen ab. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Setzt die Vektor-Rasterisierungsoptionen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Liefert den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Die Mehrseitigen Optionen. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Die Mehrseitigen Optionen. |
| [getFullFrame()](#getFullFrame--) | Ruft einen Wert ab, der angibt, ob [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Setzt einen Wert, der angibt, ob [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritts-Event-Handler ab. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Setzt den Fortschritts-Event-Handler. |
| [deepClone()](#deepClone--) | Klonen Sie diese Instanz. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert. |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Gibt einen Wert zurück, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen.

**Returns:**
boolean - ein Wert, der angibt, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Ein Wert, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob die ursprünglichen Bildmetadaten beim Export beibehalten werden. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Ruft den XMP-Metadatencontainer ab.

Wert: Der XMP-Datencontainer.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Setzt den XMP-Metadatencontainer.

Wert: Der XMP-Datencontainer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | der XMP-Metadatencontainer. |

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

### getSource() {#getSource--}
```
public Source getSource()
```


Ruft die Quelle ab, in der das Bild erstellt wird.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Ruft die Quelle ab oder setzt sie, in der das Bild erstellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | Die Quelle, in der das Bild erstellt wird. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Liefert die Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Setzt die Farbpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die Farbpalette. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Erstelle ein BMP-Bild mit 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fülle das gesamte Bild mit dem linearen Farbverlaufs-Pinsel.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Erhalte die nächstgelegene 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, sodass ein palettisiertes Bild
    // fast visuell nicht von einem nicht palettierten Bild zu unterscheiden ist.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // Eine 8-Bit-Palette enthält höchstens 256 Farben.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// Die Ausgabe sieht folgendermaßen aus:
// Die palettierte Bildgröße beträgt 11078 Bytes.
// Die nicht-palettierte Bildgröße beträgt 40054 Bytes.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Ruft die Auflösungseinstellungen ab.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Setzt die Auflösungseinstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Führe einige Bildverarbeitungen durch.

    // Verwenden Sie zusätzliche Optionen, um die gewünschten Bildparameter anzugeben.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Die Anzahl der Bits pro Kanal beträgt 8.
    // Wenn eine Palette verwendet wird, wird der Farbindex in den Bilddaten gespeichert anstelle der Farbe selbst.
    saveOptions.setBitsPerChannel((byte) 8);

    // Legen Sie den progressiven Kompressionstyp fest.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Legen Sie die Bildqualität fest. Sie ist ein Wert zwischen 1 und 100.
    saveOptions.setQuality(100);

    // Stellen Sie die horizontale/vertikale Auflösung auf 96 DPI ein.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Wenn das Quellbild farbig ist, wird es in Graustufen konvertiert.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Verwenden Sie eine Palette, um die Ausgabengröße zu reduzieren.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


Ruft die Vektor-Rasterisierungsoptionen ab.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Setzt die Vektor-Rasterisierungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Die Vektor-Rasterisierungsoptionen. |

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

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Die Mehrseitigen Optionen.

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Die Mehrseitigen Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Ruft einen Wert ab, der angibt, ob [full frame].

Wert: `true`, wenn [full frame]; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Setzt einen Wert, der angibt, ob [full frame].

Wert: `true`, wenn [full frame]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Ruft den Fortschritts-Event-Handler ab.

Wert: Der Fortschritts-Ereignishandler.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Setzt den Fortschritts-Event-Handler.

Wert: Der Fortschritts-Ereignishandler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | der Fortschritts-Ereignishandler. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Beispiel für die Verwendung separater Fortschrittsereignis-Handler für Lade-/Exportvorgänge
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// Das STDOUT-Protokoll kann folgendermaßen aussehen:
//        Ladeereignis Initialisierung : 1/4
//        Ladeereignis Vorverarbeitung : 2/4
//        Ladeereignis Verarbeitung : 3/4
//        Ladeereignis Finalisierung : 4/4
//        Exportereignis Initialisierung : 1/4
//        Exportereignis Vorverarbeitung : 2/4
//        Exportereignis Verarbeitung : 3/4
//        Exportereignis Relativer Fortschritt : 1/1
//        Ladeereignis Relativer Fortschritt : 1/1
//        Exportereignis Finalisierung : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonen Sie diese Instanz.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Versucht, eine `metadata`-Instanz zu setzen, falls diese [Image](../../com.aspose.imaging/image)-Instanz unterstützt und eine [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Die Metadaten. |

**Returns:**
boolean – True, wenn die [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-Instanz unterstützt und/oder die [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-Instanz implementiert; andernfalls false.
