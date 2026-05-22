---
title: "HdrImageOptions.AlignImages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "HdrImageOptions 属性。获取或设置一个值，指示是否对齐图像"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.core.photo.hdr/hdrimageoptions/alignimages/
---
## HdrImageOptions.AlignImages property

获取或设置一个值，指示是否 [align images]。

```csharp
public bool AlignImages { get; set; }
```

### Property Value

`true` 如果 [align images]；否则为 `false`。

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

* class [HdrImageOptions](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo.Hdr](../../hdrimageoptions/)
* assembly [Aspose.Imaging](../../../)


