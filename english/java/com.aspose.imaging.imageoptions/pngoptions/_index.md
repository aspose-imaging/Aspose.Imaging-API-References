---
title: PngOptions
second_title: Aspose.Imaging for Java API Reference
description: Create high-quality Portable Network Graphics PNG raster images effortlessly with our API offering customizable options for compression levels bits per pixel depths and alpha bits.
type: docs
weight: 37
url: /java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Create high-quality Portable Network Graphics (PNG) raster images effortlessly with our API, offering customizable options for compression levels, bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers, ensuring comprehensive image metadata management, and empowering you to tailor PNG images to your exact specifications with ease.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngOptions()](#PngOptions--) | Initializes a new instance of the `PngOptions` class. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Initializes a new instance of the `PngOptions` class. |
## Fields

| Field | Description |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | The default compression level. |
## Methods

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Gets the type of the color. |
| [setColorType(int value)](#setColorType-int-) | Sets the type of the color. |
| [getProgressive()](#getProgressive--) | Gets a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Sets a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive. |
| [getFilterType()](#getFilterType--) | Gets the filter type used during png file save process. |
| [setFilterType(int value)](#setFilterType-int-) | Sets the filter type used during png file save process. |
| [getCompressionLevel()](#getCompressionLevel--) | Gets the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Sets the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9. |
| [getBitDepth()](#getBitDepth--) | Gets the bit depth values in range of 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Sets the bit depth values in range of 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Export only first two pages. In fact, only one page will be rasterized because PNG is not a multi-page format.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Initializes a new instance of the `PngOptions` class.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Initializes a new instance of the `PngOptions` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | The PNG options. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


The default compression level.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Gets the type of the color.

Value: The type of the color.

**Returns:**
int - the type of the color.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Sets the type of the color.

Value: The type of the color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the type of the color. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Loads png image        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Use indexed color type
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Use maximal compression
    options.setCompressionLevel(9);
    // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// The output file size should be significantly reduced
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
// You can also load image of any supported format from a file or a stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the image with the blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Use progressive loading.
    saveOptions.setProgressive(true);

    // Set the horizontal and vertical resolution to 96 pixels per inch.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Each pixel is a (red, green, blue) triple followed by alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Set the maximum level of compression.
    saveOptions.setCompressionLevel(9);

    // This is the best compression, but the slowest execution time.
    // Adaptive filtering means that saving process will choose most sutable filter for each data row.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // The number of bits per channel.
    saveOptions.setBitDepth((byte) 8);

    // Save to a file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Gets a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive.

Value: `` if progressive; otherwise, ``.

**Returns:**
boolean - a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Sets a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive.

Value: `` if progressive; otherwise, ``.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether a [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is progressive. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Loads png image        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Use indexed color type
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Use maximal compression
    options.setCompressionLevel(9);
    // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// The output file size should be significantly reduced
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// The number of bits per color channel
createOptions.setBitDepth((byte) 8);

// Each pixel is a (red, green, blue) triple followed by the alpha component.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// The maximum level of compression.
createOptions.setCompressionLevel(9);

// Usage of filters allows to compress continuous tonal images more effectively.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Use progressive loading
createOptions.setProgressive(true);

// Create a PNG image with custom parameters.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the image with a semi-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Save to a file.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Gets the filter type used during png file save process.

**Returns:**
int - the filter type used during png file save process.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Sets the filter type used during png file save process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the filter type used during png file save process. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Helper class
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Here is the main example
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Set a filter type
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//The output may look like this:
//The filter type is None, the output image size is 116845 bytes.
//The filter type is Up, the output image size is 86360 bytes.
//The filter type is Sub, the output image size is 94907 bytes.
//The filter type is Paeth, the output image size is 86403 bytes.
//The filter type is Avg, the output image size is 89956 bytes.
//The filter type is Adaptive, the output image size is 97248 bytes.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Gets the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9. The higher the value - the more efficient the compression.

**Returns:**
int - the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9.
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Sets the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9. The higher the value - the more efficient the compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) compression level in the range of 0-9. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Loads png image        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Use indexed color type
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Use maximal compression
    options.setCompressionLevel(9);
    // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// The output file size should be significantly reduced
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
// You can also load image of any supported format from a file or a stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the image with the blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Use progressive loading.
    saveOptions.setProgressive(true);

    // Set the horizontal and vertical resolution to 96 pixels per inch.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Each pixel is a (red, green, blue) triple followed by alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Set the maximum level of compression.
    saveOptions.setCompressionLevel(9);

    // This is the best compression, but the slowest execution time.
    // Adaptive filtering means that saving process will choose most sutable filter for each data row.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // The number of bits per channel.
    saveOptions.setBitDepth((byte) 8);

    // Save to a file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Gets the bit depth values in range of 1, 2, 4, 8, 16.

Mind the next limits:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - the bit depth values in range of 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Sets the bit depth values in range of 1, 2, 4, 8, 16.

Mind the next limits:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | the bit depth values in range of 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
// You can also load image of any supported format from a file or a stream.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Fill the image with the blue-transparent gradient.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Use progressive loading.
    saveOptions.setProgressive(true);

    // Set the horizontal and vertical resolution to 96 pixels per inch.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Each pixel is a (red, green, blue) triple followed by alpha.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Set the maximum level of compression.
    saveOptions.setCompressionLevel(9);

    // This is the best compression, but the slowest execution time.
    // Adaptive filtering means that saving process will choose most sutable filter for each data row.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // The number of bits per channel.
    saveOptions.setBitDepth((byte) 8);

    // Save to a file.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

