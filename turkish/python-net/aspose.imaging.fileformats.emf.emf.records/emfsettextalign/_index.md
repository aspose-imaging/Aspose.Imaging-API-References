---
title: "EmfSetTextAlign Sınıfı"
type: docs
weight: 1300
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---

**Summary:** The EMR_SETTEXTALIGN record specifies text alignment.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextAlign

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSetTextAlign()](#EmfSetTextAlign__1) | Yeni bir [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) sınıfı örneği başlatır. |
| [EmfSetTextAlign(source)](#EmfSetTextAlign_source_2) | Yeni bir [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| text_alignment_mode | int | r/w | Metin hizalamasını belirten bir maske kullanarak <br/>            metin hizalama bayraklarıyla 32-bit işaretsiz tamsayıyı alır veya ayarlar. Bu bayraklar, yatay temel çizgiye sahip metin için [WmfTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)<br/>            ([MS-WMF] bölüm 2.1.2.3) veya dikey temel çizgiye sahip metin için [WmfVerticalTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)<br/>            ([MS-WMF] bölüm 2.1.2.4) olabilir. Yatay ve dikey hizalamayı etkileyenlerden sadece bir değer seçilebilir. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSetTextAlign() {#EmfSetTextAlign__1}


```
 EmfSetTextAlign() 
```

Yeni bir [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) sınıfı örneği başlatır.

### Constructor: EmfSetTextAlign(source) {#EmfSetTextAlign_source_2}


```
 EmfSetTextAlign(source) 
```

Yeni bir [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) sınıfı örneği başlatır.

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


