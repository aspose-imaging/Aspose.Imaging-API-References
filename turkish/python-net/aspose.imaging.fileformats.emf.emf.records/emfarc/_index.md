---
title: "EmfArc Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) sınıfının yeni bir örneğini başlatır. |
| [EmfArc(source)](#EmfArc_source_2) | [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | [MS-WMF] bölüm 2.2.2.19'da belirtilen 128-bit WMF RectL nesnesini alır veya ayarlar, bu <br/>            kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirtir. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Mantıksal birimlerde, yayının bitiş noktasını tanımlayan radyal çizginin bitiş noktasının koordinatlarını belirten 64-bit WMF PointL nesnesini alır veya ayarlar <br/>            . |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | [MS-WMF] bölüm 2.2.2.15'de belirtilen 64-bit WMF PointL nesnesini alır veya ayarlar, bu <br/>            mantıksal birimlerde, yayının başlangıç noktasını tanımlayan radyal çizginin bitiş noktasının koordinatlarını belirler <br/>            . |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

[EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) sınıfının yeni bir örneğini başlatır.

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

[EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) sınıfının yeni bir örneğini başlatır.

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


