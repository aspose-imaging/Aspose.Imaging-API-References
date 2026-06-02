---
title: "EmfPlusSerializableObject Sınıfı"
type: docs
weight: 440
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| tampon | System.Byte | r/w | ObjectGUID alanındaki GUID ile eşleşen serileştirilmiş görüntü efektleri<br/>            parametre bloğunu içeren BufferSize baytlık bir dizi alır veya ayarlar. Bu, Image Effects nesnelerinden (bölüm 2.2.3) biri OLMALIDIR. |
| tampon_boyutu | int | r/w | 32 bit işaretsiz tamsayıyı alır veya ayarlar; bu, 32 bit hizalı Buffer alanının bayt cinsinden boyutunu belirtir. |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | Kullanılmayan 16 bit işaretsiz tamsayıyı alır veya ayarlar. Bu alan sıfır olarak ayarlanmalı<br/>            ve alındığında YOK SAYILMALIDIR. |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | Görüntü efektini alır veya ayarlar. |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | Görüntü efekti için GUID paket temsil değeri ([MS-DTYP] bölüm 2.3.4.2)<br/>            alır veya ayarlar. Bu, ImageEffects tanımlayıcılarından (bölüm 2.1.3.1) biriyle eşleşMELİDİR. |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

[EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

