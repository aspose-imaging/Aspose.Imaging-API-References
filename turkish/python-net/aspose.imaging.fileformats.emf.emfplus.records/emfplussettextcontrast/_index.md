---
title: "EmfPlusSetTextContrast Sınıfı"
type: docs
weight: 550
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---

**Summary:** The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextContrast

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSetTextContrast(source)](#EmfPlusSetTextContrast_source_1) | [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| text_contrast | int | r/w | Gamma düzeltme değerini X 1000 alır veya ayarlar; bu, sonraki metin renderleme işlemlerine uygulanacaktır.<br/>            İzin verilen aralık 1000 ile 2200 arasındadır,<br/>            bu da 1.0 ile 2.2 arasındaki metin gamma değerlerini temsil eder. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSetTextContrast(source) {#EmfPlusSetTextContrast_source_1}


```
 EmfPlusSetTextContrast(source) 
```

[EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

