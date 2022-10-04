---
title: EmfPlusDrawEllipse
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusDrawEllipse kaydı bir elips çizmeyi belirtir.
type: docs
weight: 5950
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
## EmfPlusDrawEllipse class

EmfPlusDrawEllipse kaydı, bir elips çizmeyi belirtir.

```csharp
public sealed class EmfPlusDrawEllipse : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusDrawEllipse](emfplusdrawellipse)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusDrawEllipse`](../emfplusdrawellipse) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/compressed) { get; set; } | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değer alır veya ayarlar. Ayarlanırsa, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). Temizse, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/objectid) { get; set; } | Nesne tanımlayıcısını alır veya ayarlar. Elips çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen (bölüm 2.2.1.7) nesnesinin dizini. Değer, sıfır ile 63 arasında OLMALIDIR. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/rectdata) { get; set; } | Veri dikdörtgenini alır veya ayarlar Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->