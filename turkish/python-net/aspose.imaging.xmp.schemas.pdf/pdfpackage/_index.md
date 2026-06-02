---
title: "PdfPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Yeni bir [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) sınıfının örneğini başlatır. |
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
| [set_keywords(keywords)](#set_keywords_keywords_7) | Anahtar kelimeleri ayarlar. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | PDF sürümünü ayarlar. |
| [set_producer(producer)](#set_producer_producer_9) | Pdf'i oluşturan aracın adını ayarlar. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Tutmayı ayarlar. |
| [set_value(key, value)](#set_value_key_value_12) | Değeri ayarlar. |
| [set_value(key, value)](#set_value_key_value_13) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | XMP tip değerini ayarlar. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Değeri _key_ ile alır. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Yeni bir [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) sınıfının örneğini başlatır.

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Anahtar kelimeleri ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| anahtar kelimeler | string | Anahtar kelimeler. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

PDF sürümünü ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| version | string | Pdf sürümü, örneğin: 1.0, 1.3 vb. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Pdf'i oluşturan aracın adını ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| üretici | string | Üretici adı. |

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

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Tutmayı ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| is_trapped | bool | eğer <c>true</c> olarak ayarlanırsa belge tuzağa düşürülmüş olur. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

XMP tip değerini ayarlar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Ayarlanacak değer. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


