---
title: "WmfCreatePatternBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_CREATEPATTERNBRUSH kaydı, bir bitmap tarafından belirtilen desenle bir fırça nesnesi oluşturur."
type: docs
weight: 23
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

META\_CREATEPATTERNBRUSH kaydı, bir bitmap ile belirtilen bir desenle bir fırça nesnesi oluşturur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs kaydı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitmap()](#getBitmap--) | Bit eşlemeyi alır veya ayarlar. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Bit eşlemeyi alır veya ayarlar. |
| [getReserved()](#getReserved--) | Ayrılmış alanı alır veya ayarlar. |
| [setReserved(byte[] value)](#setReserved-byte---) | Ayrılmış alanı alır veya ayarlar. |
| [getPattern()](#getPattern--) | Deseni alır veya ayarlar. |
| [setPattern(byte[] value)](#setPattern-byte---) | Deseni alır veya ayarlar. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs kaydı.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Bit eşlemeyi alır veya ayarlar.

Değer: Fırça için deseni belirten bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Bit eşlemeyi alır veya ayarlar.

Değer: Fırça için deseni belirten bitmap.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış alan. Bu alan YOK SAYILMALI.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Ayrılmış alanı alır veya ayarlar.

Değer: Ayrılmış alan. Bu alan YOK SAYILMALI.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Deseni alır veya ayarlar.

Değer: Fırça desenini oluşturan bitmap piksel verilerini tanımlayan değişken uzunlukta bir bayt dizisi. Bu alanın uzunluğu, bayt cinsinden, bitmap parametrelerinden aşağıdaki gibi hesaplanabilir.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Deseni alır veya ayarlar.

Değer: Fırça desenini oluşturan bitmap piksel verilerini tanımlayan değişken uzunlukta bir bayt dizisi. Bu alanın uzunluğu, bayt cinsinden, bitmap parametrelerinden aşağıdaki gibi hesaplanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

