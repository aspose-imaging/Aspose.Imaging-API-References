---
title: "DjvuImage.Grayscale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。灰度转换将图像转换为黑白表示，其中每个像素的强度由介于黑到白之间的单一数值表示。此过程去除颜色信息，产生单色图像。灰度图像常用于颜色不必要或需要简洁的应用场景，例如文档扫描、打印以及某些图像分析。"
type: docs
weight: 250
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/grayscale/
---
## DjvuImage.Grayscale method

灰度转换将图像转换为黑白表示，每个像素的强度由介于黑到白之间的单一数值表示。此过程去除颜色信息，生成单色图像。灰度图像常用于颜色非必需或追求简洁的场景，如文档扫描、打印以及某些图像分析。

```csharp
public override void Grayscale()
```

## 示例

以下示例将彩色 DJVU 图像转换为其灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    djvuImage.Grayscale();
    djvuImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


