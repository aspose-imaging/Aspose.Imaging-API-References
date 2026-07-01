---
title: "PathGradientBrush"
second_title: "Aspose.Imaging for Java API 参考"
description: "封装一个 Aspose.Imaging.Brush 对象并带有渐变。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.brushes/pathgradientbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush), [com.aspose.imaging.brushes.PathGradientBrushBase](../../com.aspose.imaging.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

封装一个 `Aspose.Imaging.Brush` 对象并带有渐变。此类不可被继承。

中心颜色默认是白色。用户可以在以后随时更改此值。

环绕颜色数组默认使用包含白色的单个元素进行初始化。环绕颜色以后可以更改，但在设置环绕颜色时至少需要一个元素。

有关其初始化的更多细节，请参阅 `Blend`。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.imaging.PointF---) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.PointF---int-) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.imaging.Point---) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.imaging.Point---int-) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.imaging.GraphicsPath-) | 使用指定的路径初始化 `PathGradientBrush` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInterpolationColors()](#getInterpolationColors--) | 获取定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.imaging.ColorBlend-) | 设置定义多色线性渐变的 `com.aspose.imaging.ColorBlend`。 |
| [getCenterColor()](#getCenterColor--) | 获取路径渐变中心的颜色。 |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.imaging.Color-) | 设置路径渐变中心的颜色。 |
| [getSurroundColors()](#getSurroundColors--) | 获取与此 `PathGradientBrush` 填充的路径中的点对应的颜色数组。 |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.imaging.Color---) | 设置与此 `PathGradientBrush` 填充的路径中的点对应的颜色数组。 |
| [getBlend()](#getBlend--) | 获取一个 `Aspose.Imaging.Blend`，它指定了定义渐变自定义衰减的位置信息和因子。 |
| [setBlend(Blend value)](#setBlend-com.aspose.imaging.Blend-) | 设置一个 `Aspose.Imaging.Blend`，它指定了定义渐变自定义衰减的位置信息和因子。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | 创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | 创建一个渐变画刷，使颜色从路径中心向外变化至路径边界。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 创建一个渐变，具有中心颜色并线性衰减到一种环绕颜色。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 创建一个渐变，具有中心颜色并线性衰减到每种环绕颜色。 |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.imaging.PointF---}
```
public PathGradientBrush(PointF[] points)
```


使用指定的点初始化 `PathGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `Aspose.Imaging.PointF` 结构数组，表示构成路径顶点的点。 |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 一个 `Aspose.Imaging.PointF` 结构数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 `Aspose.Imaging.WrapMode`，指定使用此 `PathGradientBrush` 绘制的填充如何平铺。 |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.imaging.Point---}
```
public PathGradientBrush(Point[] points)
```


使用指定的点初始化 `PathGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | 一个 `Aspose.Imaging.Point` 结构数组，表示构成路径顶点的点。 |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.imaging.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | 一个 `Aspose.Imaging.Point` 结构数组，表示构成路径顶点的点。 |
| wrapMode | int | 一个 `Aspose.Imaging.WrapMode`，指定使用此 `PathGradientBrush` 绘制的填充如何平铺。 |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.imaging.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


使用指定的路径初始化 `PathGradientBrush` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 定义此 `PathGradientBrush` 填充区域的 `GraphicsPath`。 |

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

### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


获取路径渐变中心的颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - A `com.aspose.imaging.Color` that represents the color at the center of the path gradient.
### setCenterColor(Color value) {#setCenterColor-com.aspose.imaging.Color-}
```
public void setCenterColor(Color value)
```


设置路径渐变中心的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 一个表示路径渐变中心颜色的 `com.aspose.imaging.Color`。 |

### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


获取与此 `PathGradientBrush` 填充的路径中的点对应的颜色数组。

**Returns:**
com.aspose.imaging.Color[] - 一个 `com.aspose.imaging.Color` 结构数组，表示与此 `PathGradientBrush` 填充的路径中每个点关联的颜色。
### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.imaging.Color---}
```
public void setSurroundColors(Color[] value)
```


设置与此 `PathGradientBrush` 填充的路径中的点对应的颜色数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) | 一个 `com.aspose.imaging.Color` 结构数组，表示与此 `PathGradientBrush` 填充的路径中每个点关联的颜色。 |

### getBlend() {#getBlend--}
```
public Blend getBlend()
```


获取一个 `Aspose.Imaging.Blend`，它指定了定义渐变自定义衰减的位置信息和因子。

**Returns:**
[Blend](../../com.aspose.imaging/blend) - A `Aspose.Imaging.Blend` that represents a custom falloff for the gradient.
### setBlend(Blend value) {#setBlend-com.aspose.imaging.Blend-}
```
public void setBlend(Blend value)
```


设置一个 `Aspose.Imaging.Blend`，它指定了定义渐变自定义衰减的位置信息和因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.imaging/blend) | 一个表示渐变自定义衰减的 `Aspose.Imaging.Blend`。 |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


创建一个渐变画刷，使颜色从路径中心向路径边界逐渐变化。颜色之间的过渡基于钟形曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| focus | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


创建一个渐变画刷，使颜色从路径中心向路径边界逐渐变化。颜色之间的过渡基于钟形曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| focus | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| scale | float | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


创建一个渐变，具有中心颜色并线性衰减到一种环绕颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| focus | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


创建一个渐变，具有中心颜色并线性衰减到每种环绕颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| focus | float | 一个介于 0 到 1 之间的值，指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| scale | float | 一个介于 0 到 1 之间的值，指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

