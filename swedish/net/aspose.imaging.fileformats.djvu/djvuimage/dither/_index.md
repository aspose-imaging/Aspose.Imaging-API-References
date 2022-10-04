---
title: Dither
second_title: Aspose.Imaging för .NET API-referens
description: Utför dithering på den aktuella bilden.
type: docs
weight: 230
url: /sv/net/aspose.imaging.fileformats.djvu/djvuimage/dither/
---
## DjvuImage.Dither method

Utför dithering på den aktuella bilden.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | Vibrationsmetoden. |
| bitsCount | Int32 | De sista bitarna räknas för dithering. |
| customPalette | IColorPalette | Den anpassade paletten för dithering. |

### Exempel

Följande exempel laddar en DJVU-bild och utför tröskel- och floyd-dithering med olika palettdjup.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Utför tröskelvibrering med 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges desto högre kvalitet och desto större storlek på utdatabilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för tillfället.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Utför floyd-dithering med en 1-bitars färgpalett som bara innehåller 2 färger - svart och vitt.
    // Ju fler bitar som anges desto högre kvalitet och desto större storlek på utdatabilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för tillfället.
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [DjvuImage](../../djvuimage)
* namnutrymme [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->