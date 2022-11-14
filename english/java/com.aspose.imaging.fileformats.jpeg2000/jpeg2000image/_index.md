---
title: Jpeg2000Image
second_title: Aspose.Imaging for Java API Reference
description: Jpeg2000 library main class
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Jpeg2000 library main class
## Constructors

| Constructor | Description |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Initializes a new instance of the `Jpeg2000Image` class. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Initializes a new instance of the `Jpeg2000Image` class. |
## Methods

| Method | Description |
| --- | --- |
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getRawDataFormat()](#getRawDataFormat--) | Gets the raw data format. |
| [getRawLineSize()](#getRawLineSize--) | Gets the raw line size in bytes. |
| [getWidth()](#getWidth--) | Gets the image width |
| [getHeight()](#getHeight--) | Gets the image height |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets image depth (bits per pixel) |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets or sets the horizontal resolution, in pixels per inch, of this `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Gets or sets the horizontal resolution, in pixels per inch, of this `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets or sets the vertical resolution, in pixels per inch, of this `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Gets or sets the vertical resolution, in pixels per inch, of this `RasterImage`. |
| [getComments()](#getComments--) | Gets or sets the comments. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Gets or sets the comments. |
| [getCodec()](#getCodec--) | Gets the codec. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |

## Example
This example shows how to load a JPEG2000 image from a file and save it to PNG.
``` java
String dir = "c:\\temp\\";

// Load a JPEG2000 image.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Save to PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with |
| bitsPerPixel | int | The bits per pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | The options. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height |
| bitsCount | int | The bits count. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Initializes a new instance of the `Jpeg2000Image` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - The XMP metadata.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | The XMP metadata. |

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
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Gets the raw line size in bytes.

**Returns:**
int - The raw line size in bytes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets image depth (bits per pixel)

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Gets or sets the horizontal resolution, in pixels per inch, of this `RasterImage`.

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example:**
The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Get horizontal and vertical resolution of the Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 72.0
// The vertical resolution, in pixels per inch: 72.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 72.0
// The vertical resolution, in pixels per inch: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Gets or sets the horizontal resolution, in pixels per inch, of this `RasterImage`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets or sets the vertical resolution, in pixels per inch, of this `RasterImage`.

**Returns:**
double - The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example:**
The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Get horizontal and vertical resolution of the Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 72.0
// The vertical resolution, in pixels per inch: 72.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 72.0
// The vertical resolution, in pixels per inch: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Gets or sets the vertical resolution, in pixels per inch, of this `RasterImage`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Gets or sets the comments.

**Returns:**
java.lang.String[] - The comments.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Gets or sets the comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The comments. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Gets the codec.

**Returns:**
int - The codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String,ImageOptionsBase)](../../com.aspose.imaging/image\#save-String-ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
