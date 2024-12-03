---
title: RasterImage.Dither
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Performs dithering on the current image
type: docs
weight: 260
url: /net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

Performs dithering on the current image.

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | The dithering method. |
| bitsCount | Int32 | The final bits count for dithering. |
| customPalette | IColorPalette | The custom palette for dithering. |

### See Also

* enum [DitheringMethod](../../ditheringmethod/)
* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

Performs dithering on the current image.

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | The dithering method. |
| bitsCount | Int32 | The final bits count for dithering. |

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

* enum [DitheringMethod](../../ditheringmethod/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


