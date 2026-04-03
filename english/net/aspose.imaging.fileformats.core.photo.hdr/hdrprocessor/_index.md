---
title: Class HdrProcessor
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Core.Photo.Hdr.HdrProcessor class. The HDR processor
type: docs
weight: 2360
url: /net/aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/
---
## HdrProcessor class

The HDR processor

```csharp
public static class HdrProcessor
```

## Methods

| Name | Description |
| --- | --- |
| static [Process](../../aspose.imaging.fileformats.core.photo.hdr/hdrprocessor/process/)(RasterImage[], HdrImageOptions) | Processes the specified images. |

## Examples

The example shows how HDR processing is carried out.

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

### See Also

* namespace [Aspose.Imaging.FileFormats.Core.Photo.Hdr](../../aspose.imaging.fileformats.core.photo.hdr/)
* assembly [Aspose.Imaging](../../)


