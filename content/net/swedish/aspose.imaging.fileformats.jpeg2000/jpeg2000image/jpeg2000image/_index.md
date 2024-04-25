---
title: Jpeg2000Image
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image class.
type: docs
weight: 10
url: /sv/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda bild från och initiera pixel- och palettdata med. |

### Exempel

Det här exemplet visar hur man laddar en JPEG2000-bild från en fil och sparar den i PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG2000-bild.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Spara till PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda bild från och initiera pixel- och palettdata med |
| bitsPerPixel | Int32 | Bitarna per pixel. |

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda bild från och initiera pixel- och palettdata med. |

### Exempel

Det här exemplet visar hur man laddar en JPEG2000-bild från en filström och sparar den i PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en JPEG2000-bild från stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Spara till PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att ladda bild från och initiera pixel- och palettdata med. |
| bitsPerPixel | Int32 | Bitarna per pixel. |

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd |
| height | Int32 | Bildhöjden |

### Exempel

Det här exemplet visar hur man skapar en JPEG2000-bild och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en JPEG2000-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Spara till en fil
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd |
| height | Int32 | Bildhöjden |
| options | Jpeg2000Options | Alternativen. |

### Exempel

Det här exemplet visar hur man skapar en PNG-bild och sparar den i JPEG2000 med önskade alternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Använd den oåterkalleliga Discrete Wavelet Transform 9-7
    saveOptions.Irreversible = true;

    // JP2 är "container"-formatet för JPEG 2000-kodströmmar.
    // J2K är rå komprimerad data, utan omslag.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Spara till en fil
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

Det här exemplet visar hur man skapar en JPEG2000-bild med önskade alternativ och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Använd den oåterkalleliga Discrete Wavelet Transform 9-7
createOptions.Irreversible = true;

// JP2 är "container"-formatet för JPEG 2000-kodströmmar.
// J2K är rå komprimerad data, utan omslag.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Skapa en JPEG2000-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Spara till en fil
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### Se även

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd |
| height | Int32 | Bildhöjden |
| bitsCount | Int32 | Bitarna räknas. |

### Se även

* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Bilden. |

### Exempel

Det här exemplet visar hur man skapar en JPEG2000-bild från en annan rasterbild.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Skapa en JPEG2000-bild baserad på PNG-bilden.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Spara till en fil
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Initierar en ny instans av[`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Bilden att initiera pixel- och palettdata med. |
| bitsPerPixel | Int32 | Bitarna per pixel. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namnutrymme [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
