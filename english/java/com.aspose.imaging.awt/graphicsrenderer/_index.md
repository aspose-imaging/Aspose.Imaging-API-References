---
title: GraphicsRenderer
second_title: Aspose.Imaging for Java API Reference
description: The class handles drawing com.aspose.imaging.Image directly upon the java.awt.Graphic2D.
type: docs
weight: 10
url: /java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

The class handles drawing com.aspose.imaging.Image directly upon the java.awt.Graphic2D. Using this class it is possible to avoid multiple allocations and coping the pixels between com.aspose.Imaging buffers into java.awt.BufferImage in case of VectorImage.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Creates a new render. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Creates a new render. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Creates a new render. |
## Methods

| Method | Description |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Performs the rendering on the given `graphics` with scale factor 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Performs the rendering on the given `graphics`. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Creates a new render. By default render will be proceed using the [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit), and with a white background color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image which will be rendered on the java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Creates a new render.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image which will be rendered on the java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | The export options for adjusting the exporting image. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Creates a new render.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The image which will be rendered on the java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | The background color. |
| smoothingMode | int | The smoothing mode. |
| textRendering | int | The text rendering mode. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Performs the rendering on the given `graphics` with scale factor 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | The graphics for drawing. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Performs the rendering on the given `graphics`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | The graphics for drawing. |
| scaleFactor | float | The scale factor. |

