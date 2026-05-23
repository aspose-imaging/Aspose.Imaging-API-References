---
title: "EmfOffsetClipRgn Sınıfı"
type: docs
weight: 690
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---

**Summary:** The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context <br/>            by the specified offsets.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfOffsetClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn__1) | Yeni bir [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) sınıfı örneği başlatır. |
| [EmfOffsetClipRgn(source)](#EmfOffsetClipRgn_source_2) | Yeni bir [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. <br/>            yatay ve dikey ofsetleri mantıksal birimlerde. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfOffsetClipRgn() {#EmfOffsetClipRgn__1}


```
 EmfOffsetClipRgn() 
```

Yeni bir [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) sınıfı örneği başlatır.

### Constructor: EmfOffsetClipRgn(source) {#EmfOffsetClipRgn_source_2}


```
 EmfOffsetClipRgn(source) 
```

Yeni bir [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) sınıfı örneği başlatır.

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


