---
title: "EmfGlsBoundedRecord Sınıfı"
type: docs
weight: 540
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---

**Summary:** The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsBoundedRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfGlsBoundedRecord(source)](#EmfGlsBoundedRecord_source_1) | Yeni bir örnek başlatır [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/) sınıfını. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Alır veya ayarlar OpenGL işlevi yürütülerek üretilen çıktı için cihaz birimlerinde bir sınırlayıcı<br/>            dikdörtgen tanımlayan WMF RectL nesnesini ([MS-WMF] bölüm 2.2.2.19). |
| cb_data | int | r/w | Data alanının bayt cinsinden boyutunu belirten 32-bit işaretsiz tamsayı alır veya ayarlar.<br/>            Bu değer sıfır ise, bu kayda veri eklenmez. |
| veri | System.Byte | r/w | OpenGL işlevi için veriyi belirten, cbData uzunluğunda isteğe bağlı bir bayt dizisi alır veya ayarlar. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_2) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfGlsBoundedRecord(source) {#EmfGlsBoundedRecord_source_1}


```
 EmfGlsBoundedRecord(source) 
```

Yeni bir örnek başlatır [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/) sınıfını.

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


