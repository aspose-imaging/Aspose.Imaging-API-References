---
title: "EmfPolylineTo Sınıfı"
type: docs
weight: 940
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/
---

**Summary:** The EMR_POLYLINETO record specifies one or more straight lines based upon the current position.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolylineTo()](#EmfPolylineTo__1) | Yeni bir [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) sınıf örneği başlatır. |
| [EmfPolylineTo(source)](#EmfPolylineTo_source_2) | Yeni bir [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Mantıksal birimlerde nokta verilerini belirten WMF PointL nesnelerinin bir dizisini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bit WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) ve aygıt birimlerinde sınırlayıcı dikdörtgeni belirtir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPolylineTo() {#EmfPolylineTo__1}


```
 EmfPolylineTo() 
```

Yeni bir [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) sınıf örneği başlatır.

### Constructor: EmfPolylineTo(source) {#EmfPolylineTo_source_2}


```
 EmfPolylineTo(source) 
```

Yeni bir [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) sınıf örneği başlatır.

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


