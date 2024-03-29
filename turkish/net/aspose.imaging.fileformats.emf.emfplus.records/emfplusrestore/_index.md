---
title: EmfPlusRestore
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusRestore kaydı belirtilen bir dizin tarafından tanımlanan grafik durumunu kaydedilmiş grafik durumları yığınından geri yükler.
type: docs
weight: 6230
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
## EmfPlusRestore class

EmfPlusRestore kaydı, belirtilen bir dizin tarafından tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığınından geri yükler.

```csharp
public sealed class EmfPlusRestore : EmfPlusStateRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusRestore](emfplusrestore)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusRestore`](../emfplusrestore) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/stackindex) { get; set; } | a grafik durumuyla ilişkili düzeyi belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Düzey değeri, önceki bir EmfPlusSave kaydı tarafından grafik durumuna atanmıştır (bölüm 2.3.7.5). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
