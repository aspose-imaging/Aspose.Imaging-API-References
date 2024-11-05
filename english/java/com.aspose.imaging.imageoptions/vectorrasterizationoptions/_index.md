---
title: VectorRasterizationOptions
second_title: Aspose.Imaging for Java API Reference
description: The vector rasterization options.
type: docs
weight: 51
url: /java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

The vector rasterization options.
## Constructors

| Constructor | Description |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Gets the smoothing mode. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Sets the smoothing mode. |
| [getBorderX()](#getBorderX--) | Gets or sets the border X. |
| [setBorderX(float value)](#setBorderX-float-) | Gets or sets the border X. |
| [getBorderY()](#getBorderY--) | Gets or sets the border Y. |
| [setBorderY(float value)](#setBorderY-float-) | Gets or sets the border Y. |
| [getCenterDrawing()](#getCenterDrawing--) | Gets a value indicating whether center drawing. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Sets a value indicating whether center drawing. |
| [getPageHeight()](#getPageHeight--) | Gets the page height. |
| [setPageHeight(float value)](#setPageHeight-float-) | Sets the page height. |
| [getPageSize()](#getPageSize--) | Gets the page size. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Sets the page size. |
| [getPageWidth()](#getPageWidth--) | Gets the page width. |
| [setPageWidth(float value)](#setPageWidth-float-) | Sets the page width. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets a background color. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets a background color. |
| [getDrawColor()](#getDrawColor--) | Gets a foreground color. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Sets a foreground color. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Gets the text rendering hint. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Sets the text rendering hint. |
| [getPositioning()](#getPositioning--) | Gets the positioning. |
| [setPositioning(int value)](#setPositioning-int-) | Sets the positioning. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Gets the text replace mapping. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Sets the text replace mapping. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copies to. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Gets the smoothing mode.

**Returns:**
int - the smoothing mode.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Sets the smoothing mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the smoothing mode. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load image.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // In order to rasterize SVG we need to specify rasterization options.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Set default color of a background for an image. Default value is white.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Set the page size
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing is applied to lines and curves and the edges of filled areas.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Each character is drawn using its antialiased glyph bitmap without hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduce the image size 10 times, i.e. the output size will be 10% of the original size.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Save to a PNG file
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Gets or sets the border X.

**Returns:**
float - The border X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Gets or sets the border X.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The border X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Gets or sets the border Y.

**Returns:**
float - The border Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Gets or sets the border Y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The border Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Gets a value indicating whether center drawing.

**Returns:**
boolean - a value indicating whether center drawing.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Sets a value indicating whether center drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether center drawing. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Gets the page height.

**Returns:**
float - the page height.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Sets the page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the page height. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Gets the page size.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Sets the page size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | the page size. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text will be converted to shapes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // The page size.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Set the horizontal margin
    rasterizationOptions.setBorderX(50);

    // Set the vertical margin
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Gets the page width.

**Returns:**
float - the page width.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Sets the page width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | the page width. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets a background color.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Sets a background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | a background color. |


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text will be converted to shapes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // The page size.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Set the horizontal margin
    rasterizationOptions.setBorderX(50);

    // Set the vertical margin
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Gets a foreground color.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Sets a foreground color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | a foreground color. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Gets the text rendering hint.

Value: The text rendering hint.

**Returns:**
int - the text rendering hint.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Sets the text rendering hint.

Value: The text rendering hint.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the text rendering hint. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load image.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // In order to rasterize SVG we need to specify rasterization options.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Set default color of a background for an image. Default value is white.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Set the page size
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing is applied to lines and curves and the edges of filled areas.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Each character is drawn using its antialiased glyph bitmap without hinting.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduce the image size 10 times, i.e. the output size will be 10% of the original size.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Save to a PNG file
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Gets the positioning.

Value: The positioning.

**Returns:**
int - the positioning.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Sets the positioning.

Value: The positioning.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the positioning. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Gets the text replace mapping.

Value: The text replace mapping.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - the text replace mapping.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Sets the text replace mapping.

Value: The text replace mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.HashMap<java.lang.String,java.lang.String> | the text replace mapping. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copies to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | The vector rasterization options. |

