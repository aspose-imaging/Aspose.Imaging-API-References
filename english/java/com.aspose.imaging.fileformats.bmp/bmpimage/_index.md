---
title: BmpImage
second_title: Aspose.Imaging for Java API Reference
description: You can effortlessly handle Bitmap BMP and Device Independent Bitma DIB files facilitating efficient manipulation and processing of raster images.
type: docs
weight: 15
url: /java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap (DIB) files, facilitating efficient manipulation and processing of raster images. Performing various operations on images, this API streamlines the workflow, offering developers a reliable toolkit for working with BMP and DIB formats in their software applications.
## Constructors

| Constructor | Description |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Start using the BmpImage class effortlessly with this constructor that initializes a new instance. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class with this constructor, using specified parameters like path, bitsPerPixel, and compression. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Begin using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class effortlessly by initializing a new instance with this constructor, using a stream as input. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Start working with the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by creating a new instance using a stream, along with specified parameters like bitsPerPixel and compression. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class by initializing it with a RasterImage object. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Start working with the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by creating a new instance using a rasterImage along with specified parameters like bitsPerPixel and compression. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Start using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class effortlessly by creating a new instance with specified width and height parameters. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Begin using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by initializing a new instance with parameters such as width, height, bit-depth, and palette. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class with this constructor, specifying parameters like width, height, bitsPerPixel, and palette. |
## Methods

