---
title: WebPImage
second_title: Aspose.Imaging for Java API Reference
description: A webp image.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

A webp image.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from stream. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from stream. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from file. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from file. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from rasterImage. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from rasterImage. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with empty image. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with empty image. |
## Methods

| Method | Description |
| --- | --- |
| [getOptions()](#getOptions--) | Gets the options. |
| [getPages()](#getPages--) |  |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [getDefaultPage()](#getDefaultPage--) | Gets the default page. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [hasAlpha()](#hasAlpha--) | Gets the Has alpha channel. |
| [getPageExportingAction()](#getPageExportingAction--) | Gets the page exporting action. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Sets the page exporting action. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Adds page to the image. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Adds a new Webp block. |
| [clearBlocks()](#clearBlocks--) | Clears all the Webp blocks. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Adds a new Webp block. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Removes the Webp block. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `!:RasterCachedMultipageImage.Rotate` image around the center. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Resizes the width proportionally. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Resizes the width proportionally. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the Active frame only. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Performs dithering on the current image. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Cropping the image. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop image with shifts. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarization of an image with predefined threshold |
| [binarizeOtsu()](#binarizeOtsu--) | Binarization of an image with Otsu thresholding |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [grayscale()](#grayscale--) | Transformation of an image to its grayscale representation |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-correction of an image. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-correction of an image. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjust of a `brightness` for image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) contrasting |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filters the specified rectangle. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Load a WebP image from a file.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Save to PNG
    // Note that only the active frame will be stored to PNG, since PNG is not a multi-page format.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream WebP image. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream WebP image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to file WebP Image |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to file WebP Image |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from rasterImage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class from rasterImage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with empty image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | The options. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Initializes a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with empty image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The image width |
| height | int | The image height. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | The options. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Gets the options.

Value: The options.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Gets the blocks.

Gets the Webp blocks.

Value: The blocks.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets the page count.

Value: The page count. ``

**Returns:**
int - the page count.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Gets the default page.

Value: The default page. ``

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - a value of file format
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets the Has alpha channel.

Value: The Has alpha channel. ``

**Returns:**
boolean - the Has alpha channel.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // If the active TIFF frame has alpha channel, then the entire TIFF image is considered to have alpha channel.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// The output may look like this:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Gets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

Value: The page exporting action.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

Value: The page exporting action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | the page exporting action. |

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Adds page to the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Adds a new Webp block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | The Webp block to add. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// The default frame plus 36 + 36 additional frames.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Create a WebP image of 100x100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // The first circle is red
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // The second circle is black
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Gradually increase the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Gradually increase the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Save to a WebP file
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Clears all the Webp blocks.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Adds a new Webp block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based element, at which `block` will be inserted. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | The Webp block to add. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Removes the Webp block.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | The block to remove.

--------------------

Note: do not forget to Dispose the `block` if you will not add it to some other WebPImage. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`!:RasterCachedMultipageImage.Rotate` image around the center.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotation angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with default options.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Resizes the width proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| resizeType | int | Type of the resize. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Resizes the width proportionally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| resizeType | int | Type of the resize. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rotates, flips, or rotates and flips the Active frame only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation flip type. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Performs dithering on the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The custom palette for dithering. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Cropping the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop image with shifts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | int | The left shift. |
| rightShift | int | The right shift. |
| topShift | int | The top shift. |
| bottomShift | int | The bottom shift. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarization of an image with predefined threshold

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarization of an image with Otsu thresholding

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | int | The size of s x s window of pixels centered around this pixel |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation of an image to its grayscale representation

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma-correction of an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-correction of an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma for red channel coefficient |
| gammaGreen | float | Gamma for green channel coefficient |
| gammaBlue | float | Gamma for blue channel coefficient |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Adjust of a `brightness` for image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filters the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | The options. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resizes the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |

