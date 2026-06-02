---
title: "XmpBasicPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Yeni bir [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının bir örneğini başlatır. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Yeni bir [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Derecelendirme maksimum değeri. |
| RATING_MIN [static] | int | r | Derecelendirme minimum değeri. |
| RATING_REJECTED [static] | int | r | Reddedilen derecelendirme değeri. |
| count | int | r | XMP anahtar sayısını alır. |
| namespace_uri | string | r | Namespace URI'sini alır. |
| prefix | string | r | Öneki alır. |
| xml_namespace | string | r | XML ad alanını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Dize özelliği ekler. |
| [add_value(key, value)](#add_value_key_value_2) | Dize özelliği ekler. |
| clear() | Bu örneği temizler. |
| [contains_key(key)](#contains_key_key_3) | Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler. |
| [get_prop_value(key)](#get_prop_value_key_4) | Belirtilen anahtara sahip nesneyi alır. |
| [get_xml_value()](#get_xml_value__5) | XMP değerini XML temsiline dönüştürür. |
| [remove(key)](#remove_key_6) | Belirtilen anahtara sahip değeri kaldırır. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Kaynak oluşturulma tarihini ekler. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Kaynak oluşturulma tarihini ekler. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Kaynak oluşturulma tarihini ekler. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Oluşturucu aracı ayarlar. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Tanımlayıcıyı ayarlar. |
| [set_label(label)](#set_label_label_12) | Etiketi ayarlar. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Meta verilerin son değişiklik tarihini ekler. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Meta verilerin son değişiklik tarihini ekler. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Meta verilerin son değişiklik tarihini ekler. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Kaynağın son değiştirilme tarihini ekler. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Kaynağın son değiştirilme tarihini ekler. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Kaynağın son değiştirilme tarihini ekler. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_rating(choise)](#set_rating_choise_20) | Derecelendirmeyi ayarlar. |
| [set_value(key, value)](#set_value_key_value_21) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_22) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Değeri _key_ ile alır. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Yeni bir [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının bir örneğini başlatır.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Yeni bir [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| prefix | string | Önek. |
| namespace_uri | string | Ad alanı URI'si. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Dize özelliği ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | string | Dize değeri. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Dize özelliği ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | System.Object | Dize değeri. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bu koleksiyonun belirtilen anahtarı içerip içermediğini belirler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kontrol edilecek anahtar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | **True** eğer belirtilen anahtarı içeriyorsa; aksi takdirde, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Belirtilen anahtara sahip nesneyi alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Belirtilen anahtara sahip nesneyi döndürür. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML temsiline dönüştürülmüş olarak döndürür. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Belirtilen anahtara sahip değeri kaldırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kaldırılan değerle tanımlanan anahtarın dize temsili. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen anahtara sahip değer kaldırıldıysa true döndürür. |


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Kaynak oluşturulma tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| created_date | System.DateTime | Oluşturulma tarihi. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Kaynak oluşturulma tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| created_date | string | Oluşturulma tarihi. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Kaynak oluşturulma tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| created_date | string | Oluşturulma tarihi. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Oluşturucu aracı ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| creator_tool | string | Araç adı. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Tanımlayıcıyı ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tanımlayıcı | string[] | Tanımlayıcı. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Etiketi ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| etiket | string | Etiket. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Meta verilerin son değişiklik tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata_tarih | System.DateTime | Metadata tarihi. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Meta verilerin son değişiklik tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata_tarih | string | Metadata tarihi. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Meta verilerin son değişiklik tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| metadata_tarih | string | Metadata tarihi. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Kaynağın son değiştirilme tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| modified_date | System.DateTime | Son değiştirilme tarihi. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Kaynağın son değiştirilme tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| modified_date | string | Son değiştirilme tarihi. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Kaynağın son değiştirilme tarihini ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| modified_date | string | Son değiştirilme tarihi. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |
| değer | System.Object | Belirtilen anahtara sahip nesne. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Derecelendirmeyi ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| seçim | int | -1'den 5'e kadar |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Eklenecek değer. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


```
 try_get_value(key, value) 
```

Değeri _key_ ile alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | XMP öğe anahtarı. |
| değer | System.Object | XMP değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | **True**, eğer  _key_ içeriyorsa; aksi takdirde, **False**. |


