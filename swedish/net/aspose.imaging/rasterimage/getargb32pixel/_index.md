---
title: GetArgb32Pixel
second_title: Aspose.Imaging för .NET API-referens
description: Får en bild 32-bitars ARGB-pixel.
type: docs
weight: 280
url: /sv/net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

Får en bild 32-bitars ARGB-pixel.

```csharp
public int GetArgb32Pixel(int x, int y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Int32 | Pixel x platsen. |
| y | Int32 | Pixel y-platsen. |

### Returvärde

32-bitars ARGB-pixel för den angivna platsen.

### Exempel

Följande exempel laddar en rasterbild och erhåller färgen på en godtycklig pixel representerad som ett 32-bitars heltalsvärde.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Få en heltalsrepresentation av färgen på bildens övre vänstra pixel.
    int color = rasterImage.GetArgb32Pixel(0, 0);

    // För att få fram värdena för de individuella färgkomponenterna, skift färgvärdet med ett motsvarande antal bitar
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

Följande exempel visar hur bildcachelagring påverkar prestandan. I allmänhet utförs läsning av cachad data snabbare än läsning av icke-cachad data.

```csharp
[C#]

string dir = "c:\\temp\\";

// Ladda en bild från en PNG-fil.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Cachelagra alla pixeldata så att ingen ytterligare dataladdning kommer att utföras från den underliggande dataströmmen
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Att läsa alla pixlar går ganska snabbt.
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Ladda en bild från en PNG-fil
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // Att läsa alla pixlar går inte lika snabbt som vid cachning
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// Utdata kan se ut så här:
// Att läsa alla cachade pixlar tog 1500 ms.
// Att läsa alla pixlar utan preliminär cachning tog 150 000 ms.
```

### Se även

* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
