---
title: "EmfCommentWindowsMetaFile Sınıfı"
type: docs
weight: 240
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---

**Summary:** The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentWindowsMetaFile

**Inheritance:** EmfCommentPublicRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfCommentWindowsMetaFile(source)](#EmfCommentWindowsMetaFile_source_1) | Yeni bir [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| checksum | int | r/w | Bu kaydın sağlama toplamını belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Bu yorum kaydının genel veri belirttiğini tanımlayan 32‑bit işaretsiz bir tamsayı alır veya ayarlar <br/>            . 0x43494447 değeri, ASCII dizgesi "CIDG" olup, bu kaydı bir EMR_COMMENT_PUBLIC kaydı olarak tanımlar <br/>            . |
| data_size | int | r/w | Kayıt tamponunda (RecordBuffer) gelen CommentIdentifier ve CommentRecordParm alanlarının boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. <br/>            Bu alanı izleyen. <br/>            Kendisinin veya AlignmentPadding alanının (varsa) boyutunu içermez. |
| flags | int | r/w | 0x00000000 olması gereken ve MUST yok sayılması gereken 32 bit değeri alır veya ayarlar. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Bu, genel yorum kaydı tipini tanımlayan 32‑bit işaretsiz bir tamsayı alır veya ayarlar <br/>            . Bu, önceki tabloda listelenen değerlerden biri OLMALIDIR; bu değerler EmrComment enumarasyonunda (bölüm 2.1.10) belirtilmiştir, aksi takdirde ek genel <br/>            yorum kaydı tipleri yazıcı sunucusunda uygulanmış olabilir. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
| version | [WmfMetafileVersion](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileversion/) | r/w | WMF metafile sürümünü, cihaz bağımsız bitmap'lere (DIB'ler) destek <br/>            açısından, WMF MetafileVersion <br/>            enumarasyonundan ([MS-WMF] bölüm 2.1.1.19) belirten 16 bit işaretsiz tamsayıyı alır veya ayarlar. |
| win_metafile | [MetaImage](/imaging/python-net/aspose.imaging.fileformats.emf/metaimage/) | r/w | WMF metafile'ini içeren bir tamponu alır veya ayarlar. |
| win_metafile_size | int | r/w | WinMetafile alanındaki WMF metafile'inin <br/>            bayt cinsinden boyutunu belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfCommentWindowsMetaFile(source) {#EmfCommentWindowsMetaFile_source_1}


```
 EmfCommentWindowsMetaFile(source) 
```

Yeni bir [EmfCommentWindowsMetaFile](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/) sınıfı örneği başlatır.

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


