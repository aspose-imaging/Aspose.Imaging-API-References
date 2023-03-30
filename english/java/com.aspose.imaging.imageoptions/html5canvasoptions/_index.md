---
title: Html5CanvasOptions
second_title: Aspose.Imaging for Java API Reference
description: The Html5 Canvas file format creation options.
type: docs
weight: 23
url: /java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

The Html5 Canvas file format creation options.
## Constructors

| Constructor | Description |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Initializes a new instance of the [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) class. |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Initializes a new instance of the `ImageOptionsBase` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Gets the canvas tag identifier. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Sets the canvas tag identifier. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Gets a value indicating whether the full HTML page should be generated. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Sets a value indicating whether the full HTML page should be generated. |
| [getEncoding()](#getEncoding--) | Gets the encoding. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Sets the encoding. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
You can embed more than one Canvas image within HTML page or update already existing page. In order to do that you need to export only the Canvas tag.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


Initializes a new instance of the [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) class.

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Initializes a new instance of the `ImageOptionsBase` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | The image options. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Gets the canvas tag identifier.

**Returns:**
java.lang.String - the canvas tag identifier.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Sets the canvas tag identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | the canvas tag identifier. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Gets a value indicating whether the full HTML page should be generated.

**Returns:**
boolean - a value indicating whether the full HTML page should be generated.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Sets a value indicating whether the full HTML page should be generated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether the full HTML page should be generated. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
You can embed more than one Canvas image within HTML page or update already existing page. In order to do that you need to export only the Canvas tag.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gets the encoding.

**Returns:**
java.nio.charset.Charset - the encoding.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Sets the encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset | the encoding. |

