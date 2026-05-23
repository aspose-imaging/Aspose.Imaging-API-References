---
title: "EmfPlusFillClosedCurve Sınıfı"
type: docs
weight: 230
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Yeni bir [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça tanımlayıcısını alır veya ayarlar<br/>            İçeriği Flags alanındaki S bitiyle belirlenen EmfPlusBrush'ı belirten 32 bit işaretsiz tam sayı. Bu fırça, kapalı kardinal spline'ın içini doldurmak için kullanılır. |
| compressed | bool | r/w | Bu [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) sıkıştırılmış mı gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir.<br/>            Ayarlanmışsa, PointData 16 bit tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla mutlak konumları belirtir.<br/>            ----------------------<br/>            "Winding" doldurma işlemi, "çift çift (even-odd) parite" kuralına göre alanları doldurur. <br/>            Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Çizgi eğriyi tek sayıda keserse, test noktası eğrinin içindedir; aksi takdirde dışındadır.<br/>            ---------------------<br/>            "Alternate" doldurma işlemi, "sıfır olmayan" kurala göre alanları doldurur.<br/>            Bu kurala göre, bir test noktası aşağıdaki gibi kapalı bir eğrinin içinde mi dışarıda mı olduğu belirlenir: Test noktasından eğriden uzak bir noktaya bir çizgi çizin. Eğrinin test çizgisini soldan sağa kaç kez kestiğini sayın ve sağdan sola kaç kez kestiğini sayın. Bu iki sayı aynıysa, test noktası eğrinin dışındadır; aksi takdirde içindedir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlıysa, BrushId bir renk olarak EmfPlusARGB nesnesini (bölüm 2.2.2.1) belirtir.<br/>            Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Nokta verisini alır veya ayarlar<br/>            Spline'ı tanımlayan çizgilerin uç noktalarını belirten Count noktasından oluşan bir dizi. <br/>            Kapalı bir kardinal spline'da, eğri PointData dizisindeki son noktadan geçerek dizinin ilk noktasıyla bağlanır. |
| relative | bool | r/w | Bu [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) göreceli mi gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının göreceli mi yoksa mutlak mı konumlar belirttiğini gösterir.<br/>            Ayarlanmışsa, PointData'daki her öğe, koordinat uzayında önceki dizi öğesi tarafından belirtilen konuma göreceli bir konum belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarındaki önceki konum varsayılır. <br/>            Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.<br/>            Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK SAYILMALIDIR. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| gerilim | float | r/w | Gerilimi alır veya ayarlar<br/>            Spline'ın noktalardan geçerken ne kadar sık büküldüğünü belirten 32 bit kayan nokta değeri. 0.0 değeri, spline'ın düz çizgilerden oluşan bir dizi olduğunu belirtir. Değer arttıkça eğri daha yuvarlaklaşır. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bakınız. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |
| winding | bool | r/w | Bu [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) winding (dönüş) olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, doldurma işleminin nasıl yapılacağını gösterir.<br/>            Ayarlanmışsa, doldurma bir "winding" doldurma olur. Temizlenmişse, doldurma bir "alternate" doldurma olur. |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Yeni bir [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

