---
title: SvgRasterizationOptions
second_title: Aspose.Imaging for Java API Reference
description: The SVG rasterization options.
type: docs
weight: 46
url: /java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

The SVG rasterization options.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Initializes a new instance of the `SvgRasterizationOptions` class. |
## Methods

| Method | Description |
| --- | --- |
| [getScaleX()](#getScaleX--) | Gets or sets the scale x. |
| [setScaleX(float value)](#setScaleX-float-) | Gets or sets the scale x. |
| [getScaleY()](#getScaleY--) | Gets or sets the scale y. |
| [setScaleY(float value)](#setScaleY-float-) | Gets or sets the scale y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Copies this instance to `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Initializes a new instance of the `SvgRasterizationOptions` class.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Gets or sets the scale x.

**Returns:**
float - The scale x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Gets or sets the scale x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The scale x. |


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

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Gets or sets the scale y.

**Returns:**
float - The scale y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Gets or sets the scale y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The scale y. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copies this instance to `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | The vector rasterization options. |

