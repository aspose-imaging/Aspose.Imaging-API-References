---
title: "EmfLineTo Sınıfı"
type: docs
weight: 590
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/
---

**Summary:** The EMR_LINETO record specifies a line from the current position up to, but not including, the<br/>            specified point.It resets the current position to the specified point.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfLineTo

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfLineTo()](#EmfLineTo__1) | Yeni bir [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) sınıf örneği başlatır. |
| [EmfLineTo(record)](#EmfLineTo_record_2) | Yeni bir [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesini, [MS-WMF] bölüm 2.2.2.15'te tanımlı olarak alır veya ayarlar, <br/>            bu nesne satırın bitiş noktasının koordinatlarını belirler. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfLineTo() {#EmfLineTo__1}


```
 EmfLineTo() 
```

Yeni bir [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) sınıf örneği başlatır.

### Constructor: EmfLineTo(record) {#EmfLineTo_record_2}


```
 EmfLineTo(record) 
```

Yeni bir [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) sınıf örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kayıt. |

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


