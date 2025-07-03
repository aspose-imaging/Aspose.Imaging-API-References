---
title: CmxImagePage
second_title: Aspose.Imaging for Java API Reference
description: The image of CMX page
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

The image of CMX page
## Constructors

| Constructor | Description |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Initializes a new instance of the [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) class. |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Initializes a new instance of the [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Gets the CMX page. |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getWidthF()](#getWidthF--) | Gets the object width, in inches. |
| [getHeightF()](#getHeightF--) | Gets the object height, in inches. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [cacheData()](#cacheData--) | Cache can not be used. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Sets the image palette. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Initializes a new instance of the [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | The CMX page. |
| container | [Image](../../com.aspose.imaging/image) | The container. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Initializes a new instance of the [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | The CMX page. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Gets the CMX page.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - a value of file format
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - the image bits per pixel count.
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

Value: `true` if object's data is cached; otherwise, `false`.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Gets the object width, in inches.

**Returns:**
float - the object width, in inches.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Gets the object height, in inches.

**Returns:**
float - the object height, in inches.
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
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Gets the default options.

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


Cache can not be used.


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

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Sets the image palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | The palette to set. |
| updateColors | boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

