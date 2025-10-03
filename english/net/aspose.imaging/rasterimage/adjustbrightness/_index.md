---
title: RasterImage.AdjustBrightness
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Adjust of a brightness for image
type: docs
weight: 180
url: /net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

Adjust of a brightness for image.

```csharp
public virtual void AdjustBrightness(int brightness)
```

| Parameter | Type | Description |
| --- | --- | --- |
| brightness | Int32 | Brightness value. |

## Examples

The following example performs brightness correction of an image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Set the brightness value. The accepted values of brightness are in the range [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


