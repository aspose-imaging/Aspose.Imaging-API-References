---
title: "EmfDeleteObject Sınıfı"
type: docs
weight: 340
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---

**Summary:** The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDeleteObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfDeleteObject()](#EmfDeleteObject__1) | Yeni bir [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) sınıfı örneği başlatır. |
| [EmfDeleteObject(record)](#EmfDeleteObject_record_2) | Yeni bir [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Grafik nesnesinin EMF Nesne Tablosundaki indeksini veya StockObject sayımından bir stok nesnesinin indeksini belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar.<br/>             |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfDeleteObject() {#EmfDeleteObject__1}


```
 EmfDeleteObject() 
```

Yeni bir [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) sınıfı örneği başlatır.

### Constructor: EmfDeleteObject(record) {#EmfDeleteObject_record_2}


```
 EmfDeleteObject(record) 
```

Yeni bir [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) sınıfı örneği başlatır.

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


