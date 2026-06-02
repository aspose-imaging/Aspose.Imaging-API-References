---
title: "LinearGradientBrush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "封装一个 Aspose.Imaging.Brush，具有线性渐变。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.brushes/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

封装一个 `Aspose.Imaging.Brush`，具有线性渐变。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-) | 初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
| [LinearGradientBrush()](#LinearGradientBrush--) | 使用默认参数初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | 获取定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | 设置定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [getLinearColors()](#getLinearColors--) | 获取渐变的起始颜色和结束颜色。 |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.imaging.Color---) | 设置渐变的起始颜色和结束颜色。 |
| [getStartColor()](#getStartColor--) | 获取起始渐变颜色。 |
| [setStartColor(Color value)](#setStartColor-com.aspose.imaging.Color-) | 设置起始渐变颜色。 |
| [getEndColor()](#getEndColor--) | 获取结束渐变颜色。 |
| [setEndColor(Color value)](#setEndColor-com.aspose.imaging.Color-) | 设置结束渐变颜色。 |
| [getBlend()](#getBlend--) | 获取一个 `Aspose.Imaging.Blend`，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | 设置一个 `Aspose.Imaging.Blend`，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 创建基于钟形曲线的渐变衰减。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 创建基于钟形曲线的渐变衰减。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。 |
### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 矩形。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |
| angle | float | 该角度。 |
| isAngleScalable | boolean | 如果设置为 `true` [is angle scalable]。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |
| angle | float | 该角度。 |
| isAngleScalable | boolean | 如果设置为 `true` [is angle scalable]。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.RectangleF-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 矩形。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |
| angle | float | 该角度。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.imaging.Rectangle-com.aspose.imaging.Color-com.aspose.imaging.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 矩形。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |
| angle | float | 该角度。 |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | 点1。 |
| point2 | [PointF](../../com.aspose.imaging/pointf) | 点2。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Color-com.aspose.imaging.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | 点1。 |
| point2 | [Point](../../com.aspose.imaging/point) | 点2。 |
| color1 | [Color](../../com.aspose.imaging/color) | 颜色1。 |
| color2 | [Color](../../com.aspose.imaging/color) | 颜色2。 |

### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


使用默认参数初始化 [LinearGradientBrush](../../com.aspose.imaging.brushes/lineargradientbrush) 类的新实例。起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


获取定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend) - A `com.aspose.imaging.ColorBlend` that defines a multicolor linear gradient.
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


设置定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) | 一个定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |

### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


获取渐变的起始颜色和结束颜色。

**Returns:**
com.aspose.imaging.Color[] - 一个包含两个 `Color` 结构的数组，表示渐变的起始颜色和结束颜色。
### setLinearColors(Color[] value) {#setLinearColors-com.aspose.imaging.Color---}
```
public void setLinearColors(Color[] value)
```


设置渐变的起始颜色和结束颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | 一个包含两个 `Color` 结构的数组，表示渐变的起始颜色和结束颜色。 |

### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


获取起始渐变颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - The starting gradient color.
### setStartColor(Color value) {#setStartColor-com.aspose.imaging.Color-}
```
public void setStartColor(Color value)
```


设置起始渐变颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 起始渐变颜色。 |

### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


获取结束渐变颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - The ending gradient color.
### setEndColor(Color value) {#setEndColor-com.aspose.imaging.Color-}
```
public void setEndColor(Color value)
```


设置结束渐变颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 结束渐变颜色。 |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


获取一个 `Aspose.Imaging.Blend`，它指定用于定义渐变自定义衰减的位置信息和因子。

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


设置一个 `Aspose.Imaging.Blend`，它指定用于定义渐变自定义衰减的位置信息和因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | 一个表示渐变自定义衰减的 `Aspose.Imaging.Blend`。 |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


创建基于钟形曲线的渐变衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定渐变的中心（起始颜色和结束颜色等比例混合的点）。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


创建基于钟形曲线的渐变衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定渐变的中心（仅由结束颜色组成的点）。 |
| 比例 | float | 一个介于 0 到 1 之间的值，指定颜色从 `focus` 衰减的速度。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定渐变的中心（仅由结束颜色组成的点）。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建具有中心颜色的线性渐变，并在两端线性衰减至单一颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 焦点 | float | 一个介于 0 到 1 之间的值，指定渐变的中心（仅由结束颜色组成的点）。 |
| 比例 | float | 一个介于 0 到 1 之间的值，指定颜色从起始颜色到 `focus`（结束颜色）的衰减速度。 |

