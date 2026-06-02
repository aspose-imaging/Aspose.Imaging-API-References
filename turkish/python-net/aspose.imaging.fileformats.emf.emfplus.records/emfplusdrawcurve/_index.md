---
title: "EmfPlusDrawCurve Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Yeni bir [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Bu [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir.<br/>            Ayarlıysa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. <br/>            Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir<br/>            Not: Aşağıdaki Relative bayrağı ayarlıysa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| num_segments | int | r/w | Segment sayısını alır veya ayarlar <br/>            Spline'ı oluşturan çizgi segmentlerinin sayısını belirten 32 bit işaretsiz tam sayı. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Eğriyi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Çizilecek çizgilerin uç noktalarının koordinat değerlerini tanımlayan, <br/>            Sayı uzunluğunda 32 bit işaretli tam sayılar veya 32 bit kayan nokta sayılarından oluşan bir dizi alır veya ayarlar. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| gerilim | float | r/w | Gerginliği alır veya ayarlar<br/>            Noktalardan geçerken spline'ın ne kadar sık büküleceğini belirten 32 bit kayan nokta sayısı. 0 değeri spline'ın düz hatlar dizisi olduğunu belirtir. Değer arttıkça, eğri daha yuvarlak hâle gelir. Daha fazla bilgi için [SPLINE77] ve [PETZOLD] bakınız. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Yeni bir [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

