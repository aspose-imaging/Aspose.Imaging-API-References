---
title: TiffImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avTiffImageaspose.imaging.fileformats.tiff/tiffimage class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

Initierar en ny instans av[`TiffImage`](../../tiffimage) class.

```csharp
public TiffImage(TiffFrame frame)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frame | TiffFrame | Tiff-ramen att initiera bilden med. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Tiff-ram kan inte vara tom.;ram |

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

### Se även

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

Initierar en ny instans av[`TiffImage`](../../tiffimage) class.

```csharp
public TiffImage(TiffFrame[] frames)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frames | TiffFrame[] | Ramarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | ramar |

### Exempel

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

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
