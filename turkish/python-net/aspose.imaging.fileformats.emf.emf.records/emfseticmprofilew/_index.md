---
title: "EmfSetIcmProfileW Sınıfı"
type: docs
weight: 1180
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

**Summary:** The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfSetIcmProfileW(source)](#EmfSetIcmProfileW_source_1) | Yeni bir [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Eklenmişse renk profili verisinin boyutunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| cb_name | int | r/w | İstenen renk profilinin Unicode<br/>            UTF16-LE adındaki bayt sayısını belirten 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| veri | System.Byte | r/w | İstenen renk profilinin UTF16-LE<br/>            adını ve ham verisini belirten, bayt cinsinden (cbName + cbData) boyutunda bir dizi alır veya ayarlar. |
| dw_flags | int | r/w | Renk profili bayraklarını içeren 32-bit işaretsiz tamsayıyı alır veya ayarlar. |
| ad | string | r | Adı alır |
| raw_data | System.Byte | r | Ham veriyi alır |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfSetIcmProfileW(source) {#EmfSetIcmProfileW_source_1}


```
 EmfSetIcmProfileW(source) 
```

Yeni bir [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) sınıfının örneğini başlatır.

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


