---
title: "TiffRational"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF Rational."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

نوع TIFF Rational.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffRational()](#TiffRational--) | ينشئ مثلاً جديداً من الفئة `TiffRational`. |
| [TiffRational(long value)](#TiffRational-long-) | ينشئ مثلاً جديداً من الفئة `TiffRational`. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | ينشئ مثلاً جديداً من الفئة `TiffRational`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EPSILON](#EPSILON) | الإبسيلون لحساب الكسر |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(double value)](#approximateFraction-double-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | يقرب القيمة المقدمة إلى كسر. |
| [approximateFraction(float value)](#approximateFraction-float-) | يقرب القيمة المقدمة إلى كسر. |
| [getDenominator()](#getDenominator--) | يحصل على المقام. |
| [getNominator()](#getNominator--) | يحصل على البسط. |
| [getValue()](#getValue--) | يحصل على قيمة الفاصلة العائمة. |
| [getValueD()](#getValueD--) | يحصل على قيمة مزدوجة. |
| [toString()](#toString--) | يحول إلى سلسلة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `Object` المحدد يساوي هذه الحالة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


ينشئ مثلاً جديداً من الفئة `TiffRational`.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


ينشئ مثلاً جديداً من الفئة `TiffRational`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | long | قيمة البسط. |

سيتم استخدام البسط كالقيمة المحددة وسيكون المقام مساوياً لـ 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


ينشئ مثلاً جديداً من الفئة `TiffRational`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البسط | long | البسط. |
| المقام | long | المقام. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


الإبسيلون لحساب الكسر

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | القيمة. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | القيمة. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


يحصل على المقام.

القيمة: المقام.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


يحصل على البسط.

القيمة: البسط.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


يحصل على قيمة الفاصلة العائمة.

القيمة: قيمة الفاصلة العائمة.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


يحصل على قيمة مزدوجة.

القيمة: قيمة مزدوجة.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


يحول إلى سلسلة.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `Object` المحدد يساوي هذه الحالة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن `Object` للمقارنة مع هذه المثيلة. |

**Returns:**
منطقية - `true` إذا كان الـ `Object` المحدد مساويًا لهذه المثيلة؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
