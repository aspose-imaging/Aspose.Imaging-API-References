---
title: "EmfExcludeClipRect Sınıfı"
type: docs
weight: 410
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---

**Summary:** The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing <br/>            clipping region minus the specified rectangle. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExcludeClipRect

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExcludeClipRect()](#EmfExcludeClipRect__1) | Yeni bir [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) sınıfının örneğini başlatır. |
| [EmfExcludeClipRect(source)](#EmfExcludeClipRect_source_2) | Yeni bir [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| clip | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19) ve mantıksal birimlerde kırpma <br/>            dikdörtgenini belirler. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExcludeClipRect() {#EmfExcludeClipRect__1}


```
 EmfExcludeClipRect() 
```

Yeni bir [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) sınıfının örneğini başlatır.

### Constructor: EmfExcludeClipRect(source) {#EmfExcludeClipRect_source_2}


```
 EmfExcludeClipRect(source) 
```

Yeni bir [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) sınıfının örneğini başlatır.

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


