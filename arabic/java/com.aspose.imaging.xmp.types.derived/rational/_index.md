---
title: "Rational"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل XMP Rational."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.xmp.types.derived/rational/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class Rational extends XmpTypeBase
```

يمثل XMP Rational.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Rational(int numerator, int denominator)](#Rational-int-int-) | ينشئ مثلاً جديداً من الفئة `Rational`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumerator()](#getNumerator--) | يحصل على البسط. |
| [getDenominator()](#getDenominator--) | يحصل على أو يعيّن المقام. |
| [setDenominator(int value)](#setDenominator-int-) | يحصل على أو يعيّن المقام. |
| [getFloatValue()](#getFloatValue--) | يحصل على قيمة الفاصلة العائمة. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يحصل على القيمة المتضمنة كسلسلة بتنسيق XMP. |
### Rational(int numerator, int denominator) {#Rational-int-int-}
```
public Rational(int numerator, int denominator)
```


ينشئ مثلاً جديداً من الفئة `Rational`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البسط | int | البسط. |
| المقام | int | المقام. |

### getNumerator() {#getNumerator--}
```
public int getNumerator()
```


يحصل على البسط.

القيمة: البسط.

**Returns:**
int
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


يحصل على أو يعيّن المقام.

**Returns:**
int - المقام.
### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


يحصل على أو يعيّن المقام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | المقام. |

### getFloatValue() {#getFloatValue--}
```
public float getFloatValue()
```


يحصل على قيمة الفاصلة العائمة.

**Returns:**
float - القيمة العائمة.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يحصل على القيمة المتضمنة كسلسلة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجِع القيمة النصية المحتواة بتنسيق XMP.
