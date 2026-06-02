---
title: "EmfScaleViewportExtex Sınıf"
type: docs
weight: 1040
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---

**Summary:** The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the<br/>            ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleViewportExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex__1) | Yeni bir [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) sınıfının örneğini başlatır. |
| [EmfScaleViewportExtex(source)](#EmfScaleViewportExtex_source_2) | Yeni bir [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| x_denom | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu sayı yatay bölen'i belirtir. Sıfır olamaz. |
| x_num | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu sayı yatay çarpanı belirtir. Sıfır olamaz. |
| y_denom | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu sayı dikey bölen'i belirtir. Sıfır olamaz. |
| y_num | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu sayı dikey çarpanı belirtir. Sıfır olamaz. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfScaleViewportExtex() {#EmfScaleViewportExtex__1}


```
 EmfScaleViewportExtex() 
```

Yeni bir [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) sınıfının örneğini başlatır.

### Constructor: EmfScaleViewportExtex(source) {#EmfScaleViewportExtex_source_2}


```
 EmfScaleViewportExtex(source) 
```

Yeni bir [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) sınıfının örneğini başlatır.

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


