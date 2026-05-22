---
title: "TiffImage.ActiveFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 属性。无缝管理活动帧，促进在指定上下文中的动态导航和操作。使您的应用程序能够高效地与多媒体内容交互，提升用户参与度和生产力。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/activeframe/
---
## TiffImage.ActiveFrame property

无缝管理活动帧，促进在指定上下文中的动态导航和操作。让您的应用程序能够高效地与多媒体内容交互，提升用户参与度和生产力。

```csharp
public TiffFrame ActiveFrame { get; set; }
```

### Property Value

活动帧。

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

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


