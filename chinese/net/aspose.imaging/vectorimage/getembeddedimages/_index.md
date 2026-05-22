---
title: "VectorImage.GetEmbeddedImages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "VectorImage 方法。获取嵌入的图像"
type: docs
weight: 80
url: /zh/net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

获取嵌入的图像。

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### 返回值

图像数组

## 示例

支持从矢量图像中提取嵌入的光栅图像

```csharp
[C#]

var inputFileName = "test.cdr";
using (var image = Aspose.Imaging.Image.Load(inputFileName))        
{
    var vectorImage = ((Aspose.Imaging.VectorImage) image);
    var images = vectorImage.GetEmbeddedImages();
    var i = 0;
    foreach (var im in images)
    {
        var outFileName = string.Format("image{0}.png", i++);
        using (im)
        {
            im.Image.Save(outFileName, new PngOptions());
        }
    }
}
```

### 另请参见

* class [EmbeddedImage](../../embeddedimage/)
* class [VectorImage](../)
* namespace [Aspose.Imaging](../../vectorimage/)
* assembly [Aspose.Imaging](../../../)


