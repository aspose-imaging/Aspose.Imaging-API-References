---
title: Quality
second_title: Aspose.Imaging for .NET API Referansı
description: Kaliteyi alır veya ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.imaging.imageoptions/webpoptions/quality/
---
## WebPOptions.Quality property

Kaliteyi alır veya ayarlar.

```csharp
public float Quality { get; set; }
```

### Mülk değeri

Kalite.

### Örnekler

Bu örnek, farklı sıkıştırma kalitesine sahip başka bir tarama görüntüsünden bir WebP görüntüsünün nasıl oluşturulacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// GIF animasyonu yükle
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // kayıpsız sıkıştırma için kalite ayarını artırmak sıkıştırma kalitesini artırır ve dosya boyutunu küçültür
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // dosya boyutu: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // dosya boyutu: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // dosya boyutu: 40 KB


    // kayıplı sıkıştırma için Kalite değerini artırmak görüntü kalitesini artırır ve dosya boyutunu artırır
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // dosya boyutu: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // dosya boyutu: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // dosya boyutu: 51 KB
}
```

### Ayrıca bakınız

* class [WebPOptions](../../webpoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../webpoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->