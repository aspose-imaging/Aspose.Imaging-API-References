---
title: "Graphics.DrawImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。使用原始物理尺寸在坐标对指定的位置绘制指定的图像。"
type: docs
weight: 230
url: /zh/net/aspose.imaging/graphics/drawimage/
---
## DrawImage(Image, int, int) {#drawimage_20}

在由坐标对指定的位置绘制指定的图像，使用其原始物理尺寸。

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| x | Int32 | 绘制图像左上角的 x 坐标。 |
| y | Int32 | 绘制图像左上角的 y 坐标。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 结构，指定已绘制图像的位置和大小。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| x | Int32 | 绘制图像左上角的 x 坐标。 |
| y | Int32 | 绘制图像左上角的 y 坐标。 |
| 宽度 | Int32 | 已绘制图像的宽度。 |
| 高度 | Int32 | 已绘制图像的高度。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, PointF) {#drawimage_1}

在指定的位置绘制指定的[`Image`](../image/)，使用其原始物理尺寸。

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| point | PointF | [`PointF`](../../pointf/) 结构，表示已绘制图像的左上角。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

在指定的位置绘制指定的[`Image`](../image/)，使用其原始物理尺寸。

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| x | 单精度 | 绘制图像左上角的 x 坐标。 |
| y | 单精度 | 绘制图像左上角的 y 坐标。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，指定已绘制图像的位置和大小。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectDestination | Rectangle | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectDestination | RectangleF | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectDestination | Rectangle | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |
| imageAttributes | ImageAttributes | 图像属性。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectDestination | RectangleF | 用于绘制的目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |
| imageAttributes | ImageAttributes | 图像属性。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectSource | Rectangle | 源矩形。 |
| rectDestination | Rectangle | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectSource | RectangleF | 源矩形。 |
| rectDestination | RectangleF | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectSource | Rectangle | 源矩形。 |
| rectDestination | Rectangle | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 图形单位。 |
| imageAttributes | ImageAttributes | 图像属性。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| rectSource | RectangleF | 源矩形。 |
| rectDestination | RectangleF | 目标矩形。 |
| graphicsUnit | GraphicsUnit | 要使用的图形单位。 |
| imageAttributes | ImageAttributes | 要使用的图像属性。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | Point[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### 另请参见

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | Point[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | Rectangle | 源矩形。 |

### 另请参见

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | Point[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | Rectangle | 源矩形。 |
| srcUnit | GraphicsUnit | 度量单位。 |

### 另请参见

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | Point[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | Rectangle | 源矩形。 |
| srcUnit | GraphicsUnit | 度量单位。 |
| imageAttributes | ImageAttributes | 图像属性。 |

### 另请参见

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, PointF[]) {#drawimage_2}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | PointF[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | image |

### 另请参见

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | PointF[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | RectangleF | 源矩形。 |

### 另请参见

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | PointF[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | RectangleF | 源矩形。 |
| srcUnit | GraphicsUnit | 度量单位。 |

### 另请参见

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

在指定位置并使用指定尺寸绘制指定 *image* 的指定部分。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | 图像 | 要绘制的图像。 |
| destPoints | PointF[] | 由三个 PointF 结构组成的数组，用于定义平行四边形。 |
| srcRect | RectangleF | 源矩形。 |
| srcUnit | GraphicsUnit | 度量单位。 |
| imageAttributes | ImageAttributes | 图像属性。 |

### 另请参见

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, float, float, float, float) {#drawimage_23}

在指定的位置并使用指定的大小绘制指定的[`Image`](../image/)。

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| x | 单精度 | 绘制图像左上角的 x 坐标。 |
| y | 单精度 | 绘制图像左上角的 y 坐标。 |
| 宽度 | 单精度 | 已绘制图像的宽度。 |
| 高度 | 单精度 | 已绘制图像的高度。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Image, Point) {#drawimage}

在指定的位置绘制指定的[`Image`](../image/)，使用其原始物理尺寸。

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceImage | 图像 | 用于绘制的图像。 |
| point | Point | [`Point`](../../point/) 结构，表示绘制图像左上角的位置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* 为 null。 |

### 另请参见

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


