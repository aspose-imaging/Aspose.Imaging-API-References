---
title: OdgImage
second_title: Aspose.Imaging for Java API Reference
description: Manipulate OpenDocument Graphic ODG vector image file format with our API widely used by OpenOffice and LibreOffice Draw applications for storing drawing elements in a vector format.
type: docs
weight: 12
url: /java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Manipulate OpenDocument Graphic (ODG) vector image file format with our API, widely used by OpenOffice and LibreOffice Draw applications for storing drawing elements in a vector format. Seamlessly parse documents, access pages, resize and rotate images, ensuring efficient processing and customization of ODG files to meet your specific requirements.
## Constructors

| Constructor | Description |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Start a new creation of the [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) class object with the initiation of a fresh instance. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Crafted for seamless integration into software solutions, the [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) constructor initializes a new instance by leveraging a stream container. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Easily retrieve the file format value with this user-friendly property. |
| [getPages()](#getPages--) | Retrieving the collection of pages, this property empowers to access the entirety of pages associated with an image. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | This property provides access to the default options associated with an image. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load image.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Cast to OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Get all pages
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Do some image processing
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Start a new creation of the [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) class object with the initiation of a fresh instance. Harness the potential of a stream container coupled with load options parameters, maintain a versatile constructor to seamlessly load images. This constructor empowers efficient image handling, offering customizable loading configurations for enhanced adaptability and performance across diverse scenarios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | The load options |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Crafted for seamless integration into software solutions, the [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) constructor initializes a new instance by leveraging a stream container. This method ensures efficient handling of ODG image data within software environments, optimizing resource utilization and facilitating streamlined image processing workflows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | The stream container. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Easily retrieve the file format value with this user-friendly property. Ideal for developers seeking quick access to information about the file format.

**Returns:**
long - a value of file format
### getPages() {#getPages--}
```
public Image[] getPages()
```


Retrieving the collection of pages, this property empowers to access the entirety of pages associated with an image. By accessing this property, developers can iterate through individual pages, retrieve specific pages based on their index, or perform batch operations on the entire collection.

**Returns:**
com.aspose.imaging.Image[] - the pages.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


This property provides access to the default options associated with an image. By retrieving these options, developers can quickly ascertain the default settings applied to the image, facilitating the creation of new instances or the modification of existing ones based on these presets.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | The arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
