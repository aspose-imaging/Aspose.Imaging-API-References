---
title: RotateFlip
second_title: Aspose.Imaging for .NET API Referansı
description: Yalnızca Etkin çerçeveyi döndürür çevirir veya döndürür ve döndürür.
type: docs
weight: 420
url: /tr/net/aspose.imaging.fileformats.gif/gifimage/rotateflip/
---
## GifImage.RotateFlip method

Yalnızca Etkin çerçeveyi döndürür, çevirir veya döndürür ve döndürür.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Döndürme çevirme tipi. |

### Örnekler

Bu örnek bir GIF görüntüsü yükler, onu saat yönünde 90 derece döndürür ve isteğe bağlı olarak görüntüyü yatay ve/veya dikey olarak çevirir.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // Döndür, çevir ve çıktı dosyasına kaydet.
    using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### Ayrıca bakınız

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype)
* class [GifImage](../../gifimage)
* ad alanı [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->