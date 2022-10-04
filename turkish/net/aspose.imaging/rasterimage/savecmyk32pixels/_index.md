---
title: SaveCmyk32Pixels
second_title: Aspose.Imaging for .NET API Referansı
description: Pikselleri kaydeder.
type: docs
weight: 520
url: /tr/net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

Pikselleri kaydeder.

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | Piksellerin kaydedileceği dikdörtgen. |
| pixels | Int32[] | 32 bit tamsayı değerleri olarak sunulan CMYK pikselleri. |

### Örnekler

Aşağıdaki örnek, Aspose.Imaging.RasterImage.SaveCmyk32Pixels yöntemini kullanarak bir raster görüntünün orta alanını siyah piksellerle doldurur.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // CMYK renk uzayında siyahın tamsayı temsilini alın.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // Siyah kare.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Resmin ortasına siyah kareyi çizin.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### Ayrıca bakınız

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* ad alanı [Aspose.Imaging](../../rasterimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->