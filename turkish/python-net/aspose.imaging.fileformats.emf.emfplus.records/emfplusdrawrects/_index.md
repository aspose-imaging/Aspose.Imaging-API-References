---
title: "EmfPlusDrawRects Sınıfı"
type: docs
weight: 180
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

**Summary:** The EmfPlusDrawRects record specifies drawing a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawRects(source)](#EmfPlusDrawRects_source_1) | Yeni bir [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir.<br/>            Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Dikdörtgenleri çizmek için EMF+<br/>            Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) dizini. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verisini alır veya ayarlar<br/>            Dikdörtgen verisini tanımlayan Count uzunluğunda bir EmfPlusRect veya EmfPlusRectF nesnesi dizisi. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawRects(source) {#EmfPlusDrawRects_source_1}


```
 EmfPlusDrawRects(source) 
```

Yeni bir [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

