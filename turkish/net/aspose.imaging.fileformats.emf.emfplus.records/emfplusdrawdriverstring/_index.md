---
title: EmfPlusDrawDriverString
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusDrawDriverString kaydı karakter konumlarıyla metin çıktısını belirtir.
type: docs
weight: 5940
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

EmfPlusDrawDriverString kaydı, karakter konumlarıyla metin çıktısını belirtir.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusDrawDriverString`](../emfplusdrawdriverstring) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid) { get; set; } | Fırça tanımlayıcısını alır veya ayarlar Yazının ön plan rengini veya bir grafik fırçasını belirten 32 bit işaretsiz bir tam sayı, Flags içindeki S bayrağının değerine bağlı olarak |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags) { get; set; } | Sürücü dizesi seçeneklerini alır veya ayarlar flags Dize için aralığı, yönlendirmeyi ve işleme kalitesini belirten 32 bitlik işaretsiz bir tam sayı. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount) { get; set; } | Glif sayısını alır veya ayarlar count string içindeki gliflerin sayısını belirten 32 bitlik işaretsiz bir tam sayı |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos) { get; set; } | Glif konumlarını alır veya ayarlar array Her karakterin çıktı konumunu belirten bir EmfPlusPointF nesneleri dizisi (bölüm 2.2.2.36). Glifler dizisi. DriverStringOptions bayraklarındaki DriverStringOptionsRealizedAdvance bayrağı ayarlanmışsa, glif konumları ilk glifin konumundan hesaplanır. Bu durumda, GlyphPos yalnızca ilk glifin konumunu belirtir. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs) { get; set; } | Glifleri alır veya ayarlar array Çizilecek metin dizesini tanımlayan 16 bitlik değerler dizisi. DriverStringOptionsFlags alanındaki DriverStringOptionsCmapLookup bayrağı ayarlanırsa, this dizisindeki her değer bir Unicode karakteri belirtir. Aksi takdirde, her değer, Flags alanındaki ObjectId değeri tarafından belirtilen EmfPlusFont nesnesindeki a karakter glifi için bir dizin belirtir. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor) { get; set; } | Bu örneğin color olup olmadığını gösteren bir değer alır veya ayarlar. Bu bit BrushId alanındaki verinin türünü belirtir. Ayarlanırsa, BrushId bir EmfPlusARGB object (bölüm 2.2.2.1) içindeki renk değerini belirtir. Temizse, BrushId bir EmfPlusBrush nesnesinin EMF+ Object Tablo dizinini içerir (bölüm 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent) { get; set; } | Matrisin mevcut olup olmadığını alır veya ayarlar flag TransformMatrix field 0'da bir dönüşüm matrisinin bulunup bulunmadığını belirten 32 bitlik işaretsiz bir tam sayı - matris yok. 1 - dönüştürme matrisi TransformMatrix field içindedir |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid) { get; set; } | Nesne tanımlayıcısını alır veya ayarlar. Bir nesnenin EMF+ Nesne Tablosu dizini[EmfPlusFont](EmfPlusFont) metni oluşturmak için nesne (section 2.2.1.3). Değer, sıfır ile 63 arasında OLMALIDIR. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix) { get; set; } | Dönüşüm matrisini alır veya ayarlar Metin dizisindeki her değere uygulanacak dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47). Bu verilerin varlığı MatrixPresent alanından belirlenir. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
