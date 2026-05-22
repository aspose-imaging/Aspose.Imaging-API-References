---
title: "TiffImage.AddFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。将指定帧无缝合并到图像中，扩展其内容和多样性。使用此方法提升图像构成和管理，使应用程序能够高效处理多帧图像。"
type: docs
weight: 130
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/addframe/
---
## TiffImage.AddFrame method

将指定帧无缝合并到图像中，扩展其内容和多样性。使用此方法提升图像的组合与管理，使应用能够高效处理多帧图像。

```csharp
public void AddFrame(TiffFrame frame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | TiffFrame | 要添加的帧。 |

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


