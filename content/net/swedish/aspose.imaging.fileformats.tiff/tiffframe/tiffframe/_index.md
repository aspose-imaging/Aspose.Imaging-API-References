---
title: TiffFrame
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avTiffFrameaspose.imaging.fileformats.tiff/tiffframe class.
type: docs
weight: 10
url: /sv/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda en bild från och initiera rampixel och palettdata med. |

### Se även

* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen för att ladda en bild från och initiera rampixel och palettdata med. |
| options | TiffOptions | Alternativen att använda för den nyskapade ramen. |

### Se även

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild från och initiera rampixel och palettdata med. |

### Se även

* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild från och initiera rampixel och palettdata med. |
| options | TiffOptions | Alternativen att använda för den nyskapade ramen. |

### Se även

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(RasterImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden att initiera rampixel och palettdata med. |

### Exempel

Följande exempel visar hur man komponerar en mutlipage TIFF från individuella rasterbilder.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Det här är typsnitt och pensel för att rita text på enskilda ramar.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Skapa en PNG-bild och rita antalet sidor på den.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Skapa en ram baserad på PNG-bilden.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF-bilden.
        tiffImage.AddFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort det.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Glöm inte att kassera ramen om du inte vill lägga till den i någon annan TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden att initiera rampixel och palettdata med. |
| options | TiffOptions | Alternativen att använda för den nyskapade ramen. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Initierar en ny instans av[`TiffFrame`](../../tiffframe) class.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | TiffOptions | Ramalternativen. |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Options-parametern är null. |

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

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
