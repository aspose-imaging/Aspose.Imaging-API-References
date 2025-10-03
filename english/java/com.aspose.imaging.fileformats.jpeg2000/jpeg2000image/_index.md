---
title: Jpeg2000Image
second_title: Aspose.Imaging for Java API Reference
description: Efficiently manipulate JPEG2000 JP2 image files with our API supporting a range of bits per pixel depths and seamless processing of XMP metadata containing essential image information.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Efficiently manipulate JPEG2000 (JP2) image files with our API, supporting a range of bits per pixel depths and seamless processing of XMP metadata containing essential image information. With capabilities for lossless compression, ensure optimal image quality while maintaining file integrity, empowering you to tailor JP2 images to your exact specifications with ease.
## Constructors

| Constructor | Description |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Start working with the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by initializing a new instance with the path to the image you want to load. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Get started easily with the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by creating a new instance with both the file path and the desired bits per pixel parameter. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Easily initialize a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by providing a stream object. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Initialize a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with a stream to load the image, along with bits per pixel parameters. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Create a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class, specifying the width and height parameters. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Instantiate a new [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) object, providing the width, height, and image options parameters. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Create a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with parameters for width, height, and bits count. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Instantiate a new [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with a raster image. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Initialize a fresh [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) instance with a raster image and bits per pixel parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the format of the image file. |
| [getRawDataFormat()](#getRawDataFormat--) | This property retrieves the raw data format of the image. |
| [getRawLineSize()](#getRawLineSize--) | This property retrieves the size of a single line of raw image data in bytes. |
| [getWidth()](#getWidth--) | This property returns the width of the image in pixels. |
| [getHeight()](#getHeight--) | This property retrieves the height of the image in pixels. |
| [getBitsPerPixel()](#getBitsPerPixel--) | This property returns the depth of the image, measured in bits per pixel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | This property allows you to retrieve or modify the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | This property allows you to retrieve or modify the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | This property provides access to the vertical resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | This property provides access to the vertical resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). |
| [getComments()](#getComments--) | This property allows for retrieving or updating the comments associated with the image. |
| [setComments(String[] value)](#setComments-java.lang.String---) | This property allows for retrieving or updating the comments associated with the image. |
| [getCodec()](#getCodec--) | This property retrieves the JPEG2000 codec associated with the image. |
| [getOriginalOptions()](#getOriginalOptions--) | Retrieve the image options based on the original file settings. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

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


Start working with the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by initializing a new instance with the path to the image you want to load. This constructor enables easy access to JPEG2000 images, simplifying the process of loading and handling image files. By providing the file path, you can quickly begin processing and manipulating JPEG2000 images in your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Get started easily with the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by creating a new instance with both the file path and the desired bits per pixel parameter. This constructor allows for fine-tuning the image loading process, ensuring compatibility with various image formats and quality settings. With this flexibility, you can efficiently manage and manipulate JPEG2000 images according to your specific requirements.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with |
| bitsPerPixel | int | The bits per pixel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Easily initialize a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class by providing a stream object. This constructor simplifies the process of loading JPEG2000 images directly from streams, offering flexibility and convenience for handling image data from various sources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Initialize a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with a stream to load the image, along with bits per pixel parameters. This constructor offers flexibility by allowing you to specify both the image data source and the desired bits per pixel, providing finer control over the image loading process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Create a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class, specifying the width and height parameters. This constructor allows you to initialize a JPEG2000 image with specific dimensions, which is useful for scenarios where you need to create an image of a certain size programmatically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Instantiate a new [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) object, providing the width, height, and image options parameters. This constructor allows for the creation of JPEG2000 images with specific dimensions and additional options, offering flexibility in image generation.

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


Create a new instance of the [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with parameters for width, height, and bits count. This constructor allows for the creation of JPEG2000 images with specific dimensions and bit depths, providing flexibility for various imaging needs.

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


Instantiate a new [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) class with a raster image. This constructor facilitates the creation of a JPEG2000 image from an existing raster image, offering seamless integration and conversion between different image formats.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Initialize a fresh [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) instance with a raster image and bits per pixel parameters. This constructor enables precise control over the quality and size of the resulting JPEG2000 image, making it ideal for scenarios where customization is crucial.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the format of the image file. This property provides information about the file format of the image. Utilize this property to determine the format of the image file programmatically, facilitating appropriate handling and processing based on the file's format.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


This property retrieves the raw data format of the image. It provides information about how the pixel data is stored in memory. Use this property to understand the underlying data format of the image, which can be crucial for various image processing operations like color conversion, compression, or decompression.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


This property retrieves the size of a single line of raw image data in bytes. It indicates the amount of memory occupied by a single row of pixels in the image's raw data format. Understanding the raw line size is essential for tasks such as memory allocation, data manipulation, and image processing algorithms that operate on individual image lines.

**Returns:**
int - The raw line size in bytes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


This property returns the width of the image in pixels. It provides a fundamental piece of information about the image's dimensions, crucial for various image processing tasks, including resizing, cropping, and rendering.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


This property retrieves the height of the image in pixels. It serves as essential information for understanding the image's vertical dimensions, aiding in various image manipulation tasks like resizing, cropping, and rendering. Accessing this property allows users to ascertain the image's vertical size, enabling precise layout and display in applications.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


This property returns the depth of the image, measured in bits per pixel (bpp). It indicates the amount of color information stored in each pixel of the image. Understanding the image depth is crucial for determining the color fidelity and quality of the image. With this information, users can gauge the level of detail and richness of colors present in the image.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


This property allows you to retrieve or modify the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). Adjusting this resolution can impact the size and quality of the image when printed or displayed. By setting the horizontal resolution, users can optimize the image for specific output devices or applications, ensuring the best possible visual results.

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

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


This property allows you to retrieve or modify the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). Adjusting this resolution can impact the size and quality of the image when printed or displayed. By setting the horizontal resolution, users can optimize the image for specific output devices or applications, ensuring the best possible visual results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


This property provides access to the vertical resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). Modifying this resolution can affect the quality and size of the image when printed or displayed. By adjusting the vertical resolution, users can optimize the image for different output devices or applications, ensuring optimal visual rendering.

**Returns:**
double - The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

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


This property provides access to the vertical resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch (PPI). Modifying this resolution can affect the quality and size of the image when printed or displayed. By adjusting the vertical resolution, users can optimize the image for different output devices or applications, ensuring optimal visual rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getComments() {#getComments--}
```
public String[] getComments()
```


This property allows for retrieving or updating the comments associated with the image. Comments provide additional information about the image content, such as annotations, descriptions, or metadata. Modifying these comments can be useful for organizing and categorizing images, as well as conveying important details to viewers or users.

**Returns:**
java.lang.String[] - The comments.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


This property allows for retrieving or updating the comments associated with the image. Comments provide additional information about the image content, such as annotations, descriptions, or metadata. Modifying these comments can be useful for organizing and categorizing images, as well as conveying important details to viewers or users.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The comments. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


This property retrieves the JPEG2000 codec associated with the image. The JPEG2000 codec is responsible for encoding and decoding the image data in the JPEG2000 format, providing efficient compression while maintaining high image quality. Accessing this codec can be useful for performing advanced image processing operations or optimizing image compression settings tailored to specific requirements.

**Returns:**
int - The codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Retrieve the image options based on the original file settings. This method is beneficial for maintaining the bit-depth and other parameters of the original image, ensuring consistency and preserving the integrity of the image data. Accessing these options facilitates seamless handling and processing of the image while retaining its original characteristics. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
