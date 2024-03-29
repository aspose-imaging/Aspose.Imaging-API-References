---
title: Dither
second_title: Aspose.Imaging for .NET API Referansı
description: Geçerli görüntüde renk taklidi gerçekleştirir.
type: docs
weight: 310
url: /tr/net/aspose.imaging.fileformats.gif/gifimage/dither/
---
## GifImage.Dither method

Geçerli görüntüde renk taklidi gerçekleştirir.

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | Diferansiyel yöntemi. |
| bitsCount | Int32 | Son bitler renk taklidi için sayılır. |
| customPalette | IColorPalette | Renk taklidi için özel palet. |

### Örnekler

Aşağıdaki örnek, bir GIF görüntüsü yükler ve farklı palet derinliği kullanarak eşik ve floyd taklidi gerçekleştirir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 16 renk içeren 4 bitlik renk paletini kullanarak eşik taklidi gerçekleştirin.
    // Ne kadar çok bit belirtilirse, çıktı görüntüsünün kalitesi ve boyutu o kadar yüksek olur.
    // Şu anda yalnızca 1 bit, 4 bit ve 8 bit paletlerin desteklendiğini unutmayın.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Siyah ve beyaz olmak üzere yalnızca 2 renk içeren 1 bitlik renk paletini kullanarak floyd renk taklidi gerçekleştirin.
    // Ne kadar çok bit belirtilirse, çıktı görüntüsünün kalitesi ve boyutu o kadar yüksek olur.
    // Şu anda yalnızca 1 bit, 4 bit ve 8 bit paletlerin desteklendiğini unutmayın.
    gifImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
