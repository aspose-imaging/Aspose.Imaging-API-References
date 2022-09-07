---
title: WebPImage
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avWebPImageaspose.imaging.fileformats.webp/webpimage class från stream.
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Initierar en ny instans av[`WebPImage`](../../webpimage) class från stream.

```csharp
public WebPImage(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen WebP-bilden. |

### Exempel

Det här exemplet visar hur man laddar en WebP-bild från en filström och sparar den i PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en WebP-bild från en filström.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Spara till PNG
    // Observera att endast den aktiva ramen kommer att lagras i PNG, eftersom PNG inte är ett flersidigt format.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass från stream.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Streamen WebP-bilden. |
| loadOptions | LoadOptions | Lastalternativen. |

### Se även

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass från fil.

```csharp
public WebPImage(string path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen till filen WebP Image |

### Exempel

Det här exemplet visar hur man laddar en WebP-bild från en fil och sparar den i PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en WebP-bild från en fil.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Spara till PNG
    // Observera att endast den aktiva ramen kommer att lagras i PNG, eftersom PNG inte är ett flersidigt format.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass från fil.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | String | Sökvägen till filen WebP Image |
| loadOptions | LoadOptions | Lastalternativen. |

### Se även

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass från rasterImage.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |

### Exempel

Det här exemplet visar hur man skapar en WebP-bild från en annan rasterbild.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en PNG-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Skapa en WebP-bild baserad på PNG-bilden.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Spara till en WebP-fil med standardalternativ
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass från rasterImage.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |
| loadOptions | LoadOptions | Lastalternativen. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass med tom bild.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd |
| height | Int32 | Bildhöjden. |
| options | WebPOptions | Alternativen. |

### Exempel

Det här exemplet visar hur man skapar en WebP-bild med de angivna alternativen från början.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Skapa en WebP-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Fyll hela bilden i rött.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Spara till en WebP-fil
    webPImage.Save(dir + "output.webp");
}
```

Det här exemplet visar hur man skapar en animerad WebP-bild med flera ramar med de angivna alternativen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// Standardramen plus 36 + 36 ytterligare ramar.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Skapa en WebP-bild på 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // Den första cirkeln är röd
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Den andra cirkeln är svart
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Öka gradvis vinkeln på den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Öka gradvis vinkeln på den svarta bågen och torka ut den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Spara till en WebP-fil
    webPImage.Save(dir + "output.webp");
}
```

### Se även

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Initierar en ny instans av[`WebPImage`](../../webpimage) klass med tom bild.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bildens bredd |
| height | Int32 | Bildhöjden. |
| options | WebPOptions | Alternativen. |
| loadOptions | LoadOptions | Lastalternativen. |

### Se även

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