| Method | Description |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Quickly access essential details about your bitmap image with this straightforward function. |
| [getFileFormat()](#getFileFormat--) | Easily retrieve the file format value with this user-friendly property. |
| [getRawDataFormat()](#getRawDataFormat--) | Easily obtain the format of your raw data with this user-friendly function. |
| [getRawLineSize()](#getRawLineSize--) | Quickly access the size of each raw line in bytes with this straightforward property. |
| [getCompression()](#getCompression--) | Retrieve the compression type used for the image effortlessly with this property. |
| [getWidth()](#getWidth--) | Access the width of the image easily with this property. |
| [getHeight()](#getHeight--) | Retrieve the height of the image effortlessly with this property. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Access the number of bits per pixel for the image with ease using this property. |
| [getHorizontalResolution()](#getHorizontalResolution--) | This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage) object. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage) object. |
| [getVerticalResolution()](#getVerticalResolution--) | Easily retrieve or set the vertical resolution, measured in pixels per inch, of this [RasterImage](../../com.aspose.imaging/rasterimage) object with this property. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Easily retrieve or set the vertical resolution, measured in pixels per inch, of this [RasterImage](../../com.aspose.imaging/rasterimage) object with this property. |
| [hasAlpha()](#hasAlpha--) | Gets a value indicating whether this instance has alpha. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Adjust the resolution of your [RasterImage](../../com.aspose.imaging/rasterimage) effortlessly with this user-friendly method. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Retrieve the default options effortlessly with this straightforward method. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Create a BMP image 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Fill the image with a simple linear red-black gradient.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Load a PNG image from a file.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP image is saved with transparency support by default.
    // If you want to explicitly specify such mode, the BmpOptions's Compression property should be set to BitmapCompression.Bitfields.
    // The BitmapCompression.Bitfields compression method is the default compression method in the BmpOptions.
    // So the same result of exporting a Bmp image with transparency can be achieved by either one of the following ways.
    // With an implicit default options:
    pngImage.save(outputPathPng);
    // With an explicit default options:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specifying the BitmapCompression.Bitfields compression method:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Load a PNG image from a file.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP image is saved with transparency support by default, that is achieved by using the BitmapCompression.Bitfields compression method.
    // To save a BMP image with the Rgb compression method, the BmpOptions with the Compression property set to BitmapCompression.Rgb should be specified.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Start using the BmpImage class effortlessly with this constructor that initializes a new instance. Perfect for developers who want to get up and running with [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) objects quickly and efficiently.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class with this constructor, using specified parameters like path, bitsPerPixel, and compression. Ideal for developers looking to initialize BmpImage objects quickly and efficiently, with precise control over image characteristics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |
| compression | long | The compression to use. |
| horizontalResolution | double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Begin using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class effortlessly by initializing a new instance with this constructor, using a stream as input. Perfect for developers seeking a convenient way to work with BmpImage objects from various data sources, ensuring flexibility and ease of integration.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Start working with the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by creating a new instance using a stream, along with specified parameters like bitsPerPixel and compression. Perfect for developers seeking a straightforward way to handle BmpImage objects, ensuring flexibility and efficiency in their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |
| compression | long | The compression to use. |
| horizontalResolution | double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class by initializing it with a RasterImage object. Perfect for developers looking to seamlessly convert existing raster images to the BmpImage format, ensuring compatibility and ease of integration into their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Start working with the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by creating a new instance using a rasterImage along with specified parameters like bitsPerPixel and compression. Perfect for developers seeking a straightforward way to handle BmpImage objects, ensuring flexibility and efficiency in their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |
| bitsPerPixel | int | The bits per pixel. |
| compression | long | The compression to use. |
| horizontalResolution | double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Start using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class effortlessly by creating a new instance with specified width and height parameters. Ideal for developers seeking a convenient way to generate BmpImage objects of custom dimensions, ensuring flexibility and ease of integration into their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Begin using the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class seamlessly by initializing a new instance with parameters such as width, height, bit-depth, and palette. Perfect for developers seeking a straightforward way to create BmpImage objects with custom dimensions and color configurations, ensuring flexibility and efficiency in their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |
| bitsPerPixel | int | The bits per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Effortlessly create a new instance of the [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) class with this constructor, specifying parameters like width, height, bitsPerPixel, and palette. Perfect for developers seeking a convenient way to generate BmpImage objects with custom dimensions and color configurations, ensuring flexibility and ease of integration into their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |
| bitsPerPixel | int | The bits per pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The color palette. |
| compression | long | The compression to use. |
| horizontalResolution | double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Quickly access essential details about your bitmap image with this straightforward function. Perfect for developers needing to retrieve header information for their images.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//The output may look like this:
//The number of palette colors that are required for displaying the bitmap: 0
//The number of palette colors used in the bitmap: 0
//The bitmap compression: 0
//The bitmap height: 100
//The bitmap width: 100
//The bitmap raw data size in bytes: 40000
//The number of planes: 1
//The horizontal resolution of the bitmap, in pixels-per-meter: 0
//The vertical resolution of the bitmap, in pixels-per-meter: 0
//The number of bits per pixel: 32
//The extra bits masks: null
//The header size in bytes: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Easily retrieve the file format value with this user-friendly property. Ideal for developers seeking quick access to information about the file format.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// The helper class used in the main example below.
class Utils {
    // The helper method to get a string representation of the file format.
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

// Here is the main example
Utils utils = new Utils();

// Create a 32-bpp BMP image of 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Create a 24-bpp BMP image of 100 x 100 px.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// In most cases BMP doesn't support alpha channel so the output will probably look like this:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, used channels: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Easily obtain the format of your raw data with this user-friendly function. Perfect for developers looking to quickly access crucial information about their data format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The pixel format: Rgb24Bpp, used channels: 8,8,8
//The raw line size in bytes: 1500
//The bitmap compression: 0
//The bitmap width: 500
//The bitmap height: 500
//The number of bits per pixel: 24
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
//Set resolution values to 96 dpi
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Quickly access the size of each raw line in bytes with this straightforward property. Ideal for developers needing to efficiently handle raw image data.

**Returns:**
int - The raw line size in bytes.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The pixel format: Rgb24Bpp, used channels: 8,8,8
//The raw line size in bytes: 1500
//The bitmap compression: 0
//The bitmap width: 500
//The bitmap height: 500
//The number of bits per pixel: 24
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
//Set resolution values to 96 dpi
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Retrieve the compression type used for the image effortlessly with this property. Perfect for developers needing to quickly access information about image compression.

**Returns:**
long - The image compression [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// The helper class used in the main example below.
class Utils {
    // The helper method to get a string representation of the file format.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Here is the main example
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Create a monochrome palette which contains only red and green colors.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Create a 8-bpp BMP image of 100 x 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Fill the entire image in red.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Save the image to a stream to get the output image size.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// The output may look like this:
// The compression=RGB
// The number of bits per pixel=8
// The image dimensions=100 x 100
// The raw line size=100
// The output size in bytes=11078
// ---------------------------------------------
// The compression=RLE8
// The number of bits per pixel=8
// The image dimensions=100 x 100
// The raw line size=100
// The output size in bytes=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Access the width of the image easily with this property. Ideal for developers seeking quick information about the image dimensions.

**Returns:**
int - The image width in pixels.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The pixel format: Rgb24Bpp, used channels: 8,8,8
//The raw line size in bytes: 1500
//The bitmap compression: 0
//The bitmap width: 500
//The bitmap height: 500
//The number of bits per pixel: 24
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
//Set resolution values to 96 dpi
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Retrieve the height of the image effortlessly with this property. Ideal for developers needing quick access to information about image dimensions.

**Returns:**
int - The image height in pixels.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The pixel format: Rgb24Bpp, used channels: 8,8,8
//The raw line size in bytes: 1500
//The bitmap compression: 0
//The bitmap width: 500
//The bitmap height: 500
//The number of bits per pixel: 24
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
//Set resolution values to 96 dpi
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Access the number of bits per pixel for the image with ease using this property. Perfect for developers seeking quick information about image quality and depth.

**Returns:**
int - The image bits per pixel count.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//The output may look like this:
//The pixel format: Rgb24Bpp, used channels: 8,8,8
//The raw line size in bytes: 1500
//The bitmap compression: 0
//The bitmap width: 500
//The bitmap height: 500
//The number of bits per pixel: 24
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
//Set resolution values to 96 dpi
//The horizontal resolution, in pixels per inch: 96.012
//The vertical resolution, in pixels per inch: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage) object. Ideal for developers needing precise control over image resolution for their applications.

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the \#setResolution(double, double).setResolution(double, double) method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 0.0
// The vertical resolution, in pixels per inch: 0.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.012
// The vertical resolution, in pixels per inch: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage) object. Ideal for developers needing precise control over image resolution for their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

--------------------

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the \#setResolution(double, double).setResolution(double, double) method for updating both resolution values in single call. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Easily retrieve or set the vertical resolution, measured in pixels per inch, of this [RasterImage](../../com.aspose.imaging/rasterimage) object with this property. Perfect for developers requiring precise control over image resolution in their applications.

**Returns:**
double - The vertical resolution.

--------------------

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the \#setResolution(double, double).setResolution(double, double) method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 0.0
// The vertical resolution, in pixels per inch: 0.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.012
// The vertical resolution, in pixels per inch: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Easily retrieve or set the vertical resolution, measured in pixels per inch, of this [RasterImage](../../com.aspose.imaging/rasterimage) object with this property. Perfect for developers requiring precise control over image resolution in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

--------------------

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the \#setResolution(double, double).setResolution(double, double) method for updating both resolution values in single call. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets a value indicating whether this instance has alpha.

**Returns:**
boolean - a value indicating whether this instance has alpha.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Adjust the resolution of your [RasterImage](../../com.aspose.imaging/rasterimage) effortlessly with this user-friendly method. Perfect for developers seeking precise control over image resolution in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | The vertical resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 0.0
// The vertical resolution, in pixels per inch: 0.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.012
// The vertical resolution, in pixels per inch: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Retrieve the default options effortlessly with this straightforward method. Ideal for developers seeking quick access to default image settings or configurations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
