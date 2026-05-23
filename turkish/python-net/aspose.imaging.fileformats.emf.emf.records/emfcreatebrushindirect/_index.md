---
title: "EmfCreateBrushIndirect Sınıfı"
type: docs
weight: 260
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

**Summary:** The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect__1) | Yeni bir [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) sınıfının örneğini başlatır. |
| [EmfCreateBrushIndirect(source)](#EmfCreateBrushIndirect_source_2) | Yeni bir [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| ih_brush | int | r/w | Mantıksal fırça nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksini belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar<br/>            . Bu indeks, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR. |
| log_brush | [EmfLogBrushEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/) | r/w | Stil, renk ve mantıksal fırçanın desenini belirten bir LogBrushEx nesnesini alır veya ayarlar (bölüm 2.2.12). Bu nesnedeki BrushStyle alanı BS_SOLID,<br/>            BS_HATCHED veya BS_NULL olmalıdır. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCreateBrushIndirect() {#EmfCreateBrushIndirect__1}


```
 EmfCreateBrushIndirect() 
```

Yeni bir [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) sınıfının örneğini başlatır.

### Constructor: EmfCreateBrushIndirect(source) {#EmfCreateBrushIndirect_source_2}


```
 EmfCreateBrushIndirect(source) 
```

Yeni bir [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) sınıfının örneğini başlatır.

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


