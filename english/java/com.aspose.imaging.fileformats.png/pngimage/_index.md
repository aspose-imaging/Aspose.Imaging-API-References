---
title: PngImage
second_title: Aspose.Imaging for Java API Reference
description: The new png image.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

The new png image.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Initializes a new instance of the `PngImage` class. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Initializes a new instance of the `PngImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel. |
| [getHeight()](#getHeight--) | Gets the height. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets or sets the horizontal resolution. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Gets or sets the horizontal resolution. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getRawDataFormat()](#getRawDataFormat--) | Gets the raw data format. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets or sets the vertical resolution. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Gets or sets the vertical resolution. |
| [getWidth()](#getWidth--) | Gets the width. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether image has transparent color. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Gets a value indicating whether image has transparent color. |
| [hasAlpha()](#hasAlpha--) | Get a value indicating whether this instance has alpha. |
| [getTransparentColor()](#getTransparentColor--) | Gets the transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Gets the transparent color. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Gets a value indicating whether has background color. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Gets a value indicating whether has background color. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Gets the background color. |
| [getInterlaced()](#getInterlaced--) | Gets a value indicating whether this `PngImage` is interlaced. |
| [isInterlaced()](#isInterlaced--) | Gets a value indicating whether this image instance is interlaced. |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Load a PNG image from a file.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Transform the image to grayscale representation
    pngImage.grayscale();

    // Save to a file.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |
| colorType | int | The color type. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |
| colorType | int | The color type. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |
| colorType | int | The color type. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Initializes a new instance of the `PngImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | The png options. |
| width | int | The width. |
| height | int | The height. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the bits per pixel.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the height.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Gets or sets the horizontal resolution.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Get horizontal and vertical resolution of the PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The horizontal resolution, in pixels per inch: 96.0
//The vertical resolution, in pixels per inch: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Gets or sets the horizontal resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Gets the raw data format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// The PNG images to load.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// The output may look like this:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets or sets the vertical resolution.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Get horizontal and vertical resolution of the PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The horizontal resolution, in pixels per inch: 96.0
//The vertical resolution, in pixels per inch: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Gets or sets the vertical resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width.

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gets a value indicating whether image has transparent color.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Gets a value indicating whether image has transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Create a TrueColor PNG image of 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // All red pixels will be considered as fully transparent.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // All transparent pixels will have a background color.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fill the entire image with white color.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fill the top-left quarter of the image with the transparent color.
    // This makes the top-left quarter colored in the background color.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Get a value indicating whether this instance has alpha.

Value: `true` if this instance has alpha; otherwise, `false`.

**Returns:**
boolean

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Helper class
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Here is the main example
Utils utils = new Utils();

// Get all supported PNG color types.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// The output looks like this:
// A Grayscale PNG image doesn't support alpha channel
// A Truecolor PNG image doesn't support alpha channel
// A IndexedColor PNG image doesn't support alpha channel
// A GrayscaleWithAlpha PNG image supports alpha channel
// A TruecolorWithAlpha PNG image supports alpha channel
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Gets the transparent color.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Gets the transparent color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Create a TrueColor PNG image of 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // All red pixels will be considered as fully transparent.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // All transparent pixels will have a background color.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fill the entire image with white color.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fill the top-left quarter of the image with the transparent color.
    // This makes the top-left quarter colored in the background color.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Gets a value indicating whether has background color.

**Returns:**
boolean
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Gets a value indicating whether has background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Create a TrueColor PNG image of 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // All red pixels will be considered as fully transparent.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // All transparent pixels will have a background color.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fill the entire image with white color.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fill the top-left quarter of the image with the transparent color.
    // This makes the top-left quarter colored in the background color.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Gets the background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Create a TrueColor PNG image of 100x100 px.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // All red pixels will be considered as fully transparent.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // All transparent pixels will have a background color.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Fill the entire image with white color.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Fill the top-left quarter of the image with the transparent color.
    // This makes the top-left quarter colored in the background color.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Gets a value indicating whether this `PngImage` is interlaced.

Value: `true` if interlaced; otherwise, `false`.

**Returns:**
boolean
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Gets a value indicating whether this image instance is interlaced.

Value: `true` if this image instance is interlaced; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this image instance is interlaced.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata.

Value: The XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper)
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata.

Value: The XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Gets the default options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the `DataStreamSupporter.Save(string)` method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the `Image.Save(string, ImageOptionsBase)` method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
