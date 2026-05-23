---
title: "EmfSetPixelV Sınıfı"
type: docs
weight: 1260
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---

**Summary:** The EMR_SETPIXELV record defines the color of the pixel at the specified logical coordinates.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPixelV

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSetPixelV()](#EmfSetPixelV__1) | Yeni bir [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) sınıfı örneği başlatır. |
| [EmfSetPixelV(source)](#EmfSetPixelV_source_2) | Yeni bir [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Piksel rengini belirten 32 bit WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| pixel | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 64 bit WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar; bu <br/>            mantıksal koordinatları piksel için belirtir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSetPixelV() {#EmfSetPixelV__1}


```
 EmfSetPixelV() 
```

Yeni bir [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) sınıfı örneği başlatır.

### Constructor: EmfSetPixelV(source) {#EmfSetPixelV_source_2}


```
 EmfSetPixelV(source) 
```

Yeni bir [EmfSetPixelV](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/) sınıfı örneği başlatır.

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


