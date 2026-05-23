---
title: "EmfPlusDrawArc Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Yeni bir [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Verinin boyutunu alır veya ayarlar.<br/>            32 bitlik işaretsiz bir tam sayı, ardından gelen kayıt‑özel verinin 32 bit hizalı bayt sayısını belirtir.<br/>            Bu kayıt türü için değer AŞAĞIDAKİLERDEN BİRİ OLMALIDIR:<br/>            0x00000010 Flags alanındaki C biti ayarlıysa.<br/>            0x00000018 Flags alanındaki C biti temizse. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Yay çizmek için EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) indeksidir. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| rect_float | bool | r/w | Verinin EmfPlusRectF veya EmfPlusRect kayıtları içerip içermediğini gösteren bir değeri alır veya ayarlar.<br/>            Bu bit, RectData alanındaki verinin sıkıştırılıp sıkıştırılmadığını gösterir.<br/>            Ayarlıysa, RectData bir EmfPlusRect nesnesi (bölüm 2.2.2.38) içerir.<br/>            Temizse, RectData bir EmfPlusRectF nesnesi (bölüm 2.2.2.39) içerir. |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Dikdörtgen verisini alır veya ayarlar<br/>            Yay ile aynı doğrultuda olan elipsin sınırlayıcı kutusunu tanımlayan bir EmfPlusRect veya EmfPlusRectF nesnesi. Bu dikdörtgen yayının konumunu, boyutunu ve şeklini tanımlar. Bu alandaki nesne tipi Flags alanının değeriyle belirlenir. |
| size | int | r/w | Boyutu alır veya ayarlar.<br/>            12 baytlık kayıt başlığı ve kayıt‑özel veriler dahil olmak üzere tüm kayıttaki bayt sayısını 32 bit hizalı olarak belirten 32 bitlik işaretsiz bir tam sayı. Bu kayıt türü için değer AŞAĞIDAKİLERDEN BİRİ OLMALIDIR:<br/>            0x0000001C  Flags alanındaki C biti ayarlıysa.<br/>            0x00000024  Flags alanındaki C biti temizse. |
| start_angle | float | r/w | Başlangıç açısını alır veya ayarlar<br/>            X ekseni ile yay başlangıç noktası arasındaki açıyı belirten 32 bitlik negatif olmayan kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak 360 modunda yorumlanmalı ve kullanılan sonuç 0.0 dahil 360.0 hariç aralığında olmalıdır. |
| sweep_angle | float | r/w | Tarama açısını alır veya ayarlar<br/>            Başlangıç açısı değeriyle tanımlanan noktadan ölçülen, derece cinsinden yay uzunluğunu belirten 32 bitlik kayan nokta değeri. Herhangi bir değer kabul edilebilir, ancak -360.0 ile 360.0 arasında (dahil) sınırlanmalıdır. Pozitif bir değer, taramanın saat yönünde tanımlandığını, negatif bir değer ise saat yönünün tersinde tanımlandığını gösterir. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Yeni bir [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

