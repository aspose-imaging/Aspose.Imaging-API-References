---
title: "Класс Complex"
type: docs
weight: 10
url: /ru/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Complex()](#Complex__1) | Инициализирует новый экземпляр класса Complex |
| [Complex(c)](#Complex_c_2) | Инициализирует новый экземпляр структуры [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Инициализирует новый экземпляр структуры [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Комплекс с [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) равным 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Один комплекс с [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) и [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) равными 1. |
| SIZE_OF_COMPLEX [static] | int | r | Размер complex. |
| SIZE_OF_DOUBLE [static] | int | r | Размер float. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Ноль complex. |
| im | float | r/w | Получает или задает мнимую часть. |
| модуль | float | r | Получает модуль. |
| фаза | float | r | Получает фазу. |
| re | float | r/w | Получает или задает действительную часть. |
| квадрат_модуля | float | r | Получает квадрат модуля. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Складывает _a_ и _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Складывает _a_ и _b_. |
| [add(a, s)](#add_a_s_3) | Складывает _a_ и _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Складывает _a_ и _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Проверяет приближённое равенство. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Проверяет приближённое равенство. |
| [clone()](#clone__7) | Создаёт клон этого экземпляра. |
| [cos(a)](#cos_a_8) | Получает Cos от _a_. |
| [divide(a, b)](#divide_a_b_9) | Делит _a_ на _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Делит _a_ на _b_. |
| [divide(a, s)](#divide_a_s_11) | Делит _a_ на _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Делит _a_ на _s_. |
| [divide(s, a)](#divide_s_a_13) | Делит _a_ на _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Делит _s_ на _a_. |
| [exp(a)](#exp_a_15) | Возводит e в степень _a_. |
| [log(a)](#log_a_16) | Получает логарифм от _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Умножает _a_ на _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Умножает _a_ на _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Умножает _a_ на _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Умножает _a_ на _s_. |
| [negate(a)](#negate_a_21) | Отрицает _a_. |
| [parse(s)](#parse_s_22) | Разбирает указанный _s_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Получает синус _a_. |
| [sqrt(a)](#sqrt_a_24) | Получает квадратный корень от _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Вычитает _b_ из _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Вычитает _b_ из _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Вычитает _s_ из _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Вычитает _s_ из _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Вычитает _s_ из _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Вычитает _a_ из _s_. |
| [tan(a)](#tan_a_31) | Получает тангенс _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Пытается разобрать указанный _s_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Инициализирует новый экземпляр класса Complex

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Инициализирует новый экземпляр структуры [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное число. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Инициализирует новый экземпляр структуры [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| действительная | float | Действительная часть. |
| мнимая | float | Мнимая часть. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Складывает _a_ и _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сумма комплексного. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Складывает _a_ и _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Складывает _a_ и _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Комплекс, у которого Re увеличено на _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Складывает _a_ и _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Проверяет приближённое равенство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Результат приближённого равенства. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Проверяет приближённое равенство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |
| допуск | float | Допуск. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Результат приближённого равенства. |


### Method: clone() {#clone__7}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Клон этого комплексного числа. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Получает Cos от _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos от _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Делит _a_ на _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат деления. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Делит _a_ на _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Делит _a_ на _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат деления. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Делит _a_ на _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Делит _a_ на _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | float | Значение s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат деления. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Делит _s_ на _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | float | Значение s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Возводит e в степень _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e в степени _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Получает логарифм от _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | log от _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Умножает _a_ на _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат умножения. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Умножает _a_ на _b_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Умножает _a_ на _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат умножения. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Умножает _a_ на _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Отрицает _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат отрицания. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Разбирает указанный _s_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Значение s. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное число. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Получает синус _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin от _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Получает квадратный корень от _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Квадратный корень. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Вычитает _b_ из _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат вычитания. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Вычитает _b_ из _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Вычитает _s_ из _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат вычитания. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Вычитает _s_ из _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| s | float | Значение s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Вычитает _s_ из _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | float | Значение s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат вычитания. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Вычитает _a_ из _s_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | float | Значение s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Получает тангенс _a_.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Сложное a. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan от _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Пытается разобрать указанный _s_ в [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| s | string | Значение s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Результат. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если комплексное число разобрано. |


