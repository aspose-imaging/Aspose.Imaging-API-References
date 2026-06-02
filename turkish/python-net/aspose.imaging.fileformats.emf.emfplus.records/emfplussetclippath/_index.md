---
title: "EmfPlusSetClipPath Sınıfı"
type: docs
weight: 460
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---

**Summary:** The EmfPlusSetClipPath record combines the current clipping region with a graphics path.<br/>            The new current clipping region is set to the result of the CombineMode operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipPath

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetClipPath(source)](#EmfPlusSetClipPath_source_1) | Yeni bir [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | CM (4 bit) değerini alır veya ayarlar: İki bölgeyi birleştirmek için mantıksal işlemi belirtir. Değerlerin anlamları için<br/>            CombineMode numaralandırmasına (bölüm 2.1.1.4) bakın. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| object_id | System.Byte | r/w | EMF+<br/>            Nesne Tablosundaki bir EmfPlusPath nesnesinin (bölüm 2.2.1.6) dizinini alır veya ayarlar. Değer 0 ile 63 arasında, dahil olmak üzere olmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSetClipPath(source) {#EmfPlusSetClipPath_source_1}


```
 EmfPlusSetClipPath(source) 
```

Yeni bir [EmfPlusSetClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

