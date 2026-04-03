---
title: Class FrameAlignerOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Core.Photo.FrameAlignerOptions class. The frame aligner options
type: docs
weight: 2340
url: /net/aspose.imaging.fileformats.core.photo/framealigneroptions/
---
## FrameAlignerOptions class

The frame aligner options

```csharp
public class FrameAlignerOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FrameAlignerOptions](framealigneroptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [MaxOffset](../../aspose.imaging.fileformats.core.photo/framealigneroptions/maxoffset/) { get; set; } | Gets or sets the maximum offset. |
| [ModifyImages](../../aspose.imaging.fileformats.core.photo/framealigneroptions/modifyimages/) { get; set; } | Gets or sets a value indicating whether [modify image]. |
| [StandardImageIndex](../../aspose.imaging.fileformats.core.photo/framealigneroptions/standardimageindex/) { get; set; } | Gets or sets the index of the standard image. |
| [Threshold](../../aspose.imaging.fileformats.core.photo/framealigneroptions/threshold/) { get; set; } | Gets or sets the threshold. |

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

* namespace [Aspose.Imaging.FileFormats.Core.Photo](../../aspose.imaging.fileformats.core.photo/)
* assembly [Aspose.Imaging](../../)


