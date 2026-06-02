---
title: "Time"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Saniye cinsinden bir zaman değerinin temsili."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Saniye cinsinden bir zaman değerinin temsili.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Yeni bir `Time` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getScale()](#getScale--) | Zaman değeri için ölçeği alır veya ayarlar. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Zaman değeri için ölçeği alır veya ayarlar. |
| [getValue()](#getValue--) | Belirtilen ölçekte zaman değerini alır veya ayarlar. |
| [setValue(int value)](#setValue-int-) | Belirtilen ölçekte zaman değerini alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Yeni bir `Time` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | Ölçek. |
| değer | int | Değer. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Zaman değeri için ölçeği alır veya ayarlar.

NTSC için 1001/30000 veya daha az hassas 100/2997 kullanın. PAL için 1/25 kullanın. Değer: Zaman değeri için ölçek.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Zaman değeri için ölçeği alır veya ayarlar.

NTSC için 1001/30000 veya daha az hassas 100/2997 kullanın. PAL için 1/25 kullanın. Değer: Zaman değeri için ölçek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Belirtilen ölçekte zaman değerini alır veya ayarlar.

Değer: Belirtilen ölçekteki zaman değeri.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Belirtilen ölçekte zaman değerini alır veya ayarlar.

Değer: Belirtilen ölçekteki zaman değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP biçiminde içerilen dize değerini döndürür.
