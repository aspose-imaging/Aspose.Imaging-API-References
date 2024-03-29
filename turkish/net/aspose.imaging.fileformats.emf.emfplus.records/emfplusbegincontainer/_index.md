---
title: EmfPlusBeginContainer
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusBeginContainer kaydı yeni bir grafik durum kapsayıcısını açar ve bunun için bir dönüşüm belirtir.
type: docs
weight: 5840
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

EmfPlusBeginContainer kaydı, yeni bir grafik durum kapsayıcısını açar ve bunun için bir dönüşüm belirtir.

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusBeginContainer`](../emfplusbegincontainer) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect) { get; set; } | SrcRect ile kap için bir dönüşüm belirten bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) alır veya ayarlar. Bu dönüştürme, DestRect. öğesine uygulandığında SrcRect ile sonuçlanır. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit) { get; } | Sayfa birimini alır. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect) { get; set; } | DestRect ile kap için bir transformasyon belirten bir EmfPlusRectF dikdörtgeni alır veya ayarlar. Bu dönüştürme, DestRect. öğesine uygulandığında SrcRect ile sonuçlanır. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex) { get; set; } | the grafik durum kapsayıcısıyla ilişkilendirilecek bir dizini belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Grafik durumu kapsayıcısını kapatmak için dizine bir sonraki EmfPlusEndContainer kaydı (bölüm 2.3.7.3) tarafından başvurulmalıdır. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
