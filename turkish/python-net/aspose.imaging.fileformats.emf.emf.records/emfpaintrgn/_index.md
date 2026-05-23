---
title: "EmfPaintRgn Sınıfı"
type: docs
weight: 710
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---

**Summary:** The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the <br/>            playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPaintRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPaintRgn()](#EmfPaintRgn__1) | Yeni bir [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/) sınıfının örneğini başlatır. |
| [EmfPaintRgn(source)](#EmfPaintRgn_source_2) | Yeni bir [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Alır veya ayarlar bir 128-bit WMF RectL nesnesi, [MS-WMF] bölüm 2.2.2.19'da belirtilen, <br/>            sınırlayıcı dikdörtgeni belirten. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Alır veya ayarlar bir RgnDataSize uzunluğunda bayt dizisini, mantıksal birimler içinde bir RegionData (bölüm <br/>            2.2.24) nesnesini belirten. |
| rgn_data_size | int | r/w | Alır veya ayarlar bir 32-bit işaretsiz tam sayıyı, bayt cinsinden bölge verisinin boyutunu belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfPaintRgn() {#EmfPaintRgn__1}


```
 EmfPaintRgn() 
```

Yeni bir [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/) sınıfının örneğini başlatır.

### Constructor: EmfPaintRgn(source) {#EmfPaintRgn_source_2}


```
 EmfPaintRgn(source) 
```

Yeni bir [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/) sınıfının örneğini başlatır.

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


