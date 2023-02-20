---
title: IcoImage
second_title: Aspose.Imaging for Java API Reference
description: The ICO image class.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

The ICO image class.
## Constructors

| Constructor | Description |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Initializes a new instance of the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class. |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Initializes a new instance of the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets file format. |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [getPages()](#getPages--) | Gets the pages. |
| [hasAlpha()](#hasAlpha--) | Gets a value indicating whether this instance has alpha. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Adds an image entry to the ICO image according to default [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) as 32-bit PNG. |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Adds an image entry to the ICO image according to default [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) as 32-bit PNG. |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Adds an image entry to the ICO image according to specified [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [removePage(int index)](#removePage-int-) | Removes an image entry at specified `` from the ICO image. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Initializes a new instance of the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | The ICO creation options. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Initializes a new instance of the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | The ICO options. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets file format.

**Returns:**
long - file format.
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
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gets a value indicating whether this instance has alpha.

Value: `true` if this instance has alpha; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance has alpha.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Adds an image entry to the ICO image according to default [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) as 32-bit PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Adds an image entry to the ICO image according to default [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) as 32-bit PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | The image. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Adds an image entry to the ICO image according to specified [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | The image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | The ICO options. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Removes an image entry at specified `` from the ICO image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

