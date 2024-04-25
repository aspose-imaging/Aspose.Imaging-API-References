---
title: TiffOptions
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avTiffOptionsaspose.imaging.imageoptions/tiffoptions class.
type: docs
weight: 10
url: /sv/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

Initierar en ny instans av[`TiffOptions`](../../tiffoptions) class.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Det förväntade tiff-filformatet. |
| byteOrder | TiffByteOrder | TIFF-filformatet byteordning att använda. |

### Se även

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

Initierar en ny instans av[`TiffOptions`](../../tiffoptions)klass. Som standard används little endian-konventionen.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | Det förväntade tiff-filformatet. |

### Exempel

Följande exempel visar hur du skapar en gråskalekopia av en befintlig ram och lägger till den i en TIFF-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte temporär filkälla.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll den aktiva ramen med en linjär gradientborste.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Alternativ för gråskala
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Skapa en gråskalekopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Lägg till den nyskapade ramen till TIFF-bilden.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
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

### Se även

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

Initierar en ny instans av[`TiffOptions`](../../tiffoptions) class.

```csharp
public TiffOptions(TiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | TiffOptions | Alternativen att kopiera från. |

### Se även

* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

Initierar en ny instans av[`TiffOptions`](../../tiffoptions) class.

```csharp
public TiffOptions(TiffDataType[] tags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tags | TiffDataType[] | Taggarna att initiera alternativ med. |

### Se även

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../tiffoptions)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
