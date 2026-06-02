---
title: "LinearGradientBrush.LinearGradientBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "LinearGradientBrush 构造函数。初始化 LinearGradientBrush 类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 矩形。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |
| 角度 | 单精度 | 角度。 |
| isAngleScalable | Boolean | 如果设置为 `true` [可缩放角度]。 |

### 另请参见

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 矩形。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |
| 角度 | 单精度 | 角度。 |
| isAngleScalable | Boolean | 如果设置为 `true` [可缩放角度]。 |

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | RectangleF | 矩形。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |
| 角度 | 单精度 | 角度。 |

### 另请参见

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 矩形。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |
| 角度 | 单精度 | 角度。 |

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | PointF | 该 point1。 |
| point2 | PointF | 该 point2。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |

### 另请参见

* struct [PointF](../../../aspose.imaging/pointf/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

初始化 [`LinearGradientBrush`](../) 类的新实例。

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | Point | 该 point1。 |
| point2 | Point | 该 point2。 |
| color1 | 颜色 | color1。 |
| color2 | 颜色 | color2。 |

## 示例

以下示例展示了如何创建现有帧的灰度副本并将其添加到 TIFF 图像中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 创建永久的，而非临时的文件源。
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // 图像左上角到右下角的线性渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // 使用线性渐变画笔填充活动帧。
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

### 另请参见

* struct [Point](../../../aspose.imaging/point/)
* struct [Color](../../../aspose.imaging/color/)
* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)

---

## LinearGradientBrush() {#constructor}

使用默认参数初始化 [`LinearGradientBrush`](../) 类的新实例。起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

```csharp
public LinearGradientBrush()
```

### 另请参见

* class [LinearGradientBrush](../)
* namespace [Aspose.Imaging.Brushes](../../lineargradientbrush/)
* assembly [Aspose.Imaging](../../../)


