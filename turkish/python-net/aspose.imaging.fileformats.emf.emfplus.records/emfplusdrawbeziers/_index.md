---
title: "EmfPlusDrawBeziers Sınıfı"
type: docs
weight: 80
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Yeni bir [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılmış olup olmadığını gösteren bir değer alır veya ayarlar. <br/>            Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir.<br/>            Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir.<br/>            Not: Aşağıdaki Relative bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir; Bezier eğrilerini çizmek için kullanılır. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Nokta verisini alır veya ayarlar<br/>            Bezier eğrilerinin başlangıç, bitiş ve kontrol noktalarını belirten Count noktalardan oluşan bir dizi. Bir Bezier eğrisinin bitiş koordinatı, bir sonraki eğrinin başlangıç koordinatıdır. Kontrol noktaları Bezier etkisini üretmek için kullanılır.<br/>            Bu dizideki veri tipi, Flags alanı tarafından aşağıdaki gibi belirtilir: Veri Tipi Anlamı<br/>            EmfPlusPointR nesnesi (bölüm 2.2.2.37)<br/>            Flags içinde P bayrağı ayarlıysa, noktalar göreli konumları belirtir.<br/>            EmfPlusPointF nesnesi (bölüm 2.2.2.36)<br/>            Flags alanında P ve C bitleri temizse, noktalar mutlak konumları belirtir.<br/>            EmfPlusPoint nesnesi (bölüm 2.2.2.35)<br/>            Flags alanında P biti temiz ve C biti ayarlıysa, noktalar göreli konumları belirtir.<br/>            Bir Bezier eğrisi kontrol noktalarından geçmez. Kontrol noktaları şu şekilde davranır |
| relative | bool | r/w | PointData'nın göreceli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, PointData'daki her öğe, koordinat uzayında önceki dizi öğesi tarafından belirtilen konuma göreceli bir konum belirtir. <br/>            PointData'daki ilk öğe durumunda, (0,0) koordinatlarındaki önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.<br/>            Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK SAYILMALIDIR. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Yeni bir [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

