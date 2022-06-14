---
title: LinearGradientBrush
second_title: Aspose.Imaging for .NET API 参考
description: 使用默认参数初始化LinearGradientBrushaspose.imaging.brushes/lineargradientbrush类的新实例 起始颜色为黑色结束颜色为白色角度为 45 度矩形位于 00大小为 11
type: docs
weight: 10
url: /zh/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

使用默认参数初始化[`LinearGradientBrush`](../../lineargradientbrush)类的新实例。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

```csharp
public LinearGradientBrush()
```

### 也可以看看

* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

使用指定的点和颜色初始化[`LinearGradientBrush`](../../lineargradientbrush)类的新实例。

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point | A[`Point`](../../../aspose.imaging/point)结构，表示线性的起点坡度。 |
| point2 | Point | A[`Point`](../../../aspose.imaging/point)结构，表示线性渐变的端点。 |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示线性渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示线性渐变的结束颜色。 |

### 例子

以下示例说明如何创建现有帧的灰度副本并将其添加到 TIFF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 创建一个永久的，不是临时的文件 source.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
        // 从图像左上角到右下角的线性渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // 用线性渐变画笔填充活动帧。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

        // 灰度选项
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

        // 创建活动帧的灰度副本。
        // 像素数据被保留，但转换为所需的格式。
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

        // 将新创建的帧添加到 TIFF 图像中。
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### 也可以看看

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

使用指定的点和颜色初始化[`LinearGradientBrush`](../../lineargradientbrush)类的新实例。

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| point1 | PointF | A[`PointF`](../../../aspose.imaging/pointf)结构，表示线性的起点坡度。 |
| point2 | PointF | A[`PointF`](../../../aspose.imaging/pointf)结构，表示线性渐变的端点。 |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示线性渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示线性渐变的结束颜色。 |

### 也可以看看

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

基于矩形、开始和结束颜色以及一个方向角。

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef)结构，指定线性渐变的边界. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的结束颜色。 |
| angle | Single | 渐变方向线的角度，以从 x 轴顺时针方向测量的度数为单位。 |

### 也可以看看

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

基于矩形、开始和结束颜色以及一个方向角。

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef)结构，指定线性渐变的边界. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的结束颜色。 |
| angle | Single | 渐变方向线的角度，以从 x 轴顺时针方向测量的度数为单位。 |

### 也可以看看

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

基于矩形、开始和结束颜色以及一个方向角。

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef)结构，指定线性渐变的边界. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的结束颜色。 |
| angle | Single | 渐变方向线的角度，以从 x 轴顺时针方向测量的度数为单位。 |
| isAngleScalable | Boolean | 如果设置为` true` 在使用此:::R5 进行转换期间角度会发生变化:T:Aspose.Imaging.Brushes.LinearGradientBrush:::。 |

### 也可以看看

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

基于矩形、开始和结束颜色以及一个方向角。

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef)结构，指定线性渐变的边界. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的起始颜色。 |
| color2 | Color | A[`Color`](../../../aspose.imaging/color)结构，表示渐变的结束颜色。 |
| angle | Single | 渐变方向线的角度，以从 x 轴顺时针方向测量的度数为单位。 |
| isAngleScalable | Boolean | 如果设置为` true` 在使用此:::R5 进行转换期间角度会发生变化:T:Aspose.Imaging.Brushes.LinearGradientBrush:::。 |

### 也可以看看

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* 命名空间 [Aspose.Imaging.Brushes](../../lineargradientbrush)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
