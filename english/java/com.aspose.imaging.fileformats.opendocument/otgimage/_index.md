---
title: OtgImage
second_title: Aspose.Imaging for Java API Reference
description: Process OpenDocument Template OTG drawing image files with our API leveraging the OpenDocument XML format with Graphics Content for seamless manipulation.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Process OpenDocument Template (OTG) drawing image files with our API, leveraging the OpenDocument XML format with Graphics Content for seamless manipulation. Easily parse documents, customize background colors, and adjust page dimensions, ensuring optimal control and flexibility for your OTG vector graphics projects.
## Constructors

| Constructor | Description |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initialize a new [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) object by providing a stream container and loading options. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Create a new object of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class by supplying a stream container. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | This property provides access to the OTG file format, offering crucial insights into the type of data encapsulated within the image file. |
| [getPageExportingAction()](#getPageExportingAction--) | This property allows for the retrieval or modification of the page exporting action associated with the image. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | This property allows for the retrieval or modification of the page exporting action associated with the image. |
| [getPages()](#getPages--) | Retrieves the collection of pages associated with the image, enabling software developers to access and manipulate each individual page efficiently. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Retrieves the default options configured for the image, providing a convenient way to access and modify the default settings. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Initialize a new [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) object by providing a stream container and loading options. This constructor empowers developers to efficiently load OTG images from streams while specifying custom loading configurations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Create a new object of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class by supplying a stream container. This constructor enables developers to create OTG images directly from stream containers, streamlining the process of working with OTG image data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


This property provides access to the OTG file format, offering crucial insights into the type of data encapsulated within the image file. It serves as a pivotal reference point for software developers, enabling them to effectively handle OTG files within their applications. By utilizing this property, you can ascertain the specific format of the image file, facilitating seamless integration and manipulation of OTG files in their software systems.

**Returns:**
long
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


This property allows for the retrieval or modification of the page exporting action associated with the image. It serves as a crucial parameter, dictating the behavior of the image when exported or processed further. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - The page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


This property allows for the retrieval or modification of the page exporting action associated with the image. It serves as a crucial parameter, dictating the behavior of the image when exported or processed further. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | The page exporting action. |

### getPages() {#getPages--}
```
public Image[] getPages()
```


Retrieves the collection of pages associated with the image, enabling software developers to access and manipulate each individual page efficiently. This property facilitates seamless iteration through the pages for various operations, enhancing the functionality and versatility of image processing applications.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Retrieves the default options configured for the image, providing a convenient way to access and modify the default settings. This property ensures consistency in operations by offering predefined settings that align with common use cases, simplifying the development process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
