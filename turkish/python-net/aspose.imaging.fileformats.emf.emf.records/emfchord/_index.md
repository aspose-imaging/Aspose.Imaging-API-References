---
title: "EmfChord Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Yeni bir [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) sınıfı örneği başlatır. |
| [EmfChord(source)](#EmfChord_source_2) | Yeni bir [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | [MS-WMF] bölüm 2.2.2.19'da belirtilen 128-bit WMF RectL nesnesini alır veya ayarlar, bu <br/>            kapsayıcı-kapsayıcı sınırlayıcı dikdörtgeni belirtir. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesini alır veya ayarlar, kordun sonunu tanımlayan radyalin son noktasının mantıksal koordinatlarını <br/>            belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'de belirtilen, <br/>            kordun başlangıcını tanımlayan radyalin son noktasının mantıksal koordinatlarını belirten. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Yeni bir [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) sınıfı örneği başlatır.

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Yeni bir [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) sınıfı örneği başlatır.

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


