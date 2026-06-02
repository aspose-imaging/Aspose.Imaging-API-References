---
title: "EmfCommentEndGroup Sınıfı"
type: docs
weight: 200
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/
---

**Summary:** The EMR_COMMENT_ENDGROUP record specifies the end of a group of drawing records.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEndGroup

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCommentEndGroup(source)](#EmfCommentEndGroup_source_1) | Yeni bir [EmfCommentEndGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Bu yorum kaydının genel veri belirttiğini tanımlayan 32‑bit işaretsiz bir tamsayı alır veya ayarlar <br/>            . 0x43494447 değeri, ASCII dizgesi "CIDG" olup, bu kaydı bir EMR_COMMENT_PUBLIC kaydı olarak tanımlar <br/>            . |
| data_size | int | r/w | Kayıt tamponunda (RecordBuffer) gelen CommentIdentifier ve CommentRecordParm alanlarının boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Bu alanı izleyen. <br/>            Kendisinin veya AlignmentPadding alanının (varsa) boyutunu içermez. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Bu, genel yorum kaydı tipini tanımlayan 32‑bit işaretsiz bir tamsayı alır veya ayarlar <br/>            . Bu, önceki tabloda listelenen değerlerden biri OLMALIDIR; bu değerler EmrComment enumarasyonunda (bölüm 2.1.10) belirtilmiştir, aksi takdirde ek genel <br/>            yorum kaydı tipleri yazıcı sunucusunda uygulanmış olabilir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCommentEndGroup(source) {#EmfCommentEndGroup_source_1}


```
 EmfCommentEndGroup(source) 
```

Yeni bir [EmfCommentEndGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentendgroup/) sınıfı örneği başlatır.

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


