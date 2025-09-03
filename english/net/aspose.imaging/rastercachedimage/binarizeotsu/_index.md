---
title: RasterCachedImage.BinarizeOtsu
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Binarization of an image with Otsu thresholding
type: docs
weight: 90
url: /net/aspose.imaging/rastercachedimage/binarizeotsu/
---
## RasterCachedImage.BinarizeOtsu method

Binarization of an image with Otsu thresholding

```csharp
public override void BinarizeOtsu()
```

## Examples

The following example binarizes a raster cached image with Otsu thresholding. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarize the image with Otsu thresholding.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


