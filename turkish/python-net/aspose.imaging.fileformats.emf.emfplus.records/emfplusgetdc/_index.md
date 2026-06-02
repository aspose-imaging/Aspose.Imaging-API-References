---
title: "EmfPlusGetDc Sınıfı"
type: docs
weight: 300
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---

**Summary:** The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusGetDc

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusGetDc(source)](#EmfPlusGetDc_source_1) | Yeni bir [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | Kullanılmayan 16 bit işaretsiz tam sayıyı alır veya ayarlar. Bu alan sıfıra ayarlanmalı<br/>            ve alındığında mutlaka yok sayılmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusGetDc(source) {#EmfPlusGetDc_source_1}


```
 EmfPlusGetDc(source) 
```

Yeni bir [EmfPlusGetDc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

