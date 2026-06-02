---
title: "EmfSelectObject Sınıfı"
type: docs
weight: 1070
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

**Summary:** The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSelectObject()](#EmfSelectObject__1) | Yeni bir [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) sınıfının bir örneğini başlatır. |
| [EmfSelectObject(record)](#EmfSelectObject_record_2) | Yeni bir [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| object_handle | int | r/w | EMF Nesne Tablosundaki bir grafik nesnesinin indeksini veya <br/>            [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/) enumundan bir stok nesnesinin indeksini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSelectObject() {#EmfSelectObject__1}


```
 EmfSelectObject() 
```

Yeni bir [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) sınıfının bir örneğini başlatır.

### Constructor: EmfSelectObject(record) {#EmfSelectObject_record_2}


```
 EmfSelectObject(record) 
```

Yeni bir [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) sınıfının bir örneğini başlatır.

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


