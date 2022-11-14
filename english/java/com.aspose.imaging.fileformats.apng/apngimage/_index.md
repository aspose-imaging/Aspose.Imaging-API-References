---
title: ApngImage
second_title: Aspose.Imaging for Java API Reference
description: The animated PNG image.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

The animated PNG image.
## Constructors

| Constructor | Description |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Initializes a new instance of the [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getXmpData()](#getXmpData--) | Gets the XMP metadata. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Sets the XMP metadata. |
| [getPageCount()](#getPageCount--) | Gets the page count. |
| [getPages()](#getPages--) | Gets the pages. |
| [getDefaultPage()](#getDefaultPage--) | Gets the default page. |
| [getNumPlays()](#getNumPlays--) | Gets the number of times to loop animation. 0 indicates infinite looping. |
| [setNumPlays(int value)](#setNumPlays-int-) | Sets the number of times to loop animation. 0 indicates infinite looping. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Gets the default frame duration. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Sets the default frame duration. |
| [getInterlaced()](#getInterlaced--) | Gets a value indicating whether this [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is interlaced. |
| [getPageExportingAction()](#getPageExportingAction--) | Gets the page exporting action. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Sets the page exporting action. |
| [getOriginalOptions()](#getOriginalOptions--) | Gets the options based on the original file settings. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Gets the date and time the resource image was last modified. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Adds page to the image. |
| [addFrame()](#addFrame--) | Adds new frame to the end of the own frame collection. |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Adds new frame to the end of the own frame collection. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Adds new frame to the end of the own frame collection. |
| [insertFrame(int index)](#insertFrame-int-) | Inserts new frame into the own frame collection at the specified index. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Inserts new frame into the own frame collection at the specified index. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Inserts new frame into the own frame collection at the specified index. |
| [popFrameAt(int index)](#popFrameAt-int-) | Removes and returns the frame at the specified index of the own frame collection. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Removes the frame at the specified index of the own frame collection. |
| [removeAllFrames()](#removeAllFrames--) | Removes all frames from the own frame collection. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Sets the specified raster image as the default image of the current animation. |
| [resetDefaultImage()](#resetDefaultImage--) | Deletes a previously set default image. |

## Example
The following example shows how to export to APNG file format.
``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Export to APNG animation with unlimited animation cycles as default
    image.save("Animation1.webp.png", new ApngOptions());
    // Setting up animation cycles
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example
The following example shows how to export apng APNG file format from other non-animated multi-page format.
``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Setting up the default frame duration
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Initializes a new instance of the [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | The options. |
| width | int | The width. |
| height | int | The height. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - a value of file format
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Gets the XMP metadata.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Sets the XMP metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | the XMP metadata. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets the page count.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Gets the pages.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Gets the default page.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Gets the number of times to loop animation. 0 indicates infinite looping.

**Returns:**
int - the number of times to loop animation.
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Sets the number of times to loop animation. 0 indicates infinite looping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the number of times to loop animation. |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Gets the default frame duration. Used when creating new frames.

**Returns:**
long - the default frame duration, in milliseconds.
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Sets the default frame duration. Used when creating new frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | the default frame duration, in milliseconds. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Gets a value indicating whether this [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is interlaced.

**Returns:**
boolean - a value indicating whether this [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) is interlaced.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Gets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | the page exporting action. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String,ImageOptionsBase)](../../com.aspose.imaging/image\#save-String-ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
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
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Gets the date and time the resource image was last modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useDefault | boolean | if set to `true` uses the information from FileInfo as default value. |

**Returns:**
java.util.Date - The date and time the resource image was last modified.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Adds page to the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


Adds new frame to the end of the own frame collection. A new frame will be created according to the size of the current image.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Adds new frame to the end of the own frame collection. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Adds new frame to the end of the own frame collection. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |
| frameTime | long | The frame duration, in milliseconds. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Inserts new frame into the own frame collection at the specified index. A new frame will be created according to the size of the current image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |
| frameTime | long | The frame duration, in milliseconds. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Removes and returns the frame at the specified index of the own frame collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Removes the frame at the specified index of the own frame collection. The frame to be deleted will be disposed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Removes all frames from the own frame collection.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Sets the specified raster image as the default image of the current animation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Deletes a previously set default image. After this, the default image is the first frame in the own frame collection (it cannot be deleted using this method).

