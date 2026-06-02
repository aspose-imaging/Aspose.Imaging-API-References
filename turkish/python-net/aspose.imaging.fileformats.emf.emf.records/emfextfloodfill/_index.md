---
title: "EmfExtFloodFill Sınıfı"
type: docs
weight: 450
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---

**Summary:** The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtFloodFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExtFloodFill(source)](#EmfExtFloodFill_source_1) | Yeni bir [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar; bu nesne <br/>            FloodFillMode ile doldurulacak alanı belirlemek için kullanılır. |
| flood_fill_mode | [EmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emffloodfill/) | r/w | Renk değerinin <br/>            flood fill işlemi için alanı belirlemede nasıl kullanılacağını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. Değer, FloodFill <br/>            enumarasyonunda (bölüm 2.1.13) bulunmalıdır. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Doldurmanın başladığı koordinatları (mantıksal birimlerde) belirten WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExtFloodFill(source) {#EmfExtFloodFill_source_1}


```
 EmfExtFloodFill(source) 
```

Yeni bir [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) sınıfı örneği başlatır.

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


