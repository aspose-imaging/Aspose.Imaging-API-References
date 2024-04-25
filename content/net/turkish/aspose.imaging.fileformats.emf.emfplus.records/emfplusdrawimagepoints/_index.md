---
title: EmfPlusDrawImagePoints
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusDrawImagePoints kaydı paralelkenar içinde ölçeklenmiş bir görüntü çizmeyi belirtir.
type: docs
weight: 5970
url: /tr/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

EmfPlusDrawImagePoints kaydı, paralelkenar içinde ölçeklenmiş bir görüntü çizmeyi belirtir.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | [efekt uygulanıyor] olup olmadığını belirten bir değer alır veya ayarlar. Bu bit, görüntünün oluşturulmasının bir efekt uygulanmasını içerdiğini gösterir. Ayarlanırsa, Effect sınıfının bir nesnesi daha önceki bir EmfPlusSerializableObject kaydında (bölüm) belirtilmelidir ZORUNLU. 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değer alır veya ayarlar. Bu bit, PointData alanının sıkıştırılmış veriyi belirtip belirtmediğini gösterir. Ayarlanırsa, PointData, 16 bitlik tamsayı koordinatlarıyla koordinat alanındaki mutlak konumları belirtir. Temizse, PointData, koordinat uzayındaki mutlak konumları 32-bit kayan nokta koordinatlarıyla belirtir. Not P bayrağı (aşağıda) ayarlanmışsa, bu bayrak tanımsızdır ve yoksayılmalıdır. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | EMF+ Nesne Tablosunda isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini içeren 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Nesne tanımlayıcısını alır veya ayarlar. EMF+ Nesne Tablosunda, oluşturulacak görüntüyü belirten bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) dizini. Değer, sıfır ile 63 arasında OLMALIDIR. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Bir paralelkenarın üç noktasını belirten Sayma noktaları dizisini alır veya ayarlar. Üç nokta, paralelkenarının sol üst, sağ üst ve sol alt köşelerini temsil eder. Paralelkenarın dördüncü noktası, ilk üçten tahmin edilir. SrcRect alanı tarafından belirtilen görüntünün kısmı, paralelkenara sığdırmak için gerekirse ölçekleme ve shearing dönüşümlerine sahip olmalıdır. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)görecelidir. Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanırsa, PointData'daki her öğe, dizideki önceki öğe tarafından belirtilen konuma göre olan koordinat alanındaki bir konumu belirtir. PointData'daki the ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Açıksa, PointData, C bayrağına göre mutlak konumları belirtir. Not Bu bayrak ayarlanırsa, C bayrağı (yukarıdaki) tanımsızdır ve yoksayılmalıdır. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Görüntünün oluşturulacak bir bölümünü tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) alır veya ayarlar. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | SrcRect alanının birimlerini tanımlayan 32 bitlik işaretli bir tamsayı alır veya ayarlar. UnitType numaralandırmasının UnitPixel değeri OLMALIDIR (bölüm 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Notlar

Bir EmfPlusImage, bir bitmap veya meta dosyası belirtebilir. Bir görüntüdeki renkler, oluşturma sırasında değiştirilebilir. Düzeltilebilirler, karartılabilirler, aydınlatılabilirler ve kaldırılabilirler.

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
