---
title: "EmfPlusDrawEllipse Sınıfı"
type: docs
weight: 120
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

**Summary:** The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawEllipse(source)](#EmfPlusDrawEllipse_source_1) | Yeni bir [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) sınıf örneği oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılıp sıkıştırılmadığını belirten bir değeri alır veya ayarlar. <br/>            Ayarlandığında, RectData bir EmfPlusRect nesnesi içerir (bölüm 2.2.2.38). <br/>            Temizlendiğinde, RectData bir EmfPlusRectF nesnesi içerir (bölüm 2.2.2.39). |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Elipsi çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen (bölüm 2.2.1.7) nesnesinin indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verisini alır veya ayarlar<br/>            Elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawEllipse(source) {#EmfPlusDrawEllipse_source_1}


```
 EmfPlusDrawEllipse(source) 
```

Yeni bir [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) sınıf örneği oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

