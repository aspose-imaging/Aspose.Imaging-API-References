---
title: "EmfFillRgn Sınıfı"
type: docs
weight: 500
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---

**Summary:** The EMR_FILLRGN record fills the specified region by using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfFillRgn()](#EmfFillRgn__1) | Yeni bir [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) sınıfı örneği başlatır. |
| [EmfFillRgn(source)](#EmfFillRgn_source_2) | Yeni bir [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Alır veya ayarlar bir 128-bit WMF RectL nesnesi, [MS-WMF] bölüm 2.2.2.19'da belirtilen, <br/>            sınırlayıcı dikdörtgeni belirten. |
| ih_brush | int | r/w | Bölgeyi doldurmak için fırça EMF Nesne Tablosu indeksini belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar <br/>            . |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | RegionData (bölüm 2.2.24) nesnesini içeren RgnDataSize uzunluğunda bir bayt dizisi alır veya ayarlar. |
| rgn_data_size | int | r/w | Alır veya ayarlar bir 32-bit işaretsiz tam sayıyı, bayt cinsinden bölge verisinin boyutunu belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfFillRgn() {#EmfFillRgn__1}


```
 EmfFillRgn() 
```

Yeni bir [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) sınıfı örneği başlatır.

### Constructor: EmfFillRgn(source) {#EmfFillRgn_source_2}


```
 EmfFillRgn(source) 
```

Yeni bir [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) sınıfı örneği başlatır.

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


