---
title: "Complex"
second_title: "Aspose.Imaging for Java API 参考"
description: "复数结构。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

复数结构。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | 初始化一个新的 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 结构体实例。 |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 初始化一个新的 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 结构体实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | `double` 的大小。 |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | 复数的大小。 |
| [ZERO](#ZERO) | 零复数。 |
| [ONE](#ONE) | 一个复数，其 `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) 和 `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 均等于 1。 |
| [I](#I) | 一个复数，其 `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 等于 1。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | 执行从 `double` 到 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 的显式转换。 |
| [to_Complex(float value)](#to-Complex-float-) | 执行从 `float` 到 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 的显式转换。 |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 ==。 |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 !=。 |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 -。 |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 +。 |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 实现运算符 +。 |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 +。 |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 -。 |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 实现运算符 -。 |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 -。 |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 \*。 |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 \*。 |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 实现运算符 \*。 |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 /。 |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 实现运算符 /。 |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 实现运算符 /。 |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 将 `a` 与 `b` 相加。 |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 将 `a` 与 `s` 相加。 |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 与 `b` 相加。 |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 与 `s` 相加。 |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 从 `a` 中减去 `b`。 |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 从 `a` 中减去 `s`。 |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 从 `a` 中减去 `s`。 |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 从 `a` 中减去 `b`。 |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | 从 `a` 中减去 `s`。 |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 从 `s` 中减去 `a`。 |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 将 `a` 乘以 `b`。 |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 将 `a` 乘以 `s`。 |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 乘以 `b`。 |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 乘以 `s`。 |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 将 `a` 除以 `b`。 |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 将 `a` 除以 `s`。 |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | 将 `a` 除以 `s`。 |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 除以 `b`。 |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `a` 除以 `s`。 |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | 将 `s` 除以 `a`。 |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | 对 `a` 取负。 |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | 检查近似相等。 |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | 检查近似相等。 |
| [parse(String s)](#parse-java.lang.String-) | 将指定的 `s` 解析为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)。 |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | 尝试将指定的 `s` 解析为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)。 |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | 获取 `a` 的平方根。 |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | 获取 `a` 的对数。 |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | 将 e 提升到 `a` 次方。 |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | 获取 `a` 的正弦。 |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | 获取 `a` 的余弦。 |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | 获取 `a` 的正切。 |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | 将其乘以 `s`。 |
| [getRe()](#getRe--) | 获取实部。 |
| [setRe(double value)](#setRe-double-) | 设置实部。 |
| [getIm()](#getIm--) | 获取虚部。 |
| [setIm(double value)](#setIm-double-) | 设置虚部。 |
| [set(double re, double im)](#set-double-double-) | 设置值并返回自身。 |
| [getMagnitude()](#getMagnitude--) | 获取模。 |
| [getPhase()](#getPhase--) | 获取相位。 |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | 获取模的平方。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `Object` 是否等于此实例。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [deepClone()](#deepClone--) | 克隆此实例。 |
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


初始化一个新的 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 实数 | double | 实部。 |
| 虚数 | double | 虚部。 |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


初始化一个新的 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 复数。 |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


`double` 的大小。

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


复数的大小。

### ZERO {#ZERO}
```
public static final Complex ZERO
```


零复数。

### ONE {#ONE}
```
public static final Complex ONE
```


一个复数，其 `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) 和 `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 均等于 1。

### I {#I}
```
public static final Complex I
```


一个复数，其 `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) 等于 1。

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


执行从 `double` 到 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 的显式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


执行从 `float` 到 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) 的显式转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


实现运算符 ==。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
boolean - 运算符的结果。
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


实现运算符 !=。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
boolean - 运算符的结果。
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


实现运算符 -。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


实现运算符 +。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


实现运算符 +。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


实现运算符 +。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


实现运算符 -。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


实现运算符 -。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


实现运算符 -。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


实现运算符 \*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


实现运算符 \*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


实现运算符 \*。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


实现运算符 /。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


实现运算符 /。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


实现运算符 /。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


将 `a` 与 `b` 相加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


将 `a` 与 `s` 相加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


将 `a` 与 `b` 相加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


将 `a` 与 `s` 相加。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


从 `a` 中减去 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


从 `a` 中减去 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


从 `a` 中减去 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


从 `a` 中减去 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


从 `a` 中减去 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


从 `s` 中减去 `a`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


将 `a` 乘以 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


将 `a` 乘以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


将 `a` 乘以 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


将 `a` 乘以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


将 `a` 除以 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


将 `a` 除以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


将 `a` 除以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


将 `a` 除以 `b`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


将 `a` 除以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| s | double | s 值。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


将 `s` 除以 `a`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


对 `a` 取负。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


检查近似相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |

**Returns:**
boolean - 近似相等结果。
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


检查近似相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 b 复数。 |
| 容差 | double | 容差。 |

**Returns:**
boolean - 近似相等结果。
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


将指定的 `s` 解析为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | java.lang.String | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


尝试将指定的 `s` 解析为 [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | java.lang.String | s 值。 |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | 结果。 |

**Returns:**
boolean - 如果复数已解析，则为 True。
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


获取 `a` 的平方根。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


获取 `a` 的对数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


将 e 提升到 `a` 次方。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


获取 `a` 的正弦。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


获取 `a` 的余弦。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


获取 `a` 的正切。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | 该 "a" 复数。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


将其乘以 `s`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | s 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


获取实部。

**Returns:**
double - 实部。
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


设置实部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 实部。 |

### getIm() {#getIm--}
```
public final double getIm()
```


获取虚部。

**Returns:**
double - 虚部。
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


设置虚部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 虚部。 |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


设置值并返回自身。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| re | double | Re 值。 |
| im | double | Im 值。 |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


获取模。

Value: 幅值。

**Returns:**
double - 幅值。
### getPhase() {#getPhase--}
```
public final double getPhase()
```


获取相位。

值：相位。

**Returns:**
double - 相位。
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


获取模的平方。

值：平方幅值。

**Returns:**
double - 平方幅值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 `Object`。 |

**Returns:**
布尔值 - 如果指定的 `Object` 等于此实例，则为 `true`；否则为 `false`。
### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


克隆此实例。

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
