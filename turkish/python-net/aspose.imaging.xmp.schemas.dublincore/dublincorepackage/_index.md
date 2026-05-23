---
title: "DublinCorePackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/
---

**Summary:** Represents Dublic Core schema.

**Module:** [aspose.imaging.xmp.schemas.dublincore](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/)

**Full Name:** aspose.imaging.xmp.schemas.dublincore.DublinCorePackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [DublinCorePackage()](#DublinCorePackage__1) | Yeni bir [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
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
| [set_author(author)](#set_author_author_7) | Yazarı ekler. |
| [set_author(author)](#set_author_author_8) | Yazarı ekler. |
| [set_author_array(author)](#set_author_array_author_9) | Yazarı ekler. |
| [set_description(desc)](#set_description_desc_10) | Açıklamayı ekler. |
| [set_description(desc)](#set_description_desc_11) | Açıklamayı ekler. |
| [set_description_lang_alt(desc)](#set_description_lang_alt_desc_12) | Açıklamayı ekler. |
| [set_description_str(desc)](#set_description_str_desc_13) | Açıklamayı ekler. |
| [set_prop_value(key, value)](#set_prop_value_key_value_14) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_publisher(publisher)](#set_publisher_publisher_15) | Yayımcısını ekler. |
| [set_publisher(publisher)](#set_publisher_publisher_16) | Yayımcısını ekler. |
| [set_publisher_array(publisher)](#set_publisher_array_publisher_17) | Yayımcısını ekler. |
| [set_subject(subject)](#set_subject_subject_18) | Konuyu ekler. |
| [set_subject(subject)](#set_subject_subject_19) | Konuyu ekler. |
| [set_subject_array(subject)](#set_subject_array_subject_20) | Konuyu ekler. |
| [set_title(title)](#set_title_title_21) | Dublin Core başlığını ekler. |
| [set_title(title)](#set_title_title_22) | Dublin Core başlığını ekler. |
| [set_title_lang_alt(title)](#set_title_lang_alt_title_23) | Farklı diller için Dublin Core başlığı ekler. |
| [set_title_str(title)](#set_title_str_title_24) | Dublin Core başlığını ekler. |
| [set_value(key, value)](#set_value_key_value_25) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_26) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_27) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_28) | Değeri _key_ ile alır. |


### Constructor: DublinCorePackage() {#DublinCorePackage__1}


```
 DublinCorePackage() 
```

Yeni bir [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) sınıfı örneği başlatır.

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


### Method: set_author(author) {#set_author_author_7}


```
 set_author(author) 
```

Yazarı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yazar | string | Yazar. |

### Method: set_author(author) {#set_author_author_8}


```
 set_author(author) 
```

Yazarı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yazar | string[] | Yazar. |

### Method: set_author_array(author) {#set_author_array_author_9}


```
 set_author_array(author) 
```

Yazarı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yazar | string[] | Yazar. |

### Method: set_description(desc) {#set_description_desc_10}


```
 set_description(desc) 
```

Açıklamayı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desc | string | Açıklama. |

### Method: set_description(desc) {#set_description_desc_11}


```
 set_description(desc) 
```

Açıklamayı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Açıklama. |

### Method: set_description_lang_alt(desc) {#set_description_lang_alt_desc_12}


```
 set_description_lang_alt(desc) 
```

Açıklamayı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Açıklama. |

### Method: set_description_str(desc) {#set_description_str_desc_13}


```
 set_description_str(desc) 
```

Açıklamayı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| desc | string | Açıklama. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_14}


```
 set_prop_value(key, value) 
```

Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |
| değer | System.Object | Belirtilen anahtara sahip nesne. |

### Method: set_publisher(publisher) {#set_publisher_publisher_15}


```
 set_publisher(publisher) 
```

Yayımcısını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yayıncı | string | Yayıncı. |

### Method: set_publisher(publisher) {#set_publisher_publisher_16}


```
 set_publisher(publisher) 
```

Yayımcısını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yayıncı | string[] | Yayıncı. |

### Method: set_publisher_array(publisher) {#set_publisher_array_publisher_17}


```
 set_publisher_array(publisher) 
```

Yayımcısını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| yayıncı | string[] | Yayıncı. |

### Method: set_subject(subject) {#set_subject_subject_18}


```
 set_subject(subject) 
```

Konuyu ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| konu | string | Konu. |

### Method: set_subject(subject) {#set_subject_subject_19}


```
 set_subject(subject) 
```

Konuyu ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| konu | string[] | Konu. |

### Method: set_subject_array(subject) {#set_subject_array_subject_20}


```
 set_subject_array(subject) 
```

Konuyu ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| konu | string[] | Konu. |

### Method: set_title(title) {#set_title_title_21}


```
 set_title(title) 
```

Dublin Core başlığını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| başlık | string | Başlık. |

### Method: set_title(title) {#set_title_title_22}


```
 set_title(title) 
```

Dublin Core başlığını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Başlık. |

### Method: set_title_lang_alt(title) {#set_title_lang_alt_title_23}


```
 set_title_lang_alt(title) 
```

Farklı diller için Dublin Core başlığı ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Şu sınıfın örneği [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/). |

### Method: set_title_str(title) {#set_title_str_title_24}


```
 set_title_str(title) 
```

Dublin Core başlığını ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| başlık | string | Başlık. |

### Method: set_value(key, value) {#set_value_key_value_25}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Eklenecek değer. |

### Method: set_value(key, value) {#set_value_key_value_26}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_27}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_28}


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


