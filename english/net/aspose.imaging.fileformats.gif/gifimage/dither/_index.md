---
title: GifImage.Dither
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. Apply dithering to the current image. This process enhances image quality by reducing color banding and improving color transitions resulting in a smoother appearance
type: docs
weight: 300
url: /net/aspose.imaging.fileformats.gif/gifimage/dither/
---
## GifImage.Dither method

Apply dithering to the current image. This process enhances image quality by reducing color banding and improving color transitions, resulting in a smoother appearance.

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

The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


