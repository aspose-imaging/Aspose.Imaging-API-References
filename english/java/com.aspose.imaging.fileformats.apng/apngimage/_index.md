---
title: ApngImage
second_title: Aspose.Imaging for Java API Reference
description: The API for Animated PNG Animated Portable Network Graphics image file format is a versatile solution for developers looking to integrate animated content into their applications.
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

The API for Animated PNG (Animated Portable Network Graphics) image file format is a versatile solution for developers looking to integrate animated content into their applications. This API offers extensive control over frame settings, allowing users to define frame-specific parameters, including loop duration and PNG file settings. With this feature-rich tool, you can effortlessly manage and optimize the display of APNG images, import and export images, enhancing the dynamic and interactive aspects of your applications.
## Constructors

| Constructor | Description |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Begin working with the [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) class by initializing a new instance effortlessly. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Quickly access information about the file format with this convenient property. |
| [getPageCount()](#getPageCount--) | Retrieve the total number of pages in your image file effortlessly with this property. |
| [getPages()](#getPages--) | Effortlessly access the pages of your image with this convenient property. |
| [getNumPlays()](#getNumPlays--) | Effortlessly control the number of times your animation loops with this versatile property. |
| [setNumPlays(int value)](#setNumPlays-int-) | Effortlessly control the number of times your animation loops with this versatile property. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Easily adjust the default frame duration for creating new frames with this flexible property. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Easily adjust the default frame duration for creating new frames with this flexible property. |
| [getInterlaced()](#getInterlaced--) | Quickly determine whether this [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) object is interlaced with this convenient property. |
| [getOriginalOptions()](#getOriginalOptions--) | Retrieve options based on the original file settings effortlessly with this intuitive method. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Retrieve the default options effortlessly with this straightforward method. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Quickly obtain the date and time when the resource image was last modified with this user-friendly method. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Add a new page to the image effortlessly with this intuitive method. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Effortlessly expand your frame collection by adding a new frame to the end with this intuitive method. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Expand your frame collection seamlessly by appending a new frame to the with this intuitive method. |
| [insertFrame(int index)](#insertFrame-int-) | Effortlessly insert a new frame into your frame collection at the specified with this intuitive method. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Inserts new frame into the own frame collection at the specified index. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Inserts new frame into the own frame collection at the specified index. |
| [popFrameAt(int index)](#popFrameAt-int-) | Remove and retrieve the frame at the specified index from your frame collection with this intuitive method. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Remove the frame at the specified index from your frame collection seamlessly with this method. |
| [removeAllFrames()](#removeAllFrames--) | Clear your frame collection by removing all frames with this intuitive method. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Set the specified raster image as the default image for the current animation effortlessly with this method. |
| [resetDefaultImage()](#resetDefaultImage--) | Remove a previously set default image with this intuitive method. |

## Example: The following example shows how to export to APNG file format.

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


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

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


Begin working with the [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) class by initializing a new instance effortlessly. Perfect for developers seeking to start using ApngImage objects quickly and efficiently in their projects.

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


Quickly access information about the file format with this convenient property. Ideal for developers who need to retrieve details about the format of their Apng files easily.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieve the total number of pages in your image file effortlessly with this property. Ideal for developers needing quick access to page count information.

Value: The page count.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Effortlessly access the pages of your image with this convenient property. Perfect for developers seeking quick and easy access to individual pages for manipulation.

Value: The pages.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Effortlessly control the number of times your animation loops with this versatile property. Perfect for developers seeking precise control over animation behavior, with support for infinite looping in case of the value equals to 0.

Value: The number of times to loop.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Effortlessly control the number of times your animation loops with this versatile property. Perfect for developers seeking precise control over animation behavior, with support for infinite looping in case of the value equals to 0.

Value: The number of times to loop.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Easily adjust the default frame duration for creating new frames with this flexible property. Perfect for developers seeking to customize frame timing efficiently in their animations.

Value: The default frame duration, in milliseconds.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Easily adjust the default frame duration for creating new frames with this flexible property. Perfect for developers seeking to customize frame timing efficiently in their animations.

Value: The default frame duration, in milliseconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Quickly determine whether this [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) object is interlaced with this convenient property. Ideal for developers needing to check the interlacing status of PNG images easily.

Value: `true` if interlaced; otherwise, `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Retrieve options based on the original file settings effortlessly with this intuitive method. Perfect for developers seeking to access and utilize settings that align with the characteristics of the original file. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) method as the second parameter.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Retrieve the default options effortlessly with this straightforward method. Ideal for developers seeking quick access to default Apng image settings.

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


Quickly obtain the date and time when the resource image was last modified with this user-friendly method. Ideal for developers needing to track changes and manage resources effectively.

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


Add a new page to the image effortlessly with this intuitive method. Perfect for developers seeking to expand the content of their image files dynamically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The page to add. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Easily append a new frame to the end of your frame collection with this straightforward method. Ideal for developers looking to expand their frame collection dynamically for animations with multi-frame images. A new frame will be created according to the size of the current image.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Effortlessly expand your frame collection by adding a new frame to the end with this intuitive method. Perfect for developers seeking to enhance their animations of multi-frame images dynamically. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Expand your frame collection seamlessly by appending a new frame to the with this intuitive method. Ideal for developers looking to enrich their animations of multi-frame images. The contents of the new frame will be filled from the specified image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The frame image. |
| frameTime | long | The frame duration, in milliseconds. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Effortlessly insert a new frame into your frame collection at the specified with this intuitive method. Ideal for developers seeking precise control over the arrangement of frames in their animations of multi-frame images. A new frame will be created according to the size of the current image.

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


Remove and retrieve the frame at the specified index from your frame collection with this intuitive method. Perfect for developers seeking efficient management of frames in their animations.

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


Remove the frame at the specified index from your frame collection seamlessly with this method. Perfect for developers seeking streamlined management of frames in their multi-frame images. The frame to be deleted will be disposed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Clear your frame collection by removing all frames with this intuitive method. Ideal for developers seeking to reset or refresh their animations.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Set the specified raster image as the default image for the current animation effortlessly with this method. Perfect for developers seeking to customize the default image in their animations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Remove a previously set default image with this intuitive method. Ideal for developers seeking to reset or clear the default image in their animation. After this, the default image is the first frame in the own frame collection (it cannot be deleted using this method).

