---
title: "EmfEof Sınıf"
type: docs
weight: 390
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | Yeni bir örnek başlatır ve [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) sınıfını oluşturur. |
| [EmfEof(record)](#EmfEof_record_2) | Yeni bir örnek başlatır ve [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) sınıfını oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | Palet verilerini içeren isteğe bağlı bir tampon alır veya ayarlar; bu tamponun EMR_EOF kaydının sabit kısmıyla bitişik olması gerekmez. Bu nedenle, bu tampondaki "UndefinedSpace" olarak etiketlenen alanlar isteğe bağlıdır ve YOK SAYILMALIDIR. <br/>            Bu alanın boyutu 4 baytın katı olmalıdır. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| size_last | int | r/w | 32-bit işaretsiz bir tam sayı alır veya ayarlar; bu değer Size ile aynı olmalı ve kaydın son <br/>            alanı ve dolayısıyla metafile olmalıdır. LogPaletteEntry nesneleri, mevcutsa, bu alandan önce gelmelidir. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Yeni bir örnek başlatır ve [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) sınıfını oluşturur.

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

Yeni bir örnek başlatır ve [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) sınıfını oluşturur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kayıt. |

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


