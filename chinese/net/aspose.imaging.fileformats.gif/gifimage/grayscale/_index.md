---
title: "GifImage.Grayscale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。将图像转换为灰度表示会通过去除颜色信息而保留亮度，将彩色图像转换为灰度版本。此过程将图像简化为灰色阴影，使其适用于打印、文档处理和灰度分析等各种应用。"
type: docs
weight: 320
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/grayscale/
---
## GifImage.Grayscale method

将图像转换为灰度表示会通过去除颜色信息而保留亮度，将彩色图像转换为灰度版本。此过程将图像简化为灰度阴影，适用于打印、文档处理和灰度分析等各种应用。

```csharp
public override void Grayscale()
```

## 示例

以下示例将彩色 GIF 图像转换为其灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    gifImage.Grayscale();
    gifImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


