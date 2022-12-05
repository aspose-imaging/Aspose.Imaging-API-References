---
title: PsdOptions
second_title: Aspose.Imaging for Java API Reference
description: The PSD file format create options.
type: docs
weight: 37
url: /java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

The PSD file format create options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Initializes a new instance of the `PsdOptions` class. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Initializes a new instance of the `PsdOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getXmpData()](#getXmpData--) | Get or set XMP data container |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Get or set XMP data container |
| [getVersion()](#getVersion--) | Gets or sets the PSD file version. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the PSD file version. |
| [getCompressionMethod()](#getCompressionMethod--) | Gets or sets the PSD compression method. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Gets or sets the PSD compression method. |
| [getPsdVersion()](#getPsdVersion--) | Gets the file format version. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Sets the file format version. |
| [getColorMode()](#getColorMode--) | Gets or sets the PSD color mode. |
| [setColorMode(short value)](#setColorMode-short-) | Gets or sets the PSD color mode. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Gets or sets the bits count per color channel. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Gets or sets the bits count per color channel. |
| [getChannelsCount()](#getChannelsCount--) | Gets the color channels count. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Sets the color channels count. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Gets a value indicating whether - Remove the global text engine resource - Used for some text-layered PSD files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Sets a value indicating whether - Remove the global text engine resource - Used for some text-layered PSD files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Gets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Gets the PSD vectorization options. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Sets the PSD vectorization options. |

## Example: This example demonstrates the use of Aspose.
This example demonstrates the use of Aspose.Imaging for Java API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format.
``` java

// Create an instance of image class and initialize it with an existing file through File path
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Create an instance of PsdOptions class
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Set the CompressionMethod as RLE
    // Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Set the ColorMode to GrayScale
    // Note: Other supported ColorModes are ColorModes.Bitmap and ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Save the image to disk with the supplied PsdOptions settings
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. These pages will be presented as layers in the output PSD.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Initializes a new instance of the `PsdOptions` class.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Initializes a new instance of the `PsdOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | The options. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Get or set XMP data container

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper)
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Get or set XMP data container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets the PSD file version.

Value: The PSD file version.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets the PSD file version.

Value: The PSD file version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define a linear blue-transparent gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the PNG image with the linear blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // The following options will be used to save the PNG image to PSD format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // The number of bits per channel
    saveOptions.setChannelBitsCount((byte) 8);

    // The number of channels. One channel for each color component R,G,B,A
    saveOptions.setChannelsCount((short) 4);

    // The color mode
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // No compression
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Default version is 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // The RLE compression allows to reduce the size of the output image
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // The output may look like this:
    // The size of the PSD image with RAW compression: 40090
    // The size of the PSD image with RLE compression: 16185
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Gets or sets the PSD compression method.

Value: The compression method.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Gets or sets the PSD compression method.

Value: The compression method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |


**Example: This example demonstrates the use of Aspose.**
This example demonstrates the use of Aspose.Imaging for Java API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format.
``` java

// Create an instance of image class and initialize it with an existing file through File path
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Create an instance of PsdOptions class
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Set the CompressionMethod as RLE
    // Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Set the ColorMode to GrayScale
    // Note: Other supported ColorModes are ColorModes.Bitmap and ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Save the image to disk with the supplied PsdOptions settings
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Gets the file format version. It can be PSD or PSB.

Value: The file format version.

**Returns:**
byte - the file format version.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Sets the file format version. It can be PSD or PSB.

Value: The file format version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the file format version. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Gets or sets the PSD color mode.

Value: The color mode.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Gets or sets the PSD color mode.

Value: The color mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |


**Example: This example demonstrates the use of Aspose.**
This example demonstrates the use of Aspose.Imaging for Java API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format.
``` java

// Create an instance of image class and initialize it with an existing file through File path
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Create an instance of PsdOptions class
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Set the CompressionMethod as RLE
    // Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Set the ColorMode to GrayScale
    // Note: Other supported ColorModes are ColorModes.Bitmap and ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Save the image to disk with the supplied PsdOptions settings
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Gets or sets the bits count per color channel.

Value: The bits count per color channel.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Gets or sets the bits count per color channel.

Value: The bits count per color channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define a linear blue-transparent gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the PNG image with the linear blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // The following options will be used to save the PNG image to PSD format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // The number of bits per channel
    saveOptions.setChannelBitsCount((byte) 8);

    // The number of channels. One channel for each color component R,G,B,A
    saveOptions.setChannelsCount((short) 4);

    // The color mode
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // No compression
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Default version is 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // The RLE compression allows to reduce the size of the output image
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // The output may look like this:
    // The size of the PSD image with RAW compression: 40090
    // The size of the PSD image with RLE compression: 16185
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Gets the color channels count.

**Returns:**
short - The color channels count.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Sets the color channels count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | The color channels count. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define a linear blue-transparent gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the PNG image with the linear blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // The following options will be used to save the PNG image to PSD format.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // The number of bits per channel
    saveOptions.setChannelBitsCount((byte) 8);

    // The number of channels. One channel for each color component R,G,B,A
    saveOptions.setChannelsCount((short) 4);

    // The color mode
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // No compression
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // Default version is 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // The RLE compression allows to reduce the size of the output image
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // The output may look like this:
    // The size of the PSD image with RAW compression: 40090
    // The size of the PSD image with RLE compression: 16185
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Gets a value indicating whether - Remove the global text engine resource - Used for some text-layered PSD files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -> "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes.

**Returns:**
boolean - `true` if [remove global text engine resource]; otherwise, `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Sets a value indicating whether - Remove the global text engine resource - Used for some text-layered PSD files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -> "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if [remove global text engine resource]; otherwise, `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Gets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers.

**Returns:**
boolean - `true` if [refresh image preview data]; otherwise, `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if [refresh image preview data]; otherwise, `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Gets the PSD vectorization options.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Sets the PSD vectorization options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | the PSD vectorization options. |

