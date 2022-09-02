---
title: TiffOptions
second_title: Aspose.Imaging for .NET API 参考
description: 初始化TiffOptionsaspose.imaging.imageoptions/tiffoptions类.
type: docs
weight: 10
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

初始化[`TiffOptions`](../../tiffoptions)类.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | 预期的 tiff 文件格式。 |
| byteOrder | TiffByteOrder | 要使用的 tiff 文件格式字节顺序。 |

### 也可以看看

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../tiffoptions)
* 部件 [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

初始化[`TiffOptions`](../../tiffoptions)班级。默认情况下使用小端约定。

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | 预期的 tiff 文件格式。 |

### 例子

以下示例显示如何创建现有帧的灰度副本并将其添加到 TIFF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 创建一个永久的，不是临时的文件源。
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

    // 使用线性渐变画笔填充活动帧。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    //灰度选项
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // 创建活动帧的灰度副本。
    // 像素数据被保留，但转换为所需的格式。
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // 将新创建的帧添加到 TIFF 图像。
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

此示例说明如何使用各种选项将光栅图像保存为 TIFF 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// 设置大端字节序（摩托罗拉）
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// 设置 LZW 压缩。
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// 允许减小连续色调图像的大小。
// 目前该字段仅用于 LZW 编码，因为 LZW 可能是唯一的 TIFF 编码方案
// 这显着受益于预测步骤。
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// 设置 RGB 颜色模型。
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// 对于 YCbCr，您可以使用以下选项之一：
// YCbCrSubSampling 字段 JPEG 采样因子
// ----------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(默认值) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// 所有颜色分量都将存储在单个平面内。
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 创建一个 100x100 像素的 TIFF 帧。
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 用蓝黄色渐变填充整个图像。
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### 也可以看看

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../tiffoptions)
* 部件 [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

初始化[`TiffOptions`](../../tiffoptions)类.

```csharp
public TiffOptions(TiffOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | TiffOptions | 要复制的选项。 |

### 也可以看看

* class [TiffOptions](../../tiffoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../tiffoptions)
* 部件 [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

初始化[`TiffOptions`](../../tiffoptions)类.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tags | TiffDataType[] | 用于初始化选项的标签。 |

### 也可以看看

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../tiffoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
