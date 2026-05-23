---
title: "EmfExtCreateFontIndirectW Sınıfı"
type: docs
weight: 420
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

**Summary:** The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW__1) | Yeni bir [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) sınıfı örneği başlatır. |
| [EmfExtCreateFontIndirectW(source)](#EmfExtCreateFontIndirectW_source_2) | Yeni bir [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| elw | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | r/w | LogFontExDv nesnesini alır veya ayarlar (bölüm 2.2.15), bu nesne mantıksal yazı tipini belirler. Bir<br/>            LogFont nesnesi 2.2.13 VAR OLABİLİR yerine.[90]Bu alandaki nesnenin türünün belirlenmesi süreci aşağıda açıklanmıştır. |
| ih_fonts | int | r/w | 32-bit işaretsiz tamsayıyı alır veya ayarlar, bu değer mantıksal yazı tipi nesnesinin EMF Nesne Tablosundaki (bölüm 3.1.1.1) dizinini belirler<br/>            . Bu dizin KAYDEDİLMELİDİR, böylece nesne yeniden kullanılabilir veya değiştirilebilir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW__1}


```
 EmfExtCreateFontIndirectW() 
```

Yeni bir [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) sınıfı örneği başlatır.

### Constructor: EmfExtCreateFontIndirectW(source) {#EmfExtCreateFontIndirectW_source_2}


```
 EmfExtCreateFontIndirectW(source) 
```

Yeni bir [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) sınıfı örneği başlatır.

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


