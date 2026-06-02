---
title: "EmfPlusSetRenderingOrigin Sınıfı"
type: docs
weight: 540
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---

**Summary:** The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetRenderingOrigin

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetRenderingOrigin(source)](#EmfPlusSetRenderingOrigin_source_1) | Yeni bir [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |
| x | int | r/w | İşleme başlangıç noktasının yatay koordinat değerini tanımlayan 32 bitlik işaretsiz bir tam sayı alır veya ayarlar. |
| y | int | r/w | İşleme başlangıç noktasının dikey koordinat değerini tanımlayan 32 bitlik işaretsiz bir tam sayı alır veya ayarlar. |


### Constructor: EmfPlusSetRenderingOrigin(source) {#EmfPlusSetRenderingOrigin_source_1}


```
 EmfPlusSetRenderingOrigin(source) 
```

Yeni bir [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

