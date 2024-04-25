---
title: IcoImage
second_title: Aspose.Imaging for Java API Reference
description: Effortlessly manipulate ICO image files with our API supporting various file formats and frame types including PNG and BMP.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Effortlessly manipulate ICO image files with our API, supporting various file formats and frame types including PNG and BMP. Customize bits per pixel settings and update image dimensions seamlessly, ensuring optimal representation and compatibility for your icons across different platforms.
## Constructors

| Constructor | Description |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Start ICO image creation effortlessly using the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class. |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Crafted for simplicity and efficiency, the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class empowers you to create ICO images with ease. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Retrieve the file format effortlessly with this property, enabling seamless integration into your workflow. |
| [getPageCount()](#getPageCount--) | Gain immediate insight into the document structure with this straightforward property. |
| [getPages()](#getPages--) | Retrieve comprehensive information about the document's pages effortlessly through this property. |
| [hasAlpha()](#hasAlpha--) | Determine whether alpha channel is present in this instance with this property. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Expand your ICO image by adding an image page entry, leveraging the [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Enrich your ICO image effortlessly by inserting an image page entry using the default settings from [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversify your ICO image effortlessly by integrating an image entry tailored to your needs with the specified [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [removePage(int index)](#removePage-int-) | Fine-tune your ICO image by removing a specific image entry located at the designated `` within the file. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Start ICO image creation effortlessly using the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class. This constructor allows you to initialize new instances of ICO images by specifying the width, height, and creation options parameters. With this straightforward constructor, you can tailor ICO images to your exact specifications, ensuring seamless compatibility and visual appeal across different platforms and devices.

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


Crafted for simplicity and efficiency, the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class empowers you to create ICO images with ease. This constructor initializes a new instance of the class, providing a solid foundation for your image manipulation needs. Whether you're developing applications or enhancing user interfaces, the [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) class simplifies ICO image management, allowing you to focus on delivering exceptional experiences.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | The ICO options. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Retrieve the file format effortlessly with this property, enabling seamless integration into your workflow. By using this property, you gain access to critical information about the format of your file, ensuring compatibility and efficient processing.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gain immediate insight into the document structure with this straightforward property. By invoking this property, you effortlessly retrieve the total number of pages contained within the file.

**Returns:**
int - the page count.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Retrieve comprehensive information about the document's pages effortlessly through this property. By accessing this property, you gain access to a collection or array containing all the pages present within the document.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determine whether alpha channel is present in this instance with this property. It offers a quick way to check if the image or document contains an alpha channel, which is crucial for various image processing and rendering tasks. Ideal for ensuring compatibility and handling transparency effects in images or documents.

**Returns:**
boolean - a value indicating whether this instance has alpha.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Expand your ICO image by adding an image page entry, leveraging the [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). This method seamlessly incorporates raster images into your ICO file, converting them to a high-quality 32-bit PNG format. Perfect for enhancing your ICO files with raster images while ensuring optimal compatibility and rendering quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | The image. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Enrich your ICO image effortlessly by inserting an image page entry using the default settings from [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). This method conveniently converts the inserted image to a 32-bit PNG format, ensuring compatibility and high-quality rendering within the ICO image. Perfect for seamlessly integrating PNG images into your ICO files with ease and efficiency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | The image. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversify your ICO image effortlessly by integrating an image entry tailored to your needs with the specified [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). This method seamlessly incorporates the image according to your customized options, ensuring flexibility and precision in your ICO file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | The image. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | The ICO options. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Fine-tune your ICO image by removing a specific image entry located at the designated `` within the file. This method provides precise control over your image composition, allowing you to refine your ICO file with ease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

