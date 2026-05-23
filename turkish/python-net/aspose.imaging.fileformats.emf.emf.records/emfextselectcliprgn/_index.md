---
title: "EmfExtSelectClipRgn Sınıfı"
type: docs
weight: 460
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---

**Summary:** The EMR_EXTSELECTCLIPRGN record combines the specified region with the current clip region <br/>            using the specified mode. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtSelectClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn__1) | Yeni bir [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) sınıfının bir örneğini başlatır. |
| [EmfExtSelectClipRgn(source)](#EmfExtSelectClipRgn_source_2) | Yeni bir [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | Bölgeyi kullanma şeklini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Değer RegionMode (bölüm 2.1.29) enumunda olmalıdır. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Mantıksal birimlerde bir RegionData nesnesini belirten RgnDataSize uzunluğunda bayt dizisini alır veya ayarlar. <br/>            RegionMode RGN_COPY ise, bu veri atlanabilir ve kırpma bölgesi varsayılan (NULL) kırpma bölgesine ayarlanmalıdır. |
| rgn_data_size | int | r/w | Bölge verisinin bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExtSelectClipRgn() {#EmfExtSelectClipRgn__1}


```
 EmfExtSelectClipRgn() 
```

Yeni bir [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) sınıfının bir örneğini başlatır.

### Constructor: EmfExtSelectClipRgn(source) {#EmfExtSelectClipRgn_source_2}


```
 EmfExtSelectClipRgn(source) 
```

Yeni bir [EmfExtSelectClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/) sınıfının bir örneğini başlatır.

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


