---
title: "EmfMetafileHeaderExtension1 Sınıfı"
type: docs
weight: 620
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır. |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| emf_description | string | r/w | EMF açıklamasını alır veya ayarlar<br/>            İsteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE dizesi, rastgele uzunlukta ve içerikte. <br/>            Kayıttaki konumu ve karakter sayısı, sırasıyla EmfHeader içindeki offDescription <br/>            ve nDescription alanlarıyla belirtilir. Eğer bu alanlardan herhangi birinin <br/>            değeri sıfır ise, açıklama dizesi bulunmaz. |
| emf_description_buffer | System.Byte | r/w | EMF açıklama tamponunu alır veya ayarlar<br/>            EMF açıklama dizesini içeren isteğe bağlı bir bayt dizisi, bu dize <br/>            EmfMetafileHeader kaydının sabit kısmıyla bitişik olmak zorunda değildir. Buna göre, bu tampondaki "UndefinedSpace" olarak etiketlenmiş alan <br/>            isteğe bağlıdır ve YOK SAYILMALIDIR. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Bir Header nesnesini alır veya ayarlar (bölüm 2.2.9), bu nesne metafilin içeriği<br/>            ve yapısı hakkında bilgi içerir. |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Bir HeaderExtension1 nesnesini alır veya ayarlar, bu nesne metafildeki görüntü hakkında ek bilgi sağlar. |
| emf_header_record_buffer | System.Byte | r/w | EMF başlık kaydının geri kalanını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar. <br/>            Bu alanın boyutu 4 baytın katı OLMAK ZORUNDADIR. |
| emf_pixel_format_buffer | System.Byte | r/w | EMF piksel formatı tanımlayıcısını içeren isteğe bağlı bir bayt dizisini alır veya ayarlar, bu tanımlayıcı <br/>            EmfMetafileHeaderExtension1 kaydının sabit kısmıyla ya da EMF <br/>            açıklama dizesiyle bitişik olmak zorunda değildir. Buna göre, bu tampondaki "UndefinedSpace" olarak etiketlenmiş alan <br/>            isteğe bağlıdır ve YOK SAYILMALIDIR. |
| size | int | r/w | Kaydın boyutunu alır veya ayarlar |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Türü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır. |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır. |
| [create_from_record(record)](#create_from_record_record_3) | Yeni bir [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) sınıfı örneği başlatır. |
| [create_from_type(type)](#create_from_type_type_4) | Yeni bir [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) sınıfı örneği başlatır. |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Başlık. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Başlık. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | Başlık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Yeni bir [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | Başlık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

Yeni bir [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Kayıt. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


