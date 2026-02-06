---
title: DjvuImage
second_title: Aspose.Imaging for Java API Reference
description: DjVu document class supports graphics file format and facilitates seamless management of scanned documents and books integrating text drawings images and photos into a single format.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

DjVu document class supports graphics file format and facilitates seamless management of scanned documents and books, integrating text, drawings, images, and photos into a single format. Supporting multipage operations, you can efficiently access unique document identifiers, count pages, set active pages, and retrieve specific document pages. With features for resizing, rotating, dithering, cropping, grayscale transformation, gamma corrections, adjustments, and filters application, this class empowers precise manipulation and enhancement of DjVu images to meet diverse application needs with ease and precision.
## Constructors

| Constructor | Description |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Start working with DjVu images by initializing a new instance of the [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class using a Stream parameter. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Start working with DjVu images seamlessly with this constructor, which initializes a new [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class instance using a Stream and LoadOptions parameters. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Start working with DjVu images seamlessly with this constructor, which initializes a new [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class instance using a Stream and LoadOptions parameters. |
## Fields

| Field | Description |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Occurs when a property value changes. |
## Methods

| Method | Description |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Load your DjVu document with this method. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Loads the document. |
| [getIdentifier()](#getIdentifier--) | Gets the unique identifier for the document |
| [getPageCount()](#getPageCount--) | Retrieve the total number of pages in your DjVu image collection with this property. |
| [getPages()](#getPages--) | Access the individual pages of your DjVu image collection with this property. |
| [getDjvuPages()](#getDjvuPages--) | Quickly retrieve all the pages contained within your DjVu document using this property. |
| [getActivePage()](#getActivePage--) | Navigate through your DjVu document by accessing or setting the currently active page using this property. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Navigate through your DjVu document by accessing or setting the currently active page using this property. |
| [getFirstPage()](#getFirstPage--) | Access the first page of your DjVu document with this property. |
| [getLastPage()](#getLastPage--) | Retrieve the last page of your DjVu document using this property. |
| [getNextPage()](#getNextPage--) | Navigate through your DjVu document by accessing the next page with this convenient property. |
| [getPreviousPage()](#getPreviousPage--) | Quickly move backward in your DjVu document viewing or processing tasks by accessing the previous page with this convenient property. |
| [getFileFormat()](#getFileFormat--) | Obtain the file format information associated with your DjVu image file. |
| [hasAlpha()](#hasAlpha--) | Quickly determine whether your DjVu image file contains an alpha channel. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotate the image around its center with the Rotate method of the RasterCachedMultipageImage class. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resize the image using the \`Resize\` method, providing a simple and effective way to adjust the dimensions of your images according to your requirements. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | The \`ResizeWidthProportionally\` method offers a convenient solution to adjust the width of your image while maintaining its aspect ratio. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | The \`ResizeHeightProportionally\` method allows you to adjust the height of your image while preserving its aspect ratio. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | The \`RotateFlip\` method offers versatile manipulation options for your image, allowing you to rotate, flip, or perform both operations on the active frame independently. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | The "Dither" function applies a dithering effect to your image, enhancing its visual quality by reducing banding and improving color transitions. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | "Crop" trims your image to focus on specific details or remove unwanted elements, enhancing its composition and visual impact. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop with shifts allows you to precisely adjust the position and dimensions of the cropped area within an image. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarization with a predefined threshold simplifies complex images into binary representations, where pixels are categorized as either black or white based on their intensity compared to a specified threshold value. |
| [binarizeOtsu()](#binarizeOtsu--) | Binarization using Otsu thresholding is a technique that automatically calculates an optimal threshold value based on the image's histogram. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarization using Bradley's adaptive thresholding algorithm with integral image thresholding is a method that calculates a local threshold for each pixel based on a local neighborhood. |
| [grayscale()](#grayscale--) | Grayscale transformation converts an image to a black-and-white representation, where each pixel's intensity is represented by a single value ranging from black to white. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma correction, specifically for the red, green, and blue channels, involves adjusting the brightness of each color component separately. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma correction is applied to an image with customizable parameters for the red, green, and blue channels, allowing precise adjustment of color balance and brightness. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Adjust the `brightness` of an image using a specified parameter, providing control over luminance levels for optimal visual clarity. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Enhance [Image](../../com.aspose.imaging/image) contrast to improve visual clarity and highlight details with this method, which adjusts the difference in brightness between light and dark areas. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Apply filters to a specified rectangular area within the image to enhance or modify its appearance. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resize the image to the specified width and height while applying additional settings as needed. |
| [cacheData()](#cacheData--) | Cache the data privately to optimize performance and reduce the need for repeated data retrieval from external sources. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Save each page as an individual PNG image.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generate a file name based on the page number.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Start working with DjVu images by initializing a new instance of the [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class using a Stream parameter. Perfect for developers who want seamless integration of DjVu image processing into their projects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Start working with DjVu images seamlessly with this constructor, which initializes a new [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class instance using a Stream and LoadOptions parameters. Perfect for developers who want precise control over DjVu image loading options while maintaining simplicity and efficiency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load from. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Start working with DjVu images seamlessly with this constructor, which initializes a new [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) class instance using a Stream and LoadOptions parameters. Perfect for developers who want precise control over DjVu image loading options while maintaining simplicity and efficiency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to load from. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Occurs when a property value changes.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Load your DjVu document with this method. Streamline your process by quickly accessing and importing your DjVu files into your application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Loads the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Gets the unique identifier for the document

**Returns:**
int - The identifier.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total number of pages in your DjVu image collection with this property. Ideal for quickly assessing the extent of your document or book stored in DjVu format. Improve your workflow efficiency with accurate page count information.

**Returns:**
int - The page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Access the individual pages of your DjVu image collection with this property. Simplify navigation and manipulation of your document or book stored in DjVu format by accessing each page directly. Improve your workflow efficiency with easy page retrieval.

**Returns:**
com.aspose.imaging.Image[] - The pages.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Save each page as an individual PNG image.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generate a file name based on the page number.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Quickly retrieve all the pages contained within your DjVu document using this property. Simplify your document processing workflow by easily accessing and managing individual pages within your DjVu files. Improve efficiency and streamline your tasks with convenient page retrieval.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - The pages.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Navigate through your DjVu document by accessing or setting the currently active page using this property. Seamlessly switch between pages to focus on specific content and enhance your document viewing experience.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//The output may look like this:
//The total number of pages: 2
//The active page number:    1
//The first page number:     1
//The last page number:      2
//--------------------------------------------------
//Page number:     1
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
//--------------------------------------------------
//Page number:     2
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Navigate through your DjVu document by accessing or setting the currently active page using this property. Seamlessly switch between pages to focus on specific content and enhance your document viewing experience.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | The active page. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Access the first page of your DjVu document with this property. Quickly retrieve the initial page to begin viewing or processing your document efficiently.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//The output may look like this:
//The total number of pages: 2
//The active page number:    1
//The first page number:     1
//The last page number:      2
//--------------------------------------------------
//Page number:     1
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
//--------------------------------------------------
//Page number:     2
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Retrieve the last page of your DjVu document using this property. Quickly access the final page for viewing or processing purposes with ease.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//The output may look like this:
//The total number of pages: 2
//The active page number:    1
//The first page number:     1
//The last page number:      2
//--------------------------------------------------
//Page number:     1
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
//--------------------------------------------------
//Page number:     2
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Navigate through your DjVu document by accessing the next page with this convenient property. Quickly move forward in your document viewing or processing tasks.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Quickly move backward in your DjVu document viewing or processing tasks by accessing the previous page with this convenient property. Efficiently navigate through your document with ease.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtain the file format information associated with your DjVu image file. Quickly determine the format of your file for seamless integration into your workflow.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Quickly determine whether your DjVu image file contains an alpha channel. Simplify your workflow by checking for the presence of transparency information in your images.

**Returns:**
boolean - The Has alpha channel.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotate the image around its center with the Rotate method of the RasterCachedMultipageImage class. This convenient feature allows you to easily adjust the orientation of images while maintaining their center position, enhancing your image manipulation capabilities.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color of the background. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Resize the image using the \`Resize\` method, providing a simple and effective way to adjust the dimensions of your images according to your requirements. This versatile functionality empowers you to easily scale images to your desired size, enhancing their usability across various platforms and applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


The \`ResizeWidthProportionally\` method offers a convenient solution to adjust the width of your image while maintaining its aspect ratio. By proportionally resizing the width, you can ensure that your images remain visually appealing and consistent across different devices and screen sizes, enhancing their versatility and usability in various contexts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| resizeType | int | Type of the resize. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
This example loads a DJVU image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


The \`ResizeHeightProportionally\` method allows you to adjust the height of your image while preserving its aspect ratio. This ensures that your image maintains its proportions, preventing distortion and preserving its visual integrity. Whether you're optimizing images for web pages, mobile apps, or print media, this method ensures that your images look their best across different platforms and devices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newHeight | int | The new height. |
| resizeType | int | Type of the resize. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
This example loads a DJVU image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Nearest Neighbour resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale down by 2 times using Nearest Neighbour resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale up by 2 times using Bilinear resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Scale down by 2 times using Bilinear resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Save to PNG with the default options.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


The \`RotateFlip\` method offers versatile manipulation options for your image, allowing you to rotate, flip, or perform both operations on the active frame independently. Whether you're editing photos, creating graphics, or enhancing digital art, this method provides precise control over the orientation and composition of your images, ensuring they meet your creative vision with ease and efficiency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | The rotate flip type. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotate, flip and save to the output file.
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


The "Dither" function applies a dithering effect to your image, enhancing its visual quality by reducing banding and improving color transitions. Whether you're working on digital art, photography, or graphic design projects, this feature adds a professional touch to your images, making them appear smoother and more refined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | The dithering method. |
| bitsCount | int | The final bits count for dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The custom palette for dithering. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


"Crop" trims your image to focus on specific details or remove unwanted elements, enhancing its composition and visual impact. Whether you're adjusting photos for social media, creating website banners, or designing print materials, this tool helps you refine your images with precision and clarity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |


**Example: The following example crops a DJVU image.**
The following example crops a DJVU image. The cropping area is be specified via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Save the cropped image to PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Crop with shifts allows you to precisely adjust the position and dimensions of the cropped area within an image. This feature is invaluable for refining compositions, aligning elements, and emphasizing focal points in your visuals. By incorporating shifts into the cropping process, you can achieve pixel-perfect precision and fine-tune the framing of your images with ease.

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


Binarization with a predefined threshold simplifies complex images into binary representations, where pixels are categorized as either black or white based on their intensity compared to a specified threshold value. This technique is commonly used in image processing to enhance clarity, simplify analysis, and prepare images for further processing steps such as optical character recognition (OCR). By applying a fixed threshold, you can quickly transform grayscale images into binary form, making them easier to interpret and extract meaningful information from.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
The following example binarizes a DJVU image with the predefined threshold. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarization using Otsu thresholding is a technique that automatically calculates an optimal threshold value based on the image's histogram. It separates the image into foreground and background by minimizing the intra-class variance. Otsu's method is widely used for segmenting images into binary form, particularly when the distribution of pixel intensities is bimodal or multimodal. This approach is beneficial for tasks such as object detection, image segmentation, and feature extraction, where accurate delineation between foreground and background is crucial.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
The following example binarizes a DJVU image with Otsu thresholding. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarize the image with Otsu thresholding.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarization using Bradley's adaptive thresholding algorithm with integral image thresholding is a method that calculates a local threshold for each pixel based on a local neighborhood. It adapts to variations in illumination across the image, making it suitable for images with uneven lighting conditions. By computing the threshold using integral images, it efficiently handles large neighborhoods, making it applicable to real-time applications. This technique is commonly used in document processing, OCR (Optical Character Recognition), and image segmentation tasks where accurate binarization is essential for subsequent analysis.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | int | The size of s x s window of pixels centered around this pixel |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Grayscale transformation converts an image to a black-and-white representation, where each pixel's intensity is represented by a single value ranging from black to white. This process removes color information, resulting in a monochromatic image. Grayscale images are commonly used in applications where color is unnecessary or where simplicity is preferred, such as document scanning, printing, and certain types of image analysis.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
The following example transforms a colored DJVU image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gamma correction, specifically for the red, green, and blue channels, involves adjusting the brightness of each color component separately. By applying different gamma coefficients to the RGB channels, you can fine-tune the overall brightness and contrast of an image. This technique ensures accurate color representation and improves the visual quality of the image across different display devices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gamma | float | Gamma for red, green and blue channels coefficient |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Set gamma coefficient for red, green and blue channels.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma correction is applied to an image with customizable parameters for the red, green, and blue channels, allowing precise adjustment of color balance and brightness. This method enhances image quality by fine-tuning color representation, ensuring optimal rendering across different display devices. Adjusting gamma values for individual channels improves color balance and visual appeal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma for red channel coefficient |
| gammaGreen | float | Gamma for green channel coefficient |
| gammaBlue | float | Gamma for blue channel coefficient |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Set individual gamma coefficients for red, green and blue channels.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Adjust the `brightness` of an image using a specified parameter, providing control over luminance levels for optimal visual clarity. This method enhances or diminishes the overall brightness of the image, allowing for fine adjustments to achieve desired lighting effects. By modulating brightness, users can optimize image visibility and enhance detail reproduction for improved viewing experience.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | int | Brightness value. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Enhance [Image](../../com.aspose.imaging/image) contrast to improve visual clarity and highlight details with this method, which adjusts the difference in brightness between light and dark areas. By fine-tuning contrast levels, users can achieve more vivid and impactful images, enhancing overall image quality and maximizing detail visibility. This adjustment helps to bring out subtle nuances in color and texture, resulting in more dynamic and visually appealing images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contrast | float | Contrast value (in range [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Apply filters to a specified rectangular area within the image to enhance or modify its appearance. By targeting specific regions, this method allows for precise adjustments, such as blurring, sharpening, or applying artistic effects, to achieve desired visual outcomes. Fine-tuning filters on selected areas empowers users to customize image aesthetics, improve clarity, and create artistic effects tailored to their preferences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | The options. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a median filter with a rectangle size of 5 to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a bilateral smoothing filter with a kernel size of 5 to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a Gaussian blur filter with a radius of 5 and a sigma value of 4.0 to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a Gauss-Wiener filter with a radius of 5 and a smooth value of 4.0 to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a motion wiener filter with a length of 5, a smooth value of 4.0 and an angle of 90.0 degrees to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Apply a sharpen filter with a kernel size of 5 and a sigma value of 4.0 to the entire image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Resize the image to the specified width and height while applying additional settings as needed. This method enables users to adjust the dimensions of the image while maintaining desired attributes such as aspect ratio, image quality, and compression settings. By providing flexibility in resizing options, users can tailor the image to fit specific requirements and optimize its appearance for various applications and platforms.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | The resize settings. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// The adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// The small rectangular filter
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// The number of colors in the palette.
resizeSettings.setEntriesCount(256);

// The color quantization is not used
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// The euclidian method
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Scale down by 2 times using adaptive resampling.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Save to PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache the data privately to optimize performance and reduce the need for repeated data retrieval from external sources. This approach also helps conserve resources, particularly in scenarios where data access is frequent or resources are limited.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Load an image from a DJVU file.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // This call caches all the pages so that no additional data loading will be performed from the underlying data stream.
    image.cacheData();

    // Or you can cache the pages individually.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

