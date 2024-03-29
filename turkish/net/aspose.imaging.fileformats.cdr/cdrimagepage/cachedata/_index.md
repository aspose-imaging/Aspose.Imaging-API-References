---
title: CacheData
second_title: Aspose.Imaging for .NET API Referansı
description: Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlarDataStreamContaineraspose.imaging/datastreamsupporter/datastreamcontainer .
type: docs
weight: 90
url: /tr/net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

Verileri önbelleğe alır ve temel alınandan ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer) .

```csharp
public override void CacheData()
```

### Örnekler

Aşağıdaki örnek, bir CDR görüntüsünün tüm sayfalarının nasıl önbelleğe alınacağını gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir CDR dosyasından bir resim yükleyin.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // Bu çağrı yalnızca varsayılan sayfayı önbelleğe alır.
    image.CacheData();

    // Temel veri akışından ek veri yüklemesi gerçekleştirilmeyecek şekilde tüm sayfaları önbelleğe alın.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ayrıca bakınız

* class [CdrImagePage](../../cdrimagepage)
* ad alanı [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
