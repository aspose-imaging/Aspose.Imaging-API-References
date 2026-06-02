---
title: "Complex"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Структура комплексного числа."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.imagefilters.complexutils/complex/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Complex extends Struct<Complex> implements System.IEquatable<Complex>
```

Структура комплексного числа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Complex()](#Complex--) |  |
| [Complex(double real, double imaginary)](#Complex-double-double-) | Инициализирует новый экземпляр структуры [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [Complex(Complex c)](#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Инициализирует новый экземпляр структуры [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
## Поля

| Поле | Описание |
| --- | --- |
| [SIZE_OF_DOUBLE](#SIZE-OF-DOUBLE) | Размер `double`. |
| [SIZE_OF_COMPLEX](#SIZE-OF-COMPLEX) | Размер комплексного числа. |
| [ZERO](#ZERO) | Нулевой комплекс. |
| [ONE](#ONE) | Один комплекс, имеющий `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) и `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) равные 1. |
| [I](#I) | Комплекс, имеющий `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) равный 1. |
## Методы

| Метод | Описание |
| --- | --- |
| [to_Complex(double value)](#to-Complex-double-) | Выполняет явное преобразование из `double` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [to_Complex(float value)](#to-Complex-float-) | Выполняет явное преобразование из `float` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [op_Equality(Complex a, Complex b)](#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор ==. |
| [op_Inequality(Complex a, Complex b)](#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор !=. |
| [op_UnaryNegation(Complex a)](#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор -. |
| [op_Addition(Complex a, Complex b)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор +. |
| [op_Addition(Complex a, double s)](#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Реализует оператор +. |
| [op_Addition(double s, Complex a)](#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор +. |
| [op_Subtraction(Complex a, Complex b)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор -. |
| [op_Subtraction(Complex a, double s)](#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Реализует оператор -. |
| [op_Subtraction(double s, Complex a)](#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор -. |
| [op_Multiply(Complex a, Complex b)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор \*. |
| [op_Multiply(double s, Complex a)](#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор \*. |
| [op_Multiply(Complex a, double s)](#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Реализует оператор \*. |
| [op_Division(Complex a, Complex b)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор /. |
| [op_Division(Complex a, double s)](#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Реализует оператор /. |
| [op_Division(double s, Complex a)](#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Реализует оператор /. |
| [add(Complex a, Complex b)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Складывает `a` и `b`. |
| [add(Complex a, double s)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Складывает `a` и `s`. |
| [add(Complex a, Complex b, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Складывает `a` и `b`. |
| [add(Complex a, double s, Complex[] result)](#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Складывает `a` и `s`. |
| [subtract(Complex a, Complex b)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Вычитает `b` из `a`. |
| [subtract(Complex a, double s)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Вычитает `s` из `a`. |
| [subtract(double s, Complex a)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Вычитает `s` из `a`. |
| [subtract(Complex a, Complex b, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Вычитает `b` из `a`. |
| [subtract(Complex a, double s, Complex[] result)](#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Вычитает `s` из `a`. |
| [subtract(double s, Complex a, Complex[] result)](#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Вычитает `a` из `s`. |
| [multiply(Complex a, Complex b)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Умножает `a` на `b`. |
| [multiply(Complex a, double s)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Умножает `a` на `s`. |
| [multiply(Complex a, Complex b, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Умножает `a` на `b`. |
| [multiply(Complex a, double s, Complex[] result)](#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Умножает `a` на `s`. |
| [divide(Complex a, Complex b)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Делит `a` на `b`. |
| [divide(Complex a, double s)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Делит `a` на `s`. |
| [divide(double s, Complex a)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-) | Делит `a` на `s`. |
| [divide(Complex a, Complex b, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Делит `a` на `b`. |
| [divide(Complex a, double s, Complex[] result)](#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---) | Делит `a` на `s`. |
| [divide(double s, Complex a, Complex[] result)](#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---) | Делит `s` на `a`. |
| [negate(Complex a)](#negate-com.aspose.imaging.imagefilters.complexutils.Complex-) | Отрицает `a`. |
| [approxEqual(Complex a, Complex b)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) | Проверяет приближённое равенство. |
| [approxEqual(Complex a, Complex b, double tolerance)](#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-) | Проверяет приближённое равенство. |
| [parse(String s)](#parse-java.lang.String-) | Разбирает указанный `s` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [tryParse(String s, Complex[] result)](#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---) | Пытается разобрать указанный `s` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
| [sqrt(Complex a)](#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-) | Получает квадратный корень от `a`. |
| [log(Complex a)](#log-com.aspose.imaging.imagefilters.complexutils.Complex-) | Получает логарифм от `a`. |
| [exp(Complex a)](#exp-com.aspose.imaging.imagefilters.complexutils.Complex-) | Возводит e в степень `a`. |
| [sin(Complex a)](#sin-com.aspose.imaging.imagefilters.complexutils.Complex-) | Получает синус от `a`. |
| [cos(Complex a)](#cos-com.aspose.imaging.imagefilters.complexutils.Complex-) | Получает косинус от `a`. |
| [tan(Complex a)](#tan-com.aspose.imaging.imagefilters.complexutils.Complex-) | Получает тангенс от `a`. |
| [isEquals(Complex obj1, Complex obj2)](#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-) |  |
| [multiply_internalize(double s)](#multiply-internalize-double-) | Умножает на `s`. |
| [getRe()](#getRe--) | Получает действительную часть. |
| [setRe(double value)](#setRe-double-) | Устанавливает действительную часть. |
| [getIm()](#getIm--) | Получает мнимую часть. |
| [setIm(double value)](#setIm-double-) | Устанавливает мнимую часть. |
| [set(double re, double im)](#set-double-double-) | Устанавливает значения и возвращает себя. |
| [getMagnitude()](#getMagnitude--) | Получает модуль. |
| [getPhase()](#getPhase--) | Получает фазу. |
| [getSquaredMagnitude()](#getSquaredMagnitude--) | Получает квадрат модуля. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [toString()](#toString--) | Возвращает строку, представляющую этот экземпляр. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
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


Инициализирует новый экземпляр структуры [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| действительная | double | Действительная часть. |
| мнимая | double | Мнимая часть. |

### Complex(Complex c) {#Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public Complex(Complex c)
```


Инициализирует новый экземпляр структуры [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| c | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное число. |

### SIZE_OF_DOUBLE {#SIZE-OF-DOUBLE}
```
public static final int SIZE_OF_DOUBLE
```


Размер `double`.

### SIZE_OF_COMPLEX {#SIZE-OF-COMPLEX}
```
public static final int SIZE_OF_COMPLEX
```


Размер комплексного числа.

### ZERO {#ZERO}
```
public static final Complex ZERO
```


Нулевой комплекс.

### ONE {#ONE}
```
public static final Complex ONE
```


Один комплекс, имеющий `Re`(\#getRe.getRe/\#setRe(double).setRe(double)) и `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) равные 1.

### I {#I}
```
public static final Complex I
```


Комплекс, имеющий `Im`(\#getIm.getIm/\#setIm(double).setIm(double)) равный 1.

### to_Complex(double value) {#to-Complex-double-}
```
public static Complex to_Complex(double value)
```


Выполняет явное преобразование из `double` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### to_Complex(float value) {#to-Complex-float-}
```
public static Complex to_Complex(float value)
```


Выполняет явное преобразование из `float` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the conversion.
### op_Equality(Complex a, Complex b) {#op-Equality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Equality(Complex a, Complex b)
```


Реализует оператор ==.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
boolean - Результат оператора.
### op_Inequality(Complex a, Complex b) {#op-Inequality-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean op_Inequality(Complex a, Complex b)
```


Реализует оператор !=.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
boolean - Результат оператора.
### op_UnaryNegation(Complex a) {#op-UnaryNegation-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_UnaryNegation(Complex a)
```


Реализует оператор -.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, Complex b) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(Complex a, Complex b)
```


Реализует оператор +.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(Complex a, double s) {#op-Addition-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Addition(Complex a, double s)
```


Реализует оператор +.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Addition(double s, Complex a) {#op-Addition-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Addition(double s, Complex a)
```


Реализует оператор +.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, Complex b) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(Complex a, Complex b)
```


Реализует оператор -.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(Complex a, double s) {#op-Subtraction-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Subtraction(Complex a, double s)
```


Реализует оператор -.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Subtraction(double s, Complex a) {#op-Subtraction-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Subtraction(double s, Complex a)
```


Реализует оператор -.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, Complex b) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(Complex a, Complex b)
```


Реализует оператор \*.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(double s, Complex a) {#op-Multiply-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Multiply(double s, Complex a)
```


Реализует оператор \*.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Multiply(Complex a, double s) {#op-Multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Multiply(Complex a, double s)
```


Реализует оператор \*.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, Complex b) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(Complex a, Complex b)
```


Реализует оператор /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(Complex a, double s) {#op-Division-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex op_Division(Complex a, double s)
```


Реализует оператор /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### op_Division(double s, Complex a) {#op-Division-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex op_Division(double s, Complex a)
```


Реализует оператор /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of the operator.
### add(Complex a, Complex b) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex add(Complex a, Complex b)
```


Складывает `a` и `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The sum complex.
### add(Complex a, double s) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex add(Complex a, double s)
```


Складывает `a` и `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex with its Re increased by `s`.
### add(Complex a, Complex b, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, Complex b, Complex[] result)
```


Складывает `a` и `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### add(Complex a, double s, Complex[] result) {#add-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void add(Complex a, double s, Complex[] result)
```


Складывает `a` и `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### subtract(Complex a, Complex b) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(Complex a, Complex b)
```


Вычитает `b` из `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, double s) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex subtract(Complex a, double s)
```


Вычитает `s` из `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(double s, Complex a) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex subtract(double s, Complex a)
```


Вычитает `s` из `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of subtraction.
### subtract(Complex a, Complex b, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, Complex b, Complex[] result)
```


Вычитает `b` из `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### subtract(Complex a, double s, Complex[] result) {#subtract-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(Complex a, double s, Complex[] result)
```


Вычитает `s` из `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### subtract(double s, Complex a, Complex[] result) {#subtract-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void subtract(double s, Complex a, Complex[] result)
```


Вычитает `a` из `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### multiply(Complex a, Complex b) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex multiply(Complex a, Complex b)
```


Умножает `a` на `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, double s) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex multiply(Complex a, double s)
```


Умножает `a` на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### multiply(Complex a, Complex b, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, Complex b, Complex[] result)
```


Умножает `a` на `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### multiply(Complex a, double s, Complex[] result) {#multiply-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void multiply(Complex a, double s, Complex[] result)
```


Умножает `a` на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### divide(Complex a, Complex b) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(Complex a, Complex b)
```


Делит `a` на `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, double s) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static Complex divide(Complex a, double s)
```


Делит `a` на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(double s, Complex a) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex divide(double s, Complex a)
```


Делит `a` на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of division.
### divide(Complex a, Complex b, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, Complex b, Complex[] result)
```


Делит `a` на `b`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### divide(Complex a, double s, Complex[] result) {#divide-com.aspose.imaging.imagefilters.complexutils.Complex-double-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(Complex a, double s, Complex[] result)
```


Делит `a` на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| s | double | Значение s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### divide(double s, Complex a, Complex[] result) {#divide-double-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static void divide(double s, Complex a, Complex[] result)
```


Делит `s` на `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

### negate(Complex a) {#negate-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex negate(Complex a)
```


Отрицает `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of negation.
### approxEqual(Complex a, Complex b) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean approxEqual(Complex a, Complex b)
```


Проверяет приближённое равенство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |

**Returns:**
boolean - Результат приближённого равенства.
### approxEqual(Complex a, Complex b, double tolerance) {#approxEqual-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-double-}
```
public static boolean approxEqual(Complex a, Complex b, double tolerance)
```


Проверяет приближённое равенство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |
| b | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное b. |
| допуск | double | Допуск. |

**Returns:**
boolean - Результат приближённого равенства.
### parse(String s) {#parse-java.lang.String-}
```
public static Complex parse(String s)
```


Разбирает указанный `s` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The complex number.
### tryParse(String s, Complex[] result) {#tryParse-java.lang.String-com.aspose.imaging.imagefilters.complexutils.Complex---}
```
public static boolean tryParse(String s, Complex[] result)
```


Пытается разобрать указанный `s` в [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | java.lang.String | Значение s. |
| result | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | Результат. |

**Returns:**
boolean - True, если комплексное число разобрано.
### sqrt(Complex a) {#sqrt-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sqrt(Complex a)
```


Получает квадратный корень от `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The square root.
### log(Complex a) {#log-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex log(Complex a)
```


Получает логарифм от `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The log of `a`.
### exp(Complex a) {#exp-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex exp(Complex a)
```


Возводит e в степень `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - e raised by `a`.
### sin(Complex a) {#sin-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex sin(Complex a)
```


Получает синус от `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Sin of `a`.
### cos(Complex a) {#cos-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex cos(Complex a)
```


Получает косинус от `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Cos of `a`.
### tan(Complex a) {#tan-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static Complex tan(Complex a)
```


Получает тангенс от `a`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) | Комплексное "a". |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - Tan of `a`.
### isEquals(Complex obj1, Complex obj2) {#isEquals-com.aspose.imaging.imagefilters.complexutils.Complex-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public static boolean isEquals(Complex obj1, Complex obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |
| obj2 | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

**Returns:**
boolean
### multiply_internalize(double s) {#multiply-internalize-double-}
```
public Complex multiply_internalize(double s)
```


Умножает на `s`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| s | double | Значение s. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The result of multiplication.
### getRe() {#getRe--}
```
public final double getRe()
```


Получает действительную часть.

**Returns:**
double - действительная часть.
### setRe(double value) {#setRe-double-}
```
public final void setRe(double value)
```


Устанавливает действительную часть.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | действительная часть. |

### getIm() {#getIm--}
```
public final double getIm()
```


Получает мнимую часть.

**Returns:**
double - мнимая часть.
### setIm(double value) {#setIm-double-}
```
public final void setIm(double value)
```


Устанавливает мнимую часть.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | мнимая часть. |

### set(double re, double im) {#set-double-double-}
```
public final Complex set(double re, double im)
```


Устанавливает значения и возвращает себя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| re | double | Значение Re. |
| im | double | Значение Im. |

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - The object itself.
### getMagnitude() {#getMagnitude--}
```
public final double getMagnitude()
```


Получает модуль.

Значение: модуль.

**Returns:**
double - модуль.
### getPhase() {#getPhase--}
```
public final double getPhase()
```


Получает фазу.

Значение: фаза.

**Returns:**
double - фаза.
### getSquaredMagnitude() {#getSquaredMagnitude--}
```
public final double getSquaredMagnitude()
```


Получает квадрат модуля.

Значение: квадрат модуля.

**Returns:**
double - квадрат модуля.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный `Object` этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `Object` для сравнения с этим экземпляром. |

**Returns:**
логический тип - `true`, если указанный `Object` равен этому экземпляру; иначе `false`.
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую этот экземпляр.

**Returns:**
java.lang.String - Строка, представляющая этот экземпляр.
### deepClone() {#deepClone--}
```
public final Complex deepClone()
```


Клонирует этот экземпляр.

**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) - A clone of this complex.
### CloneTo(Complex that) {#CloneTo-com.aspose.imaging.imagefilters.complexutils.Complex-}
```
public void CloneTo(Complex that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex) |  |

### Clone() {#Clone--}
```
public Complex Clone()
```




**Returns:**
[Complex](../../com.aspose.imaging.imagefilters.complexutils/complex)
