---
title: TiffImage.Dither
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Execute dithering on the current image to enhance its visual quality and reduce color banding artifacts. Integrate this method into your image processing workflow to ensure smoother transitions between colors resulting in improved overall image appearance and clarity
type: docs
weight: 240
url: /net/aspose.imaging.fileformats.tiff/tiffimage/dither/
---
## TiffImage.Dither method

Execute dithering on the current image to enhance its visual quality and reduce color banding artifacts. Integrate this method into your image processing workflow to ensure smoother transitions between colors, resulting in improved overall image appearance and clarity.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | The dithering method. |
| bitsCount | Int32 | The final bits count for dithering. |
| customPalette | IColorPalette | The custom palette for dithering. |

## Examples

The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


