---
title: "EmfPlusDrawPie Sınıfı"
type: docs
weight: 170
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | Yeni bir [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir.<br/>            Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Pastayı çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verilerini alır veya ayarlar<br/>            Ya bir EmfPlusRect ya da EmfPlusRectF nesnesi, dilim dilimini içeren elipsin sınırlayıcı kutusunu tanımlar. Bu dikdörtgen, dilimin konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne türü, Flags alanının değeriyle belirtilir. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| start_angle | float | r/w | Başlangıç açısını alır veya ayarlar<br/>            X ekseni ile dilim diliminin başlangıç noktası arasındaki açıyı belirten 32 bitlik, negatif olmayan kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak 360 modunda yorumlanmalıdır; kullanılan sonuç 0.0 dahil ve 360.0 hariç aralığında olmalıdır. |
| sweep_angle | float | r/w | Tarama açısını alır veya ayarlar<br/>            Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, çizilecek dilim dilimini tanımlayan yay uzunluğunu derece cinsinden belirten 32 bitlik kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 dahil aralığına sınırlanmalıdır. Pozitif bir değer, taramanın saat yönünde tanımlandığını, negatif bir değer ise saat yönünün tersinde tanımlandığını gösterir. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

Yeni bir [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

