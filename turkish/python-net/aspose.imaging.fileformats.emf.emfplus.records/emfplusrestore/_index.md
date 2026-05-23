---
title: "EmfPlusRestore Sınıfı"
type: docs
weight: 400
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

**Summary:** The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_1) | Yeni bir [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| stack_index | int | r/w | Bir grafik durumuyla ilişkili seviyeyi belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Seviye değeri, önceki bir EmfPlusSave kaydı (bölüm 2.3.7.5) tarafından grafik durumuna atanmıştır. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusRestore(source) {#EmfPlusRestore_source_1}


```
 EmfPlusRestore(source) 
```

Yeni bir [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

