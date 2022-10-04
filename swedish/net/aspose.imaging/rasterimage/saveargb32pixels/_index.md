---
title: SaveArgb32Pixels
second_title: Aspose.Imaging för .NET API-referens
description: Sparar 32-bitars ARGB-pixlar.
type: docs
weight: 510
url: /sv/net/aspose.imaging/rasterimage/saveargb32pixels/
---
## RasterImage.SaveArgb32Pixels method

Sparar 32-bitars ARGB-pixlar.

```csharp
public void SaveArgb32Pixels(Rectangle rectangle, int[] pixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln att spara pixlar till. |
| pixels | Int32[] | 32-bitars ARGB-pixelmatrisen. |

### Exempel

Följande exempel fyller det centrala området av en rasterbild med svarta pixlar med metoden Aspose.Imaging.RasterImage.SaveArgb32Pixels.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Den svarta fyrkanten
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black.ToArgb();
    }

    // Rita den svarta fyrkanten i mitten av bilden.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveArgb32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveArgb32Pixels.png");
}
```

### Se även

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->