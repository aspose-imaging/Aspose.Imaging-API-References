---
title: WebPFrameBlock
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avWebPFrameBlockaspose.imaging.fileformats.webp/webpframeblock
type: docs
weight: 10
url: /sv/net/aspose.imaging.fileformats.webp/webpframeblock/webpframeblock/
---
## WebPFrameBlock(RasterImage) {#constructor}

Initierar en ny instans av[`WebPFrameBlock`](../../webpframeblock)

klass.

```csharp
public WebPFrameBlock(RasterImage rasterImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rasterImage | RasterImage | Rasterbilden. |

### Se även

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPFrameBlock](../../webpframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* hopsättning [Aspose.Imaging](../../../)

---

## WebPFrameBlock(int, int) {#constructor_1}

Initierar en ny instans av[`WebPFrameBlock`](../../webpframeblock) class.

```csharp
public WebPFrameBlock(int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |

### Exempel

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

* class [WebPFrameBlock](../../webpframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->