---
title: "FrameAligner.Process"
second_title: "Aspose.Imaging for .NET API 参考"
description: "FrameAligner 方法。处理指定的图像"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.core.photo/framealigner/process/
---
## FrameAligner.Process method

处理指定的图像。

```csharp
public static List<Point?> Process(RasterImage[] images, FrameAlignerOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | RasterImage[] | 这些图像。 |
| 选项 | FrameAlignerOptions | 选项。 |

### 返回值

按图像的偏移数组

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

* struct [Point](../../../aspose.imaging/point/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [FrameAlignerOptions](../../framealigneroptions/)
* class [FrameAligner](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../framealigner/)
* assembly [Aspose.Imaging](../../../)


