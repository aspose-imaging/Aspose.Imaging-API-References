---
title: "ImageOptionsBase"
second_title: "Aspose.Imaging för Java API-referens"
description: "Bildens grundalternativ."
type: docs
weight: 62
url: /sv/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

Bildens grundalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | Ett värde som anger om originalmetadata för bilden ska behållas vid export. |
| [getXmpData()](#getXmpData--) | Hämtar XMP-metadatabehållaren. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Ställer in XMP-metadatabehållaren. |
| [getExifData()](#getExifData--) | Hämtar Exif-data. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Ställer in Exif-data. |
| [getSource()](#getSource--) | Hämtar källan att skapa bilden i. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | Hämtar eller ställer in källan att skapa bilden i. |
| [getPalette()](#getPalette--) | Hämtar färgpaletten. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Ställer in färgpaletten. |
| [getResolutionSettings()](#getResolutionSettings--) | Hämtar upplösningsinställningarna. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Ställer in upplösningsinställningarna. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Hämtar vektorrasteriseringsalternativen. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Ställer in vektorrasteriseringsalternativen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Flersidiga alternativ |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | Flersidiga alternativ |
| [getFullFrame()](#getFullFrame--) | Hämtar ett värde som indikerar om [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ställer in ett värde som indikerar om [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar händelsehanteraren för framsteg. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Ställer in händelsehanteraren för framsteg. |
| [deepClone()](#deepClone--) | Klonar den här instansen. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans. |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


Hämtar ett värde som anger om originalmetadata för bilden ska behållas vid export.

**Returns:**
boolean - ett värde som anger om originalbildens metadata ska behållas vid export.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


Ett värde som anger om originalmetadata för bilden ska behållas vid export.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som anger om originalbildens metadata ska behållas vid export. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Hämtar XMP-metadatabehållaren.

Värde: XMP-databehållaren.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ställer in XMP-metadatabehållaren.

Värde: XMP-databehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | XMP-metadatabehållaren. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Hämtar Exif-data.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Ställer in Exif-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif‑data. |

### getSource() {#getSource--}
```
public Source getSource()
```


Hämtar källan att skapa bilden i.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


Hämtar eller ställer in källan att skapa bilden i.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | Källan att skapa bilden i. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Hämtar färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ställer in färgpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Färgpaletten. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Skapa en BMP-bild 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Den linjära gradienten från bildens övre vänstra till nedre högra hörn.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Fyll hela bilden med den linjära gradientpenseln.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palettiserad.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8-bitars palett innehåller högst 256 färger.
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

// Utdata ser ut så här:
// Den palettiserade bildstorleken är 11078 byte.
// Den icke-palettiserade bildstorleken är 40054 byte.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Hämtar upplösningsinställningarna.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Ställer in upplösningsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Läs in en BMP-bild från en fil.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Utför någon bildbehandling.

    // Använd ytterligare alternativ för att ange de önskade bildparametrarna.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Antalet bitar per kanal är 8.
    // När en palett används lagras färgindexet i bilddata istället för själva färgen.
    saveOptions.setBitsPerChannel((byte) 8);

    // Ange den progressiva komprimeringstypen.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Ange bildkvaliteten. Det är ett värde mellan 1 och 100.
    saveOptions.setQuality(100);

    // Ange den horisontella/vertikala upplösningen till 96 punkter per tum.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Om källbilden är färgad kommer den att konverteras till gråskala.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Använd en palett för att minska utdata storleken.
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


Hämtar vektorrasteriseringsalternativen.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Ställer in vektorrasteriseringsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Vektor rasteriseringsalternativ. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Hämtar ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Returns:**
int - buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ställer in ledtråden för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar.

Värde: Buffertstorleksindikationen, i megabyte. Icke-positivt värde betyder ingen minnesbegränsning för interna buffertar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | buffertstorleksindikationen som definierar maximal tillåten storlek för alla interna buffertar. |

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


Flersidiga alternativ

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


Flersidiga alternativ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Hämtar ett värde som indikerar om [full frame].

Värde: `true` om [full frame]; annars `false`.

**Returns:**
boolean - ett värde som indikerar om [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Ställer in ett värde som indikerar om [full frame].

Värde: `true` om [full frame]; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Hämtar händelsehanteraren för framsteg.

Värde: Progress‑händelsehanteraren.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Ställer in händelsehanteraren för framsteg.

Värde: Progress‑händelsehanteraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | progress‑händelsehanteraren. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Exempel på användning av separata händelsehanterare för operationens framsteg för inläsnings-/exportoperationer.
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

// STDOUT‑loggen kan se ut så här:
//        Laddningshändelse Initiering : 1/4
//        Laddningshändelse Förbehandling : 2/4
//        Laddningshändelse Bearbetning : 3/4
//        Laddningshändelse Slutförande : 4/4
//        Exporthändelse Initiering : 1/4
//        Exporthändelse Förbehandling : 2/4
//        Exporthändelse Bearbetning : 3/4
//        Exporthändelse Relativt framsteg : 1/1
//        Laddningshändelse Relativt framsteg : 1/1
//        Exporthändelse Slutförande : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Klonar den här instansen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


Försöker att sätta en `metadata`‑instans, om detta [Image](../../com.aspose.imaging/image)‑objekt stödjer och implementerar en [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)‑instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | Metadatan. |

**Returns:**
boolean - True, om [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)-instansen stöder och/eller implementerar [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)-instansen; annars false.
