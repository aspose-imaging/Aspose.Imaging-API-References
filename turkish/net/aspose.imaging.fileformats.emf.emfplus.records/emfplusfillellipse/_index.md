---
title: EmfPlusFillEllipse
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusFillEllipse kaydı bir elipsin içinin doldurulmasını belirtir
type: docs
weight: 6070
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
## EmfPlusFillEllipse class

EmfPlusFillEllipse kaydı, bir elipsin içinin doldurulmasını belirtir

```csharp
public sealed class EmfPlusFillEllipse : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusFillEllipse](emfplusfillellipse)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusFillEllipse`](../emfplusfillellipse) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/brushid) { get; set; } | Fırça tanımlayıcısını alır veya ayarlar Fırçayı belirten 32 bitlik işaretsiz bir tamsayı, içeriği Bayraklar alanındaki S biti tarafından belirlenir. Bu tanım, elips 'nin içini doldurmak için kullanılır. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscolor) { get; set; } | Bu örneğin color olup olmadığını belirten bir değer alır veya ayarlar. Ayarlanırsa, BrushId bir rengi EmfPlusARGB nesnesi olarak belirtir (bölüm 2.2.2.1). Temizse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. ) EMF+ Nesne Tablosunda. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/iscompressed) { get; set; } | Bu örneğin sıkıştırılıp sıkıştırılmadığını gösteren bir değer alır veya ayarlar. Ayarlanırsa, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). Temizse, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39). |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/rectdata) { get; set; } | Doğrusal veriyi alır veya ayarlar Ellipse 'nin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->