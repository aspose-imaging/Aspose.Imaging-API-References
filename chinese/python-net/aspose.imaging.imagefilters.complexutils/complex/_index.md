---
title: "Complex 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Complex()](#Complex__1) | 初始化 Complex 类的新实例 |
| [Complex(c)](#Complex_c_2) | 初始化 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 结构的新实例。 |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | 初始化 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | 我有一个复数，其 [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 等于 1。 |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | 一个复数，其 [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 和 [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 均等于 1。 |
| SIZE_OF_COMPLEX [static] | int | r | 复数的大小。 |
| SIZE_OF_DOUBLE [static] | int | r | float 的大小。 |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | 零复数。 |
| im | float | r/w | 获取或设置虚部。 |
| 幅度 | float | r | 获取幅度。 |
| 相位 | float | r | 获取相位。 |
| re | float | r/w | 获取或设置实部。 |
| 平方幅度 | float | r | 获取平方幅度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | 将 _a_ 与 _b_ 相加。 |
| [add(a, b, result)](#add_a_b_result_2) | 将 _a_ 与 _b_ 相加。 |
| [add(a, s)](#add_a_s_3) | 将 _a_ 与 _s_ 相加。 |
| [add(a, s, result)](#add_a_s_result_4) | 将 _a_ 与 _s_ 相加。 |
| [approx_equal(a, b)](#approx_equal_a_b_5) | 检查近似相等。 |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | 检查近似相等。 |
| [clone()](#clone__7) | 克隆此实例。 |
| [cos(a)](#cos_a_8) | 获取 _a_ 的余弦。 |
| [divide(a, b)](#divide_a_b_9) | 将 _a_ 除以 _b_。 |
| [divide(a, b, result)](#divide_a_b_result_10) | 将 _a_ 除以 _b_。 |
| [divide(a, s)](#divide_a_s_11) | 将 _a_ 除以 _s_。 |
| [divide(a, s, result)](#divide_a_s_result_12) | 将 _a_ 除以 _s_。 |
| [divide(s, a)](#divide_s_a_13) | 将 _a_ 除以 _s_。 |
| [divide(s, a, result)](#divide_s_a_result_14) | 将 _s_ 除以 _a_。 |
| [exp(a)](#exp_a_15) | 将 e 提升 _a_。 |
| [log(a)](#log_a_16) | 获取 _a_ 的对数。 |
| [multiply(a, b)](#multiply_a_b_17) | 将 _a_ 乘以 _b_。 |
| [multiply(a, b, result)](#multiply_a_b_result_18) | 将 _a_ 乘以 _b_。 |
| [multiply(a, s)](#multiply_a_s_19) | 将 _a_ 乘以 _s_。 |
| [multiply(a, s, result)](#multiply_a_s_result_20) | 将 _a_ 乘以 _s_。 |
| [negate(a)](#negate_a_21) | 对 _a_ 取负。 |
| [parse(s)](#parse_s_22) | 将指定的 _s_ 解析为一个 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/)。 |
| [sin(a)](#sin_a_23) | 获取 _a_ 的正弦。 |
| [sqrt(a)](#sqrt_a_24) | 获取 _a_ 的平方根。 |
| [subtract(a, b)](#subtract_a_b_25) | 从 _a_ 中减去 _b_。 |
| [subtract(a, b, result)](#subtract_a_b_result_26) | 从 _a_ 中减去 _b_。 |
| [subtract(a, s)](#subtract_a_s_27) | 从 _a_ 中减去 _s_。 |
| [subtract(a, s, result)](#subtract_a_s_result_28) | 从 _a_ 中减去 _s_。 |
| [subtract(s, a)](#subtract_s_a_29) | 从 _a_ 中减去 _s_。 |
| [subtract(s, a, result)](#subtract_s_a_result_30) | 从 _s_ 中减去 _a_。 |
| [tan(a)](#tan_a_31) | 获取 _a_ 的正切。 |
| [try_parse(s, result)](#try_parse_s_result_32) | 尝试将指定的 _s_ 解析为一个 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/)。 |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

初始化 Complex 类的新实例

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

初始化 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 复数。 |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

初始化 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) 结构的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 实部 | float | 实部。 |
| 虚部 | float | 虚部。 |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

将 _a_ 与 _b_ 相加。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 sum 复数。 |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

将 _a_ 与 _b_ 相加。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

将 _a_ 与 _s_ 相加。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 复数的实部增加了 _s_。 |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

将 _a_ 与 _s_ 相加。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

检查近似相等。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 近似相等的结果。 |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

检查近似相等。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |
| 容差 | float | 容差。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 近似相等的结果。 |


### Method: clone() {#clone__7}


```
 clone() 
```

克隆此实例。

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 此复数的克隆。 |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

获取 _a_ 的余弦。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos of _a_。 |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

将 _a_ 除以 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 除法的结果。 |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

将 _a_ 除以 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

将 _a_ 除以 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 除法的结果。 |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

将 _a_ 除以 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

将 _a_ 除以 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | float | s 值。 |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 除法的结果。 |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

将 _s_ 除以 _a_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | float | s 值。 |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

将 e 提升 _a_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e raised by _a_。 |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

获取 _a_ 的对数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 对 _a_ 的对数。 |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

将 _a_ 乘以 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 乘法的结果。 |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

将 _a_ 乘以 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

将 _a_ 乘以 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 乘法的结果。 |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

将 _a_ 乘以 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

对 _a_ 取负。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 取负的结果。 |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

将指定的 _s_ 解析为一个 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | s 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 复数。 |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

获取 _a_ 的正弦。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin of _a_。 |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

获取 _a_ 的平方根。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 平方根。 |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

从 _a_ 中减去 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 减法的结果。 |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

从 _a_ 中减去 _b_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 b 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

从 _a_ 中减去 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 减法的结果。 |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

从 _a_ 中减去 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| s | float | s 值。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

从 _a_ 中减去 _s_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | float | s 值。 |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 减法的结果。 |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

从 _s_ 中减去 _a_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | float | s 值。 |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

获取 _a_ 的正切。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 该 a 复数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan of _a_。 |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

尝试将指定的 _s_ 解析为一个 [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| s | string | s 值。 |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | 结果。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果成功解析复数，则为 True。 |


