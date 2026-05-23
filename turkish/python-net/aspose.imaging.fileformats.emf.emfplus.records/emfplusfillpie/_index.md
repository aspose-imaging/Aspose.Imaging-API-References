---
title: "EmfPlusFillPie Sınıfı"
type: docs
weight: 260
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | Yeni bir [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça tanımlayıcısını alır veya ayarlar<br/>            Fırçayı tanımlayan 32 bit işaretsiz tam sayı, içeriği Flags alanındaki S biti tarafından belirlenir. |
| sıkıştırılmış | bool | r/w | PointData'nın sıkıştırılıp sıkıştırılmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir.<br/>            Temizlenmişse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. <br/>            Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verilerini alır veya ayarlar<br/>            Ya bir EmfPlusRect ya da EmfPlusRectF nesnesi, dilim dilimini içeren elipsin sınırlayıcı kutusunu tanımlar. Bu dikdörtgen, dilimin konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne türü, Flags alanının değeriyle belirtilir. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| start_angle | float | r/w | Başlangıç açısını alır veya ayarlar<br/>            X ekseni ile dilim diliminin başlangıç noktası arasındaki açıyı belirten 32 bitlik, negatif olmayan kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak 360 modunda yorumlanmalıdır; kullanılan sonuç 0.0 dahil ve 360.0 hariç aralığında olmalıdır. |
| sweep_angle | float | r/w | Tarama açısını alır veya ayarlar<br/>            Başlangıç açısı değeriyle tanımlanan başlangıç noktasından ölçülen, çizilecek dilim dilimini tanımlayan yay uzunluğunu derece cinsinden belirten 32 bitlik kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 dahil aralığına sınırlanmalıdır. Pozitif bir değer, taramanın saat yönünde tanımlandığını, negatif bir değer ise saat yönünün tersinde tanımlandığını gösterir. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

Yeni bir [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

