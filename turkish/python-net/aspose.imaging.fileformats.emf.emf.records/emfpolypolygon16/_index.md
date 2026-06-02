---
title: "EmfPolyPolygon16 Sınıfı"
type: docs
weight: 840
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---

**Summary:** The EMR_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined <br/>            using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn <br/>            by this record can overlap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPolyPolygon16()](#EmfPolyPolygon16__1) | Yeni bir [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) sınıf örneği başlatır |
| [EmfPolyPolygon16(source)](#EmfPolyPolygon16_source_2) | Yeni bir [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) sınıf örneği başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | WMF PointS nesnelerinin bir dizisini alır veya ayarlar, [MS-WMF] <br/>            bölüm 2.2.2.16'da belirtilen, nokta dizisini belirten. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bit WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) ve aygıt birimlerinde sınırlayıcı dikdörtgeni belirtir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPolyPolygon16() {#EmfPolyPolygon16__1}


```
 EmfPolyPolygon16() 
```

Yeni bir [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) sınıf örneği başlatır

### Constructor: EmfPolyPolygon16(source) {#EmfPolyPolygon16_source_2}


```
 EmfPolyPolygon16(source) 
```

Yeni bir [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) sınıf örneği başlatır

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


