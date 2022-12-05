---
title: DjvuPage
second_title: Aspose.Imaging for Java API Reference
description: Djvu page class
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Djvu page class
## Fields

| Field | Description |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Occurs when [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Occurs when a property value changes. |
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the image bits per pixel count. |
| [getParentImage()](#getParentImage--) | Gets the parent image the page belongs to |
| [getWidth()](#getWidth--) | Gets the width of the page |
| [getHeight()](#getHeight--) | Gets the height of the page |
| [getImage()](#getImage--) | Gets the image. |
| [getThumbnailImage()](#getThumbnailImage--) | Gets or sets the thumbnail image for the page |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Gets or sets the thumbnail image for the page |
| [getPageNumber()](#getPageNumber--) | Gets the page number. |
| [isColor()](#isColor--) | Gets a value indicating whether this instance is color. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Gets the text for the rectangle location |
| [getForegroundImage()](#getForegroundImage--) | Gets the foreground image for the page |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Gets the foreground image for the page |
| [getTextImage()](#getTextImage--) | Gets the text image. |
| [getTextImage(int subsample)](#getTextImage-int-) | Gets the text image. |
| [getBackgroundImage()](#getBackgroundImage--) | Gets the background image. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Extracts the thumbnail image from the Djvu page. |
### PageExportedAction {#PageExportedAction}
```
public static final Event<OnPageExportedAction> PageExportedAction
```


Occurs when [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Occurs when a property value changes.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Gets the image bits per pixel count.

Value: The image bits per pixel count.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Gets the parent image the page belongs to

Value: The document.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width of the page

Value: The width.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets the height of the page

Value: The height.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Gets the image.

Value: The image.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Gets or sets the thumbnail image for the page

Value: The thumbnail image.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Gets or sets the thumbnail image for the page

Value: The thumbnail image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets the page number.

Value: The page number.

**Returns:**
int

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

### isColor() {#isColor--}
```
public boolean isColor()
```


Gets a value indicating whether this instance is color.

Value: `true` if this instance is color; otherwise, `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Gets the text for the rectangle location

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The location rect. |

**Returns:**
java.lang.String - Text found on location
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Gets the foreground image for the page

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Gets the foreground image for the page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subsample | int | The subsample. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Gets the text image.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Gets the text image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subsample | int | The subsample. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Gets the background image.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Extracts the thumbnail image from the Djvu page.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The Djvu raster image.
