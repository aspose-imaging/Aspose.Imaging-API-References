---
title: "TiffSRational"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "نوع TIFF Rational."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

نوع TIFF Rational.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | ينشئ مثيلاً جديداً من الفئة `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | ينشئ مثيلاً جديداً من الفئة [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | ينشئ مثيلاً جديداً من الفئة `TiffSRational`. |
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
| [toString()](#toString--) | يعيد `System.String` الذي يمثل هذه الحالة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


ينشئ مثيلاً جديداً من الفئة `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


ينشئ مثيلاً جديداً من الفئة [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | قيمة البسط. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


ينشئ مثيلاً جديداً من الفئة `TiffSRational`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البسط | int | البسط. |
| المقام | int | المقام. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


الإبسيلون لحساب الكسر

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | القيمة. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | القيمة. |
| إبسيلون | double | الخطأ المسموح به. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


يقرب القيمة المقدمة إلى كسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | القيمة. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


يحصل على المقام.

القيمة: المقام.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


يحصل على البسط.

القيمة: البسط.

**Returns:**
int
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


يعيد `System.String` الذي يمثل هذه الحالة.

**Returns:**
java.lang.String - `System.String` الذي يمثل هذه الحالة.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الـ `Object` المحدد يساوي هذه الحالة.

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
