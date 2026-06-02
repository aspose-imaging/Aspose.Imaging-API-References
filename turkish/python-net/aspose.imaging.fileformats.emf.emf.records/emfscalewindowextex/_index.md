---
title: "EmfScaleWindowExtex Sınıf"
type: docs
weight: 1050
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---

**Summary:** The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by<br/>            using the ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleWindowExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex__1) | Yeni bir örnek başlatır ve [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) sınıfını oluşturur. |
| [EmfScaleWindowExtex(source)](#EmfScaleWindowExtex_source_2) | Yeni bir örnek başlatır ve [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) sınıfını oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| x_denom | int | r/w | Yatay bölücüyü belirten 32-bit işaretli bir tam sayı alır veya ayarlar. SIFIR OLMAMALIDIR. |
| x_num | int | r/w | Yatay çarpanı belirten 32-bit işaretli bir tam sayı alır veya ayarlar. SIFIR OLMAMALIDIR. |
| y_denom | int | r/w | Dikey bölen'i belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. SIFIR OLMAMASI GEREKİR. |
| y_num | int | r/w | Dikey çarpanı belirten 32-bit işaretli bir tam sayıyı alır veya ayarlar. SIFIR OLMAMASI GEREKİR. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfScaleWindowExtex() {#EmfScaleWindowExtex__1}


```
 EmfScaleWindowExtex() 
```

Yeni bir örnek başlatır ve [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) sınıfını oluşturur.

### Constructor: EmfScaleWindowExtex(source) {#EmfScaleWindowExtex_source_2}


```
 EmfScaleWindowExtex(source) 
```

Yeni bir örnek başlatır ve [EmfScaleWindowExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/) sınıfını oluşturur.

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


