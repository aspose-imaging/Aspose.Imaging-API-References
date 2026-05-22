---
title: "TiffOptions.YCbCrSubsampling"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffOptions 属性。获取或设置 YCbCr 颜色空间的子采样因子"
type: docs
weight: 700
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling/
---
## TiffOptions.YCbCrSubsampling property

获取或设置 YCbCr 颜色空间的子采样因子。

```csharp
public ushort[] YCbCrSubsampling { get; set; }
```

### Property Value

YCbCr 颜色空间的子采样因子。

### 异常

| 异常 | 条件 |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | 字段长度无效。YCbCrSubsampling 字段必须包含两个值。 |
| ArgumentNullException | 值 |

## 示例

此示例展示如何使用各种选项将光栅图像保存为 TIFF 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// 为每个颜色分量设置 8 位。
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// 设置大端字节序（Motorola）
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// 设置 LZW 压缩。
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// 允许减小连续色调图像的大小。
// 当前此字段仅在 LZW 编码下使用，因为 LZW 可能是唯一受益于预测步骤的 TIFF 编码方案
// 显著受益于预测步骤。
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// 设置 RGB 颜色模型。
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// 对于 YCbCr，您可以使用以下选项之一：
// YCbCrSubSampling 字段   JPEG 采样因子
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// 所有颜色分量将存储在单个平面中。
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// 创建一个 100x100 像素的 TIFF 帧。
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 用蓝黄渐变填充整幅图像。
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

### 另请参见

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


