---
title: "PathGradientBrushBase"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示具有基础路径渐变功能的 Brush。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.brushes/pathgradientbrushbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush), [com.aspose.imaging.brushes.TransformBrush](../../com.aspose.imaging.brushes/transformbrush)
```
public abstract class PathGradientBrushBase extends TransformBrush
```

表示具有基路径渐变功能的 `Brush`。

请注意，在创建 `PathGradientBrushBase` 类时，至少应使用 2 个点进行初始化。内部创建的路径始终是闭合图形，最后一点连接到第一点。该形状使用此 `PathGradientBrushBase` 填充。GDI+ 实现会在传入空数组或点集合具有相同坐标时抛出 `OutOfMemoryError`。当点数组少于 2 个点时，`PathGradientBrushBase` 会抛出异常，`ArgumentException` 将在点数组不可接受时被抛出，而不是 `OutOfMemoryError`。默认情况下，中心点根据传入点的质心计算。用户可以稍后更改此点。焦点比例默认是空点 (0.0, 0.0)。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPathPoints()](#getPathPoints--) | 获取此画笔构建所依据的路径点。 |
| [getGraphicsPath()](#getGraphicsPath--) | 获取此画笔构建所依据的图形路径。 |
| [getCenterPoint()](#getCenterPoint--) | 获取或设置路径渐变的中心点。 |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.imaging.PointF-) | 获取或设置路径渐变的中心点。 |
| [getFocusScales()](#getFocusScales--) | 获取渐变衰减的焦点。 |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.imaging.PointF-) | 获取或设置渐变衰减的焦点。 |
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


获取此画笔构建所依据的路径点。

**Returns:**
com.aspose.imaging.PointF[] - 路径点。
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


获取此画笔构建所依据的图形路径。

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The graphics path.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


获取或设置路径渐变的中心点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the center point of the path gradient.
### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.imaging.PointF-}
```
public void setCenterPoint(PointF value)
```


获取或设置路径渐变的中心点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | 一个 `Aspose.Imaging.PointF`，表示路径渐变的中心点。 |

### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


获取渐变衰减的焦点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `Aspose.Imaging.PointF` that represents the focus point for the gradient falloff.
### setFocusScales(PointF value) {#setFocusScales-com.aspose.imaging.PointF-}
```
public void setFocusScales(PointF value)
```


获取或设置渐变衰减的焦点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) | 一个 `Aspose.Imaging.PointF`，表示渐变衰减的焦点。 |

