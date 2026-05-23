---
title: "EmfPlusSave Sınıfı"
type: docs
weight: 420
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---

**Summary:** The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSave

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusSave(source)](#EmfPlusSave_source_1) | Yeni bir [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| data_size | int | r/w | Takip eden RecordData alanındaki veri baytlarının 32-bit hizalı sayısını TANIMLAMASI gereken 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>            Bu sayı 12 baytlık kayıt başlığını içermez. |
| flags | int | r/w | İşlemin nasıl gerçekleştirileceği ve kaydın yapısı hakkında bilgi içeren 16-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | 12 baytlık kayıt başlığı ve kayda özgü verileri dahil olmak üzere, tüm kayıttaki 32-bit hizalı bayt sayısını belirten 32-bit işaretsiz tam sayıyı alır veya ayarlar.<br/>             |
| stack_index | int | r/w | Grafik durumu ile ilişkilendirilecek bir seviyeyi belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar.<br/>            Seviye değeri, sonraki bir EmfPlusRestore kaydı (bölüm 2.3.7.4) işlemi tarafından grafik durumunu geri almak için kullanılabilir. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Kayıt türünü tanımlayan 16-bit işaretsiz tam sayıyı alır. |


### Constructor: EmfPlusSave(source) {#EmfPlusSave_source_1}


```
 EmfPlusSave(source) 
```

Yeni bir [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Kaynak. |

