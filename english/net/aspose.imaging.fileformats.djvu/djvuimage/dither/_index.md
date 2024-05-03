---
title: DjvuImage.Dither
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. The Dither function applies a dithering effect to your image enhancing its visual quality by reducing banding and improving color transitions. Whether youre working on digital art photography or graphic design projects this feature adds a professional touch to your images making them appear smoother and more refined
type: docs
weight: 230
url: /net/aspose.imaging.fileformats.djvu/djvuimage/dither/
---
## DjvuImage.Dither method

The "Dither" function applies a dithering effect to your image, enhancing its visual quality by reducing banding and improving color transitions. Whether you're working on digital art, photography, or graphic design projects, this feature adds a professional touch to your images, making them appear smoother and more refined.

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

The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Perform threshold dithering using 4-bit color palette which contains 16 colors.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Perform floyd dithering using 1-bit color palette which contains only 2 colors - black and white.
    // The more bits specified the higher quality and the bigger size of the output image.
    // Note that only 1-bit, 4-bit and 8-bit palettes are supported at the moment.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


