---
title: "Timecode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Videodaki zaman kodu değerini temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Videodaki zaman kodu değerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | `Timecode` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) | `TimeValue` içinde kullanılan biçimi alır veya ayarlar. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | `TimeValue` içinde kullanılan biçimi alır veya ayarlar. |
| [getTimeValue()](#getTimeValue--) | Belirtilen biçimdeki zaman değerini alır veya ayarlar. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Belirtilen biçimdeki zaman değerini alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP biçiminde içeren dize değerini döndürür. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


`Timecode` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | Zaman biçimi. |
| timeValue | java.lang.String | Zaman değeri. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


`TimeValue` içinde kullanılan biçimi alır veya ayarlar.

Değer: `TimeValue` içinde kullanılan biçim.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


`TimeValue` içinde kullanılan biçimi alır veya ayarlar.

Değer: `TimeValue` içinde kullanılan biçim.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Belirtilen biçimdeki zaman değerini alır veya ayarlar.

Değer: Belirtilen biçimdeki zaman değeri.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Belirtilen biçimdeki zaman değerini alır veya ayarlar.

Değer: Belirtilen biçimdeki zaman değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP biçiminde içeren dize değerini döndürür.

**Returns:**
java.lang.String - xmp temsili içeren dizeyi döndürür.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | Bu nesneyle karşılaştırmak için bir nesne. |

**Returns:**
boolean - mevcut nesne `other` parametresiyle eşitse true; aksi takdirde false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak `System.Object`. |

**Returns:**
boolean - belirtilen `System.Object` bu örnek ile eşitse `true`; aksi takdirde `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
