---
title: "PointExtensions"
second_title: "Aspose.Imaging for Java API 参考"
description: "包含 Point 和 PointF 结构的扩展方法。"
type: docs
weight: 20
url: /zh/java/com.aspose.imaging.extensions/pointextensions/
---
**Inheritance:**
java.lang.Object
```
public final class PointExtensions
```

包含针对 `Point` 和 `PointF` 结构的扩展方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [toPointsArray(Point[] points)](#toPointsArray-com.aspose.imaging.Point---) | 将 `Point` 数组转换为 `PointF` 数组。 |
| [toGdiPoints(PointF[] points)](#toGdiPoints-com.aspose.imaging.PointF---) | 将 `PointF` 数组转换为 `System.Drawing.PointF` 数组。 |
| [toGdiPoint(PointF point)](#toGdiPoint-com.aspose.imaging.PointF-) | 将 `PointF` 转换为 `System.Drawing.PointF`。 |
### toPointsArray(Point[] points) {#toPointsArray-com.aspose.imaging.Point---}
```
public static PointF[] toPointsArray(Point[] points)
```


将 `Point` 数组转换为 `PointF` 数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.imaging/point) | 要转换的 `Point` 数组。 |

**Returns:**
com.aspose.imaging.PointF[] - 已转换的 `PointF` 数组。
### toGdiPoints(PointF[] points) {#toGdiPoints-com.aspose.imaging.PointF---}
```
public static Point2D.Float[] toGdiPoints(PointF[] points)
```


将 `PointF` 数组转换为 `System.Drawing.PointF` 数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | 要转换的 `PointF` 数组。 |

**Returns:**
java.awt.geom.Point2D.Float[] - 已转换的 `System.Drawing.PointF` 数组。
### toGdiPoint(PointF point) {#toGdiPoint-com.aspose.imaging.PointF-}
```
public static Point2D.Float toGdiPoint(PointF point)
```


将 `PointF` 转换为 `System.Drawing.PointF`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | 要转换的 `PointF`。 |

**Returns:**
java.awt.geom.Point2D.Float - 已转换的 `System.Drawing.PointF`。
