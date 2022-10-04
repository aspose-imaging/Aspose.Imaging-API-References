---
title: EmfCreateColorSpaceW
second_title: Aspose.Imaging for .NET API Referansı
description: EMR_CREATECOLORSPACEW kaydı bir renk profilinden Unicode karakterlerden oluşan bir adla mantıksal bir renk uzayı nesnesi oluşturur.
type: docs
weight: 3480
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
## EmfCreateColorSpaceW class

EMR_CREATECOLORSPACEW kaydı, bir renk profilinden, Unicode karakterlerden oluşan bir adla mantıksal bir renk uzayı nesnesi oluşturur.

```csharp
public sealed class EmfCreateColorSpaceW : EmfObjectCreationRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfCreateColorSpaceW](emfcreatecolorspacew)(EmfRecord) | Yeni bir örneğini başlatır[`EmfCreateColorSpaceW`](../emfcreatecolorspacew) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/cbdata) { get; set; } | Veri alanının bayt cinsinden boyutunu belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/data) { get; set; } | Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/dwflags) { get; set; } | Bu kayıttaki veriler hakkında bilgi sağlayan 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/ihcs) { get; set; } | EMF nesne tablosundaki mantıksal renk uzayı nesnesinin dizinini belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar (bölüm 3.1.1.1). Bu nesne yeniden kullanılabilmesi veya değiştirilebilmesi için bu dizin kaydedilmelidir. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/lcs) { get; set; } | Unicode UTF16-LE karakterlerinde bir renk profilinin adını belirtebilen bir WMF LogColorSpaceW nesnesi ([MS-WMF] bölüm 2.2.2.12) alır veya ayarlar |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Rekorun boyutunu alır veya ayarlar |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Türü alır veya ayarlar. |

### Notlar

Bu kayıt tarafından tanımlanan mantıksal renk alanı nesnesi, sonraki grafik işlemlerinde kullanılacak mantıksal renk alanını tanımlayan bir EMR_SETCOLORSPACE kaydıyla (bölüm 2.3.8.7) oynatma aygıtı bağlamı 'ye seçilebilir.

### Ayrıca bakınız

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->