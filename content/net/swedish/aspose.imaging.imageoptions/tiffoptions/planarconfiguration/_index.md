---
title: PlanarConfiguration
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in den plana konfigurationen.
type: docs
weight: 350
url: /sv/aspose.imaging.imageoptions/tiffoptions/planarconfiguration/
---
## TiffOptions.PlanarConfiguration property

Hämtar eller ställer in den plana konfigurationen.

```csharp
public TiffPlanarConfigs PlanarConfiguration { get; set; }
```

### Fastighetsvärde

Den plana konfigurationen.

### Exempel

Det här exemplet visar hur man skapar en TIFF-bild från början och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Ställ in 8 bitar för varje färgkomponent.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Ställ in Big Endian-byteordningen (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Ställ in LZW-komprimeringen.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Ställ in RGB-färgmodellen.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Alla färgkomponenter kommer att lagras inom ett enda plan.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Skapa en TIFF-ram på 100x100 px.
// Observera att du inte behöver disponera en ram explicit om den ingår i TiffImage.
// När behållaren kasseras kommer alla ramar att kasseras automatiskt.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Fyll hela ramen med den blå-gula gradienten.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Skapa en TIFF-bild.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

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

Det här exemplet visar hur man skapar en TIFF-bild med 2 ramar och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Alternativ för den första bildrutan
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Ställ in 8 bitar för varje färgkomponent.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Ställ in Big Endian-byteordningen (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Ställ in LZW-komprimeringen.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Ställ in RGB-färgmodellen.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Alla färgkomponenter kommer att lagras inom ett enda plan.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Skapa den första TIFF-ramen på 100x100 px.
// Observera att du inte behöver disponera ramar explicit om de ingår i TiffImage.
// När behållaren kasseras kommer alla ramar att kasseras automatiskt.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Fyll den första ramen med den blå-gula gradienten.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Alternativ för den första bildrutan
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Ställ in 1 bit per pixel för en svartvit bild.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Ställ in byteordningen för Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Ställ in CCITT Group 3 Fax-komprimering.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Ställ in svart/vit färgmodell där 0 är svart, 1 är vit.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Skapa den andra TIFF-ramen på 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Fyll den andra ramen med den blå-gula gradienten.
// Den kommer automatiskt att konverteras till B/W-formatet på grund av motsvarande inställningar för ramen.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Skapa en TIFF-bild.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### Se även

* enum [TiffPlanarConfigs](../../../aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs)
* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
