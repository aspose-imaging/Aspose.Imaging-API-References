---
title: "EmfFrameRgn Sınıfı"
type: docs
weight: 530
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

**Summary:** The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfFrameRgn()](#EmfFrameRgn__1) | Yeni bir [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) sınıfı örneği başlatır. |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_2) | Yeni bir [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 128-bit WMF RectL nesnesini alır veya ayarlar, [MS-WMF] bölüm 2.2.2.19'da belirtilen, <br/>            sınırlayıcı dikdörtgeni belirten. |
| height | int | r/w | Mantıksal birimlerde, yatay fırça <br/>            darbesinin yüksekliğini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
| ih_brush | int | r/w | Fırça EMF Nesne Tablosu indeksini belirten 32-bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | RegionData nesnesini belirten bir RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar, <br/>            mantıksal birimlerde. |
| rgn_data_size | int | r/w | Alır veya ayarlar bir 32-bit işaretsiz tam sayıyı, bayt cinsinden bölge verisinin boyutunu belirten. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| width | int | r/w | Mantıksal birimlerde, dikey fırça darbesinin genişliğini belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

Yeni bir [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) sınıfı örneği başlatır.

### Constructor: EmfFrameRgn(source) {#EmfFrameRgn_source_2}


```
 EmfFrameRgn(source) 
```

Yeni bir [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) sınıfı örneği başlatır.

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


