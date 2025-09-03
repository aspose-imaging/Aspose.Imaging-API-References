---
title: RasterCachedImage.Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Transformation of an image to its grayscale representation
type: docs
weight: 150
url: /net/aspose.imaging/rastercachedimage/grayscale/
---
## RasterCachedImage.Grayscale method

Transformation of an image to its grayscale representation

```csharp
public override void Grayscale()
```

## Examples

The following example transforms a colored raster cached image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


