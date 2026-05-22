---
title: "XmpGuid"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP küresel benzersiz tanımlayıcısını temsil eder."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

XMP küresel benzersiz tanımlayıcısını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | `XmpGuid` sınıfının yeni bir örneğini başlatır. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | `XmpGuid` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPrefix()](#getPrefix--) | uuid gibi öneki alır veya ayarlar. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | uuid gibi öneki alır veya ayarlar. |
| [getValue()](#getValue--) | Değeri alır veya ayarlar. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Değeri alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


`XmpGuid` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Değer. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


`XmpGuid` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| guid | java.util.UUID | Benzersiz tanımlayıcı. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


uuid gibi öneki alır veya ayarlar.

Değer: uuid gibi önek.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


uuid gibi öneki alır veya ayarlar.

Değer: uuid gibi önek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Değeri alır veya ayarlar.

Değer: Değer.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Değeri alır veya ayarlar.

Değer: Değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.
