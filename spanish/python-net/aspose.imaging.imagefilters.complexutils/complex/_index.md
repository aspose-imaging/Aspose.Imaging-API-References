---
title: "Clase Complex"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Complex()](#Complex__1) | Inicializa una nueva instancia de la clase Complex |
| [Complex(c)](#Complex_c_2) | Inicializa una nueva instancia de la estructura [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Inicializa una nueva instancia de la estructura [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complejo con [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) igual a 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complejo con [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) y [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) iguales a 1. |
| SIZE_OF_COMPLEX [estático] | int | r | El tamaño del complejo. |
| SIZE_OF_DOUBLE [estático] | int | r | El tamaño del float. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Complejo cero. |
| im | float | r/w | Obtiene o establece la parte imaginaria. |
| magnitud | float | r | Obtiene la magnitud. |
| fase | float | r | Obtiene la fase. |
| re | float | r/w | Obtiene o establece la parte real. |
| squared_magnitude | float | r | Obtiene la magnitud al cuadrado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Suma _a_ y _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Suma _a_ y _b_. |
| [add(a, s)](#add_a_s_3) | Suma _a_ y _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Suma _a_ y _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Comprueba la igualdad aproximada. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Comprueba la igualdad aproximada. |
| [clone()](#clone__7) | Clona esta instancia. |
| [cos(a)](#cos_a_8) | Obtiene el coseno de _a_. |
| [divide(a, b)](#divide_a_b_9) | Divide _a_ entre _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Divide _a_ entre _b_. |
| [divide(a, s)](#divide_a_s_11) | Divide _a_ entre _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Divide _a_ entre _s_. |
| [divide(s, a)](#divide_s_a_13) | Divide _a_ entre _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Divide _s_ entre _a_. |
| [exp(a)](#exp_a_15) | Eleva e a _a_. |
| [log(a)](#log_a_16) | Obtiene el logaritmo de _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Multiplica _a_ por _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Multiplica _a_ por _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Multiplica _a_ por _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Multiplica _a_ por _s_. |
| [negate(a)](#negate_a_21) | Niega _a_. |
| [parse(s)](#parse_s_22) | Analiza el _s_ especificado en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Obtiene el Sin de _a_. |
| [sqrt(a)](#sqrt_a_24) | Obtiene la raíz cuadrada de _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Resta _b_ de _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Resta _b_ de _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Resta _s_ de _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Resta _s_ de _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Resta _s_ de _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Resta _a_ de _s_. |
| [tan(a)](#tan_a_31) | Obtiene el Tan de _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Intenta analizar el _s_ especificado en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Inicializa una nueva instancia de la clase Complex

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Inicializa una nueva instancia de la estructura [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El número complejo. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Inicializa una nueva instancia de la estructura [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| real | float | La parte real. |
| imaginario | float | La parte imaginaria. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Suma _a_ y _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo suma. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Suma _a_ y _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Suma _a_ y _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El número complejo con su Re aumentado en _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Suma _a_ y _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Comprueba la igualdad aproximada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El resultado de igualdad aproximada. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Comprueba la igualdad aproximada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |
| tolerancia | float | La tolerancia. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El resultado de igualdad aproximada. |


### Method: clone() {#clone__7}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Una copia de este número complejo. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Obtiene el coseno de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos de _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Divide _a_ entre _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la división. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Divide _a_ entre _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Divide _a_ entre _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la división. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Divide _a_ entre _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Divide _a_ entre _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | float | El valor s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la división. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Divide _s_ entre _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | float | El valor s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Eleva e a _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e elevado a _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Obtiene el logaritmo de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El logaritmo de _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Multiplica _a_ por _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la multiplicación. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Multiplica _a_ por _b_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Multiplica _a_ por _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la multiplicación. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Multiplica _a_ por _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Niega _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la negación. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Analiza el _s_ especificado en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | El valor s. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El número complejo. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Obtiene el Sin de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin de _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Obtiene la raíz cuadrada de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | La raíz cuadrada. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Resta _b_ de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la sustracción. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Resta _b_ de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Resta _s_ de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la sustracción. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Resta _s_ de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| s | float | El valor s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Resta _s_ de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | float | El valor s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado de la sustracción. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Resta _a_ de _s_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | float | El valor s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Obtiene el Tan de _a_.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El complejo a. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan de _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Intenta analizar el _s_ especificado en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| s | string | El valor s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | El resultado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero, si el número complejo se analiza. |


