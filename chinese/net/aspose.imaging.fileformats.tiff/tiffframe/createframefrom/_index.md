---
title: "TiffFrame.CreateFrameFrom"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 方法。从指定的 tiffFrame 创建帧，使用指定的选项。像素数据得以保留，但会转换为所需的格式"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/createframefrom/
---
## TiffFrame.CreateFrameFrom method

使用指定的 *options* 从指定的 *tiffFrame* 创建帧。像素数据被保留，但会转换为所需的格式。

```csharp
public static TiffFrame CreateFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tiffFrame | TiffFrame | 要从其创建的 tiff 帧。 |
| 选项 | TiffOptions | 要使用的新选项。 |

### 返回值

新创建的帧。

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

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


