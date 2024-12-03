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
| [OdImage(StreamContainer streamContainer, LoadOptions options)](#OdImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initialize a new [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) object by providing a stream container along with load options, facilitating seamless integration into software applications. |
| [OdImage(StreamContainer streamContainer)](#OdImage-com.aspose.imaging.StreamContainer-) | Creates a new instance of the [OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage) class, designed specifically for initialization with a stream container. |
## Methods

| Method | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Retrieves the default page associated with the image, providing essential access to the primary page within the image collection. |
| [isCached()](#isCached--) | Obtains a boolean value indicating whether the data of the object is currently cached, thus eliminating the need for data reading. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Retrieves the count of bits per pixel for the image. |
| [getPageCount()](#getPageCount--) | Retrieves the total count of pages within the image. |
| [getMetadata()](#getMetadata--) | Retrieves metadata specific to OpenDocument files. |
| [getRecords()](#getRecords--) | Retrieves the OpenDocument records stored within the image. |
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
