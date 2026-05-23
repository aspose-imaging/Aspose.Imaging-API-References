---
title: "EmfCreateColorSpaceW Sınıfı"
type: docs
weight: 280
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

**Summary:** The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCreateColorSpaceW(source)](#EmfCreateColorSpaceW_source_1) | Yeni bir [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Veri alanının boyutunu bayt cinsinden belirten 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| veri | System.Byte | r/w | Renk profili verilerini belirten isteğe bağlı bir bayt dizisini alır veya ayarlar. |
| dw_flags | int | r/w | Bu kayıttaki veri hakkında bilgi sağlayan 32 bit işaretsiz bir tam sayıyı alır veya ayarlar. |
| ih_cs | int | r/w | Mantıksal renk uzayı nesnesinin EMF nesne tablosundaki (bölüm 3.1.1.1) dizinini belirten 32‑bit işaretsiz bir tamsayı alır veya ayarlar.<br/>            Bu dizin, nesnenin yeniden kullanılabilmesi veya değiştirilebilmesi için KAYDEDİLMELİDİR. |
| lcs | [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | r/w | Unicode UTF16-LE karakterlerinde bir renk profili adını belirtebilen bir WMF LogColorSpaceW nesnesini ([MS-WMF] bölüm 2.2.2.12) alır veya ayarlar<br/>             |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCreateColorSpaceW(source) {#EmfCreateColorSpaceW_source_1}


```
 EmfCreateColorSpaceW(source) 
```

Yeni bir [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) sınıfının bir örneğini başlatır.

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


