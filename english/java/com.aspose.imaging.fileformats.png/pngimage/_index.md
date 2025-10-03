---
title: PngImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate Portable Network Graphics PNG raster images with our versatile API featuring support for compression levels and various color depths including Grayscale Indexed Color TrueColor and alpha channels.
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

Manipulate Portable Network Graphics (PNG) raster images with our versatile API, featuring support for compression levels and various color depths including Grayscale, Indexed Color, TrueColor, and alpha channels. Seamlessly process XMP metadata, enabling comprehensive image metadata management, while easily loading PNG images, performing diverse manipulations, applying filters, and converting images to other file formats for optimal versatility and customization.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Initialize a new object of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by providing the width and height parameters. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Constructs a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class using the path parameter to specify the location of the image file to load. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by providing a raster image as a parameter. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Initializes a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by specifying the path to the image file and the color type. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by specifying a raster image and a color type. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by initializing it with a stream. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Instantiate a fresh instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class, specifying the desired width, height, and color type parameters. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Initialize a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class, incorporating PNG options alongside width and height parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the bits per pixel value for the image. |
| [getHeight()](#getHeight--) | Obtain the height of the image in pixels. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Retrieve or modify the horizontal resolution of the image. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Retrieve or modify the horizontal resolution of the image. |
| [getFileFormat()](#getFileFormat--) | Retrieves the format of the file associated with the image instance. |
| [getRawDataFormat()](#getRawDataFormat--) | Accesses the raw data format of the image. |
| [getVerticalResolution()](#getVerticalResolution--) | Provides access to the vertical resolution of the image. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Provides access to the vertical resolution of the image. |
| [getWidth()](#getWidth--) | Allows retrieval of the width of the image in pixels, providing essential information about its dimensions. |
| [hasTransparentColor()](#hasTransparentColor--) | Provides a boolean value indicating whether the image contains a transparent color. |
| [hasAlpha()](#hasAlpha--) | Returns a boolean value indicating whether the image has an alpha channel, which determines its transparency. |
| [getTransparentColor()](#getTransparentColor--) | Retrieves the transparent color of the image, if it exists. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Provides a boolean value indicating whether the image contains a transparent color. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Modifies the transparent color of the image, if it exists. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Retrieves a boolean value indicating whether the image has a background color. |
| [getBackgroundColor()](#getBackgroundColor--) | Retrieves the background color of the image, if one is specified. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Retrieves a boolean value indicating whether the image has a background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Retrieves the background color of the image, if one is specified. |
| [getInterlaced()](#getInterlaced--) | Retrieves a boolean value indicating whether the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is interlaced, which determines if the image data is stored in a progressive manner for faster loading or transmission. |
| [isInterlaced()](#isInterlaced--) | Gets a value indicating whether this image instance is interlaced. |
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


Initialize a new object of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by providing the width and height parameters. This constructor simplifies the creation of PNG images by allowing developers to specify the dimensions directly, facilitating efficient management of PNG image data within their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Constructs a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class using the path parameter to specify the location of the image file to load. This constructor enables developers to conveniently create PNG images by loading them from a file, simplifying the process of working with PNG images in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by providing a raster image as a parameter. This constructor allows developers to directly initialize a PNG image object using an existing raster image, streamlining the process of working with PNG images in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Initializes a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by specifying the path to the image file and the color type. This constructor allows for convenient creation of PNG images from files with different color types, providing flexibility in handling various image formats.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load an image. |
| colorType | int | The color type. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by specifying a raster image and a color type. This constructor enables developers to directly convert raster images into PNG format while specifying the desired color type, offering flexibility in color representation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |
| colorType | int | The color type. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Creates a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class by initializing it with a stream. This constructor allows developers to load PNG images directly from a stream, providing flexibility in image retrieval from different sources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load an image. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Instantiate a fresh instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class, specifying the desired width, height, and color type parameters. This constructor enables swift creation of PNG images with tailored dimensions and color configurations, facilitating streamlined image generation for various applications and workflows.

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


Initialize a new instance of the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) class, incorporating PNG options alongside width and height parameters. This constructor empowers developers to create PNG images with customizable settings and dimensions, offering flexibility in image generation for diverse use cases.

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


Retrieve the bits per pixel value for the image. This property provides crucial information regarding the color depth of the image, enabling developers to understand the level of detail and color accuracy present in the image data.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtain the height of the image in pixels. This property returns the vertical dimension of the image, allowing developers to determine its size in pixels along the vertical axis.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Retrieve or modify the horizontal resolution of the image. This property represents the number of pixels per inch along the horizontal axis of the image. Adjusting this resolution can affect the physical size of the image when printed or displayed.

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


Retrieve or modify the horizontal resolution of the image. This property represents the number of pixels per inch along the horizontal axis of the image. Adjusting this resolution can affect the physical size of the image when printed or displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieves the format of the file associated with the image instance. This property provides essential information regarding the file type, enabling efficient handling and processing based on the specific format requirements.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Accesses the raw data format of the image. This property provides insight into how the image data is structured internally, which can be useful for advanced image processing tasks or format conversion.

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


Provides access to the vertical resolution of the image. Developers can use this property to retrieve or modify the resolution setting, which indicates the number of pixels per inch (PPI) along the vertical axis of the image.

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


Provides access to the vertical resolution of the image. Developers can use this property to retrieve or modify the resolution setting, which indicates the number of pixels per inch (PPI) along the vertical axis of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Allows retrieval of the width of the image in pixels, providing essential information about its dimensions. This property is frequently used by developers to determine the image's width, enabling them to perform various operations based on its size

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Provides a boolean value indicating whether the image contains a transparent color. This property is crucial for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent regions in the image.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Returns a boolean value indicating whether the image has an alpha channel, which determines its transparency. This property is useful for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent areas in the image.

**Returns:**
boolean - `true` if this instance has alpha; otherwise, `false`.

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


Retrieves the transparent color of the image, if it exists. This property is valuable for applications requiring precise handling of transparent areas within images, allowing developers to access and manipulate the specific transparent color used.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Provides a boolean value indicating whether the image contains a transparent color. This property is crucial for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent regions in the image.

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

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Modifies the transparent color of the image, if it exists. This property is valuable for applications requiring precise handling of transparent areas within images, allowing developers to access and manipulate the specific transparent color used.

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


Retrieves a boolean value indicating whether the image has a background color. This property is useful for applications needing to determine if an image includes a background color, which can be important for various processing tasks such as compositing, rendering, or exporting.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Retrieves the background color of the image, if one is specified. This property is helpful for applications that need to identify and potentially manipulate the background color of an image.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Retrieves a boolean value indicating whether the image has a background color. This property is useful for applications needing to determine if an image includes a background color, which can be important for various processing tasks such as compositing, rendering, or exporting.

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

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Retrieves the background color of the image, if one is specified. This property is helpful for applications that need to identify and potentially manipulate the background color of an image.

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


Retrieves a boolean value indicating whether the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is interlaced, which determines if the image data is stored in a progressive manner for faster loading or transmission.

**Returns:**
boolean - `true` if interlaced; otherwise, `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Gets a value indicating whether this image instance is interlaced.

Value: `true` if this image instance is interlaced; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this image instance is interlaced.
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
