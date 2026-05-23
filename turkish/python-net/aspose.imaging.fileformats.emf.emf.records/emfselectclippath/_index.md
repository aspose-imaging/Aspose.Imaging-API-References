---
title: "EmfSelectClipPath Sınıfı"
type: docs
weight: 1060
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---

**Summary:** The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback <br/>            device context, combining the new region with any existing clipping region using the specified mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectClipPath

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSelectClipPath()](#EmfSelectClipPath__1) | Yeni bir [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) sınıfının bir örneğini başlatır. |
| [EmfSelectClipPath(source)](#EmfSelectClipPath_source_2) | Yeni bir [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | Yolu kullanma şeklini belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. Değer <br/>            RegionMode numaralandırmasında (bölüm 2.1.29) olmalıdır. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSelectClipPath() {#EmfSelectClipPath__1}


```
 EmfSelectClipPath() 
```

Yeni bir [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) sınıfının bir örneğini başlatır.

### Constructor: EmfSelectClipPath(source) {#EmfSelectClipPath_source_2}


```
 EmfSelectClipPath(source) 
```

Yeni bir [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) sınıfının bir örneğini başlatır.

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


