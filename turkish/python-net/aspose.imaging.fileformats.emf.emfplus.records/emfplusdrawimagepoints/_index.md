---
title: "EmfPlusDrawImagePoints Sınıfı"
type: docs
weight: 140
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Yeni bir [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Bir değer alır veya ayarlar; bu değer [applying an effect] olup olmadığını gösterir.<br/>            Bu bit, görüntünün render edilmesinin bir efekti uygulamayı içerdiğini gösterir.<br/>            Ayarlanmışsa, Effect sınıfının bir nesnesi daha önceki<br/>            EmfPlusSerializableObject kaydında (bölüm 2.3.5.2) belirtilmiş olmalıdır. |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılmış olup olmadığını gösteren bir değer alır veya ayarlar.<br/>            Bu bit, PointData alanının sıkıştırılmış veri belirttiğini gösterir.<br/>            Ayarlanmışsa, PointData koordinat uzayında 16-bit tam sayı<br/>            koordinatlarıyla mutlak konumları belirtir. Temizlenmişse, PointData koordinat uzayında<br/>            32-bit kayan nokta koordinatlarıyla mutlak konumları belirtir.<br/>            Not: Aşağıdaki P bayrağı ayarlanmışsa, bu bayrak tanımsızdır ve YOK SAYILMALIDIR. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| image_attributes_id | int | r/w | EMF+ Nesne Tablosundaki isteğe bağlı EmfPlusImageAttributes nesnesinin (bölüm 2.2.1.5) indeksini içeren 32-bit işaretsiz bir tam sayı alır veya ayarlar. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            EMF+ Nesne Tablosundaki bir EmfPlusImage nesnesinin (bölüm 2.2.1.4) indeksidir; bu, render edilecek görüntüyü belirtir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Paralelkenarın üç noktasını belirten Count noktalarından oluşan bir dizi alır veya ayarlar.<br/>            Bu üç nokta, paralelkenarın sol üst, sağ üst ve sol alt köşelerini temsil eder.<br/>            Paralelkenarın dördüncü noktası ilk üç noktadan türetilir.<br/>            SrcRect alanı tarafından belirtilen görüntü bölümü, paralelkenarın içine sığması için gerekirse ölçekleme ve kaydırma<br/>            dönüşümlerine tabi tutulmalıdır. |
| relative | bool | r/w | Bu [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) öğesinin göreli olup olmadığını gösteren bir değer alır veya ayarlar.<br/>            Bu bit, PointData alanının göreli mi yoksa mutlak konumları mı belirttiğini gösterir.<br/>            Ayarlanmışsa, PointData'daki her eleman, dizideki önceki eleman tarafından belirtilen konuma göre<br/>            göreli bir konumu tanımlar. PointData'nın ilk elemanı için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse,<br/>            PointData, C bayrağına göre mutlak konumları belirtir.<br/>            Not: Bu bayrak ayarlanmışsa, yukarıdaki C bayrağı tanımsızdır ve YOK SAYILMALIDIR. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Render edilecek görüntünün bir bölümünü tanımlayan bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) alır veya ayarlar. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | SrcRect alanının birimlerini tanımlayan 32-bit işaretli bir tam sayı alır veya ayarlar. Bu, UnitType enumarasyonunun (bölüm 2.1.1.33) UnitPixel değerine eşit olmalıdır. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Yeni bir [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

