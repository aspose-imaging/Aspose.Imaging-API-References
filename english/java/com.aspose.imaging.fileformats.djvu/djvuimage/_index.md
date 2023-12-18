---
title: DjvuImage
second_title: Aspose.Imaging for Java API Reference
description: DjvuDocument class
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

DjvuDocument class
## Constructors

| Constructor | Description |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Initializes a new instance of the `DjvuImage` class. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the `DjvuImage` class. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the `DjvuImage` class. |
## Fields

| Field | Description |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Occurs when a property value changes. |
## Methods

| Method | Description |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Loads the document. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Loads the document. |
| [getIdentifier()](#getIdentifier--) | Gets the unique identifier for the document |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [getPages()](#getPages--) | Gets the pages. |
| [getDjvuPages()](#getDjvuPages--) | Gets the pages for the document |
| [getActivePage()](#getActivePage--) | Gets or sets the currently active page |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Gets or sets the currently active page |
| [getFirstPage()](#getFirstPage--) | Gets the first page of the document |
| [getLastPage()](#getLastPage--) | Gets the last page of the document |
| [getNextPage()](#getNextPage--) | Gets the next page of the document |
| [getPreviousPage()](#getPreviousPage--) | Gets the previous page of the document |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [hasAlpha()](#hasAlpha--) | Gets the Has alpha channel. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `!:RasterCahcedMultipageImage.Rotate` image around the center. |
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
| [cacheData()](#cacheData--) | Caches the data private. |

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


Initializes a new instance of the `DjvuImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Initializes a new instance of the `DjvuImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to load from. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Initializes a new instance of the `DjvuImage` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |
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


Loads the document.

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


Gets the page count.

Value: The page count.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Gets the pages.

Value: The pages.

**Returns:**
com.aspose.imaging.Image[] - the pages.

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


Gets the pages for the document

Value: The pages.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - the pages for the document
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Gets or sets the currently active page

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The active page.

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


Gets or sets the currently active page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | The active page. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Gets the first page of the document

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


Gets the last page of the document

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


Gets the next page of the document

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Gets the previous page of the document

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets the Has alpha channel.

Value: The Has alpha channel.

**Returns:**
boolean - the Has alpha channel.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`!:RasterCahcedMultipageImage.Rotate` image around the center.

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


Resizes the image.

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


Resizes the width proportionally.

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


Resizes the width proportionally.

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


Rotates, flips, or rotates and flips the Active frame only.

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


Performs dithering on the current image.

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


Cropping the image.

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


Binarization of an image with Otsu thresholding


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


Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

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


Transformation of an image to its grayscale representation


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


Gamma-correction of an image.

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


Gamma-correction of an image.

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


Adjust of a `brightness` for image.

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


[Image](../../com.aspose.imaging/image) contrasting

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


Filters the specified rectangle.

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


Resizes the image.

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


Caches the data private.


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

