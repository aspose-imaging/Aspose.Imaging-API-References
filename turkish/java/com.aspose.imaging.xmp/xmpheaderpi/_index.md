---
title: "XmpHeaderPi"
second_title: "Aspose.Imaging for Java API Referansı"
description: "XMP başlık işleme talimatını temsil eder."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

XMP başlık işleme talimatını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | `XmpHeaderPi` sınıfının yeni bir örneğini başlatır. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | `XmpHeaderPi` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getGuid()](#getGuid--) | Başlık GUID'sini temsil eder. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Başlık GUID'sini temsil eder. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


`XmpHeaderPi` sınıfının yeni bir örneğini başlatır.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


`XmpHeaderPi` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| guid | java.lang.String | Benzersiz tanımlayıcı. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Başlık GUID'sini temsil eder.

Başlık PI metni bir GUID içerir, bu da veri akışında tesadüfen ortaya çıkma olasılığını azaltır.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Başlık GUID'sini temsil eder.

Başlık PI metni bir GUID içerir, bu da veri akışında tesadüfen ortaya çıkma olasılığını azaltır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Bu nesneyle karşılaştırmak için bir nesne. |

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
