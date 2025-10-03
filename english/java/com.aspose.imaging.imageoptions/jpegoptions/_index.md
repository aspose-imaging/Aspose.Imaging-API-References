---
title: JpegOptions
second_title: Aspose.Imaging for Java API Reference
description: Create high-quality JPEG images effortlessly with our API offering adjustable levels of compression to optimize storage size without compromising image quality.
type: docs
weight: 26
url: /java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Create high-quality JPEG images effortlessly with our API, offering adjustable levels of compression to optimize storage size without compromising image quality. Benefit from support for various compression types, near lossless coding, RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP containers, ensuring versatile and customizable options for your image creation needs.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initializes a new instance of the `JpegOptions` class. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Initializes a new instance of the `JpegOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Gets the default memory allocation limit. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Sets the default memory allocation limit. |
| [getJfif()](#getJfif--) | Gets the jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Sets the jfif. |
| [getComment()](#getComment--) | Gets the jpeg file comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the jpeg file comment. |
| [getExifData()](#getExifData--) | Gets Exif data container. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Sets Exif data. |
| [getJpegExifData()](#getJpegExifData--) | Get Exif data container. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Get or set exif data container |
| [getCompressionType()](#getCompressionType--) | Gets the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Sets the compression type. |
| [getColorType()](#getColorType--) | Gets the color type for jpeg image. |
| [setColorType(int value)](#setColorType-int-) | Sets the color type for jpeg image. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Gets bits per channel for lossless jpeg image. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Sets bits per channel for lossless jpeg image. |
| [getQuality()](#getQuality--) | Gets image quality. |
| [setQuality(int value)](#setQuality-int-) | Sets image quality. |
| [getScaledQuality()](#getScaledQuality--) | The scaled quality. |
| [getRdOptSettings()](#getRdOptSettings--) | Gets the RD optimizer settings. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Sets the RD optimizer settings. |
| [getRgbColorProfile()](#getRgbColorProfile--) | The destination RGB color profile for CMYK jpeg images. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | The destination RGB color profile for CMYK jpeg images. |
| [getCmykColorProfile()](#getCmykColorProfile--) | The destination CMYK color profile for CMYK jpeg images. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | The destination CMYK color profile for CMYK jpeg images. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Gets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Gets the JPEG-LS interleave mode. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Sets the JPEG-LS interleave mode. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Gets the JPEG-LS preset parameters. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Sets the JPEG-LS preset parameters. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Gets the horizontal subsamplings for each component. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Sets the horizontal subsamplings for each component. |
| [getVerticalSampling()](#getVerticalSampling--) | Gets the vertical subsamplings for each component. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Sets the vertical subsamplings for each component. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Gets the sample rounding mode to fit an 8-bit value to an n-bit value. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Sets the sample rounding mode to fit an 8-bit value to an n-bit value. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Gets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present. |
| [getResolutionUnit()](#getResolutionUnit--) | Gets the resolution unit. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Sets the resolution unit. |

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


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. In fact, only one page will be rasterized because JPEG is not a multi-page format.
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

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initializes a new instance of the `JpegOptions` class.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initializes a new instance of the `JpegOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | The JPEG options. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Gets the default memory allocation limit.

**Returns:**
int - The default memory allocation limit.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Sets the default memory allocation limit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The default memory allocation limit. |

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
public ExifData getExifData()
```


Gets Exif data container.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Sets Exif data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif data. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Get Exif data container.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Get or set exif data container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Gets the compression type.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Sets the compression type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.setBitsPerChannel((byte) 8);

// Set the progressive type of compression.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Set the image quality. It is a value between 1 and 100.
createOptions.setQuality(100);

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fill the image with a grayscale gradient
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Save to a file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets the color type for jpeg image.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.setBitsPerChannel((byte) 8);

// Set the progressive type of compression.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Set the image quality. It is a value between 1 and 100.
createOptions.setQuality(100);

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fill the image with a grayscale gradient
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Save to a file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Sets the color type for jpeg image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Load a BMP image from a file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Do some image processing.

    // Use additional options to specify the desired image parameters.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // The number of bits per channel is 8.
    // When a palette is used, the color index is stored in the image data instead of the color itself.
    saveOptions.setBitsPerChannel((byte) 8);

    // Set the progressive type of compression.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Set the image quality. It is a value between 1 and 100.
    saveOptions.setQuality(100);

    // Set the horizontal/vertical resolution to 96 dots per inch.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // If the source image is colored, it will be converted to grayscaled.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Use a palette to reduce the output size.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Gets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Sets bits per channel for lossless jpeg image. Now we support from 2 to 8 bits per channel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.setBitsPerChannel((byte) 8);

// Set the progressive type of compression.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Set the image quality. It is a value between 1 and 100.
createOptions.setQuality(100);

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fill the image with a grayscale gradient
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Save to a file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Gets image quality.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Sets image quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.setBitsPerChannel((byte) 8);

// Set the progressive type of compression.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Set the image quality. It is a value between 1 and 100.
createOptions.setQuality(100);

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fill the image with a grayscale gradient
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Save to a file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


The scaled quality.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Gets the RD optimizer settings.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Sets the RD optimizer settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | The RD optimizer settings. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


The destination RGB color profile for CMYK jpeg images. Use for saving images. Must be in pair with CMYKColorProfile for correct color conversion.

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


The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


The destination CMYK color profile for CMYK jpeg images. Use for saving images. Must be in pair with RGBColorProfile for correct color conversion.

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

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Gets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Sets the JPEG-LS difference bound for near-lossless coding (NEAR parameter from the JPEG-LS specification).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Gets the JPEG-LS interleave mode.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Sets the JPEG-LS interleave mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Gets the JPEG-LS preset parameters.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Sets the JPEG-LS preset parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Gets the horizontal subsamplings for each component.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Sets the horizontal subsamplings for each component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Gets the vertical subsamplings for each component.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Sets the vertical subsamplings for each component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Gets the sample rounding mode to fit an 8-bit value to an n-bit value. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Sets the sample rounding mode to fit an 8-bit value to an n-bit value. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Gets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Sets a value indicating whether red, green and blue components should be mixed with a background color, if alpha channel is present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Gets the resolution unit.

**Returns:**
byte - the resolution unit.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.setBitsPerChannel((byte) 8);

// Set the progressive type of compression.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Set the image quality. It is a value between 1 and 100.
createOptions.setQuality(100);

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Fill the image with a grayscale gradient
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Save to a file.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Sets the resolution unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the resolution unit. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Load a BMP image from a file.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Do some image processing.

    // Use additional options to specify the desired image parameters.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // The number of bits per channel is 8.
    // When a palette is used, the color index is stored in the image data instead of the color itself.
    saveOptions.setBitsPerChannel((byte) 8);

    // Set the progressive type of compression.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Set the image quality. It is a value between 1 and 100.
    saveOptions.setQuality(100);

    // Set the horizontal/vertical resolution to 96 dots per inch.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // If the source image is colored, it will be converted to grayscaled.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Use a palette to reduce the output size.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

