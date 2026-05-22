---
title: "XmpElementBase"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Özellikler içeren temel xmp öğesini temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Özellikler içeren temel xmp öğesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Özelliği ekler. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Özniteliği alır. |
| [clearAttributes()](#clearAttributes--) | Tüm öznitelikleri kaldırır. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `Object`'in bu örnek ile eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Özelliği ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik. |
| değer | java.lang.String | Değer. |

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Özniteliği alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik. |

**Returns:**
java.lang.String - Belirtilen öznitelik adı için özniteliği döndürür.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Tüm öznitelikleri kaldırır.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Bu nesneyle karşılaştırmak için bir nesne. |

**Returns:**
boolean - mevcut nesne `other` parametresiyle eşitse true; aksi takdirde false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen `Object`'in bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu `Object` bu örnek ile karşılaştırmak için. |

**Returns:**
boolean - `true` eğer belirtilen `Object` bu örnek ile eşitse; aksi takdirde `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
