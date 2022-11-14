---
title: OtgImage
second_title: Aspose.Imaging for Java API Reference
description: The Otg image
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

The Otg image
## Constructors

| Constructor | Description |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initializes a new instance of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Initializes a new instance of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets a value of file format |
| [getPageExportingAction()](#getPageExportingAction--) | Gets the page exporting action. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Sets the page exporting action. |
| [getPages()](#getPages--) | Gets the pages. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Gets the default options. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Initializes a new instance of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Initializes a new instance of the [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Gets a value of file format

**Returns:**
long - a value of file format
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Gets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

Value: The page exporting action.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved.

Value: The page exporting action.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | the page exporting action. |

### getPages() {#getPages--}
```
public Image[] getPages()
```


Gets the pages.

Value: The pages.

**Returns:**
com.aspose.imaging.Image[] - the pages.
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
