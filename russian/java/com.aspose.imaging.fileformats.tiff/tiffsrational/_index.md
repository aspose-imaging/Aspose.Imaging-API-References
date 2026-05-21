---
title: "TiffSRational"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип rational TIFF."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.tiff/tiffsrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Тип rational TIFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Инициализирует новый экземпляр класса `TiffSRational`. |
| [TiffSRational(int value)](#TiffSRational-int-) | Инициализирует новый экземпляр класса [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational). |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Инициализирует новый экземпляр класса `TiffSRational`. |
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
| [toString()](#toString--) | Возвращает `System.String`, представляющий этот экземпляр. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный `Object` этому экземпляру. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Инициализирует новый экземпляр класса `TiffSRational`.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Инициализирует новый экземпляр класса [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение числителя. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Инициализирует новый экземпляр класса `TiffSRational`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| числитель | int | Числитель. |
| знаменатель | int | Знаменатель. |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


Эпсилон для вычисления дроби

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение. |
| эпсилон | double | Допустимая ошибка. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Аппроксимирует предоставленное значение до дроби.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Получает знаменатель.

Значение: знаменатель.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Получает числитель.

Значение: числитель.

**Returns:**
int
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


Возвращает `System.String`, представляющий этот экземпляр.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
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
