---
title: WebPImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate WebP raster images with our API using its modern features for both lossless and lossy compression ensuring optimal image quality with reduced file sizes.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipulate WebP raster images with our API, using its modern features for both lossless and lossy compression, ensuring optimal image quality with reduced file sizes. Seamlessly handle extended file formats, animations, and alpha channels, while easily updating dimensions, resizing proportionally, cropping, rotating, applying filters, adjusting image parameters, and converting to other image formats for versatile web image optimization.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided stream source. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a stream and specified load options, facilitating versatile handling of WebP image data. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Instantiate a fresh instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided file source. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a file and specified load options, facilitating flexible handling of WebP image data. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided rasterImage object. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a rasterImage object and specified load options, enabling flexible handling of image data. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with an empty image of specified width and height dimensions. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with an empty image and specified load options. |
## Methods

| Method | Description |
| --- | --- |
| [getOptions()](#getOptions--) | Retrieve or modify the options associated with the specified property, enabling fine-tuned customization of behavior and settings. |
| [getPages()](#getPages--) | Access the WebP blocks within the image, allowing detailed examination or manipulation of the underlying block structure. |
| [getPageCount()](#getPageCount--) | Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multipage content. |
| [getFileFormat()](#getFileFormat--) | Access the file format value associated with the image, providing information about the format in which the image is stored. |
| [hasAlpha()](#hasAlpha--) | Retrieve whether the image contains an alpha channel, indicating the presence of transparency information. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Append a new page to the image, expanding its content and accommodating additional visual elements. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Incorporate a new WebP block into the image, enriching its content and facilitating advanced image manipulation. |
| [clearBlocks()](#clearBlocks--) | Clear all existing WebP blocks from the image, facilitating a clean slate for subsequent modifications or additions. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Insert a new WebP block at the specified index within the image, enabling precise control over the block sequence. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Remove the specified WebP block from the image, facilitating efficient management of image data structure. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotate the image around its center by a specified angle, while proportionally resizing it and applying specified background color parameters. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resize the image, adjusting its dimensions while preserving the aspect ratio. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Proportionally adjust the width of the image while maintaining its aspect ratio. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Adjust the height of the image proportionally, while preserving its aspect ratio for consistent resizing. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Apply rotation, flipping, or both operations exclusively to the active frame within the image. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Perform dithering on the current image to reduce color banding and enhance visual quality. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crop the image using a specified rectangle region, removing unwanted portions while retaining the desired content. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop the image by applying left, right, top, and bottom shifts, effectively selecting a region of interest within the image. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Perform binarization on the image using a predefined threshold value, converting it into a binary image where pixels are classified as foreground or background based on their intensity relative to the threshold. |
| [binarizeOtsu()](#binarizeOtsu--) | Perform binarization on the image using Otsu's thresholding method, automatically determining the optimal threshold value based on the image's histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. |
| [grayscale()](#grayscale--) | Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Apply gamma correction to the image, adjusting pixel intensities to achieve desired brightness and color balance. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Perform gamma correction on the image using individual coefficients for the red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implement `brightness` adjustment for the image, allowing the modification of overall luminance levels. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Enhance the contrast of the [Image](../../com.aspose.imaging/image), amplifying the differences between light and dark areas. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resize the image according to specified settings, enabling precise control over dimensions, aspect ratio, and scaling behavior. |

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


Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided stream source. Utilize this constructor to seamlessly create WebP image objects directly from streams, enabling efficient handling and manipulation of WebP image data within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream WebP image. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a stream and specified load options, facilitating versatile handling of WebP image data. Incorporate this constructor to seamlessly initialize WebP image objects from streams while customizing loading parameters as needed within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream WebP image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Instantiate a fresh instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided file source. Utilize this constructor to seamlessly create WebP image objects directly from files, streamlining the process of loading and manipulating WebP image data within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to file WebP Image |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a file and specified load options, facilitating flexible handling of WebP image data. Utilize this constructor to seamlessly initialize WebP image objects from files while customizing loading parameters according to your application's requirements.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | The path to file WebP Image |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class, initialized from a provided rasterImage object. This constructor allows for seamless conversion of raster images to WebP format, enabling efficient handling and manipulation of image data within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class using a rasterImage object and specified load options, enabling flexible handling of image data. Utilize this constructor to seamlessly initialize WebP image objects from raster images while customizing loading parameters according to your application's requirements.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The raster image. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Instantiate a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with an empty image of specified width and height dimensions. This constructor allows for the creation of blank WebP images, providing a foundation for subsequent image manipulation and content generation within your application.

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


Create a new instance of the [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) class with an empty image and specified load options. This constructor allows for the initialization of WebP images with customizable loading parameters, providing flexibility in image creation and manipulation within your application.

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


Retrieve or modify the options associated with the specified property, enabling fine-tuned customization of behavior and settings. Utilize this property to seamlessly access and manipulate configurable parameters, facilitating versatile control and optimization within your application's functionality.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Access the WebP blocks within the image, allowing detailed examination or manipulation of the underlying block structure. Utilize this property to analyze or modify individual blocks within the WebP image data, facilitating advanced image processing techniques within your application.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multipage content. Incorporate this functionality to enhance user experience, enabling seamless access to comprehensive document structures.

**Returns:**
int - the page count.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Access the file format value associated with the image, providing information about the format in which the image is stored. Utilize this property to determine the file format of the image, facilitating compatibility checks and format-specific processing within your application.

**Returns:**
long - a value of file format
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Retrieve whether the image contains an alpha channel, indicating the presence of transparency information. Utilize this property to determine whether the image includes transparency, enabling appropriate handling and processing of alpha-related operations within your application.

**Returns:**
boolean - `true` if there is an alpha channel.

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

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Append a new page to the image, expanding its content and accommodating additional visual elements. Integrate this method to facilitate dynamic page management within your application, enabling seamless creation and augmentation of multipage documents or images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Incorporate a new WebP block into the image, enriching its content and facilitating advanced image manipulation. Integrate this method to dynamically enhance the structure and complexity of the WebP image data within your application, enabling precise control and optimization of image rendering.

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


Clear all existing WebP blocks from the image, facilitating a clean slate for subsequent modifications or additions. Utilize this method to effectively reset the block structure within the WebP image data, ensuring optimal management and organization of image content within your application.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Insert a new WebP block at the specified index within the image, enabling precise control over the block sequence. Integrate this method to seamlessly incorporate additional WebP blocks into the image data structure, facilitating advanced image processing and optimization within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based element, at which `block` will be inserted. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | The Webp block to add. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Remove the specified WebP block from the image, facilitating efficient management of image data structure. Utilize this method to streamline image processing workflows by eliminating unnecessary blocks or components within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | The block to remove.

--------------------

Note: do not forget to Dispose the `block` if you will not add it to some other WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotate the image around its center by a specified angle, while proportionally resizing it and applying specified background color parameters. Incorporate this method into your image processing workflow to achieve precise transformations with customizable background colors, ensuring optimal visual presentation within your application.

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


Resize the image, adjusting its dimensions while preserving the aspect ratio. Integrate this method into your image processing workflow to dynamically scale images to fit various display or storage requirements within your application.

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


Proportionally adjust the width of the image while maintaining its aspect ratio. Integrate this method into your image processing workflow to dynamically resize images with consistent proportions, ensuring optimal display or storage within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| resizeType | int | Type of the resize. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Adjust the height of the image proportionally, while preserving its aspect ratio for consistent resizing. Integrate this method into your image processing workflow to dynamically resize images with uniform proportions, ensuring optimal display or storage within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| resizeType | int | Type of the resize. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Apply rotation, flipping, or both operations exclusively to the active frame within the image. Integrate this method into your image processing workflow to achieve precise manipulation of individual frames, enhancing flexibility and control over frame transformations within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotation flip type. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Perform dithering on the current image to reduce color banding and enhance visual quality. Integrate this method into your image processing workflow to achieve smoother transitions between colors and improve the overall appearance of the image within your application.

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


Crop the image using a specified rectangle region, removing unwanted portions while retaining the desired content. Integrate this method into your image processing workflow to precisely extract and focus on specific areas of interest within the image, enhancing clarity and composition for various applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop the image by applying left, right, top, and bottom shifts, effectively selecting a region of interest within the image. Utilize this method to dynamically extract desired portions of the image while adjusting its composition and focus according to your application's requirements.

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


Perform binarization on the image using a predefined threshold value, converting it into a binary image where pixels are classified as foreground or background based on their intensity relative to the threshold. Integrate this method into your image processing workflow to facilitate segmentation and feature extraction tasks, enhancing the accuracy and efficiency of subsequent analysis within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of (byte)255 will be assigned to it, 0 otherwise. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Perform binarization on the image using Otsu's thresholding method, automatically determining the optimal threshold value based on the image's histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction, enhancing the accuracy and reliability of image analysis tasks within your application.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. This method dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | int | The size of s x s window of pixels centered around this pixel |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. This method dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Apply gamma correction to the image, adjusting pixel intensities to achieve desired brightness and color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Perform gamma correction on the image using individual coefficients for the red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. Integrate this method into your image processing pipeline to achieve precise control over color rendering and enhance visual fidelity within your application.

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


Implement `brightness` adjustment for the image, allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Enhance the contrast of the [Image](../../com.aspose.imaging/image), amplifying the differences between light and dark areas. Integrate this method into your image processing workflow to improve visual clarity and overall image quality within your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. Integrate this method into your image manipulation workflow to achieve targeted enhancements or transformations within your application.

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


Resize the image according to specified settings, enabling precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |

