---
title: EmfPlusDrawString
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusDrawString kaydı metin çıktısını dize biçimlendirme ile belirtir
type: docs
weight: 6020
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

EmfPlusDrawString kaydı, metin çıktısını dize biçimlendirme ile belirtir

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusDrawString`](../emfplusdrawstring) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid) { get; set; } | Fırça tanımlayıcısını alır veya ayarlar İçeriği Bayraklar alanındaki S biti tarafından belirlenen, fırçayı belirten 32 bitlik işaretsiz bir tam sayı. Bu tanım, ön plan metin rengini boyamak için kullanılır; yani, yalnızca gliflerin kendileri. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid) { get; set; } | Biçim tanımlayıcısını alır veya ayarlar EMF+ Nesne Tablosunda isteğe bağlı bir EmfPlusStringFormat nesnesinin (bölüm 2.2.1.9) dizinini belirten 32 bitlik işaretsiz bir tam sayı. Bu nesne, metin düzeni bilgilerini ve bir string öğesine uygulanacak görüntüleme manipülasyonlarını belirtir. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor) { get; set; } | Bu örneğin color olup olmadığını belirten bir değer alır veya ayarlar. Ayarlanırsa, BrushId bir rengi EmfPlusARGB nesnesi olarak belirtir (bölüm 2.2.2.1). Temizse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. ) EMF+ Nesne Tablosunda. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect) { get; set; } | Düzeni alır veya ayarlar rect string dizesini alacak hedefin sınırlayıcı alanını tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length) { get; set; } | Dizedeki karakter sayısını belirten uzunluk 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid) { get; set; } | Nesne tanımlayıcısını alır veya ayarlar. Metni işlemek için EMF+ Nesne Tablosundaki bir EmfPlusFont nesnesinin (bölüm 2.2.1.3) dizini. Değer, sıfır ile 63 arasında OLMALIDIR. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata) { get; set; } | Dizeyi alır veya ayarlar data Çizilecek dizeyi belirten 16 bitlik Unicode karakter dizisi |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
