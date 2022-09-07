---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusDrawClosedCurve kaydı kapalı bir ana eğri çizgi çizmeyi belirtir
type: docs
weight: 5920
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

EmfPlusDrawClosedCurve kaydı, kapalı bir ana eğri çizgi çizmeyi belirtir

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType - RecordType numaralandırmasından bu kayıt türünü EmfPlusDrawClosedCurve olarak tanımlayan 16 bitlik işaretsiz bir tam sayı (bölüm 2.1.1.1). Değer 0x4017. OLMALIDIR |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)sıkıştırılmıştır. Bu bit, PointData alanının sıkıştırılmış verileri belirtip belirtmediğini gösterir. Ayarlanırsa, PointData, 16 bitlik tamsayı koordinatlarıyla koordinat alanındaki mutlak konumları belirtir. Temizse, PointData 32 bit kayan nokta koordinatlarıyla koordinat uzayındaki mutlak konumları belirtir Not Göreceli bayrak (aşağıda) ayarlanmışsa, bu bayrak tanımsızdır ve yoksayılmalıdır |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Nesne tanımlayıcısını alır veya ayarlar. Kapalı eğriyi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer, sıfır ile 63 arasında OLMALIDIR. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Noktayı alır veya ayarlar data Spline'ı tanımlayan çizgilerin uç noktalarını belirten Sayım noktaları dizisi. Kapalı bir ana eğride, eğri, PointData dizisindeki son nokta boyunca devam eder ve dizideki ilk nokta ile bağlanır. Bu dizideki veri türü, Bayraklar alanı tarafından şu şekilde belirtilir: Veri Türü Anlamı EmfPlusPointR nesne (bölüm 2.2.2.37) Bayraklar'da P bayrağı ayarlanmışsa, noktalar göreli konumları belirtir. EmfPlusPointF nesne (bölüm 2.2.2.36) P ve C bitleri Bayraklar alanında ayarlanırsa, noktalar şunları belirtir: mutlak konumlar. EmfPlusPoint nesnesi (bölüm 2.2.2.35) P biti açıksa ve C biti Bayraklar alanında ayarlanmışsa, noktalar göreli konumları belirtir. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)görecelidir. Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanırsa, PointData'daki her öğe, koordinat alanında dizideki önceki öğe tarafından belirtilen konuma göreli olan bir konumu belirtir. PointData'daki ilk öğesi durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Açıksa, PointData, C bayrağına göre mutlak konumları belirtir. Not Bu bayrak ayarlanırsa, Sıkıştırılmış bayrak (yukarıda) tanımsızdır ve MUTLAKA yoksayılmalıdır |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Gerilim değerini alır veya ayarlar. Spline noktalardan geçerken ne kadar sıkı büküldüğünü belirten 32 bitlik kayan nokta sayısı. 0 değeri, spline'ın bir düz çizgi dizisi olduğunu belirtir. Değer arttıkça, eğri daha yuvarlak hale gelir. Daha fazla bilgi için bkz. [SPLINE77] ve [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
