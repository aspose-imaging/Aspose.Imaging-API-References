---
title: "EmfArcTo Sınıfı"
type: docs
weight: 50
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/
---

**Summary:** The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArcTo

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfArcTo()](#EmfArcTo__1) | Yeni bir [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) sınıfı örneği başlatır. |
| [EmfArcTo(source)](#EmfArcTo_source_2) | Yeni bir [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bit WMF RectL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.19'da belirtilen, <br/>            sınırlayıcı dikdörtgeni belirten. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesini alır veya ayarlar, ikinci radyalin bitiş noktasının koordinatlarını mantıksal birimlerde <br/>            belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'de belirtilen, <br/>            ilk radyalin bitiş noktasının koordinatlarını mantıksal birimlerde belirten. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfArcTo() {#EmfArcTo__1}


```
 EmfArcTo() 
```

Yeni bir [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) sınıfı örneği başlatır.

### Constructor: EmfArcTo(source) {#EmfArcTo_source_2}


```
 EmfArcTo(source) 
```

Yeni bir [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) sınıfı örneği başlatır.

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


