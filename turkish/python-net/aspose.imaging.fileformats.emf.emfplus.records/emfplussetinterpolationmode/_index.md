---
title: "EmfPlusSetInterpolationMode Sınıfı"
type: docs
weight: 510
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---

**Summary:** The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetInterpolationMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetInterpolationMode(source)](#EmfPlusSetInterpolationMode_source_1) | Yeni bir [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| interpolation_mode | [EmfPlusInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/) | r/w | InterpolationMode sayımından (bölüm 2.1.1.16) ara değerleme modu değerini alır veya ayarlar. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSetInterpolationMode(source) {#EmfPlusSetInterpolationMode_source_1}


```
 EmfPlusSetInterpolationMode(source) 
```

Yeni bir [EmfPlusSetInterpolationMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

