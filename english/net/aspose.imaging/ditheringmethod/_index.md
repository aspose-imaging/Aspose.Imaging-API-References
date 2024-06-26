---
title: Enum DitheringMethod
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.DitheringMethod enum. Dithering method
type: docs
weight: 840
url: /net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

Dithering method.

```csharp
public enum DitheringMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ThresholdDithering | `0` | Threshold dithering. Simplest and fastest dithering algorithm. |
| FloydSteinbergDithering | `1` | The Floyd-Steinberg dithering. A more complex dithering algorithm, uses nearest neighbors intensity values. |

## Examples

The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


