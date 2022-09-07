---
title: PngImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avPngImageaspose.imaging.fileformats.png/pngimage class.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |

### Exempel

Det här exemplet visar hur man skapar en PNG-bild av den angivna storleken, fyller den med enfärgad och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en PNG-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Gör lite bildbehandling, t.ex. fyll hela bilden i rött.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Spara till en fil.
    pngImage.Save(dir + "output.png");
}
```

### Se även

* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild. |

### Exempel

Det här exemplet visar hur man laddar en PNG-bild från en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en PNG-bild från en fil.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Förvandla bilden till gråskalerepresentation
    pngImage.Grayscale();

    // Spara till en fil.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Se även

* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |

### Exempel

Det här exemplet visar hur man laddar PNG-bild från en BMP-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en TrueColor PNG-bild från en BMP-bild.
// Skapa först en temporal BMP-bild som kommer att vara en grund för att bygga en PNG-bild.
// Du kan också ladda BMP-bild från en fil eller använda en bild av något annat rasterformat.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fyll hela BMP-bilden i rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen för att ladda en bild. |
| colorType | PngColorType | Färgtypen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException |  |

### Exempel

Det här exemplet visar hur man laddar en PNG-bild från en fil med den angivna färgtypen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en PNG-bild från en fil.
// Observera att den färgglada bilden kommer att konverteras till gråskala automatiskt.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Spara till en fil.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Se även

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |
| colorType | PngColorType | Färgtypen. |

### Exempel

Det här exemplet visar hur man laddar PNG-bild från en BMP-bild med den angivna färgtypen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en gråskala PNG-bild från en färgad BMP-bild.
// Skapa först en temporal BMP-bild som kommer att vara en grund för att bygga en PNG-bild.
// Du kan också ladda BMP-bild från en fil eller använda en bild av något annat rasterformat.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fyll hela BMP-bilden i rött.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Färgerna på bildpixlarna kommer att konverteras till sina motsvarigheter i gråskala.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen för att ladda en bild. |

### Exempel

Det här exemplet visar hur man laddar en PNG-bild från en fil eller en filström.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en PNG-bild från en filström.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Förvandla bilden till gråskalerepresentation
        pngImage.Grayscale();

        // Spara till en fil.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### Se även

* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |
| colorType | PngColorType | Färgtypen. |

### Exempel

Det här exemplet visar hur man skapar en PNG-bild av den angivna storleken med den angivna färgtypen, fyller den med enfärgad och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en PNG-bild i gråskala på 100x100 px.
// Alla färger konverteras automatiskt till gråskaleformatet.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Gör lite bildbehandling, t.ex. fyll hela bilden i rött.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Spara till en fil.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### Se även

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

Initierar en ny instans av[`PngImage`](../../pngimage) class.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pngOptions | PngOptions | Png-alternativen. |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |

### Exempel

Det här exemplet visar hur man skapar en PNG-bild med de angivna alternativen, fyller den med en linjär övertoningsfärg och sparar den i en fil.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Antalet bitar per färgkanal
createOptions.BitDepth = 8;

// Varje pixel är en (röd, grön, blå) trippel följt av alfakomponenten.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Den maximala kompressionsnivån.
createOptions.CompressionLevel = 9;

// Användning av filter gör det möjligt att komprimera kontinuerliga tonala bilder mer effektivt.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Använd progressiv laddning
createOptions.Progressive = true;

// Skapa en PNG-bild med anpassade parametrar.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll bilden med en halvtransparent gradient.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Spara till en fil.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### Se även

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* namnutrymme [Aspose.Imaging.FileFormats.Png](../../pngimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
