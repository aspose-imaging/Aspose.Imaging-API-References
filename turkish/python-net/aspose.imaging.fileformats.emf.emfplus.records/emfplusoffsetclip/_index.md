---
title: "EmfPlusOffsetClip Sınıfı"
type: docs
weight: 350
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/
---

**Summary:** The EmfPlusOffsetClip record applies a translation transform on the current clipping region for the world space.<br/>            The new current clipping region is set to the result of the translation transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusOffsetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusOffsetClip(source)](#EmfPlusOffsetClip_source_1) | Yeni bir [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| dx | float | r/w | Çevirme için yatay kaydırmayı belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| dy | float | r/w | Çevirme için dikey kaydırmayı belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusOffsetClip(source) {#EmfPlusOffsetClip_source_1}


```
 EmfPlusOffsetClip(source) 
```

Yeni bir [EmfPlusOffsetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusoffsetclip/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

