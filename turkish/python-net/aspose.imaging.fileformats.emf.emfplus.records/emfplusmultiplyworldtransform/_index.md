---
title: "EmfPlusMultiplyWorldTransform Sınıfı"
type: docs
weight: 320
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---

**Summary:** The EmfPlusMultiplyWorldTransform record multiplies the current world space transform by a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusMultiplyWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusMultiplyWorldTransform(source)](#EmfPlusMultiplyWorldTransform_source_1) | Yeni bir [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Çarpma matrisini tanımlayan bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. |
| post_multiplied_matrix | bool | r | [post multiplied matrix] olup olmadığını gösteren bir değer alır.<br/>            Ayarlanmışsa, dönüşüm matrisi sonradan çarpılmalıdır. Temizlenmişse, önceden çarpılmalıdır. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusMultiplyWorldTransform(source) {#EmfPlusMultiplyWorldTransform_source_1}


```
 EmfPlusMultiplyWorldTransform(source) 
```

Yeni bir [EmfPlusMultiplyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

