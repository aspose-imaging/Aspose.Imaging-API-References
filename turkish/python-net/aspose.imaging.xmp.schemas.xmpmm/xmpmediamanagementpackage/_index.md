---
title: "XmpMediaManagementPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Yeni bir [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) sınıfı örneği başlatır. |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | Türetilen kaynağı ayarlar. |
| [set_document_id(guid)](#set_document_id_guid_8) | Belge tanımlayıcısını ayarlar. |
| [set_document_id(guid)](#set_document_id_guid_9) | Belge tanımlayıcısını ayarlar. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | Belge tanımlayıcısını ayarlar. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Örnek kimliğini ayarlar. |
| [set_instance_id(guid)](#set_instance_id_guid_12) | Örnek kimliğini ayarlar. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | Örnek kimliğini ayarlar. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Orijinal belge kimliğini ayarlar. |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | Orijinal belge kimliğini ayarlar. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | Orijinal belge kimliğini ayarlar. |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_value(key, value)](#set_value_key_value_18) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_19) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_21) | Değeri _key_ ile alır. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Yeni bir [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) sınıfı örneği başlatır.

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

Türetilen kaynağı ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | Kaynak referansı. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Belge tanımlayıcısını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

Belge tanımlayıcısını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

Belge tanımlayıcısını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Örnek kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

Örnek kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

Örnek kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Orijinal belge kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

Orijinal belge kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

Orijinal belge kimliğini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| guid | System.Guid | Benzersiz tanımlayıcı. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Değeri tanımlayan anahtar. |
| değer | System.Object | Belirtilen anahtara sahip nesne. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Eklenecek değer. |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


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


