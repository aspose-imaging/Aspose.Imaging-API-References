---
title: GifOptions
second_title: Aspose.Imaging for Java API Reference
description: The API for Graphical Interchange Format GIF raster image file creation offers developers comprehensive options for generating GIF images with precise control.
type: docs
weight: 22
url: /java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

The API for Graphical Interchange Format (GIF) raster image file creation offers developers comprehensive options for generating GIF images with precise control. With features to set background color, color palette, resolution, interlaced type, transparent color, XMP metadata container, and image compression, this API ensures flexibility and efficiency in creating optimized and visually appealing GIFs tailored to specific application requirements.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initializes a new instance of the `GifOptions` class. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Initializes a new instance of the `GifOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Gets or sets a value indicating whether palette correction is applied. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Gets or sets a value indicating whether palette correction is applied. |
| [getLoopsCount()](#getLoopsCount--) | Gets the loops count (Default 1 loop) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Sets the loops count (Default 1 loop) |
| [getColorResolution()](#getColorResolution--) | Gets or sets the GIF color resolution. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Gets or sets the GIF color resolution. |
| [isPaletteSorted()](#isPaletteSorted--) | Gets or sets a value indicating whether palette entries are sorted. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Gets or sets a value indicating whether palette entries are sorted. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Gets or sets the GIF pixel aspect ratio. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Gets or sets the GIF pixel aspect ratio. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Gets or sets the GIF background color index. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Gets or sets the GIF background color index. |
| [hasTrailer()](#hasTrailer--) | Gets or sets a value indicating whether GIF has trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Gets or sets a value indicating whether GIF has trailer. |
| [getInterlaced()](#getInterlaced--) | True if image should be interlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True if image should be interlaced. |
| [getMaxDiff()](#getMaxDiff--) | Gets or sets the maximum allowed pixel difference. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Gets or sets the maximum allowed pixel difference. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets the background color. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether GIF image has transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Sets a value indicating whether GIF image has transparent color. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
This example demonstrates the use of different classes from SaveOptions Namespace for export purposes. An image of type Gif is loaded into an instance of Image and then exported out to several formats.
``` java
String dir = "c:\\temp\\";

//Load an existing image (of type Gif) in an instance of Image class
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Export to BMP file format using the default options
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Export to JPEG file format using the default options
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Export to PNG file format using the default options
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Export to TIFF file format using the default options
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. These pages will be presented as animated frames in the output GIF.
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initializes a new instance of the `GifOptions` class.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Initializes a new instance of the `GifOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | The GIF Options. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Gets or sets a value indicating whether palette correction is applied.

**Returns:**
boolean - `true` if palette correction is applied; otherwise, `false`.

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Gets or sets a value indicating whether palette correction is applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if palette correction is applied; otherwise, `false`.

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // The number of bits required to store a color, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palette correction means that whenever image is exported to GIF the source image colors will be analyzed
    // in order to build the best matching palette (in case image Palette does not exist or not specified in the options)
    saveOptions.setDoPaletteCorrection(true);

    // Load a GIF image in a progressive way.
    // An interlaced GIF doesn't display its scanlines linearly from top to bottom, but instead reorders it
    // so the content of the GIF becomes clear even before it finishes loading.
    saveOptions.setInterlaced(true);

    // Save as a lossless GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Set the maximum allowed pixel difference. If greater than zero, lossy compression will be used.
    // The recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.
    saveOptions.setMaxDiff(80);

    // Save as a lossy GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//The output may look like this:
//The size of the lossless GIF: 212816 bytes.
//The size of the lossy GIF: 89726 bytes.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Gets the loops count (Default 1 loop)

Value: The loops count.

**Returns:**
int - the loops count (Default 1 loop)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Sets the loops count (Default 1 loop)

Value: The loops count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the loops count (Default 1 loop) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Gets or sets the GIF color resolution.

**Returns:**
byte - The color resolution.

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Gets or sets the GIF color resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The color resolution.

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // The number of bits required to store a color, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palette correction means that whenever image is exported to GIF the source image colors will be analyzed
    // in order to build the best matching palette (in case image Palette does not exist or not specified in the options)
    saveOptions.setDoPaletteCorrection(true);

    // Load a GIF image in a progressive way.
    // An interlaced GIF doesn't display its scanlines linearly from top to bottom, but instead reorders it
    // so the content of the GIF becomes clear even before it finishes loading.
    saveOptions.setInterlaced(true);

    // Save as a lossless GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Set the maximum allowed pixel difference. If greater than zero, lossy compression will be used.
    // The recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.
    saveOptions.setMaxDiff(80);

    // Save as a lossy GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//The output may look like this:
//The size of the lossless GIF: 212816 bytes.
//The size of the lossy GIF: 89726 bytes.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Gets or sets a value indicating whether palette entries are sorted.

**Returns:**
boolean - `true` if palette entries are sorted; otherwise, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Gets or sets a value indicating whether palette entries are sorted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if palette entries are sorted; otherwise, `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gets or sets the GIF pixel aspect ratio.

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Returns:**
byte - The GIF pixel aspect ratio.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gets or sets the GIF pixel aspect ratio.

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The GIF pixel aspect ratio. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Gets or sets the GIF background color index.

