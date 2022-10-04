---
title: Pages
second_title: Aspose.Imaging for .NET API Referansı
description: Sayfaları alır.
type: docs
weight: 100
url: /tr/net/aspose.imaging.fileformats.cmx/cmximage/pages/
---
## CmxImage.Pages property

Sayfaları alır.

```csharp
public override Image[] Pages { get; }
```

### Mülk değeri

Sayfalar.

### Örnekler

Aşağıdaki örnek, bir CMX görüntüsünün tüm sayfalarının nasıl önbelleğe alınacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir CMX dosyasından bir resim yükleyin.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.CacheData();

    // Temel veri akışından ek veri yüklemesi gerçekleştirilmeyecek şekilde tüm sayfaları önbelleğe alın.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ayrıca bakınız

* class [Image](../../../aspose.imaging/image)
* class [CmxImage](../../cmximage)
* ad alanı [Aspose.Imaging.FileFormats.Cmx](../../cmximage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->