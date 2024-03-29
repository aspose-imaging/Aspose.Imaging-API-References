---
title: GetPixel
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft ein Bildpixel ab.
type: docs
weight: 330
url: /de/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

Ruft ein Bildpixel ab.

```csharp
public Color GetPixel(int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Int32 | Die Pixel-x-Position. |
| y | Int32 | Die Pixel-y-Position. |

### Rückgabewert

Die Pixelfarbe für die angegebene Position.

### Beispiele

Das folgende Beispiel lädt ein Rasterbild und erhält die Farbe eines beliebigen Pixels.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Holen Sie sich die Farbe des oberen linken Pixels des Bildes.
    Color color = rasterImage.GetPixel(0, 0);

    // Erhalte die Werte der einzelnen Farbkomponenten
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### Siehe auch

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
