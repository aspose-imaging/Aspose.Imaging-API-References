---
title: "EmfPlusDrawLines Sınıfı"
type: docs
weight: 150
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Yeni bir [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Kapanmış [closed shape] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| compressed | bool | r/w | Bu [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir.<br/>            Ayarlıysa, PointData koordinat uzayında 16-bit tam sayı koordinatlarıyla mutlak konumları belirtir. <br/>            Temizlenmişse, PointData koordinat uzayında 32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir<br/>            Not: Aşağıdaki Relative bayrağı ayarlıysa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Çizgileri çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Nokta verisini alır veya ayarlar<br/>            Çizilecek çizgilerin başlangıç ve bitiş noktalarını belirten Count noktalarından oluşan bir dizi. |
| relative | bool | r/w | Bu [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) göreceli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, PointData alanının göreceli mi yoksa mutlak mı konumları belirttiğini gösterir.<br/>            Ayarlıysa, PointData'daki her öğe, koordinat uzayında bir konumu, dizideki önceki öğe tarafından belirtilen konuma göreli olarak belirtir.<br/>            PointData'daki ilk öğe için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir.<br/>            Not: Bu bayrak ayarlıysa, yukarıdaki Sıkıştırılmış bayrak tanımsızdır ve YOK SAYILMALIDIR |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Yeni bir [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

