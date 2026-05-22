---
title: "GifImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。使用指定的矩形区域裁剪图像。此操作会移除图像的外部部分，仅保留矩形定义的选定区域"
type: docs
weight: 280
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/crop/
---
## GifImage.Crop method

使用指定的矩形区域裁剪图像。此操作去除图像的外部部分，仅保留矩形定义的选定区域。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

## 示例

以下示例裁剪 GIF 图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(gifImage.Width / 4, gifImage.Height / 4, gifImage.Width / 2, gifImage.Height / 2);
    gifImage.Crop(area);

    // 将裁剪后的图像保存为 PNG
    gifImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


