---
title: JpegImage
second_title: Aspose.Imaging for Java API Reference
description: Efficiently manipulate JPEG raster images with our API offering support for various color profiles such as RGB and CMYK customizable bits per pixel resolution and processing of EXIF JFIF and XMP metadata containers.
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Efficiently manipulate JPEG raster images with our API, offering support for various color profiles such as RGB and CMYK, customizable bits per pixel resolution, and processing of EXIF, JFIF, and XMP metadata containers. Enjoy automated rotation based on orientation data and choose from different compression levels, including lossless JPEG, to achieve optimal image quality and file size balance for your projects.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | The [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class initiates effortlessly by invoking its constructor with the specified path parameter. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Initialize a JPEG image object with the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class using a stream parameter. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Initialize a new instance of the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class with a raster image parameter. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Create a new instance of the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class with the specified width and height parameters. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Initialize a new [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) object with the provided JPEG options. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the format of the image effortlessly with this property. |
| [getJpegOptions()](#getJpegOptions--) | Gain access to the JPEG options employed during the creation or loading of this [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) instance with ease. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the pixel depth of the image effortlessly with this property, offering insights into the richness of color or grayscale representation. |
| [getComment()](#getComment--) | Manage JPEG file comments with this property, allowing you to add or retrieve descriptive annotations associated with the image. |
| [setComment(String value)](#setComment-java.lang.String-) | Manage JPEG file comments with this property, allowing you to add or retrieve descriptive annotations associated with the image. |
| [getJpegExifData()](#getJpegExifData--) | Gets Exif instance. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Manage EXIF data with this property, allowing you to add or retrieve metadata associated with the image. |
| [getExifData()](#getExifData--) | Gets Exif data; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Sets Exif data; |
| [getHeight()](#getHeight--) | Retrieve the height of the image effortlessly with this property. |
| [getHorizontalResolution()](#getHorizontalResolution--) | This property grants you access to the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | This property grants you access to the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch. |
| [getJfif()](#getJfif--) | This property allows you to access or modify the JFIF (JPEG File Interchange Format) data associated with the JPEG image. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | This property allows you to access or modify the JFIF (JPEG File Interchange Format) data associated with the JPEG image. |
| [getRawDataFormat()](#getRawDataFormat--) | This property retrieves the raw data format of the image, which indicates how the image data is structured and encoded. |
| [getVerticalResolution()](#getVerticalResolution--) | This property manages the vertical resolution, expressed in pixels per inch, for the associated [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | This property manages the vertical resolution, expressed in pixels per inch, for the associated [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getWidth()](#getWidth--) | This property retrieves the width of the image, expressed in pixels. |
| [getRgbColorProfile()](#getRgbColorProfile--) | The RGB color profile for CMYK and YCCK JPEG images ensures accurate color conversion and representation. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | The RGB color profile for CMYK and YCCK JPEG images ensures accurate color conversion and representation. |
| [getCmykColorProfile()](#getCmykColorProfile--) | The CMYK color profile associated with CMYK and YCCK JPEG images ensures precise color conversion and fidelity. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | The CMYK color profile associated with CMYK and YCCK JPEG images ensures precise color conversion and fidelity. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | The RGBColorProfile is essential for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | The RGBColorProfile is essential for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | The CMYK color profile is vital for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | The CMYK color profile is vital for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Retrieves or modifies the flag denoting whether the embedded color profile is disregarded. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Retrieves or modifies the flag denoting whether the embedded color profile is disregarded. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the original image options of this [Image](../../com.aspose.imaging/image) instance. |
| [removeMetadata()](#removeMetadata--) | Removes this image instance metadata by setting this `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) and `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) values to `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establishes the resolution for the specified [RasterImage](../../com.aspose.imaging/rasterimage), ensuring accurate scaling and printing capabilities. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Load a JPEG image from a file.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Do some image processing.
    // Save to another JPEG file.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


The [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class initiates effortlessly by invoking its constructor with the specified path parameter. This constructor enables seamless creation of JPEG images, ensuring swift integration into your projects with ease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Initialize a JPEG image object with the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class using a stream parameter. This constructor simplifies the process of working with JPEG images, offering a straightforward approach for integrating them into your projects effortlessly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Initialize a new instance of the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class with a raster image parameter. This constructor provides a convenient way to create JPEG images directly from raster images, streamlining the workflow for working with JPEG images in your applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Create a new instance of the [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) class with the specified width and height parameters. This constructor allows you to create JPEG images with custom dimensions, giving you flexibility in managing image sizes in your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Initialize a new [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) object with the provided JPEG options. This constructor empowers you to tailor various settings for the JPEG image, such as compression level, quality, and additional parameters, granting precise control over the resulting image format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | The jpeg options. |
| width | int | Image width. |
| height | int | Image height. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the format of the image effortlessly with this property. It provides valuable insight into the file format, aiding in seamless integration and compatibility checks across various platforms and applications.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Gain access to the JPEG options employed during the creation or loading of this [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) instance with ease. This property offers valuable details about the specific settings utilized, empowering users to understand and replicate image processing workflows effectively. Whether it's compression levels, quality settings, or other parameters, this property provides essential insights for seamless image manipulation.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//The output looks like this:
//The number of bits per channel: 8
//The max allowed size for all internal buffers: 0
//The color type: YCbCr
//The compression type: Baseline
//The image quality: 75
//The sampling for component 0: 1x1
//The sampling for component 1: 1x1
//The sampling for component 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the pixel depth of the image effortlessly with this property, offering insights into the richness of color or grayscale representation. Whether it's a vibrant photograph or a monochrome illustration, this property provides crucial information about the image's visual complexity.

**Returns:**
int - The image bits per pixel count.
### getComment() {#getComment--}
```
public String getComment()
```


Manage JPEG file comments with this property, allowing you to add or retrieve descriptive annotations associated with the image. Whether it's tagging images with metadata or appending additional context, this property offers flexibility in organizing and categorizing your JPEG files.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Manage JPEG file comments with this property, allowing you to add or retrieve descriptive annotations associated with the image. Whether it's tagging images with metadata or appending additional context, this property offers flexibility in organizing and categorizing your JPEG files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Gets Exif instance.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Manage EXIF data with this property, allowing you to add or retrieve metadata associated with the image. Whether it's extracting information about the camera settings or modifying existing metadata, this property offers flexibility in managing the EXIF data container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Gets Exif data;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//The output looks like this:
//The general EXIF data
//------------------------------------------
//The EXIF version: [B@163e4e87
//The camera serial number: 7100536
//The color space: SRgb
//The brightness:
//The contrast: Normal
//The gamma:
//The sharpness: 0
//The aperture: 4.64(4643856 / 1000000)
//The exposure mode: Manual
//The exposure bias: 0.67(4 / 6)
//The exposure time: 0.01(1 / 160)
//The focal length: 145.00(1450 / 10)
//The focal plane resolution unit: Cm
//The lens model: 70.0 - 200.0 mm f/ 4.0
//The shutter speed: 7.32(7321928 / 1000000)
//The JPEG EXIF data
//------------------------------------------
//The camera manufacturer: NIKON CORPORATION
//The camera model: NIKON D5
//The photometric interpretation: 0
//The artist:
//The copyright:
//The image description:
//The orientation: TopLeft
//The software: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Sets Exif data;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif data; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Retrieve the height of the image effortlessly with this property. It provides quick access to the vertical dimension of the image, allowing you to efficiently determine its size and aspect ratio without the need for complex calculations or additional methods.

**Returns:**
int - The image height in pixels.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


This property grants you access to the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch. By setting or retrieving this value, you can precisely control the resolution of the image, ensuring it meets your specific requirements for quality and clarity.

**Returns:**
double - The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 300.0
// The vertical resolution, in pixels per inch: 300.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


This property grants you access to the horizontal resolution of the [RasterImage](../../com.aspose.imaging/rasterimage), measured in pixels per inch. By setting or retrieving this value, you can precisely control the resolution of the image, ensuring it meets your specific requirements for quality and clarity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the `setResolution` method for updating both resolution values in single call. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


This property allows you to access or modify the JFIF (JPEG File Interchange Format) data associated with the JPEG image. JFIF is a standard format for exchanging JPEG-compressed images between computers and other devices. By getting or setting this property, you can interact with the JFIF data, which may include information such as the image's resolution, aspect ratio, and thumbnail.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


This property allows you to access or modify the JFIF (JPEG File Interchange Format) data associated with the JPEG image. JFIF is a standard format for exchanging JPEG-compressed images between computers and other devices. By getting or setting this property, you can interact with the JFIF data, which may include information such as the image's resolution, aspect ratio, and thumbnail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


This property retrieves the raw data format of the image, which indicates how the image data is structured and encoded. Understanding the raw data format is essential for processing or manipulating the image data effectively. It provides insights into the underlying representation of the image, such as whether it's compressed, encoded in a specific color space, or stored in a particular file format. Accessing this property allows you to gain valuable information about the image's data structure, enabling you to perform various operations or optimizations tailored to its specific format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


This property manages the vertical resolution, expressed in pixels per inch, for the associated [RasterImage](../../com.aspose.imaging/rasterimage). Adjusting this resolution impacts the size and quality of the image when printed or displayed at a fixed physical size. By setting this property, you control how densely the image's pixels are packed vertically, affecting its overall sharpness and clarity.

**Returns:**
double - The vertical resolution.

Note by default this value is always 72 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 300.0
// The vertical resolution, in pixels per inch: 300.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


This property manages the vertical resolution, expressed in pixels per inch, for the associated [RasterImage](../../com.aspose.imaging/rasterimage). Adjusting this resolution impacts the size and quality of the image when printed or displayed at a fixed physical size. By setting this property, you control how densely the image's pixels are packed vertically, affecting its overall sharpness and clarity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 72 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


This property retrieves the width of the image, expressed in pixels. It provides essential information about the image's dimensions, enabling accurate rendering, manipulation, or display of the image data.

**Returns:**
int - The image width in pixels.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


The RGB color profile for CMYK and YCCK JPEG images ensures accurate color conversion and representation. It must be paired with the CMYKColorProfile to maintain consistency and fidelity in color rendering. This pairing is essential for applications that require precise color management and reproduction of images, ensuring that the RGB data is properly interpreted and displayed.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


The RGB color profile for CMYK and YCCK JPEG images ensures accurate color conversion and representation. It must be paired with the CMYKColorProfile to maintain consistency and fidelity in color rendering. This pairing is essential for applications that require precise color management and reproduction of images, ensuring that the RGB data is properly interpreted and displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
The following example loads PNG and saves it to CMYK JPEG using custom ICC profile. Then loads CMYK JPEG and saves it back to PNG. The color conversion from RGB to CMYK and from CMYK to RGB is performed using custom ICC profiles.
``` java
String dir = "c:\\temp\\";

// Load PNG and save it to CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Use custom ICC profiles
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Load CMYK JPEG and save it to PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Use custom ICC profiles
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


The CMYK color profile associated with CMYK and YCCK JPEG images ensures precise color conversion and fidelity. It works in conjunction with the RGBColorProfile to guarantee accurate color representation across various devices and applications. This pairing is crucial for maintaining consistency in color rendering and achieving optimal image quality.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


The CMYK color profile associated with CMYK and YCCK JPEG images ensures precise color conversion and fidelity. It works in conjunction with the RGBColorProfile to guarantee accurate color representation across various devices and applications. This pairing is crucial for maintaining consistency in color rendering and achieving optimal image quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
The following example loads PNG and saves it to CMYK JPEG using custom ICC profile. Then loads CMYK JPEG and saves it back to PNG. The color conversion from RGB to CMYK and from CMYK to RGB is performed using custom ICC profiles.
``` java
String dir = "c:\\temp\\";

// Load PNG and save it to CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Use custom ICC profiles
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Load CMYK JPEG and save it to PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Use custom ICC profiles
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


The RGBColorProfile is essential for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. When paired with the CMYKColorProfile, it ensures that the colors are rendered correctly and maintains consistency across different devices and applications. This combination is crucial for preserving the intended color representation and achieving high-quality image output.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


The RGBColorProfile is essential for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. When paired with the CMYKColorProfile, it ensures that the colors are rendered correctly and maintains consistency across different devices and applications. This combination is crucial for preserving the intended color representation and achieving high-quality image output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


The CMYK color profile is vital for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. It works in tandem with the RGBColorProfile to ensure correct color representation, maintaining consistency and quality across different devices and software. This synchronization is crucial for achieving accurate and reliable color rendering in the final saved images.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


The CMYK color profile is vital for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. It works in tandem with the RGBColorProfile to ensure correct color representation, maintaining consistency and quality across different devices and software. This synchronization is crucial for achieving accurate and reliable color rendering in the final saved images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Retrieves or modifies the flag denoting whether the embedded color profile is disregarded. By setting this flag, users can specify whether the default color profile should be used instead of the embedded one. This option ensures greater control over color management, facilitating adjustments for consistency and compatibility across various platforms and applications.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Retrieves or modifies the flag denoting whether the embedded color profile is disregarded. By setting this flag, users can specify whether the default color profile should be used instead of the embedded one. This option ensures greater control over color management, facilitating adjustments for consistency and compatibility across various platforms and applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the original image options of this [Image](../../com.aspose.imaging/image) instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Removes this image instance metadata by setting this `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) and `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) values to `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establishes the resolution for the specified [RasterImage](../../com.aspose.imaging/rasterimage), ensuring accurate scaling and printing capabilities. This method empowers users to tailor the image resolution to suit their specific requirements, whether for digital display or physical reproduction. By setting the resolution, users can optimize image quality and ensure compatibility with various output devices and mediums, enhancing the overall visual experience and usability of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the `RasterImage`. |
| dpiY | double | The vertical resolution, in dots per inch, of the `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// The output may look like this:
// The horizontal resolution, in pixels per inch: 300.0
// The vertical resolution, in pixels per inch: 300.0
// Set resolution values to 96 dpi
// The horizontal resolution, in pixels per inch: 96.0
// The vertical resolution, in pixels per inch: 96.0
```

