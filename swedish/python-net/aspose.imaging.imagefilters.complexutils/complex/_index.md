---
title: "Complex-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Complex()](#Complex__1) | Initierar en ny instans av Complex-klassen |
| [Complex(c)](#Complex_c_2) | Initierar en ny instans av [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) strukt. |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Initierar en ny instans av [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) strukt. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Ett komplex med [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) lika med 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Ett komplex med [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) och [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) lika med 1. |
| SIZE_OF_COMPLEX [static] | int | r | Storleken på komplex. |
| SIZE_OF_DOUBLE [static] | int | r | Storleken på flyttal. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Noll komplex. |
| im | float | r/w | Hämtar eller anger den imaginära delen. |
| magnitud | float | r | Hämtar magnituden. |
| fas | float | r | Hämtar fasen. |
| re | float | r/w | Hämtar eller anger den reella delen. |
| kvadrerad_magnitud | float | r | Hämtar den kvadrerade magnituden. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Adderar _a_ och _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Adderar _a_ och _b_. |
| [add(a, s)](#add_a_s_3) | Adderar _a_ och _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Adderar _a_ och _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Kontrollerar ungefärlig likhet. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Kontrollerar ungefärlig likhet. |
| [clone()](#clone__7) | Klonar den här instansen. |
| [cos(a)](#cos_a_8) | Hämtar Cos av _a_. |
| [divide(a, b)](#divide_a_b_9) | Dividerar _a_ med _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Dividerar _a_ med _b_. |
| [divide(a, s)](#divide_a_s_11) | Dividerar _a_ med _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Dividerar _a_ med _s_. |
| [divide(s, a)](#divide_s_a_13) | Dividerar _a_ med _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Dividerar _s_ med _a_. |
| [exp(a)](#exp_a_15) | Upphöjer e till _a_. |
| [log(a)](#log_a_16) | Hämtar logaritmen av _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Multiplicerar _a_ med _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Multiplicerar _a_ med _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Multiplicerar _a_ med _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Multiplicerar _a_ med _s_. |
| [negate(a)](#negate_a_21) | Negerar _a_. |
| [parse(s)](#parse_s_22) | Analyserar den angivna _s_ till ett [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Hämtar sinus av _a_. |
| [sqrt(a)](#sqrt_a_24) | Hämtar kvadratroten av _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Subtraherar _b_ från _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Subtraherar _b_ från _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Subtraherar _s_ från _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Subtraherar _s_ från _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Subtraherar _s_ från _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Subtraherar _a_ från _s_. |
| [tan(a)](#tan_a_31) | Hämtar tangens av _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Försöker tolka den angivna _s_ till ett [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Initierar en ny instans av Complex-klassen

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Initierar en ny instans av [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) strukt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Det komplexa talet. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Initierar en ny instans av [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) strukt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| reell | float | Den reella delen. |
| imaginär | float | Den imaginära delen. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Adderar _a_ och _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den summa-komplexen. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Adderar _a_ och _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Adderar _a_ och _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Det komplexa talet med sin Re ökad med _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Adderar _a_ och _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Kontrollerar ungefärlig likhet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Det ungefärliga likhetsresultatet. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Kontrollerar ungefärlig likhet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |
| tolerans | float | Toleransen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Det ungefärliga likhetsresultatet. |


### Method: clone() {#clone__7}


```
 clone() 
```

Klonar den här instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | En klon av detta komplexa tal. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Hämtar Cos av _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos av _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Dividerar _a_ med _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av division. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Dividerar _a_ med _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Dividerar _a_ med _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av division. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Dividerar _a_ med _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Dividerar _a_ med _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | float | Det s-värdet. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av division. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Dividerar _s_ med _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | float | Det s-värdet. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Upphöjer e till _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e upphöjt till _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Hämtar logaritmen av _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Logaritmen av _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Multiplicerar _a_ med _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av multiplikation. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Multiplicerar _a_ med _b_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Multiplicerar _a_ med _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av multiplikation. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Multiplicerar _a_ med _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Negerar _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av negation. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Analyserar den angivna _s_ till ett [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Det s-värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Det komplexa talet. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Hämtar sinus av _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin av _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Hämtar kvadratroten av _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Kvadratroten. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Subtraherar _b_ från _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av subtraktion. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Subtraherar _b_ från _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den b-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Subtraherar _s_ från _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av subtraktion. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Subtraherar _s_ från _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| s | float | Det s-värdet. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Subtraherar _s_ från _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | float | Det s-värdet. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet av subtraktion. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Subtraherar _a_ från _s_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | float | Det s-värdet. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Hämtar tangens av _a_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Den a-komplexen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan av _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Försöker tolka den angivna _s_ till ett [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| s | string | Det s-värdet. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Resultatet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant, om det komplexa talet har parsats. |


