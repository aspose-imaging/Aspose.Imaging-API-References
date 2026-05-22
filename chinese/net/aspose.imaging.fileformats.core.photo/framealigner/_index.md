---
title: "类 FrameAligner"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Core.Photo.FrameAligner 类。对齐帧"
type: docs
weight: 2330
url: /zh/net/aspose.imaging.fileformats.core.photo/framealigner/
---
## FrameAligner class

对齐帧

```csharp
public static class FrameAligner
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Process](../../aspose.imaging.fileformats.core.photo/framealigner/process/)(RasterImage[], FrameAlignerOptions) | 处理指定的图像。 |

## 示例

示例展示了如何将一系列图像相对于第一张进行对齐。

```csharp
[C#]

const int imagesCount = 5;
const bool modify = true;

var images = new RasterImage[imagesCount];
images[0] = (RasterImage)Image.Load("DSC_5715.JPG");
images[1] = (RasterImage)Image.Load("DSC_5715_l10t7.jpg");
images[2] = (RasterImage)Image.Load("DSC_5715_l-10t-7.jpg");
images[3] = (RasterImage)Image.Load("DSC_5715_l-19.jpg");
images[4] = (RasterImage)Image.Load("manor_plus2ev.jpg");

var results = FrameAligner.Process(images, new FrameAlignerOptions
{
    ModifyImages = modify
});

Console.WriteLine(results[0]);
Console.WriteLine(results[1]);
Console.WriteLine(results[2]);
Console.WriteLine(results[3]);
Console.WriteLine(results[4]);

var i = 0;
foreach (var image in images)
{
    i++;
    var outputFilePath = $"{i}_result.jpg";
    image.Save(outputFilePath);
    image.Dispose();
}
```

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../aspose.imaging.fileformats.core.photo/)
* assembly [Aspose.Imaging](../../)


