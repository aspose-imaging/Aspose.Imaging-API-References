---
title: FrameAligner.Process
second_title: Aspose.Imaging for .NET API Reference
description: FrameAligner method. Processes the specified images
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.core.photo/framealigner/process/
---
## FrameAligner.Process method

Processes the specified images.

```csharp
public static List<Point?> Process(RasterImage[] images, FrameAlignerOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| images | RasterImage[] | The images. |
| options | FrameAlignerOptions | The options. |

### Return Value

Array of offsets by images

## Examples

The example shows how to align a series of images relative to the first one.

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

### See Also

* struct [Point](../../../aspose.imaging/point/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [FrameAlignerOptions](../../framealigneroptions/)
* class [FrameAligner](../)
* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../framealigner/)
* assembly [Aspose.Imaging](../../../)


