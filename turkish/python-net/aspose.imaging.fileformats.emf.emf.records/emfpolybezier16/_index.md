---
title: "EmfPolyBezier16 Sınıfı"
type: docs
weight: 770
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---

**Summary:** The EMR_POLYBEZIER16 record specifies one or more Bezier curves. The curves are drawn using<br/>            the current pen.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyBezier16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolyBezier16()](#EmfPolyBezier16__1) | Yeni bir [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) sınıf örneği başlatır. |
| [EmfPolyBezier16(source)](#EmfPolyBezier16_source_2) | Yeni bir [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) sınıf örneği başlatır. |
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


### Constructor: EmfPolyBezier16() {#EmfPolyBezier16__1}


```
 EmfPolyBezier16() 
```

Yeni bir [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) sınıf örneği başlatır.

### Constructor: EmfPolyBezier16(source) {#EmfPolyBezier16_source_2}


```
 EmfPolyBezier16(source) 
```

Yeni bir [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) sınıf örneği başlatır.

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


