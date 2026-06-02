---
title: "XmpMeta"
second_title: "Aspose.Imaging for Java API Referansı"
description: "xmp meta verisini temsil eder."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

xmp meta'yı temsil eder. İsteğe bağlı. Bu öğenin amacı, RDF'nin diğer XMP olmayan kullanımlarını içerebilecek genel XML metni içinde XMP meta verilerini tanımlamaktır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | `XmpMeta` sınıfının yeni bir örneğini başlatır. |
| [XmpMeta()](#XmpMeta--) | `XmpMeta` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Özelliği ekler. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [equals(Object other)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


`XmpMeta` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP araç takımı sürümü. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


`XmpMeta` sınıfının yeni bir örneğini başlatır.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Adobe Xmp araç takımı sürümünü alır veya ayarlar.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Adobe Xmp araç takımı sürümünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Bu nesneyle karşılaştırmak için bir nesne. |

**Returns:**
boolean - mevcut nesne `other` parametresiyle eşitse true; aksi takdirde false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | java.lang.Object | Bu örnek ile karşılaştırılacak `System.Object`. |

**Returns:**
boolean - belirtilen `System.Object` bu örnek ile eşitse `true`; aksi takdirde `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
