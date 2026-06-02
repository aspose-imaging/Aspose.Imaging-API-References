---
title: "Класс TiffSRational"
type: docs
weight: 280
url: /ru/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | float | r | Эпсилон для вычисления дроби |
| знаменатель | int | r | Получает знаменатель. |
| числитель | int | r | Получает числитель. |
| значение | float | r | Получает значение типа float. |
| value_d | float | r | Получает значение типа double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Приближает заданное значение к дроби. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Приближает заданное значение к дроби. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Приближает заданное значение к дроби. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Приближает заданное значение к дроби. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Приближает заданное значение к дроби. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Приближает заданное значение к дроби. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Приближает заданное значение к дроби. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Приближает заданное значение к дроби. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| числитель | int | Числитель. |
| знаменатель | int | Знаменатель. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Инициализирует новый экземпляр класса [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | int | Значение. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число, ошибка которого меньше [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |
| эпсилон | float | Допустимая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число с ошибкой меньше, чем _epsilon_. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число, ошибка которого меньше [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |
| эпсилон | float | Допустимая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число с ошибкой меньше, чем _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число, ошибка которого меньше [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число, ошибка которого меньше [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |
| эпсилон | float | Допустимая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число с ошибкой меньше, чем _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Приближает заданное значение к дроби.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |
| эпсилон | float | Допустимая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | Рациональное число с ошибкой меньше, чем _epsilon_. |


