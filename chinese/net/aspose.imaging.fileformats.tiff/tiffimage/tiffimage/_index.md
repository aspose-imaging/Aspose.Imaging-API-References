---
title: "TiffImage.TiffImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 构造函数。初始化一个新的 TiffImage 类对象，指定 frame 参数。此构造函数有助于创建 TiffImage 实例，使开发者能够指定要加载或处理的帧，从而简化应用程序中 Tiff 图像处理任务。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

初始化一个新的 [`TiffImage`](../) 类对象，指定 frame 参数。此构造函数有助于创建 TiffImage 实例，使开发者能够指定要加载或处理的帧，简化应用程序中 Tiff 图像处理任务。

```csharp
public TiffImage(TiffFrame frame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | TiffFrame | 用于初始化图像的 tiff 帧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | Tiff *frame* 不能为空。 |

## 示例

此示例展示了如何从头创建 TIFF 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// 为每个颜色分量设置 8 位。
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// 设置大端字节序（Motorola）
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// 设置 LZW 压缩。
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// 设置 RGB 颜色模型。
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// 所有颜色分量将存储在单个平面中。
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 创建一个 100x100 像素的 TIFF 帧。
// 请注意，如果帧已包含在 TiffImage 中，则无需显式释放该帧。
// 当容器被释放时，所有帧将自动被释放。
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// 用蓝黄渐变填充整个帧。
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// 创建一个 TIFF 图像。
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

### 另请参见

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

创建一个新的 [`TiffImage`](../) 类实例，提供帧列表作为参数。此构造函数使得能够使用多个帧初始化 TiffImage 对象，促进在软件应用中高效处理 TIFF 图像序列。

```csharp
public TiffImage(TiffFrame[] frames)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | TiffFrame[] | 这些帧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 帧 |

## 示例

此示例展示了如何创建包含 2 帧的 TIFF 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 第一帧的选项
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// 设置大端字节序（Motorola）
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// 设置 LZW 压缩。
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// 设置 RGB 颜色模型。
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// 所有颜色分量将存储在单个平面中。
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 创建第一帧 100x100 像素的 TIFF。
// 请注意，如果帧已包含在 TiffImage 中，则无需显式释放帧。
// 当容器被释放时，所有帧将自动被释放。
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// 用蓝黄渐变填充第一帧。
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// 第一帧的选项
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 为黑白图像设置每像素 1 位。
createOptions2.BitsPerSample = new ushort[] { 1 };

// 设置小端字节序（Intel）
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// 设置 CCITT Group 3 传真压缩。
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// 设置黑白颜色模型，其中 0 为黑色，1 为白色。
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// 创建第二帧 200x200 像素的 TIFF。
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// 用蓝黄渐变填充第二帧。
// 由于帧的相应设置，它将自动转换为黑白格式。
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// 创建一个 TIFF 图像。
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### 另请参见

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


