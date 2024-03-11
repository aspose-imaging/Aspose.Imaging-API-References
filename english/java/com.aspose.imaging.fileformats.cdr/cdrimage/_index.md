---
title: CdrImage
second_title: Aspose.Imaging for Java API Reference
description: The API for CorelDRAW CDR vector image format support is an essential toolkit for developers working with vector graphics.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

The API for CorelDRAW CDR vector image format support is an essential toolkit for developers working with vector graphics. This API enables the seamless processing of CDR files, allowing for the storage and manipulation of diverse elements such as text, lines, shapes, images, colors, and effects. With its comprehensive capabilities, developers can efficiently work with vector representations of image contents, ensuring precision and flexibility in creating and editing CorelDRAW vector graphics programmatically.
## Constructors

| Constructor | Description |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Start working with the [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) class effortlessly by initializing a new instance with a stream and loadOptions parameters. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Retrieve the default page of the image with ease using this user-friendly property. |
| [isCached()](#isCached--) | Effortlessly determine whether the object's data is currently cached, eliminating the need for data reading. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the bit depth of the image effortlessly with this user-friendly property. |
| [getWidth()](#getWidth--) | Retrieve the width of the image seamlessly with this intuitive property. |
| [getHeight()](#getHeight--) | Retrieve the height of the image effortlessly with this intuitive property. |
| [getPageCount()](#getPageCount--) | Effortlessly retrieve or update the total page count of the image with this intuitive property. |
| [getPages()](#getPages--) | Retrieve the pages of the image seamlessly with this intuitive property. |
| [getCdrDocument()](#getCdrDocument--) | Effortlessly retrieve or update the CDR document using this intuitive property. |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format of the image effortlessly with this intuitive property. |
| [getPageExportingAction()](#getPageExportingAction--) | Effortlessly retrieve the page exporting action associated with the image using this intuitive property. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Effortlessly modify the page exporting action associated with the image using this intuitive property. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Retrieve the default options effortlessly with this user-friendly method. |
| [cacheData()](#cacheData--) | Effortlessly cache the data to prevent additional loading from the underlying source with this user-friendly method. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Effortlessly resize the image to desired dimensions with this intuitive method. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Adjust the orientation of the image by rotating, flipping, or applying both operations with this versatile method. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Customize the color palette of the image with this intuitive method. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Load an image from a CDR file.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // This call caches only the default page.
    image.cacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Start working with the [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) class effortlessly by initializing a new instance with a stream and loadOptions parameters. Ideal for developers seeking a convenient way to load CDR images from various data sources while customizing the loading process as needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) |  |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Retrieve the default page of the image with ease using this user-friendly property. Perfect for developers seeking quick access to the primary page of their image, ensuring efficient navigation and management.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Effortlessly determine whether the object's data is currently cached, eliminating the need for data reading. Ideal for developers seeking to optimize performance by leveraging cached data efficiently, ensuring faster access to object information.

**Returns:**
boolean - `true` if object's data is cached; otherwise, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the bit depth of the image effortlessly with this user-friendly property. Ideal for developers seeking to determine the level of detail or color depth present in their images, ensuring accurate processing and manipulation.

**Returns:**
int - The image bits per pixel count.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Retrieve the width of the image seamlessly with this intuitive property. Ideal for developers seeking to access the dimensions of their images dynamically, ensuring precise layout and rendering in their applications.

**Returns:**
int - The image width in pixels.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Retrieve the height of the image effortlessly with this intuitive property. Perfect for developers seeking to access the dimensions of their images dynamically, ensuring accurate layout and rendering in their applications.

**Returns:**
int - the image height in pixels.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Effortlessly retrieve or update the total page count of the image with this intuitive property. Ideal for developers seeking to manage multi-page images dynamically, ensuring efficient navigation and manipulation of image content.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Retrieve the pages of the image seamlessly with this intuitive property. Ideal for developers seeking to access and manipulate individual pages within multi-page images, ensuring efficient navigation and processing.

**Returns:**
com.aspose.imaging.Image[] - the pages.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Effortlessly retrieve or update the CDR document using this intuitive property. Ideal for developers seeking to access or modify the CDR document, ensuring flexibility and efficiency in their applications.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the file format of the image effortlessly with this intuitive property. Ideal for developers seeking to determine the format of their images dynamically, ensuring compatibility and accurate processing in their applications.

**Returns:**
long
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Effortlessly retrieve the page exporting action associated with the image using this intuitive property. Ideal for developers seeking to customize the export behavior of pages within multi-page images, ensuring flexibility and efficiency in their applications. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Effortlessly modify the page exporting action associated with the image using this intuitive property. Ideal for developers seeking to customize the export behavior of pages within multi-page images, ensuring flexibility and efficiency in their applications. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | the page exporting action. |

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Retrieve the default options effortlessly with this user-friendly method. Perfect for developers seeking quick access to the default settings or configurations associated with an object, ensuring efficient customization and streamlined workflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Effortlessly cache the data to prevent additional loading from the underlying source with this user-friendly method. Ideal for developers seeking to optimize performance by preloading data, ensuring faster access and smoother operation in their applications. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Load an image from a CDR file.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // This call caches only the default page.
    image.cacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Effortlessly resize the image to desired dimensions with this intuitive method. Perfect for developers seeking to adjust the size of images dynamically, ensuring they fit the layout or requirements of their applications seamlessly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newWidth | int | The new width. |
| newHeight | int | The new height. |
| resizeType | int | The resize type. |

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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Adjust the orientation of the image by rotating, flipping, or applying both operations with this versatile method. Perfect for developers seeking to customize image orientation dynamically, ensuring optimal presentation or alignment in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of rotating flip. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Customize the color palette of the image with this intuitive method. Ideal for developers seeking to apply specific color schemes or adjustments dynamically, ensuring precise control over the visual appearance of their images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

