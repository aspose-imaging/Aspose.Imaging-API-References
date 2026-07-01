---
title: "الوقت"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تمثيل قيمة الوقت بالثواني."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

تمثيل قيمة الوقت بالثواني.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | ينشئ مثيلاً جديدًا للفئة `Time`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getScale()](#getScale--) | يحصل أو يضبط المقياس لقيمة الوقت. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | يحصل أو يضبط المقياس لقيمة الوقت. |
| [getValue()](#getValue--) | يحصل أو يضبط قيمة الوقت بالمقياس المحدد. |
| [setValue(int value)](#setValue-int-) | يحصل أو يضبط قيمة الوقت بالمقياس المحدد. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة النصية المحتواة بتنسيق XMP. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


ينشئ مثيلاً جديدًا للفئة `Time`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | المقياس. |
| value | int | القيمة. |

### getScale() {#getScale--}
```
public Rational getScale()
```


يحصل أو يضبط المقياس لقيمة الوقت.

لـ NTSC، استخدم 1001/30000، أو الأقل دقة 100/2997. لـ PAL، استخدم 1/25. القيمة: المقياس لقيمة الوقت.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


يحصل أو يضبط المقياس لقيمة الوقت.

لـ NTSC، استخدم 1001/30000، أو الأقل دقة 100/2997. لـ PAL، استخدم 1/25. القيمة: المقياس لقيمة الوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


يحصل أو يضبط قيمة الوقت بالمقياس المحدد.

القيمة: قيمة الوقت بالمقياس المحدد.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


يحصل أو يضبط قيمة الوقت بالمقياس المحدد.

القيمة: قيمة الوقت بالمقياس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
