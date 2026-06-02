---
title: "EmfSaveDc Sınıfı"
type: docs
weight: 1030
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---

**Summary:** Saves the current state of playback device context on a<br/>            stack of states saved by preceding EMR_SAVEDC<br/>            records, if any. The state consists of graphics properties<br/>            and objects, including the currently selected bitmap,<br/>            brush, palette, font, pen, and region. An<br/>            EMR_RESTOREDC record is used to restore the state.<br/>            This EMF record specifies no parameters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSaveDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSaveDc()](#EmfSaveDc__1) | Yeni bir [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) sınıfının bir örneğini başlatır. |
| [EmfSaveDc(source)](#EmfSaveDc_source_2) | Yeni bir [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSaveDc() {#EmfSaveDc__1}


```
 EmfSaveDc() 
```

Yeni bir [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) sınıfının bir örneğini başlatır.

### Constructor: EmfSaveDc(source) {#EmfSaveDc_source_2}


```
 EmfSaveDc(source) 
```

Yeni bir [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) sınıfının bir örneğini başlatır.

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


