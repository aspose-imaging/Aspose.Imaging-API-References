---
title: TiffImage.BinarizeOtsu
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Utilize Otsu thresholding to perform binarization on the image automatically determining the optimal threshold value based on the images histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction enhancing the accuracy and reliability of image analysis tasks within your application
type: docs
weight: 220
url: /net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

Utilize Otsu thresholding to perform binarization on the image, automatically determining the optimal threshold value based on the image's histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction, enhancing the accuracy and reliability of image analysis tasks within your application.

```csharp
public override void BinarizeOtsu()
```

## Examples

The following example binarizes a TIFF image with Otsu thresholding. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Binarize the image with Otsu thresholding.
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


