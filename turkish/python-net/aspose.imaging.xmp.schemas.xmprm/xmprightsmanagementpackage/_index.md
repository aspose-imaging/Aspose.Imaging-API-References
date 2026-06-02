---
title: "XmpRightsManagementPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmprm](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/)

**Full Name:** aspose.imaging.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Yeni bir [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) sınıfı örneği başlatır. |
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
| [set_certificate(certificate)](#set_certificate_certificate_7) | Sertifikayı ayarlar. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_8) | Hak yönetimi içeriği olarak işaretler |
| [set_owners(owners)](#set_owners_owners_9) | Sahipleri ayarlar. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_11) | Kullanım koşullarını ayarlar. |
| [set_value(key, value)](#set_value_key_value_12) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_13) | Değeri ayarlar. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_14) | Web beyanını ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_15) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_16) | Değeri _key_ ile alır. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Yeni bir [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) sınıfı örneği başlatır.

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


### Method: set_certificate(certificate) {#set_certificate_certificate_7}


```
 set_certificate(certificate) 
```

Sertifikayı ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sertifika | string | Sertifika. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_8}


```
 set_marked_as_right_management(value) 
```

Hak yönetimi içeriği olarak işaretler

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| değer | bool | eğer <c>true</c> olarak ayarlanırsa bunun hak yönetimli bir kaynak olduğunu gösterir. |

### Method: set_owners(owners) {#set_owners_owners_9}


```
 set_owners(owners) 
```

Sahipleri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| sahipler | string[] | Sahipler. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |
| değer | System.Object | Belirtilen anahtara sahip nesne. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_11}


```
 set_usage_terms(usage_terms) 
```

Kullanım koşullarını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| usage_terms | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | Kullanım koşulları. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Eklenecek değer. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Eklenecek değer. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_14}


```
 set_web_statement(web_statement_url) 
```

Web beyanını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| web_statement_url | string | Web beyanı URL'si. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_15}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_16}


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


