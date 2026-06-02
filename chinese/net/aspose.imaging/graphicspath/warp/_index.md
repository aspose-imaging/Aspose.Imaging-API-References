---
title: "GraphicsPath.Warp"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GraphicsPath 方法。将由矩形和平行四边形定义的扭曲变换应用于此 GraphicsPath。"
type: docs
weight: 200
url: /zh/net/aspose.imaging/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个 [`PointF`](../../pointf/) 结构数组，用于定义一个平行四边形，矩形 *srcRect* 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点推断得到。 |
| srcRect | RectangleF | 一个表示被转换为由 *destPoints* 定义的平行四边形的矩形的 [`RectangleF`](../../rectanglef/)。 |

### 另请参见

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个 [`PointF`](../../pointf/) 结构数组，用于定义一个平行四边形，矩形 *srcRect* 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点推断得到。 |
| srcRect | RectangleF | 一个表示被转换为由 *destPoints* 定义的平行四边形的矩形的 [`RectangleF`](../../rectanglef/)。 |
| matrix | Matrix | 一个指定要应用于路径的几何变换的 [`Matrix`](../../matrix/)。 |

### 另请参见

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个 [`PointF`](../../pointf/) 结构数组，用于定义一个平行四边形，矩形 *srcRect* 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点推断得到。 |
| srcRect | RectangleF | 一个表示被转换为由 *destPoints* 定义的平行四边形的矩形的 [`RectangleF`](../../rectanglef/)。 |
| matrix | Matrix | 一个指定要应用于路径的几何变换的 [`Matrix`](../../matrix/)。 |
| warpMode | WarpMode | 一个 [`WarpMode`](../../warpmode/) 枚举，指定此扭曲操作使用透视模式还是双线性模式。 |

### 另请参见

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个 [`PointF`](../../pointf/) 结构数组，用于定义一个平行四边形，矩形 *srcRect* 将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点推断得到。 |
| srcRect | RectangleF | 一个表示被转换为由 *destPoints* 定义的平行四边形的矩形的 [`RectangleF`](../../rectanglef/)。 |
| matrix | Matrix | 一个指定要应用于路径的几何变换的 [`Matrix`](../../matrix/)。 |
| warpMode | WarpMode | 一个 [`WarpMode`](../../warpmode/) 枚举，指定此扭曲操作使用透视模式还是双线性模式。 |
| flatness | Single | 一个介于 0 到 1 之间的值，指定结果路径的平坦程度。更多信息请参阅 [`Flatten`](../flatten/) 方法。 |

### 另请参见

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


