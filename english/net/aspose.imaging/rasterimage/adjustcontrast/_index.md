---
title: RasterImage.AdjustContrast
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Image contrasting
type: docs
weight: 190
url: /net/aspose.imaging/rasterimage/adjustcontrast/
---
## RasterImage.AdjustContrast method

Image contrasting

```csharp
public virtual void AdjustContrast(float contrast)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contrast | Single | Contrast value (in range [-100; 100]) |

## Examples

The following example performs contrast correction of an image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


