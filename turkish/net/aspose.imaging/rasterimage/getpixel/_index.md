---
title: GetPixel
second_title: Aspose.Imaging for .NET API Referansı
description: Bir görüntü pikseli alır.
type: docs
weight: 330
url: /tr/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

Bir görüntü pikseli alır.

```csharp
public Color GetPixel(int x, int y)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| x | Int32 | Piksel x konumu. |
| y | Int32 | Piksel y konumu. |

### Geri dönüş değeri

Belirtilen konum için piksel rengi.

### Örnekler

Aşağıdaki örnek, bir raster görüntü yükler ve rastgele bir pikselin rengini alır.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Resmin sol üst pikselinin rengini alın.
    Color color = rasterImage.GetPixel(0, 0);

    // Tek tek renk bileşenlerinin değerlerini alın
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### Ayrıca bakınız

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
