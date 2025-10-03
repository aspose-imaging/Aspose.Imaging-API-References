---
title: TiffImage.BinarizeBradley
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Implement binarization on the image employing Bradleys adaptive thresholding algorithm with integral image thresholding. This approach dynamically computes local thresholds based on the images neighborhood enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application
type: docs
weight: 200
url: /net/aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/
---
## TiffImage.BinarizeBradley method

Implement binarization on the image employing Bradley's adaptive thresholding algorithm with integral image thresholding. This approach dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application.

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightnessDifference | Double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| windowSize | Int32 | The size of s x s window of pixels centered around this pixel |

## Examples

The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
    tiffImage.BinarizeBradley(5, 10);
    tiffImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


