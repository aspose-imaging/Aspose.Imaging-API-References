---
title: "TiffFrame.TiffFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 构造函数。初始化 TiffFrame 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化帧像素和调色板数据的流。 |

### 另请参见

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化帧像素和调色板数据的流。 |
| 选项 | TiffOptions | 用于新创建帧的选项。 |

### 另请参见

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像并初始化帧像素和调色板数据的路径。 |

### 另请参见

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(string path, TiffOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像并初始化帧像素和调色板数据的路径。 |
| 选项 | TiffOptions | 用于新创建帧的选项。 |

### 另请参见

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(RasterImage image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |

## 示例

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

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| 选项 | TiffOptions | 用于新创建帧的选项。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

初始化 [`TiffFrame`](../) 类的新实例。

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 选项 | TiffOptions | 帧选项。 |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | Options 参数为 null。 |

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

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


