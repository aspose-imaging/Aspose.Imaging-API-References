---
title: "GraphicsRenderer"
second_title: "Aspose.Imaging for Java API 参考"
description: "该类直接在 java.awt.Graphic2D 上绘制 com.aspose.imaging.Image。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

该类直接在 java.awt.Graphic2D 上处理绘制 com.aspose.imaging.Image。使用此类可以避免在 VectorImage 情况下在 com.aspose.Imaging 缓冲区与 java.awt.BufferImage 之间进行多次分配和像素拷贝。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | 创建一个新的渲染。 |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | 创建一个新的渲染。 |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | 创建一个新的渲染。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | 在给定的 `graphics` 上执行渲染，缩放因子为 1.0。 |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | 在给定的 `graphics` 上执行渲染。 |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


创建一个新的渲染。默认情况下，渲染将使用 [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality)、[TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit) 进行处理，并使用白色背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 将在 java.awt.Graphics2D 上渲染的图像 |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


创建一个新的渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 将在 java.awt.Graphics2D 上渲染的图像 |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | 用于调整导出图像的导出选项。 |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


创建一个新的渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 将在 java.awt.Graphics2D 上渲染的图像 |
| backgroundColor | [Color](../../com.aspose.imaging/color) | 背景颜色。 |
| smoothingMode | int | 平滑模式。 |
| textRendering | int | 文本渲染模式。 |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


在给定的 `graphics` 上执行渲染，缩放因子为 1.0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | 用于绘图的 graphics。 |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


在给定的 `graphics` 上执行渲染。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | 用于绘图的 graphics。 |
| scaleFactor | float | 缩放因子。 |

