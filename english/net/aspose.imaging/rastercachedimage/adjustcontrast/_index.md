---
title: RasterCachedImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Image contrasting
type: docs
weight: 30
url: /net/aspose.imaging/rastercachedimage/adjustcontrast/
---
## RasterCachedImage.AdjustContrast method

Image contrasting

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

## Examples

The following example performs contrast correction of a raster cached image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


