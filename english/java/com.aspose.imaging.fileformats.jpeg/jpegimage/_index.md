---
title: JpegImage
second_title: Aspose.Imaging for Java API Reference
description: A jpeg image.
type: docs
weight: 14
url: /java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class JpegImage extends RasterCachedImage
```

A jpeg image.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | Initializes a new instance of the `JpegImage` class. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Initializes a new instance of the `JpegImage` class. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Initializes a new instance of the `JpegImage` class. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Initializes a new instance of the `JpegImage` class. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Initializes a new instance of the `JpegImage` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getJpegOptions()](#getJpegOptions--) | Gets the JPEG options used to create or load this `JpegImage` instance. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getComment()](#getComment--) | Gets the jpeg file comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the jpeg file comment. |
| [getExifData()](#getExifData--) | Get or set exif data container |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.imaging.exif.JpegExifData-) | Get or set exif data container |
| [getXmpData()](#getXmpData--) | Gets the XMP metadata. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Sets the XMP metadata. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Gets the horizontal resolution, in pixels per inch, of this `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Sets the horizontal resolution, in pixels per inch, of this `RasterImage`. |
| [getJfif()](#getJfif--) | Gets the jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Sets the jfif. |
| [getRawDataFormat()](#getRawDataFormat--) | Gets the raw data format. |
| [getVerticalResolution()](#getVerticalResolution--) | Gets the vertical resolution, in pixels per inch, of this `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Sets the vertical resolution, in pixels per inch, of this `RasterImage`. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getRgbColorProfile()](#getRgbColorProfile--) | The RGB color profile for CMYK and YCCK jpeg images. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | The RGB color profile for CMYK and YCCK jpeg images. |
| [getCmykColorProfile()](#getCmykColorProfile--) | The CMYK color profile for CMYK and YCCK jpeg images. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | The CMYK color profile for CMYK and YCCK jpeg images. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | The RGB color profile for CMYK and YCCK jpeg images, used for image saving process. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | The RGB color profile for CMYK and YCCK jpeg images, used for image saving process. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | The CMYK color profile for CMYK and YCCK jpeg images, used for image saving process. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | The CMYK color profile for CMYK and YCCK jpeg images, used for image saving process. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Gets a value indicating whether embedded color profile is ignored. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Sets a value indicating whether embedded color profile is ignored. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Sets the resolution for this `RasterImage`. |
| [autoRotate()](#autoRotate--) | Perform automatic rotate of image depending on orientation data provided by Exif. |

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


Initializes a new instance of the `JpegImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to load image from and initialize pixel and palette data with. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Initializes a new instance of the `JpegImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load image from and initialize pixel and palette data with. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Initializes a new instance of the `JpegImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Initializes a new instance of the `JpegImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width. |
| height | int | The image height. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Initializes a new instance of the `JpegImage` class.

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


Gets a value of file format

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Gets the JPEG options used to create or load this `JpegImage` instance.

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


Gets the image bits per pixel count.

**Returns:**
int - The image bits per pixel count.
### getComment() {#getComment--}
```
public String getComment()
```


Gets the jpeg file comment.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Sets the jpeg file comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Get or set exif data container

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata)

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Get or set exif data container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets the XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - The XMP metadata.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Sets the XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | The XMP metadata. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

**Returns:**
int - The image height.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Gets the horizontal resolution, in pixels per inch, of this `RasterImage`.

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


Sets the horizontal resolution, in pixels per inch, of this `RasterImage`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The horizontal resolution.

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Gets the jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Sets the jfif.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Gets the raw data format.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Gets the vertical resolution, in pixels per inch, of this `RasterImage`.

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


Sets the vertical resolution, in pixels per inch, of this `RasterImage`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The vertical resolution.

Note by default this value is always 72 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

**Returns:**
int - The image width.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


The RGB color profile for CMYK and YCCK jpeg images. Must be in pair with CMYKColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


The RGB color profile for CMYK and YCCK jpeg images. Must be in pair with CMYKColorProfile for correct color conversion.

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


The CMYK color profile for CMYK and YCCK jpeg images. Must be in pair with RGBColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


The CMYK color profile for CMYK and YCCK jpeg images. Must be in pair with RGBColorProfile for correct color conversion.

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


The RGB color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with CMYKColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


The RGB color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with CMYKColorProfile for correct color conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


The CMYK color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with RGBColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


The CMYK color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with RGBColorProfile for correct color conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Gets a value indicating whether embedded color profile is ignored. If embedded color profile is ignored, default color profile is used.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Sets a value indicating whether embedded color profile is ignored. If embedded color profile is ignored, default color profile is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Sets the resolution for this `RasterImage`.

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

### autoRotate() {#autoRotate--}
```
public void autoRotate()
```


Perform automatic rotate of image depending on orientation data provided by Exif.

