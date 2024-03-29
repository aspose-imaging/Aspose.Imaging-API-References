---
title: SaveArgb32Pixels
second_title: Aspose.Imaging for .NET API Referansı
description: 32 bit ARGB piksellerini kaydeder.
type: docs
weight: 510
url: /tr/net/aspose.imaging/rasterimage/saveargb32pixels/
---
## RasterImage.SaveArgb32Pixels method

32 bit ARGB piksellerini kaydeder.

```csharp
public void SaveArgb32Pixels(Rectangle rectangle, int[] pixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | Piksellerin kaydedileceği dikdörtgen. |
| pixels | Int32[] | 32 bit ARGB piksel dizisi. |

### Örnekler

Aşağıdaki örnek, Aspose.Imaging.RasterImage.SaveArgb32Pixels yöntemini kullanarak bir raster görüntünün orta alanını siyah piksellerle doldurur.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // siyah kare
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black.ToArgb();
    }

    // Resmin ortasına siyah kareyi çizin.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveArgb32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveArgb32Pixels.png");
}
```

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
