---
title: BmpOptions
second_title: Aspose.Imaging for Java API Reference
description: The bmp file format creation options.
type: docs
weight: 11
url: /java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

The bmp file format creation options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Initializes a new instance of the `BmpOptions` class. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Initializes a new instance of the `BmpOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets or sets the image bits per pixel count. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Gets or sets the image bits per pixel count. |
| [getCompression()](#getCompression--) | Gets the compression type. |
| [setCompression(long value)](#setCompression-long-) | Sets the compression type. |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. In fact, only one page will be rasterized because BMP is not a multi-page format.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Initializes a new instance of the `BmpOptions` class.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Initializes a new instance of the `BmpOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | The BMP options. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets or sets the image bits per pixel count.

**Returns:**
int - The image bits per pixel count.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Gets or sets the image bits per pixel count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The image bits per pixel count. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Create BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Use 8 bits per pixel to reduce the size of the output image.
    saveOptions.setBitsPerPixel(8);

    // Set the closest 8-bit color palette which covers the maximal number of image pixels, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Save without compression.
    // You can also use RLE-8 compression to reduce the size of the output image.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Set the horizontal and vertical resolution to 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Gets the compression type. The default compression type is [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), that allows saving a [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) with transparency.

Value: The compression type.

**Returns:**
long - the compression type.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Sets the compression type. The default compression type is [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), that allows saving a [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) with transparency.

Value: The compression type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | the compression type. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Create BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Use 8 bits per pixel to reduce the size of the output image.
    saveOptions.setBitsPerPixel(8);

    // Set the closest 8-bit color palette which covers the maximal number of image pixels, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Save without compression.
    // You can also use RLE-8 compression to reduce the size of the output image.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Set the horizontal and vertical resolution to 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

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


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

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

