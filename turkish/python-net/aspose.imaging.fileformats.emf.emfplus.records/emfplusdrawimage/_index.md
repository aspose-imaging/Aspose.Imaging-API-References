---
title: "EmfPlusDrawImage Sınıfı"
type: docs
weight: 130
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Yeni bir [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir.<br/>            Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| image_attributes_id | int | r/w | Görüntü öznitelikleri tanımlayıcısını alır veya ayarlar<br/>            EMF+ Nesne Tablosundaki isteğe bağlı bir EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) dizinini belirten 32 bit işaretsiz tam sayı. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) indeksidir; bu, render edilecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verisini alır veya ayarlar<br/>            Görüntünün sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi.<br/>            SrcRect alanı tarafından belirtilen görüntü bölümü bu dikdörtgene sığacak şekilde ölçeklendirilir. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Kaynak dikdörtgeni alır veya ayarlar<br/>            İşlenecek görüntünün bir bölümünü belirten bir EmfPlusRectF nesnesi.<br/>            Bu dikdörtgen tarafından belirtilen görüntü bölümü, RectData alanı tarafından belirtilen hedef dikdörtgene sığacak şekilde ölçeklendirilir. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Kaynak birimini alır veya ayarlar<br/>            SrcRect alanının birimlerini belirten 32 bit işaretli tam sayı.<br/>            UnitType enumarasyonunun (bölüm 2.1.1.33) UnitTypePixel üyesi olmalıdır. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Yeni bir [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

