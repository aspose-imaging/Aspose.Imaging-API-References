---
title: RasterImage.BinarizeOtsu
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Binarization of an image with Otsu thresholding
type: docs
weight: 260
url: /net/aspose.imaging/rasterimage/binarizeotsu/
---
## RasterImage.BinarizeOtsu method

Binarization of an image with Otsu thresholding

```csharp
public virtual void BinarizeOtsu()
```

## Examples

The following example binarizes a raster image with Otsu thresholding. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Binarize the image with Otsu thresholding.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


