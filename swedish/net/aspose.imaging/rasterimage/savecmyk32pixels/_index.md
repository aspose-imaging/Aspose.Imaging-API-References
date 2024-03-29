---
title: SaveCmyk32Pixels
second_title: Aspose.Imaging för .NET API-referens
description: Sparar pixlarna.
type: docs
weight: 520
url: /sv/net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

Sparar pixlarna.

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln att spara pixlar till. |
| pixels | Int32[] | CMYK-pixlarna presenteras som 32-bitars heltalsvärden. |

### Exempel

Följande exempel fyller det centrala området av en rasterbild med svarta pixlar med metoden Aspose.Imaging.RasterImage.SaveCmyk32Pixels.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Få en heltalsrepresentation av svart i CMYK-färgrymden.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Den svarta fyrkanten.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Rita den svarta fyrkanten i mitten av bilden.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### Se även

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
