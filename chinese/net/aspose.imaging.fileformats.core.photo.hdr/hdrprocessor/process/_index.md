---
title: "HdrProcessor.Process"
second_title: "Aspose.Imaging for .NET API 参考"
description: "HdrProcessor 方法。处理指定的图像"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/process/
---
## HdrProcessor.Process method

处理指定的图像。

```csharp
public static int[] Process(RasterImage[] images, HdrImageOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| images | RasterImage[] | 这些图像。 |
| 选项 | HdrImageOptions | 选项。 |

### 返回值

ARGB 像素数组

## 示例

示例展示了如何执行 HDR 处理。

```csharp
[C#]

var image1 = "DSC_6912.JPG";
var image2 = "DSC_6913.JPG";
var image3 = "DSC_6914.JPG";
var align = true;

var resultFilePath = $"{image1}_result.jpg";
var images = new RasterImage[3];
images[0] = (RasterImage)Image.Load(image1);
images[1] = (RasterImage)Image.Load(image2);
images[2] = (RasterImage)Image.Load(image3);

try
{
    var pixels = HdrProcessor.Process(images, new HdrImageOptions
    {
        SampleCount = 100,
        SmoothFactor = 200,
        AlignImages = align
    });

    using (var image = new PngImage(images[0].Width, images[0].Height))
    {
        image.SaveArgb32Pixels(image.Bounds, pixels);
        image.Save(resultFilePath);
    }
}
finally
{
    foreach (var image in images)
    {
        image.Dispose();
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [HdrImageOptions](../../hdrimageoptions/)
* class [HdrProcessor](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo.Hdr](../../hdrprocessor/)
* assembly [Aspose.Imaging](../../../)


