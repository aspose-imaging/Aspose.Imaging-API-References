---
title: "TiffOptions.BitsPerSample"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffOptions 属性。获取或设置每个样本的位数。"
type: docs
weight: 50
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/bitspersample/
---
## TiffOptions.BitsPerSample property

获取或设置每个样本的位数。

```csharp
public ushort[] BitsPerSample { get; set; }
```

### Property Value

每个样本的位数值。

## 备注

设置此值时请记住，它还会将 SamplesPerPixel 值设置为数组长度。这两个属性紧密耦合，因此只能一起设置。

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

以下示例展示了如何从单个光栅图像组合成多页 TIFF。

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // 这是用于在各帧上绘制文本的 Font 和 Brush。
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // 创建 5 帧
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // 创建 PNG 图像并在其上绘制页码。
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // 基于 PNG 图像创建帧。
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // 将帧添加到 TIFF 图像中。
        tiffImage.AddFrame(frame);
    }

    // 该图像使用单个默认帧创建。让我们将其移除。
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // 如果不将帧添加到其他 TiffImage，请记得释放该帧。
    activeFrame.Dispose();

    tiffImage.Save();
}
```

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

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


