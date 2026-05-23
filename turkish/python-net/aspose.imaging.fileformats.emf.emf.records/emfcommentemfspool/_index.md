---
title: "EmfCommentEmfSpool Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

**Summary:** The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) sınıfının yeni bir örneğini başlatır. |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_2) | [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Bu yorum kaydının EMFSPOOL kayıtlarını içerdiğini belirten 32-bit işaretsiz tamsayı alır veya ayarlar <br/>            . Değer 0x00000000, bunun bir <br/>            EMR_COMMENT_EMFSPOOL kaydı olduğunu gösterir. |
| data_size | int | r/w | Kayıt tamponunda (RecordBuffer) gelen CommentIdentifier ve CommentRecordParm alanlarının boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Bu alanı izleyen. <br/>            Kendisinin veya AlignmentPadding alanının (varsa) boyutunu içermez. |
| emf_spool_record_identifier | [EmfCommentEmfSpool+EmfSpoolRecordIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool+emfspoolrecordidentifierenum/) | r/w | EMR_COMMENT_EMFSPOOL kaydının türünü belirten 32-bit işaretsiz tamsayı alır veya ayarlar <br/>            . |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Bir veya daha fazla <br/>            EMFSPOOL yazı tipi tanım kaydını ([MS-EMFSPOOL] bölüm 2.2.3.3) içeren değişken uzunlukta bayt dizisi alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

[EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) sınıfının yeni bir örneğini başlatır.

### Constructor: EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_2}


```
 EmfCommentEmfSpool(source) 
```

[EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) sınıfının yeni bir örneğini başlatır.

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


