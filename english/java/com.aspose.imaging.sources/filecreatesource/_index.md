---
title: FileCreateSource
second_title: Aspose.Imaging for Java API Reference
description: Represents a file source for creation.
type: docs
weight: 10
url: /java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Represents a file source for creation.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initializes a new instance of the `FileCreateSource` class. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initializes a new instance of the `FileCreateSource` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFilePath()](#getFilePath--) | Gets the file path to create. |
| [isTemporal()](#isTemporal--) | Gets a value indicating whether file will be temporal. |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |

## Example
This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface. The example creates a new Image and draw shapes using Figures and GraphicsPath
``` java
//Creates an instance of BmpOptions and set its various properties
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
//Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Creates an instance of Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Creates and initialize an instance of Graphics class
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Clears Graphics surface
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Creates an instance of Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Create an instance of SolidBrush having Red Color
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Draw a String
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // save all changes
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initializes a new instance of the `FileCreateSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to create. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initializes a new instance of the `FileCreateSource` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to create. |
| isTemporal | boolean | If set to `true` the created file will be temporal. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Gets the file path to create.

Value: The file path to create.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Gets a value indicating whether file will be temporal.

Value: `true` if file will be temporal; otherwise, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Gets the stream container.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Use with caution. You will need to dispose the stream container after retrieval.
