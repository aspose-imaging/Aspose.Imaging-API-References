---
title: "EmfPlusFillPath Sınıfı"
type: docs
weight: 250
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---

**Summary:** Fill path record<br/>            FLAGS:<br/>            16-bit unsigned integer that provides information about how the operation is to be performed,<br/>            and about the structure of the record.<br/>            0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1<br/>            S X X X X X X X |   ObjectId    |<br/>            S (1 bit): This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.<br/>            X (1 bit): Reserved and MUST be ignored.<br/>            ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPath

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusFillPath(source)](#EmfPlusFillPath_source_1) | Yeni bir [EmpPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Fırça Kimliğini alır veya ayarlar<br/>            Fırçayı tanımlayan 32 bit işaretsiz tam sayı, içeriği <br/>            Flags alanındaki S biti tarafından belirlenir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| is_color | bool | r/w | Bu örneğin renk olup olmadığını gösteren bir değeri alır veya ayarlar.<br/>            Ayarlanmışsa, BrushId bir renk olarak EmfPlusARGB nesnesini (bölüm 2.2.2.1) belirtir. Temizlenmişse,<br/>            BrushId EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. |
| object_id | System.Byte | r/w | Nesne tanımlayıcısını alır veya ayarlar.<br/>            Doldurulacak EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizini, EMF+ Nesne Tablosunda. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusFillPath(source) {#EmfPlusFillPath_source_1}


```
 EmfPlusFillPath(source) 
```

Yeni bir [EmpPlusFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

