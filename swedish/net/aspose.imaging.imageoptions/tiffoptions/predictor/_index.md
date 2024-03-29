---
title: Predictor
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in prediktorn för LZW-komprimering.
type: docs
weight: 360
url: /sv/net/aspose.imaging.imageoptions/tiffoptions/predictor/
---
## TiffOptions.Predictor property

Hämtar eller ställer in prediktorn för LZW-komprimering.

```csharp
public TiffPredictor Predictor { get; set; }
```

### Fastighetsvärde

Prediktortypen.

### Exempel

Det här exemplet visar hur man sparar en rasterbild i TIFF-formatet med hjälp av olika alternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Ställ in Big Endian-byteordningen (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Ställ in LZW-komprimeringen.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Tillåt att minska storleken på bilder med kontinuerliga toner.
// För närvarande används detta fält endast med LZW-kodning eftersom LZW förmodligen är det enda TIFF-kodningsschemat
// som drar stor nytta av ett prediktorsteg.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// Ställ in RGB-färgmodellen.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// För YCbCr kan du använda ett av följande val:
// YCbCrSubSampling field JPEG samplingsfaktorer
// ----------------------------------------------------
// 1,1 1x1, 1x1, 1x1
// 2,1 2x1, 1x1, 1x1
// 2,2(standardvärde) 2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Alla färgkomponenter kommer att lagras inom ett enda plan.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Skapa en TIFF-ram på 100x100 px.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fyll hela bilden med den blå-gula gradienten.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### Se även

* enum [TiffPredictor](../../../aspose.imaging.fileformats.tiff.enums/tiffpredictor)
* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
