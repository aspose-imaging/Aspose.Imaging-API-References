---
title: "PathMulticolorGradientBrush"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "封装一个带有渐变的 Aspose.Imaging.Brush 对象。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.brushes/pathmulticolorgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

封装一个带有渐变的 `Aspose.Imaging.Brush` 对象。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---) | 使用指定的点初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。 |
| [PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-) | 使用指定的点和包装模式初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。 |
| [PathMulticolorGradientBrush(Point[] pathPoints)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---) | 使用指定的点初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。 |
| [PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-) | 使用指定的点和包装模式初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。 |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-) | 使用指定的路径初始化 `PathMulticolorGradientBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | 获取或设置定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | 获取或设置定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
### PathMulticolorGradientBrush(PointF[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---}
```
public PathMulticolorGradientBrush(PointF[] pathPoints)
```


使用指定的点初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个由 [PointF](../../com.aspose.imaging/pointf) 结构组成的数组，表示构成路径顶点的点。 |

### PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] pathPoints, int wrapMode)
```


使用指定的点和包装模式初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pathPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个由 [PointF](../../com.aspose.imaging/pointf) 结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 [WrapMode](../../com.aspose.imaging/wrapmode)，指定使用此 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 绘制的填充如何平铺。 |

### PathMulticolorGradientBrush(Point[] pathPoints) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---}
```
public PathMulticolorGradientBrush(Point[] pathPoints)
```


使用指定的点初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | 一个由 [Point](../../com.aspose.imaging/point) 结构组成的数组，表示构成路径顶点的点。 |

### PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.imaging.Point---int-}
```
public PathMulticolorGradientBrush(Point[] pathPoints, int wrapMode)
```


使用指定的点和包装模式初始化 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pathPoints | [Point\[\]](../../com.aspose.imaging/point) | 一个由 [Point](../../com.aspose.imaging/point) 结构组成的数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 [WrapMode](../../com.aspose.imaging/wrapmode)，指定使用此 [PathMulticolorGradientBrush](../../com.aspose.imaging.brushes/pathmulticolorgradientbrush) 绘制的填充如何平铺。 |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


使用指定的路径初始化 `PathMulticolorGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 定义此 `PathMulticolorGradientBrush` 所填充区域的 `GraphicsPath`。 |

### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


获取或设置定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。

值：一个定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。

**Returns:**
[ColorBlend](../../com.aspose.imaging/colorblend)
### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.imaging.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


获取或设置定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。

值：一个定义多颜色线性渐变的 `com.aspose.imaging.ColorBlend`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.imaging/colorblend) |  |

