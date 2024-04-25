---
title: OdImage
second_title: Aspose.Imaging for Java API Reference
description: The open document
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.opendocument/odimage/
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
| [OdImage(StreamContainer streamContainer, LoadOptions options)](#OdImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initialize a new [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) object by providing a stream container along with load options, facilitating seamless integration into software applications. |
| [OdImage(StreamContainer streamContainer)](#OdImage-com.aspose.imaging.StreamContainer-) | Creates a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class, designed specifically for initialization with a stream container. |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Retrieves the default page associated with the image, providing essential access to the primary page within the image collection. |
| [isCached()](#isCached--) | Obtains a boolean value indicating whether the data of the object is currently cached, thus eliminating the need for data reading. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieves the count of bits per pixel for the image. |
| [getWidth()](#getWidth--) | Retrieves the width of the image, indicating the horizontal dimension in pixels. |
| [getHeight()](#getHeight--) | Returns the height of the image, denoting the vertical dimension in pixels. |
| [getPageCount()](#getPageCount--) | Retrieves the total count of pages within the image. |
| [getMetadata()](#getMetadata--) | Retrieves metadata specific to OpenDocument files. |
| [getRecords()](#getRecords--) | Retrieves the OpenDocument records stored within the image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Adjusts the dimensions of the image according to specified width, height, and resize settings. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | This method resizes the image, adjusting both width and height based on the specified dimensions and resize type. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | This method provides functionality to rotate, flip, or perform both operations simultaneously on the image. |
### OdImage(StreamContainer streamContainer, LoadOptions options) {#OdImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdImage(StreamContainer streamContainer, LoadOptions options)
```


Initialize a new [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) object by providing a stream container along with load options, facilitating seamless integration into software applications. This constructor efficiently handle image data, offering flexibility and control over the loading process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### OdImage(StreamContainer streamContainer) {#OdImage-com.aspose.imaging.StreamContainer-}
```
public OdImage(StreamContainer streamContainer)
```


Creates a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class, designed specifically for initialization with a stream container. This constructor enables seamless integration with stream-based data sources, facilitating efficient handling of OdImage instances within software systems.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Retrieves the default page associated with the image, providing essential access to the primary page within the image collection. This property streamlines navigation and manipulation of image data, enhancing the efficiency of software development workflows.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtains a boolean value indicating whether the data of the object is currently cached, thus eliminating the need for data reading. This property serves as an optimization indicator, enhancing performance by minimizing redundant data access operation.

**Returns:**
boolean - a value indicating whether object's data is cached currently and no data reading is required.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Retrieves the count of bits per pixel for the image. This property provides insight into the level of detail and color depth represented in the image, aiding in various image processing tasks and optimizations.

**Returns:**
int - the image bits per pixel count.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Retrieves the width of the image, indicating the horizontal dimension in pixels. This property provides essential information about the image's size, enabling precise rendering, manipulation, and analysis of image data.

**Returns:**
int - the image width in pixels.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Returns the height of the image, denoting the vertical dimension in pixels. This property is crucial for understanding the image's overall size and proportions, facilitating accurate display and processing of image content.

**Returns:**
int - the image height in pixels.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Retrieves the total count of pages within the image. This property is essential for applications managing multi-page images, enabling them to accurately determine the number of pages available for processing or display.

**Returns:**
int - the page count.
### getMetadata() {#getMetadata--}
```
public final OdMetadata getMetadata()
```


Retrieves metadata specific to OpenDocument files. This property allows access to essential information embedded within OD files, facilitating various operations such as extraction, modification, or analysis of metadata.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Retrieves the OpenDocument records stored within the image. This property grants access to specific structured data elements embedded within OpenDocument files, facilitating retrieval or manipulation of relevant information for further processing or analysis.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - the records.
### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Adjusts the dimensions of the image according to specified width, height, and resize settings. This method provides flexibility in resizing images while maintaining desired proportions and adhering to defined resize configurations, ensuring accurate adjustment of image dimensions to meet specific requirements or display criteria.

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


This method resizes the image, adjusting both width and height based on the specified dimensions and resize type. It offers a comprehensive approach to resizing, allowing for precise adjustments while maintaining image quality and integrity. By incorporating the resize type parameter, users can choose from various resizing algorithms or methods to achieve optimal results for different use cases or preferences.

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


This method provides functionality to rotate, flip, or perform both operations simultaneously on the image. It allows users to manipulate the orientation of the image according to their specific requirements. With support for rotation angles and flip directions, it offers flexibility in transforming the image to desired orientations or orientations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type of the rotate flip. |

