---
title: "GifImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。使用预定义阈值对图像进行二值化，将灰度或彩色图像转换为二进制图像，依据像素强度值是否超过指定阈值将每个像素分类为黑或白。"
type: docs
weight: 250
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/binarizefixed/
---
## GifImage.BinarizeFixed method

使用预定义阈值对图像进行二值化，将灰度或彩色图像转换为二值图像，根据像素强度是否超过指定阈值，将每个像素分类为黑或白。

```csharp
public override void BinarizeFixed(byte threshold)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为255，否则为0。 |

## 示例

以下示例使用预定义阈值对 GIF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage djvuImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为255，否则为0。
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


