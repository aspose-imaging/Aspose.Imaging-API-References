---
title: "XmpTrailerPi"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP kuyruk işleme talimatını temsil eder."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

XMP kuyruk işleme talimatını temsil eder.

The end=\"w\" veya end=\"r\" bölümü, XMP'nin yerinde değiştirilebilir olup olmadığını belirlemek için paket tarama işlemcileri tarafından kullanılacaktır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | `XmpTrailerPi` sınıfının yeni bir örneğini başlatır. |
| [XmpTrailerPi()](#XmpTrailerPi--) | `XmpTrailerPi` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isWritable()](#isWritable--) | Bu örneğin yazılabilir olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setWritable(boolean value)](#setWritable-boolean-) | Bu örneğin yazılabilir olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getXmlValue()](#getXmlValue--) | xmp değerini xml temsiline dönüştürür. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


`XmpTrailerPi` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isWritable | boolean | Trailer'ın yazılabilir olup olmadığını gösterir. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


`XmpTrailerPi` sınıfının yeni bir örneğini başlatır.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Bu örneğin yazılabilir olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: bu örnek yazılabilir ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Bu örneğin yazılabilir olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: bu örnek yazılabilir ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp değerini xml temsiline dönüştürür.

**Returns:**
java.lang.String - XMP'nin XML temsilini döndürür.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Bu nesneyle karşılaştırmak için bir nesne. |

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
