---
title: "EmfSetBrushOrgEx Sınıfı"
type: docs
weight: 1120
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---

**Summary:** The EMR_SETBRUSHORGEX record specifies the origin of the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBrushOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx__1) | [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) sınıfının yeni bir örneğini başlatır. |
| [EmfSetBrushOrgEx(source)](#EmfSetBrushOrgEx_source_2) | [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | [MS-WMF] bölüm 2.2.2.15'de belirtilen 64-bit WMF PointL nesnesini alır veya ayarlar, <br/>            bu nesne fırçanın cihaz birimlerinde yatay ve dikey başlangıç noktasını belirler. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSetBrushOrgEx() {#EmfSetBrushOrgEx__1}


```
 EmfSetBrushOrgEx() 
```

[EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) sınıfının yeni bir örneğini başlatır.

### Constructor: EmfSetBrushOrgEx(source) {#EmfSetBrushOrgEx_source_2}


```
 EmfSetBrushOrgEx(source) 
```

[EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) sınıfının yeni bir örneğini başlatır.

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


