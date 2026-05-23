---
title: "EmfPlusFillPolygon Sınıfı"
type: docs
weight: 270
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Yeni bir [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça tanımlayıcısını alır veya ayarlar<br/>            Fırçayı tanımlayan 32 bit işaretsiz tam sayı, içeriği <br/>            Flags alanındaki S biti tarafından belirlenir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, BrushId bir renk olarak EmfPlusARGB nesnesi (bölüm 2.2.2.1) ile belirtilir. <br/>            Temizlenmişse, BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. |
| is_compressed | bool | r/w | Bu örneğin sıkıştırılmış olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, PointData 16 bit <br/>            tam sayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PointData 32 bit kayan nokta koordinatlarıyla koordinat <br/>            uzayında mutlak konumları belirtir. |
| is_relative | bool | r/w | Bu örneğin göreli olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, PointData içindeki her öğe, dizi içindeki önceki öğe tarafından belirtilen konuma göre koordinat <br/>            uzayında bir konumu belirtir. PointData'daki ilk öğe durumunda, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PointData C bayrağına göre mutlak konumları belirtir. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Nokta verisini alır veya ayarlar<br/>            Poligonun köşelerini tanımlayan Count sayıda nokta içeren bir dizi. <br/>            Dizideki ilk iki nokta poligonun ilk kenarını belirtir. <br/>            Her ek nokta yeni bir kenar belirtir, bu kenarın köşeleri <br/>            noktayı ve önceki noktayı içerir. Son nokta ve <br/>            ilk nokta çakışmazsa, bunlar poligonun son kenarını belirtir. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Yeni bir [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

