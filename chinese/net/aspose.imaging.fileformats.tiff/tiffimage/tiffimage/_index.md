---
title: TiffImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化TiffImageaspose.imaging.fileformats.tiff/tiffimage类的新实例
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

初始化[`TiffImage`](../../tiffimage)类的新实例。

```csharp
public TiffImage(TiffFrame frame)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| frame | TiffFrame | 用于初始化图像的 tiff 帧。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | Tiff 帧不能为空。;frame |

### 例子

此示例说明如何从头开始创建 TIFF 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// 为每个颜色分量设置 8 位。
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

    // 设置大端字节序（摩托罗拉）
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

    // 设置 LZW 压缩。
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

    // 设置 RGB 颜色模型.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

    // 所有颜色分量都将存储在一个平面内。
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

    // 创建一个 100x100 像素的 TIFF 帧。
    // 请注意，如果帧包含在 TiffImage.
 中，则不必显式处理帧
// 当容器被释放时，所有的帧都会被自动释放。
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
    // 用蓝黄色渐变填充整个帧。
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

### 也可以看看

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

初始化[`TiffImage`](../../tiffimage)类的新实例。

```csharp
public TiffImage(TiffFrame[] frames)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| frames | TiffFrame[] | 帧。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | frames |

### 例子

此示例显示如何使用 2 创建 TIFF 图像帧并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

       // 第一帧的选项
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

    // 设置大端字节序（摩托罗拉）
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

    // 设置 LZW 压缩。
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

    // 设置 RGB 颜色模型.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

    // 所有颜色分量都将存储在一个平面内。
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

    // 创建第一个 100x100 像素的 TIFF 帧。
    // 请注意，如果帧包含在 TiffImage.
 中，则不必显式处理帧
// 当容器被释放时，所有的帧都会被自动释放。
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// 用蓝黄色渐变填充第一帧。
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

    // 设置 Little Endian 字节顺序 (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// 设置 CCITT Group 3 传真压缩。
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

    // 设置 B/W 颜色模型，其中 0 为黑色，1 为白色。
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

    // 创建第二个 200x200px 的 TIFF 帧。
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

    // 用蓝黄色渐变填充第二帧。
    // 由于frame的相应设置，会自动转换为B/W格式。
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

    // 创建一个 TIFF 图像。
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### 也可以看看

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
