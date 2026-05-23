---
title: "EmfInvertRgn Sınıf"
type: docs
weight: 580
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---

**Summary:** The EMR_INVERTRGN record inverts the colors in the specified region.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfInvertRgn

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfInvertRgn(source)](#EmfInvertRgn_source_1) | Yeni bir [EmfInvertRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bitlik bir WMF RectL nesnesini alır veya ayarlar; bu nesne [MS-WMF] bölüm 2.2.2.19'da belirtilmiştir,<br/>            bu da sınırlayıcı dikdörtgeni belirtir. |
| rgn_data | System.Byte | r/w | Bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar; bu dizi mantıksal birimlerde bir RegionData nesnesini belirtir. |
| rgn_data_size | int | r/w | Alır veya ayarlar bir 32-bit işaretsiz tam sayıyı, bayt cinsinden bölge verisinin boyutunu belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfInvertRgn(source) {#EmfInvertRgn_source_1}


```
 EmfInvertRgn(source) 
```

Yeni bir [EmfInvertRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kaynak. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kaynak. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Kayıt türü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


