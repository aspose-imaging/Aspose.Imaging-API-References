---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示一种使用多种颜色和相应位置定义的线性渐变画刷。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.brushes/linearmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.LinearGradientBrushBase](../../com.aspose.imaging.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

表示一种使用多种颜色和相应位置定义的线性渐变 `Brush`。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | 使用默认参数初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 使用指定的点初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 使用指定的点初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-) | 使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-) | 使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-) | 使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-) | 使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | 获取定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | 设置定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


使用默认参数初始化 `LinearMulticolorGradientBrush` 类的新实例。起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


使用指定的点初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` 结构表示线性渐变的起始点。 |
| point2 | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` 结构表示线性渐变的终止点。 |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


使用指定的点初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | `Aspose.Imaging.PointF` 结构表示线性渐变的起始点。 |
| point2 | [PointF](../../com.aspose.imaging/pointf) | `Aspose.Imaging.PointF` 结构表示线性渐变的终止点。 |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Aspose.Imaging.RectangleF` 结构指定线性渐变的边界。 |
| angle | float | 角度以度为单位，顺时针从 x 轴测量，表示渐变方向线的角度。 |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `Aspose.Imaging.RectangleF` 结构指定线性渐变的边界。 |
| angle | float | 角度以度为单位，顺时针从 x 轴测量，表示渐变方向线的角度。 |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `Aspose.Imaging.RectangleF` 结构指定线性渐变的边界。 |
| angle | float | 角度以度为单位，顺时针从 x 轴测量，表示渐变方向线的角度。 |
| isAngleScalable | boolean | 如果设置为 `true`，则在使用此 `LinearMulticolorGradientBrush` 进行变换时会更改角度。 |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.imaging.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


使用矩形和方向角度初始化 `LinearMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `Aspose.Imaging.RectangleF` 结构指定线性渐变的边界。 |
| angle | float | 角度以度为单位，顺时针从 x 轴测量，表示渐变方向线的角度。 |
| isAngleScalable | boolean | 如果设置为 `true`，则在使用此 `LinearMulticolorGradientBrush` 进行变换时会更改角度。 |

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

