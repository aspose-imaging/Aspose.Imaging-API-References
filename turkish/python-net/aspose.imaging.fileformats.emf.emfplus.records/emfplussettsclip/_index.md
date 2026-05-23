---
title: "EmfPlusSetTsClip Sınıfı"
type: docs
weight: 570
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

**Summary:** The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_1) | Yeni bir [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| compressed | bool | r | Bu [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) sıkıştırılmış mı gösteren bir değeri alır.<br/>            Bu bit, rects alanındaki dikdörtgen verisinin biçimini belirtir. Ayarlıysa, her bir<br/>            dikdörtgen 4 bayt olarak tanımlanır. Temizlenmişse, her bir dikdörtgen 8 bayt olarak tanımlanır. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| num_rects | int | r | Dikdörtgen sayısını alır.<br/>            Bu alan, rect alanında tanımlanan dikdörtgenlerin sayısını belirtir. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Kırpma alanlarını tanımlayan NumRects dikdörtgenlerinden oluşan bir dizi alır veya ayarlar. Bu verinin biçimi Flags alanındaki C biti tarafından belirlenir. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_1}


```
 EmfPlusSetTsClip(source) 
```

Yeni bir [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

