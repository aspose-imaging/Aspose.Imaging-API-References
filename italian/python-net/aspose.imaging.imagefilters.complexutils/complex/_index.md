---
title: "Classe Complex"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Complex()](#Complex__1) | Inizializza una nuova istanza della classe Complex |
| [Complex(c)](#Complex_c_2) | Inizializza una nuova istanza della struct [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Inizializza una nuova istanza della struct [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complesso con [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) uguale a 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complesso con [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) e [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) uguali a 1. |
| SIZE_OF_COMPLEX [static] | int | r | La dimensione del complesso. |
| SIZE_OF_DOUBLE [static] | int | r | La dimensione del float. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Complesso zero. |
| im | float | r/w | Ottiene o imposta la parte immaginaria. |
| magnitudine | float | r | Ottiene la magnitudine. |
| fase | float | r | Ottiene la fase. |
| re | float | r/w | Ottiene o imposta la parte reale. |
| magnitudine_quadrata | float | r | Ottiene la magnitudine quadrata. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Aggiunge _a_ e _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Aggiunge _a_ e _b_. |
| [add(a, s)](#add_a_s_3) | Aggiunge _a_ e _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Aggiunge _a_ e _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Verifica l'uguaglianza approssimativa. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Verifica l'uguaglianza approssimativa. |
| [clone()](#clone__7) | Clona questa istanza. |
| [cos(a)](#cos_a_8) | Ottiene Cos di _a_. |
| [divide(a, b)](#divide_a_b_9) | Divide _a_ per _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Divide _a_ per _b_. |
| [divide(a, s)](#divide_a_s_11) | Divide _a_ per _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Divide _a_ per _s_. |
| [divide(s, a)](#divide_s_a_13) | Divide _a_ per _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Divide _s_ per _a_. |
| [exp(a)](#exp_a_15) | Eleva e a _a_. |
| [log(a)](#log_a_16) | Ottiene il log di _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Moltiplica _a_ per _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Moltiplica _a_ per _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Moltiplica _a_ per _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Moltiplica _a_ per _s_. |
| [negate(a)](#negate_a_21) | Nega _a_. |
| [parse(s)](#parse_s_22) | Analizza il _s_ specificato in un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Ottiene Sin di _a_. |
| [sqrt(a)](#sqrt_a_24) | Ottiene la radice quadrata di _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Sottrae _b_ da _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Sottrae _b_ da _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Sottrae _s_ da _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Sottrae _s_ da _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Sottrae _s_ da _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Sottrae _a_ da _s_. |
| [tan(a)](#tan_a_31) | Ottiene Tan di _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Prova ad analizzare il _s_ specificato in un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Inizializza una nuova istanza della classe Complex

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Inizializza una nuova istanza della struct [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il numero complesso. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Inizializza una nuova istanza della struct [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| reale | float | La parte reale. |
| immaginario | float | La parte immaginaria. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Aggiunge _a_ e _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso della somma. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Aggiunge _a_ e _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Aggiunge _a_ e _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso con la sua parte Re aumentata di _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Aggiunge _a_ e _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Verifica l'uguaglianza approssimativa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il risultato di uguaglianza approssimativa. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Verifica l'uguaglianza approssimativa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |
| tolleranza | float | La tolleranza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il risultato di uguaglianza approssimativa. |


### Method: clone() {#clone__7}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Una copia di questo complesso. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Ottiene Cos di _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos di _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Divide _a_ per _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della divisione. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Divide _a_ per _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Divide _a_ per _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della divisione. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Divide _a_ per _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Divide _a_ per _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | float | Il valore s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della divisione. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Divide _s_ per _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | float | Il valore s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Eleva e a _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e elevato a _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Ottiene il log di _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il log di _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Moltiplica _a_ per _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della moltiplicazione. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Moltiplica _a_ per _b_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Moltiplica _a_ per _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della moltiplicazione. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Moltiplica _a_ per _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Nega _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della negazione. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Analizza il _s_ specificato in un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Il valore s. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il numero complesso. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Ottiene Sin di _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin di _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Ottiene la radice quadrata di _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | La radice quadrata. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Sottrae _b_ da _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della sottrazione. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Sottrae _b_ da _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Sottrae _s_ da _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della sottrazione. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Sottrae _s_ da _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| s | float | Il valore s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Sottrae _s_ da _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | float | Il valore s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato della sottrazione. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Sottrae _a_ da _s_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | float | Il valore s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Ottiene Tan di _a_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il complesso a. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan di _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Prova ad analizzare il _s_ specificato in un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| s | string | Il valore s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Il risultato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero, se il numero complesso è analizzato. |


