---
title: "XmpDate Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Yeni bir [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) sınıfının bir örneğini başlatır. |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Yeni bir [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | ISO 8601 (roundtrip) biçim dizesi. |
| biçim | string | r | Geçerli değer için biçim dizesini alır. |
| değer | System.DateTime | r/w | Tarih değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |
| [get_xmp_representation()](#get_xmp_representation__2) | XMP formatında içerilen değeri döndüren dize. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Yeni bir [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| date_string | string | Tarihin dize temsili. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Yeni bir [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| date_time | System.DateTime | ISO RFC 8601 biçimlendirmesinin bir alt kümesi kullanılarak temsil edilen bir tarih‑zaman değeri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Üye bazlı bir klon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

XMP formatında içerilen değeri döndüren dize.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | xmp temsili içeren dizeyi döndürür |


