---
title: Complex Class
type: docs
weight: 10
url: /python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Complex()](#Complex__1) | Initializes a new instance of the Complex class |
| [Complex(c)](#Complex_c_2) | Initializes a new instance of the [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) struct. |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Initializes a new instance of the [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) struct. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | I complex having [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) equal to 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | One complex having [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) and [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) equal to 1. |
| SIZE_OF_COMPLEX [static] | int | r | The size of complex. |
| SIZE_OF_DOUBLE [static] | int | r | The size of float. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Zero complex. |
| im | float | r/w | Gets or sets the imaginary part. |
| magnitude | float | r | Gets the magnitude. |
| phase | float | r | Gets the phase. |
| re | float | r/w | Gets or sets the real part. |
| squared_magnitude | float | r | Gets the squared magnitude. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Adds _a_ and _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Adds _a_ and _b_. |
| [add(a, s)](#add_a_s_3) | Adds _a_ and _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Adds _a_ and _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Checks approximate equality. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Checks approximate equality. |
| [clone()](#clone__7) | Clones this instance. |
| [cos(a)](#cos_a_8) | Gets Cos of _a_. |
| [divide(a, b)](#divide_a_b_9) | Divides _a_ by _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Divides _a_ by _b_. |
| [divide(a, s)](#divide_a_s_11) | Divides _a_ by _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Divides _a_ by _s_. |
| [divide(s, a)](#divide_s_a_13) | Divides _a_ by _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Divides _s_ by _a_. |
| [exp(a)](#exp_a_15) | Raises e by _a_. |
| [log(a)](#log_a_16) | Gets log of _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Multiplies _a_ by _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Multiplies _a_ by _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Multiplies _a_ by _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Multiplies _a_ by _s_. |
| [negate(a)](#negate_a_21) | Negates _a_. |
| [parse(s)](#parse_s_22) | Parses the specified _s_ into a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Gets Sin of _a_. |
| [sqrt(a)](#sqrt_a_24) | Gets square root of _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Subtracts _b_ from _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Subtracts _b_ from _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Subtracts _s_ from _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Subtracts _s_ from _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Subtracts _s_ from _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Subtracts _a_ from _s_. |
| [tan(a)](#tan_a_31) | Gets Tan of _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Tries to parse the specified _s_ into a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Initializes a new instance of the Complex class

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Initializes a new instance of the [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The complex number. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Initializes a new instance of the [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) struct.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| real | float | The real part. |
| imaginary | float | The imaginary part. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Adds _a_ and _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The sum complex. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Adds _a_ and _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Adds _a_ and _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The complex with its Re increased by _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Adds _a_ and _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Checks approximate equality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |

**Returns**

| Type | Description |
| :- | :- |
| bool | The approximate equality result. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Checks approximate equality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |
| tolerance | float | The tolerance. |

**Returns**

| Type | Description |
| :- | :- |
| bool | The approximate equality result. |


### Method: clone() {#clone__7}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | A clone of this complex. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Gets Cos of _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos of _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Divides _a_ by _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of division. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Divides _a_ by _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Divides _a_ by _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of division. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Divides _a_ by _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Divides _a_ by _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | float | The s value. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of division. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Divides _s_ by _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | float | The s value. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Raises e by _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e raised by _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Gets log of _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The log of _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Multiplies _a_ by _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of multiplication. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Multiplies _a_ by _b_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Multiplies _a_ by _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of multiplication. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Multiplies _a_ by _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Negates _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of negation. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Parses the specified _s_ into a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | The s value. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The complex number. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Gets Sin of _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin of _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Gets square root of _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The square root. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Subtracts _b_ from _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of subtraction. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Subtracts _b_ from _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The b complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Subtracts _s_ from _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of subtraction. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Subtracts _s_ from _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| s | float | The s value. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Subtracts _s_ from _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | float | The s value. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result of subtraction. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Subtracts _a_ from _s_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | float | The s value. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Gets Tan of _a_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The a complex. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan of _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Tries to parse the specified _s_ into a [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| s | string | The s value. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | The result. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True, if the complex number is parsed. |


