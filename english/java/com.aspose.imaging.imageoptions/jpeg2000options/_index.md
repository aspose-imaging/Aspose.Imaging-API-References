---
title: Jpeg2000Options
second_title: Aspose.Imaging for Java API Reference
description: The Jpeg2000 file format options.
type: docs
weight: 24
url: /java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

The Jpeg2000 file format options.
## Constructors

| Constructor | Description |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initializes a new instance of the `Jpeg2000Options` class. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Initializes a new instance of the `Jpeg2000Options` class. |
## Methods

| Method | Description |
| --- | --- |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [getComments()](#getComments--) | Gets or sets the Jpeg comment markers. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Gets or sets the Jpeg comment markers. |
| [getCodec()](#getCodec--) | Gets or sets the JPEG2000 codec |
| [setCodec(int value)](#setCodec-int-) | Gets or sets the JPEG2000 codec |
| [getCompressionRatios()](#getCompressionRatios--) | Gets or sets the Array of compression ratio. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Gets or sets the Array of compression ratio. |
| [getIrreversible()](#getIrreversible--) | Gets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Sets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default). |

## Example
The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.
``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. In fact, only one page will be rasterized because JPEG 2000 is not a multi-page format.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Initializes a new instance of the `Jpeg2000Options` class.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initializes a new instance of the `Jpeg2000Options` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | The Jpeg2000 file format options to copy settings from. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata container.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - The XMP data container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | The XMP data container. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Gets or sets the Jpeg comment markers.

**Returns:**
java.lang.String[] - The Jpeg comment markers.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Gets or sets the Jpeg comment markers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The Jpeg comment markers. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Gets or sets the JPEG2000 codec

**Returns:**
int - The JPEG2000 codec
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Gets or sets the JPEG2000 codec

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The JPEG2000 codec |


**Example:**
This example shows how to create a PNG image and save it to JPEG2000 with the desired options.
``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the entire image in red.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Use the irreversible Discrete Wavelet Transform 9-7
    saveOptions.setIrreversible(true);

    // JP2 is the "container" format for JPEG 2000 codestreams.
    // J2K is raw compressed data, without a wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Save to a file
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Gets or sets the Array of compression ratio. Different compression ratios for successive layers. The rate specified for each quality level is the desired compression factor. Decreasing ratios required.

**Returns:**
int[] - The compression ratios.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Gets or sets the Array of compression ratio. Different compression ratios for successive layers. The rate specified for each quality level is the desired compression factor. Decreasing ratios required.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The compression ratios. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Gets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default).

**Returns:**
boolean - a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Sets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression |


**Example:**
This example shows how to create a PNG image and save it to JPEG2000 with the desired options.
``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the entire image in red.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Use the irreversible Discrete Wavelet Transform 9-7
    saveOptions.setIrreversible(true);

    // JP2 is the "container" format for JPEG 2000 codestreams.
    // J2K is raw compressed data, without a wrapper.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Save to a file
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