**Returns:**
byte - The GIF background color index.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Gets or sets the GIF background color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The GIF background color index. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gets or sets a value indicating whether GIF has trailer.

**Returns:**
boolean - `true` if GIF has trailer; otherwise, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gets or sets a value indicating whether GIF has trailer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if GIF has trailer; otherwise, `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True if image should be interlaced.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True if image should be interlaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // The number of bits required to store a color, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palette correction means that whenever image is exported to GIF the source image colors will be analyzed
    // in order to build the best matching palette (in case image Palette does not exist or not specified in the options)
    saveOptions.setDoPaletteCorrection(true);

    // Load a GIF image in a progressive way.
    // An interlaced GIF doesn't display its scanlines linearly from top to bottom, but instead reorders it
    // so the content of the GIF becomes clear even before it finishes loading.
    saveOptions.setInterlaced(true);

    // Save as a lossless GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Set the maximum allowed pixel difference. If greater than zero, lossy compression will be used.
    // The recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.
    saveOptions.setMaxDiff(80);

    // Save as a lossy GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//The output may look like this:
//The size of the lossless GIF: 212816 bytes.
//The size of the lossy GIF: 89726 bytes.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used. Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy. It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain. The range of allowed values is [0, 1000].

**Returns:**
int - The range of allowed values.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used. Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy. It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain. The range of allowed values is [0, 1000].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The range of allowed values. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Fill the entire image with the blue-yellow gradient.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // The number of bits required to store a color, minus 1.
    saveOptions.setColorResolution((byte) 7);

    // Palette correction means that whenever image is exported to GIF the source image colors will be analyzed
    // in order to build the best matching palette (in case image Palette does not exist or not specified in the options)
    saveOptions.setDoPaletteCorrection(true);

    // Load a GIF image in a progressive way.
    // An interlaced GIF doesn't display its scanlines linearly from top to bottom, but instead reorders it
    // so the content of the GIF becomes clear even before it finishes loading.
    saveOptions.setInterlaced(true);

    // Save as a lossless GIF.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Set the maximum allowed pixel difference. If greater than zero, lossy compression will be used.
    // The recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.
    saveOptions.setMaxDiff(80);

    // Save as a lossy GIF.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//The output may look like this:
//The size of the lossless GIF: 212816 bytes.
//The size of the lossy GIF: 89726 bytes.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Sets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | the background color. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Gets a value indicating whether GIF image has transparent color.

**Returns:**
boolean - a value indicating whether GIF image has transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public final void setTransparentColor(boolean value)
```


Sets a value indicating whether GIF image has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether GIF image has transparent color. |

