---
title: Crop
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü kırpılıyor.
type: docs
weight: 300
url: /tr/net/aspose.imaging.fileformats.gif/gifimage/crop/
---
## GifImage.Crop method

Görüntü kırpılıyor.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | dikdörtgen. |

### Örnekler

Aşağıdaki örnek, bir GIF görüntüsünü kırpar. Kırpma alanı Aspose.Imaging.Rectangle ile belirlenir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Görüntüyü kırpın. Kırpma alanı, görüntünün dikdörtgen orta alanıdır.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(gifImage.Width / 4, gifImage.Height / 4, gifImage.Width / 2, gifImage.Height / 2);
    gifImage.Crop(area);

    // Kırpılan görüntüyü PNG'ye kaydedin
    gifImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
