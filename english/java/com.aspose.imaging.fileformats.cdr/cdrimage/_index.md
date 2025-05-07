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
| [getPageCount()](#getPageCount--) | Effortlessly retrieve or update the total page count of the image with this intuitive property. |
| [getPages()](#getPages--) | Retrieve the pages of the image seamlessly with this intuitive property. |
| [getCdrDocument()](#getCdrDocument--) | Effortlessly retrieve or update the CDR document using this intuitive property. |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format of the image effortlessly with this intuitive property. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [cacheData()](#cacheData--) | Effortlessly cache the data to prevent additional loading from the underlying source with this user-friendly method. |
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
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the image width.

Value: The image width.

**Returns:**
int - the image width.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the image height.

Value: The image height.

**Returns:**
int - the image height.
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

