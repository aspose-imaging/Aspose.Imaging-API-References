---
title: CmxImage
second_title: Aspose.Imaging for Java API Reference
description: The API for Corel Metafile Exchange CMX vector image format with metadata descriptions support is a comprehensive solution for developers working with CMX files.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

The API for Corel Metafile Exchange (CMX) vector image format with metadata descriptions support is a comprehensive solution for developers working with CMX files. This API allows for the seamless loading of CMX images, extracting metadata such as bits per pixel, object dimensions, and more. With additional functionalities like resizing, rotating, setting palettes, and converting to other formats, this API empowers developers to efficiently manipulate and customize CMX vector images to meet their specific application requirements.
## Constructors

| Constructor | Description |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Start working with the [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) class seamlessly by initializing a new instance with a streamContainer and loadOptions parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format of the image effortlessly with this user-friendly property. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieve the bit depth of the image effortlessly with this user-friendly property. |
| [getDefaultPage()](#getDefaultPage--) | Effortlessly retrieve the default page of the image with this intuitive property. |
| [isCached()](#isCached--) | Determine whether the object's data is currently cached, eliminating the need for data reading. |
| [getWidthF()](#getWidthF--) | Retrieve the width of the object in inches with this intuitive property. |
| [getHeightF()](#getHeightF--) | Effortlessly obtain the height of the object, measured in inches, with this user-friendly property. |
| [getDocument()](#getDocument--) | Retrieve the CMX document effortlessly with this intuitive property. |
| [getCmxPage()](#getCmxPage--) | Effortlessly retrieve the CMX page of the image with this intuitive property. |
| [getPageCount()](#getPageCount--) | Retrieve the total page count of the image with this intuitive property. |
| [getPages()](#getPages--) | Retrieve the pages of the image seamlessly with this intuitive property. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Retrieve the default options effortlessly with this user-friendly method. |
| [cacheData()](#cacheData--) | Cache the data to prevent additional loading from the underlying source [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) with this convenient method. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Effortlessly resize the image to desired dimensions with this intuitive method. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Effortlessly adjust the orientation of the image by rotating, flipping, or applying both operations with this versatile method. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Customize the color palette of the image with this intuitive method. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Load an image from a CMX file.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // This call caches only the default page.
    image.cacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Start working with the [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) class seamlessly by initializing a new instance with a streamContainer and loadOptions parameters. Ideal for developers seeking a convenient way to load CMX images from various data sources while customizing the loading process as needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the file format of the image effortlessly with this user-friendly property. Ideal for developers seeking to determine the format of their images dynamically, ensuring compatibility and accurate processing in their applications.

**Returns:**
long - The file format [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieve the bit depth of the image effortlessly with this user-friendly property. Ideal for developers seeking to determine the level of detail or color depth present in their images, ensuring accurate processing and manipulation.

**Returns:**
int - The image bits per pixel count.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Effortlessly retrieve the default page of the image with this intuitive property. Ideal for developers seeking quick access to the primary page of their image, ensuring efficient navigation and management.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Determine whether the object's data is currently cached, eliminating the need for data reading. Ideal for developers seeking to optimize performance by leveraging cached data efficiently, ensuring faster access to object information.

**Returns:**
boolean - `true` if object's data is cached; otherwise, `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Retrieve the width of the object in inches with this intuitive property. Ideal for developers seeking precise measurements of objects in their applications, ensuring accurate layout and presentation.

**Returns:**
float - The object width, in inches.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Effortlessly obtain the height of the object, measured in inches, with this user-friendly property. Ideal for developers seeking precise dimensional information for effective layout and presentation in their applications.

**Returns:**
float - The object height, in inches.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Retrieve the CMX document effortlessly with this intuitive property. Ideal for developers seeking to access or modify CMX images, ensuring flexibility and efficiency in their applications.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Effortlessly retrieve the CMX page of the image with this intuitive property. Ideal for developers seeking quick access to individual pages within CMX images, ensuring efficient navigation and management.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total page count of the image with this intuitive property. Ideal for developers seeking to manage multi-page images dynamically, ensuring efficient navigation and manipulation of image content.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Retrieve the pages of the image seamlessly with this intuitive property. Ideal for developers seeking to access and manipulate individual pages within multi-page images, ensuring efficient navigation and processing.

**Returns:**
com.aspose.imaging.Image[] - the pages.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Load an image from a CMX file.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // This call caches only the default page.
    image.cacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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


Cache the data to prevent additional loading from the underlying source [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) with this convenient method. Ideal for developers seeking to optimize performance by preloading data, ensuring faster access and smoother operation in their applications.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Load an image from a CMX file.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // This call caches only the default page.
    image.cacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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


Effortlessly adjust the orientation of the image by rotating, flipping, or applying both operations with this versatile method. Perfect for developers seeking to customize image orientation dynamically, ensuring optimal presentation or alignment in their applications.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of the rotate flip. |

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

