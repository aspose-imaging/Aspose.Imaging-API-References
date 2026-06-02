---
title: "Complex"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "بنية العدد المركب."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

بنية العدد المركب.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | يُنشئ مثيلاً جديدًا من بنية [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنشئ مثيلاً جديدًا من بنية [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | حجم `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | حجم complex. |
| [ZERO](#ZERO) | صفر مركب. |
| [ONE](#ONE) | مركب واحد له `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) و `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) يساوي 1. |
| [I](#I) | مركب I له `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) يساوي 1. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | يُجري تحويلًا صريحًا من `double` إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | يُجري تحويلًا صريحًا من `float` إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يُنفّذ المشغل +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يُنفّذ المشغل -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُنفّذ المشغل -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُطبق المشغل \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُطبق المشغل \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يُطبق المشغل \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُطبق المشغل /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يُطبق المشغل /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يُطبق المشغل /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يضيف `a` و `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يضيف `a` و `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يضيف `a` و `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | يضيف `a` و `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يطرح `b` من `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يطرح `s` من `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يطرح `s` من `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يطرح `b` من `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | يطرح `s` من `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يطرح `a` من `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يضرب `a` في `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يضرب `a` في `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يضرب `a` في `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | يضرب `a` في `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يقسم `a` على `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يقسم `a` على `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | يقسم `a` على `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يقسم `a` على `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | يقسم `a` على `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | يقسم `s` على `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | يعكس إشارة `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | يفحص المساواة التقريبية. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | يفحص المساواة التقريبية. |
| [parse(String s)](#parse-java.lang.String-) | يحلل `s` المحدد إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | يحاول تحليل `s` المحدد إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | يحصل على الجذر التربيعي لـ `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | يحصل على اللوغاريتم لـ `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | يرفع e إلى `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | يحصل على جيب `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | يحصل على جيب تمام `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | يحصل على ظل `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | يضرب في `s`. |
| [getRe()](#getRe--) | يحصل على الجزء الحقيقي. |
| [setRe(double value)](#setRe-double-) | يضبط الجزء الحقيقي. |
| [getIm()](#getIm--) | يحصل على الجزء التخيلي. |
| [setIm(double value)](#setIm-double-) | يضبط الجزء التخيلي. |
| [set(double re, double im)](#set-double-double-) | يضبط القيم ويعيد نفسه. |
| [getMagnitude()](#getMagnitude--) | يحصل على المقدار. |
| [getPhase()](#getPhase--) | يحصل على الطور. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | يحصل على المقدار المربع. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `Object` المحدد يساوي هذه المثيلة. |
| [toString()](#toString--) | يعيد سلسلة تمثل هذه الحالة. |
| [deepClone()](#deepClone--) | ينسخ هذه المثيلة. |
| [CloneTo(Complex that)](#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [Clone()](#Clone--) |  |
### Complex() {#Complex--}
```
public Complex()
```


### Complex(double real, double imaginary) {#Complex-double-double-}
```
public Complex(double real, double imaginary)
```


يُنشئ مثيلاً جديدًا من بنية [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| حقيقي | double | الجزء الحقيقي. |
| تخيلي | double | الجزء التخيلي. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


يُنشئ مثيلاً جديدًا من بنية [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | العدد المركب. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


حجم `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


حجم complex.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


صفر مركب.

### ONE {#ONE}
```
public static final Complex ONE
```


مركب واحد له `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) و `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) يساوي 1.

### I {#I}
```
public static final Complex I
```


مركب I له `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) يساوي 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


يُجري تحويلًا صريحًا من `double` إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


يُجري تحويلًا صريحًا من `float` إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


يُنفّذ المشغل ==.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
منطقي - نتيجة العملية.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


يُنفّذ المشغل !=.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
منطقي - نتيجة العملية.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


يُنفّذ المشغل -.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


يُنفّذ المشغل +.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


يُنفّذ المشغل +.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


يُنفّذ المشغل +.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


يُنفّذ المشغل -.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


يُنفّذ المشغل -.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


يُنفّذ المشغل -.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


يُطبق المشغل \*.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


يُطبق المشغل \*.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


يُطبق المشغل \*.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


يُطبق المشغل /.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


يُطبق المشغل /.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


يُطبق المشغل /.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


يضيف `a` و `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


يضيف `a` و `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


يضيف `a` و `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


يضيف `a` و `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


يطرح `b` من `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


يطرح `s` من `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


يطرح `s` من `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


يطرح `b` من `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


يطرح `s` من `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


يطرح `a` من `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


يضرب `a` في `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


يضرب `a` في `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


يضرب `a` في `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


يضرب `a` في `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


يقسم `a` على `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


يقسم `a` على `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


يقسم `a` على `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


يقسم `a` على `b`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


يقسم `a` على `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| s | double | قيمة s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


يقسم `s` على `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


يعكس إشارة `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


يفحص المساواة التقريبية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |

**Returns:**
boolean - نتيجة المساواة التقريبية.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


يفحص المساواة التقريبية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب b. |
| التسامح | double | التسامح. |

**Returns:**
boolean - نتيجة المساواة التقريبية.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


يحلل `s` المحدد إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


يحاول تحليل `s` المحدد إلى [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | java.lang.String | قيمة s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النتيجة. |

**Returns:**
boolean - True، إذا تم تحليل العدد المركب.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


يحصل على الجذر التربيعي لـ `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


يحصل على اللوغاريتم لـ `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


يرفع e إلى `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


يحصل على جيب `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


يحصل على جيب تمام `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


يحصل على ظل `a`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | المركب "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


يضرب في `s`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | قيمة s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


يحصل على الجزء الحقيقي.

**Returns:**
double - الجزء الحقيقي.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


يضبط الجزء الحقيقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | الجزء الحقيقي. |

### getIm() {#getIm--}
```
public final double getIm()
```


يحصل على الجزء التخيلي.

**Returns:**
double - الجزء التخيلي.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


يضبط الجزء التخيلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | الجزء التخيلي. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


يضبط القيم ويعيد نفسه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| re | double | قيمة Re. |
| im | double | قيمة Im. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


يحصل على المقدار.

القيمة: المقدار.

**Returns:**
double - المقدار.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


يحصل على الطور.

القيمة: الطور.

**Returns:**
double - الطور.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


يحصل على المقدار المربع.

القيمة: المقدار المربع.

**Returns:**
double - المقدار المربع.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `Object` المحدد يساوي هذه المثيلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال `Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `Object` المحدد يساوي هذه الحالة؛ وإلا `false`.
### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تمثل هذه الحالة.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


ينسخ هذه المثيلة.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
