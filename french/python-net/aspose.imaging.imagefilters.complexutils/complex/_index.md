---
title: "Classe Complex"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Complex()](#Complex__1) | Initialise une nouvelle instance de la classe Complex |
| [Complex(c)](#Complex_c_2) | Initialise une nouvelle instance de la structure [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Initialise une nouvelle instance de la structure [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complexe ayant [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) égal à 1. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Un complexe ayant [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) et [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) égaux à 1. |
| SIZE_OF_COMPLEX [static] | int | r | La taille du complex. |
| SIZE_OF_DOUBLE [static] | int | r | La taille du float. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Complexe zéro. |
| im | float | r/w | Obtient ou définit la partie imaginaire. |
| magnitude | float | r | Obtient la magnitude. |
| phase | float | r | Obtient la phase. |
| re | float | r/w | Obtient ou définit la partie réelle. |
| squared_magnitude | float | r | Obtient la magnitude au carré. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | Ajoute _a_ et _b_. |
| [add(a, b, result)](#add_a_b_result_2) | Ajoute _a_ et _b_. |
| [add(a, s)](#add_a_s_3) | Ajoute _a_ et _s_. |
| [add(a, s, result)](#add_a_s_result_4) | Ajoute _a_ et _s_. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Vérifie l'égalité approximative. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Vérifie l'égalité approximative. |
| [clone()](#clone__7) | Clone cette instance. |
| [cos(a)](#cos_a_8) | Obtient le cosinus de _a_. |
| [divide(a, b)](#divide_a_b_9) | Divise _a_ par _b_. |
| [divide(a, b, result)](#divide_a_b_result_10) | Divise _a_ par _b_. |
| [divide(a, s)](#divide_a_s_11) | Divise _a_ par _s_. |
| [divide(a, s, result)](#divide_a_s_result_12) | Divise _a_ par _s_. |
| [divide(s, a)](#divide_s_a_13) | Divise _a_ par _s_. |
| [divide(s, a, result)](#divide_s_a_result_14) | Divise _s_ par _a_. |
| [exp(a)](#exp_a_15) | Élève e à la puissance _a_. |
| [log(a)](#log_a_16) | Obtient le logarithme de _a_. |
| [multiply(a, b)](#multiply_a_b_17) | Multiplie _a_ par _b_. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | Multiplie _a_ par _b_. |
| [multiply(a, s)](#multiply_a_s_19) | Multiplie _a_ par _s_. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | Multiplie _a_ par _s_. |
| [negate(a)](#negate_a_21) | Inverse le signe de _a_. |
| [parse(s)](#parse_s_22) | Analyse le _s_ spécifié en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |
| [sin(a)](#sin_a_23) | Obtient le sinus de _a_. |
| [sqrt(a)](#sqrt_a_24) | Obtient la racine carrée de _a_. |
| [subtract(a, b)](#subtract_a_b_25) | Soustrait _b_ de _a_. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | Soustrait _b_ de _a_. |
| [subtract(a, s)](#subtract_a_s_27) | Soustrait _s_ de _a_. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | Soustrait _s_ de _a_. |
| [subtract(s, a)](#subtract_s_a_29) | Soustrait _s_ de _a_. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | Soustrait _a_ de _s_. |
| [tan(a)](#tan_a_31) | Obtient la tangente de _a_. |
| [try_parse(s, result)](#try_parse_s_result_32) | Essaie d'analyser le _s_ spécifié en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/). |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Initialise une nouvelle instance de la classe Complex

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Initialise une nouvelle instance de la structure [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le nombre complexe. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Initialise une nouvelle instance de la structure [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| réel | float | La partie réelle. |
| imaginaire | float | La partie imaginaire. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

Ajoute _a_ et _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe somme. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

Ajoute _a_ et _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

Ajoute _a_ et _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe avec son Re augmenté de _s_. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

Ajoute _a_ et _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Vérifie l'égalité approximative.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Le résultat d'égalité approximative. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Vérifie l'égalité approximative.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |
| tolérance | float | La tolérance. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Le résultat d'égalité approximative. |


### Method: clone() {#clone__7}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Un clone de ce complexe. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

Obtient le cosinus de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos de _a_. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

Divise _a_ par _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la division. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

Divise _a_ par _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

Divise _a_ par _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la division. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

Divise _a_ par _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

Divise _a_ par _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | float | La valeur s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la division. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

Divise _s_ par _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | float | La valeur s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

Élève e à la puissance _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e élevé à _a_. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

Obtient le logarithme de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le logarithme de _a_. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

Multiplie _a_ par _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la multiplication. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

Multiplie _a_ par _b_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

Multiplie _a_ par _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la multiplication. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

Multiplie _a_ par _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

Inverse le signe de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la négation. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Analyse le _s_ spécifié en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | La valeur s. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le nombre complexe. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

Obtient le sinus de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin de _a_. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

Obtient la racine carrée de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | La racine carrée. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

Soustrait _b_ de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la soustraction. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

Soustrait _b_ de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe b. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

Soustrait _s_ de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la soustraction. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

Soustrait _s_ de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| s | float | La valeur s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

Soustrait _s_ de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | float | La valeur s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat de la soustraction. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

Soustrait _a_ de _s_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | float | La valeur s. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

Obtient la tangente de _a_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le complexe a. |

**Returns**

| Type | Description |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan de _a_. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Essaie d'analyser le _s_ spécifié en un [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| s | string | La valeur s. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Le résultat. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai, si le nombre complexe est analysé. |


