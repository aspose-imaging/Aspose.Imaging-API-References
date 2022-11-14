---
title: OdImage
second_title: Aspose.Imaging for Java API Reference
description: The open document
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

The open document
## Constructors

| Constructor | Description |
| --- | --- |
| [OdImage(StreamContainer streamContainer, LoadOptions options)](#OdImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class. |
| [OdImage(StreamContainer streamContainer)](#OdImage-com.aspose.imaging.StreamContainer-) | Initializes a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Gets the default page. |
| [isCached()](#isCached--) | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getWidth()](#getWidth--) | Gets the image width. |
| [getHeight()](#getHeight--) | Gets the image height. |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [getMetadata()](#getMetadata--) | Gets the metadata. |
| [getRecords()](#getRecords--) | Gets the records. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Resizes the image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Resizes the image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rotates, flips, or rotates and flips the image. |
### OdImage(StreamContainer streamContainer, LoadOptions options) {#OdImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdImage(StreamContainer streamContainer, LoadOptions options)
```


Initializes a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### OdImage(StreamContainer streamContainer) {#OdImage-com.aspose.imaging.StreamContainer-}
```
public OdImage(StreamContainer streamContainer)
```


Initializes a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Gets the default page.

Value: The default page.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Gets a value indicating whether object's data is cached currently and no data reading is required.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

**Returns:**
int - the image bits per pixel count.
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets the page count.

Value: The page count.

**Returns:**
int - the page count.
### getMetadata() {#getMetadata--}
```
public final OdMetadata getMetadata()
```


Gets the metadata.

Value: The metadata.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Gets the records.

Value: The records.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - the records.
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rotates, flips, or rotates and flips the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of the rotate flip. |

