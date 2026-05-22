---
title: "TiffImage.RemoveFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。轻松删除图像序列中由索引标识的帧，简化应用程序内的帧管理。集成此功能可提升帧操作的效率和精度，促进图像内容的无缝组织与呈现。"
type: docs
weight: 300
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/removeframe/
---
## RemoveFrame(int) {#removeframe}

轻松地根据索引删除图像序列中的帧，简化应用程序中的帧管理。集成此功能可提升帧操作的效率和精度，促进图像内容的无缝组织和呈现。

```csharp
public TiffFrame RemoveFrame(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 要删除的帧的索引。 |

### 返回值

已删除的帧。

## 备注

注意：如果您不打算将该帧添加到其他 TiffImage，请务必释放（Dispose）该帧。

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

---

## RemoveFrame(TiffFrame) {#removeframe_1}

高效地从图像序列中移除指定帧，帮助简化应用程序中的帧管理。集成此功能可提升帧操作的精度和灵活性，确保图像内容的无缝组织和呈现。

```csharp
public void RemoveFrame(TiffFrame frame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 帧 | TiffFrame | 要删除的帧。 |

## 备注

注意：如果您不打算将该帧添加到其他 TiffImage，请务必释放（Dispose）该帧。

### 另请参见

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


