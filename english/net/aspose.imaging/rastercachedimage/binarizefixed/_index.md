---
title: RasterCachedImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Binarization of an image with predefined threshold
type: docs
weight: 60
url: /net/aspose.imaging/rastercachedimage/binarizefixed/
---
## RasterCachedImage.BinarizeFixed method

Binarization of an image with predefined threshold

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a raster cached image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


