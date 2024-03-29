---
title: EmfPlusMultiplyWorldTransform
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusMultiplyWorldTransform kaydı geçerli dünya uzay dönüşümünü a belirtilen dönüşüm matrisi ile çarpar.
type: docs
weight: 6150
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
## EmfPlusMultiplyWorldTransform class

EmfPlusMultiplyWorldTransform kaydı, geçerli dünya uzay dönüşümünü a belirtilen dönüşüm matrisi ile çarpar.

```csharp
public sealed class EmfPlusMultiplyWorldTransform : EmfPlusTerminalServerRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusMultiplyWorldTransform](emfplusmultiplyworldtransform)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusMultiplyWorldTransform`](../emfplusmultiplyworldtransform) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/matrixdata) { get; set; } | Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/postmultipliedmatrix) { get; } | [son çarpılmış matris] olup olmadığını gösteren bir değer alır. Ayarlanırsa, dönüştürme matrisi sonradan çarpılmalıdır. Açıksa, önceden çarpılmalıdır. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
