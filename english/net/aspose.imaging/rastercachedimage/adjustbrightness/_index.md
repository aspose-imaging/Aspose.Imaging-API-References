---
title: RasterCachedImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Adjust of a brightness for image
type: docs
weight: 20
url: /net/aspose.imaging/rastercachedimage/adjustbrightness/
---
## RasterCachedImage.AdjustBrightness method

Adjust of a brightness for image.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of a raster cached image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


