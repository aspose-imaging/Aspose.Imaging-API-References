---
title: "TiffRational"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип rational TIFF."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Тип rational TIFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffRational()](#TiffRational--) | Инициализирует новый экземпляр класса `TiffRational`. |
| [TiffRational(long value)](#TiffRational-long-) | Инициализирует новый экземпляр класса `TiffRational`. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Инициализирует новый экземпляр класса `TiffRational`. |
## Поля

| Поле | Описание |
| --- | --- |
| [EPSILON](#EPSILON) | Эпсилон для вычисления дроби |
## Методы

| Метод | Описание |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(double value)](#approximateFraction-double-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Аппроксимирует предоставленное значение до дроби. |
| [approximateFraction(float value)](#approximateFraction-float-) | Аппроксимирует предоставленное значение до дроби. |
| [getDenominator()](#getDenominator--) | Получает знаменатель. |
| [getNominator()](#getNominator--) | Получает числитель. |
| [getValue()](#getValue--) | Получает значение float. |
| [getValueD()](#getValueD--) | Получает значение double. |
| [toString()](#toString--) | Преобразует в строку. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Инициализирует новый экземпляр класса `TiffRational`.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Инициализирует новый экземпляр класса `TiffRational`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | long | Значение числителя. |

Числитель будет использоваться как указанное значение, а знаменатель будет равен 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Инициализирует новый экземпляр класса `TiffRational`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| числитель | long | Числитель. |
| знаменатель | long | Знаменатель. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Эпсилон для вычисления дроби

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Получает знаменатель.

Значение: знаменатель.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Получает числитель.

Значение: числитель.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Получает значение float.

Значение: значение float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Получает значение double.

Значение: двойное значение.

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


Преобразует в строку.

**Returns:**
java.lang.String - Строка, представляющая этот экземпляр.
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
