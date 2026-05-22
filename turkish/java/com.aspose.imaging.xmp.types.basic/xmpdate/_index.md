---
title: "XmpDate"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP paketindeki Tarihi temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

XMP paketindeki Tarihi temsil eder.

Bir tarih‑saat değeri, Date and Time Formats bölümünde tanımlanan biçimlerin bir alt kümesi kullanılarak temsil edilir: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Yeni bir `XmpDate` sınıfı örneği başlatır. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Yeni bir `XmpDate` sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | ISO 8601 (roundtrip) biçim dizesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Tarih değerini alır veya ayarlar. |
| [setValue(Date value)](#setValue-java.util.Date-) | Tarih değerini alır veya ayarlar. |
| [getFormat()](#getFormat--) | Geçerli değer için biçim dizesini alır. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içeriği olan dizeyi döndürür. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Yeni bir `XmpDate` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dateTime | java.util.Date | ISO RFC 8601 biçimlendirmesinin bir alt kümesi kullanılarak temsil edilen bir tarih-zaman değeri. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Yeni bir `XmpDate` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dateString | java.lang.String | Tarihin dize temsili. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


ISO 8601 (roundtrip) biçim dizesi.

Daha fazla bilgi için: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Tarih değerini alır veya ayarlar.

Değer: Tarih değeri.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Tarih değerini alır veya ayarlar.

Değer: Tarih değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Geçerli değer için biçim dizesini alır.

Değer: Geçerli değer için biçim dizesi.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içeriği olan dizeyi döndürür.

**Returns:**
java.lang.String - xmp temsili içeren dizeyi döndürür
