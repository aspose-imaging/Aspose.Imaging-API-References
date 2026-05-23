---
title: "EmfCreatePen Sınıfı"
type: docs
weight: 320
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---

**Summary:** The EMR_CREATEPEN record defines a logical pen for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCreatePen()](#EmfCreatePen__1) | Yeni bir [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/) sınıfı örneği başlatır. |
| [EmfCreatePen(source)](#EmfCreatePen_source_2) | Yeni bir [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| ih_pen | int | r/w | Alır veya ayarlar bir 32-bit işaretsiz tam sayıyı, mantıksal kalem nesnesinin EMF Object Table (section 3.1.1.1) içindeki dizinini belirten<br/>            Bu dizin KAYDEDİLMELİDİR, böylece bu nesne yeniden kullanılabilir veya değiştirilebilir. |
| log_pen | [EmfLogPen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpen/) | r/w | Alır veya ayarlar bir LogPen nesnesini (bölüm 2.2.19) stil, genişlik ve renk<br/>            mantıksal kalemin. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCreatePen() {#EmfCreatePen__1}


```
 EmfCreatePen() 
```

Yeni bir [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/) sınıfı örneği başlatır.

### Constructor: EmfCreatePen(source) {#EmfCreatePen_source_2}


```
 EmfCreatePen(source) 
```

Yeni bir [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/) sınıfı örneği başlatır.

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


