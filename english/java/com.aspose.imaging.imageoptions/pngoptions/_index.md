---
title: PngOptions
second_title: Aspose.Imaging for Java API Reference
description: The png file format create options.
type: docs
weight: 35
url: /java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

The png file format create options.
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
| [getXmpData()](#getXmpData--) | Gets or sets the XMP metadata container. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Gets or sets the XMP metadata container. |
| [getColorType()](#getColorType--) | Gets or sets the type of the color. |
| [setColorType(int value)](#setColorType-int-) | Gets or sets the type of the color. |
| [getProgressive()](#getProgressive--) | Gets or sets a value indicating whether this `PngOptions` is progressive. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Gets or sets a value indicating whether this `PngOptions` is progressive. |
| [getFilterType()](#getFilterType--) | Gets or sets the filter type used during png file save process. |
| [setFilterType(int value)](#setFilterType-int-) | Gets or sets the filter type used during png file save process. |
| [getCompressionLevel()](#getCompressionLevel--) | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| [getBitDepth()](#getBitDepth--) | Gets the bit depth. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Sets the bit depth. |

## Example
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


## Example
The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.
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

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets or sets the XMP metadata container.

Value: The XMP data container.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper)
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Gets or sets the XMP metadata container.

Value: The XMP data container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets or sets the type of the color.

**Returns:**
int - The type of the color.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Gets or sets the type of the color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The type of the color. |


**Example:**
The following example shows how to compress a PNG image, using indexed color with best fit palette
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


**Example:**
The following example shows how to save an image to PNG format using various options.
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
public boolean getProgressive()
```


Gets or sets a value indicating whether this `PngOptions` is progressive.

**Returns:**
boolean - `true` if progressive; otherwise, `false`.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Gets or sets a value indicating whether this `PngOptions` is progressive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if progressive; otherwise, `false`. |


**Example:**
The following example shows how to compress a PNG image, using indexed color with best fit palette
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


**Example:**
This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.
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
public int getFilterType()
```


Gets or sets the filter type used during png file save process.

**Returns:**
int - the filter type used during png file save process.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Gets or sets the filter type used during png file save process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the filter type used during png file save process. |


**Example:**
The following example shows how different filter types affect the size of the output PNG image.
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
public int getCompressionLevel()
```


The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode.

**Returns:**
int - the compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode.
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |


**Example:**
The following example shows how to compress a PNG image, using indexed color with best fit palette
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


**Example:**
The following example shows how to save an image to PNG format using various options.
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
public byte getBitDepth()
```


Gets the bit depth.

**Returns:**
byte - The bit depth.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Sets the bit depth.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The bit depth. |


**Example:**
The following example shows how to save an image to PNG format using various options.
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

