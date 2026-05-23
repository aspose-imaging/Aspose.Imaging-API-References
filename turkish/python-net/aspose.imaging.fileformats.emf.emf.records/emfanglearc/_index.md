---
title: "EmfAngleArc Sınıf"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---

**Summary:** The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the <br/>            given radius and center. The length of the arc is defined by the given start and sweep angles

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAngleArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfAngleArc()](#EmfAngleArc__1) | Yeni bir örnek başlatır ve [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) sınıfını oluşturur. |
| [EmfAngleArc(source)](#EmfAngleArc_source_2) | Yeni bir örnek başlatır ve [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) sınıfını oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64-bit WMF PointL nesnesi alır veya ayarlar, [MS-WMF] bölüm 2.2.2.15'te belirtilen, <br/>            dairenin merkezinin mantıksal koordinatlarını belirtir. |
| yarıçap | int | r/w | Dairenin yarıçapını mantıksal birimlerde belirten 32-bit işaretsiz bir tam sayı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start_angle | float | r/w | Yay başlangıç açısını derece cinsinden belirten 32-bit float alır veya ayarlar. |
| sweep_angle | float | r/w | Yay süpürme açısını derece cinsinden belirten 32-bit float alır veya ayarlar. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfAngleArc() {#EmfAngleArc__1}


```
 EmfAngleArc() 
```

Yeni bir örnek başlatır ve [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) sınıfını oluşturur.

### Constructor: EmfAngleArc(source) {#EmfAngleArc_source_2}


```
 EmfAngleArc(source) 
```

Yeni bir örnek başlatır ve [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) sınıfını oluşturur.

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


