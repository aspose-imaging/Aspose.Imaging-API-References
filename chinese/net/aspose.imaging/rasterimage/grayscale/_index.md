---
title: "RasterImage.Grayscale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。将图像转换为灰度表示"
type: docs
weight: 380
url: /zh/net/aspose.imaging/rasterimage/grayscale/
---
## RasterImage.Grayscale method

将图像转换为灰度表示

```csharp
public virtual void Grayscale()
```

## 示例

以下示例将彩色光栅图像转换为灰度表示。灰度图像仅由灰色阴影组成，只携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


