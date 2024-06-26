---
title: RasterImage.BinarizeFixed
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Binarization of an image with predefined threshold
type: docs
weight: 230
url: /net/aspose.imaging/rasterimage/binarizefixed/
---
## RasterImage.BinarizeFixed method

Binarization of an image with predefined threshold

```csharp
public virtual void BinarizeFixed(byte threshold)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threshold | Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

## Examples

The following example binarizes a raster image with the predefined threshold. Binarized images contain only 2 colors - black and white.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Binarize the image with a threshold value of 127.
    // If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


