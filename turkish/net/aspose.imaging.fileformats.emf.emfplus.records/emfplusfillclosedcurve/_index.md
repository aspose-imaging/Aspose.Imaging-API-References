---
title: EmfPlusFillClosedCurve
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusFillClosedCurve kaydı kapalı bir kardinal splineın içinin doldurulmasını belirtir
type: docs
weight: 6060
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

EmfPlusFillClosedCurve kaydı, kapalı bir kardinal spline'ın içinin doldurulmasını belirtir

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve)(EmfPlusRecord) | Yeni bir örneğini başlatır[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid) { get; set; } | Fırça tanımlayıcısını alır veya ayarlar İçeriği, Bayraklar alanındaki S biti tarafından belirlenen olan EmfPlusBrush'ı belirten 32 bitlik işaretsiz bir tam sayı. Bu fırça, kapalı kardinal spline'ın içini doldurmak için kullanılır. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)sıkıştırılmıştır. Bu bit, PointData alanının sıkıştırılmış verileri belirtip belirtmediğini gösterir. Ayarlanırsa, PointData, 16 bitlik tamsayı koordinatlarıyla koordinat alanındaki mutlak konumları belirtir. Temizse, PointData, 32 bit kayan nokta koordinatlarıyla koordinat alanında mutlak konumları belirtir. ---------------------- Bir "sargı" dolgusu işlemi "çift-tek parite" kuralına göre alanları doldurur. Bu kurala göre, bir test noktasının kapalı bir eğrisinin içinde veya dışında olduğu şu şekilde belirlenebilir: Test noktasından eğriden uzaktaki bir noktaya bir çizgi çizin. Bu doğru eğriyi tek sayıda geçerse, test noktası eğrinin içindedir; aksi takdirde test noktası eğrinin dışındadır. --------------------- "Alternatif" bir doldurma işlemi alanları "sıfır olmayan" kuralına göre doldurur. . Bu kurala göre, kapalı bir eğrinin içinde veya dışında bir test noktası belirlenebilir: Bir test noktasından eğriden uzaktaki bir noktaya bir çizgi çizin. Eğrinin test çizgisini soldan sağa kaç kez geçtiğini sayın ve eğrinin sağdan sola test çizgisini kaç kez geçtiğini sayın. Bu iki sayı aynıysa, test noktası eğrinin dışındadır; aksi takdirde test noktası eğrinin içindedir. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Takip eden RecordData alanındaki 32-bit hizalı bayt veri sayısını tanımlaması ZORUNLU olan 32-bit işaretsiz bir tamsayı alır veya ayarlar. Bu sayı, 12 baytlık kayıt başlığını içermez. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bazı kayıtlar için bilgi içeren 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor) { get; set; } | Bu örneğin color olup olmadığını belirten bir değer alır veya ayarlar. Ayarlanırsa, BrushId bir rengi EmfPlusARGB nesnesi olarak belirtir (bölüm 2.2.2.1). Temizse, BrushId bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. ) EMF+ Nesne Tablosunda. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata) { get; set; } | Noktayı alır veya ayarlar data Spline'ı tanımlayan çizgilerin uç noktalarını belirten Sayım noktaları dizisi. Kapalı bir ana eğride, eğri PointData dizisindeki son nokta boyunca devam eder ve dizi dizisindeki ilk nokta ile bağlanır |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve) görecelidir. Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir. Ayarlanırsa, PointData'daki her öğe, dizideki önceki öğe tarafından belirtilen konuma göre olan koordinat alanındaki bir konumu belirtir. PointData'daki ilk öğenin durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Açıksa, PointData, C bayrağına göre mutlak konumları belirtir. Not Bu bayrak ayarlanırsa, C bayrağı (yukarıdaki) tanımsızdır ve yoksayılmalıdır. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | 12 baytlık kayıt başlığı ve kayda özel veriler dahil olmak üzere tüm kayıttaki 32 bit hizalanmış bayt sayısını belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension) { get; set; } | Gerilim değerini alır veya ayarlar. Spline'ın noktalardan geçerken ne kadar sıkı büküldüğünü belirten 32 bitlik kayan nokta değeri. 0.0 değeri, spline'ın düz çizgi dizisi olduğunu belirtir. Değer arttıkça eğri daha yuvarlak hale gelir. Daha fazla bilgi için bkz. [SPLINE77] ve [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Kayıt türünü tanımlayan 16 bitlik işaretsiz bir tamsayı alır. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.[`EmfPlusFillClosedCurve`](../emfplusfillclosedcurve)sarılıyor. Bu bit, doldurma işleminin nasıl gerçekleştirileceğini gösterir. Ayarlanırsa, dolgu bir "sargı" dolgudur. Temizse, dolgu "alternatif" bir dolgudur. |

### Ayrıca bakınız

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
