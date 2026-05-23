---
title: "EmfPolygon16 Sınıfı"
type: docs
weight: 910
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---

**Summary:** The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines. The polygon is outlined by using the current pen and filled by using the current brush <br/>            and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolygon16()](#EmfPolygon16__1) | Yeni bir [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) sınıfı örneği başlatır. |
| [EmfPolygon16(source)](#EmfPolygon16_source_2) | Yeni bir [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) sınıfı örneği başlatır. |
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


### Constructor: EmfPolygon16() {#EmfPolygon16__1}


```
 EmfPolygon16() 
```

Yeni bir [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) sınıfı örneği başlatır.

### Constructor: EmfPolygon16(source) {#EmfPolygon16_source_2}


```
 EmfPolygon16(source) 
```

Yeni bir [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) sınıfı örneği başlatır.

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


