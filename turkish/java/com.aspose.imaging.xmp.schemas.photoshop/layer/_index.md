---
title: "Layer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Photoshop metin katmanını temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Photoshop metin katmanını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Yeni bir `Layer` sınıfı örneği başlatır. |
| [Layer()](#Layer--) | Yeni bir `Layer` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Metin katmanının adını alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Metin katmanının adını alır veya ayarlar. |
| [getText()](#getText--) | Katmanın metin içeriğini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Katmanın metin içeriğini alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içeriği olan dizeyi döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen `System.Object`'in bu örnekle eşit olup olmadığını belirler. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Yeni bir `Layer` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerName | java.lang.String | Katmanın adı. |
| layerText | java.lang.String | Katman metni. |

### Layer() {#Layer--}
```
public Layer()
```


Yeni bir `Layer` sınıfı örneği başlatır.

### getName() {#getName--}
```
public String getName()
```


Metin katmanının adını alır veya ayarlar.

Değer: Metin katmanının adı.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Metin katmanının adını alır veya ayarlar.

Değer: Metin katmanının adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Katmanın metin içeriğini alır veya ayarlar.

Değer: Katmanın metin içeriği.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Katmanın metin içeriğini alır veya ayarlar.

Değer: Katmanın metin içeriği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içeriği olan dizeyi döndürür.

**Returns:**
java.lang.String - XMP formatında içerilen dize değerini döndürür.
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
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Mevcut nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Bu nesneyle karşılaştırmak için bir nesne. |

**Returns:**
boolean - mevcut nesne `other` parametresiyle eşitse true; aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, karma algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.
