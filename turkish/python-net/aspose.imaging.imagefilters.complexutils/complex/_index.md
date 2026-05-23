---
title: "Complex Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.imaging.imagefilters.complexutils/complex/
---

**Summary:** The complex number structure.

**Module:** [aspose.imaging.imagefilters.complexutils](/imaging/python-net/aspose.imaging.imagefilters.complexutils/)

**Full Name:** aspose.imaging.imagefilters.complexutils.Complex

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Complex()](#Complex__1) | Complex sınıfının yeni bir örneğini başlatır. |
| [Complex(c)](#Complex_c_2) | Yeni bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) yapısının örneğini başlatır. |
| [Complex(real, imaginary)](#Complex_real_imaginary_3) | Yeni bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) yapısının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| I [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Bir kompleks, [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) değeri 1'e eşit. |
| ONE [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Bir kompleks, [Complex.re](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) ve [Complex.im](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) değeri 1'e eşit. |
| SIZE_OF_COMPLEX [static] | int | r | complex'in boyutu. |
| SIZE_OF_DOUBLE [static] | int | r | float'ın boyutu. |
| ZERO [static] | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | Sıfır complex. |
| im | float | r/w | Hayali kısmı alır veya ayarlar. |
| magnitude | float | r | Büyüklüğü alır. |
| phase | float | r | Fazı alır. |
| re | float | r/w | Gerçek kısmı alır veya ayarlar. |
| squared_magnitude | float | r | Kare büyüklüğü alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add(a, b)](#add_a_b_1) | _a_ ve _b_'yi toplar. |
| [add(a, b, result)](#add_a_b_result_2) | _a_ ve _b_'yi toplar. |
| [add(a, s)](#add_a_s_3) | _a_ ve _s_'yi toplar. |
| [add(a, s, result)](#add_a_s_result_4) | _a_ ve _s_'yi toplar. |
| [approx_equal(a, b)](#approx_equal_a_b_5) | Yaklaşık eşitliği kontrol eder. |
| [approx_equal(a, b, tolerance)](#approx_equal_a_b_tolerance_6) | Yaklaşık eşitliği kontrol eder. |
| [clone()](#clone__7) | Bu örneği klonlar. |
| [cos(a)](#cos_a_8) | _a_'nın Cos değerini alır. |
| [divide(a, b)](#divide_a_b_9) | _a_'yı _b_'ye böler. |
| [divide(a, b, result)](#divide_a_b_result_10) | _a_'yı _b_'ye böler. |
| [divide(a, s)](#divide_a_s_11) | _a_'yı _s_ ile böler. |
| [divide(a, s, result)](#divide_a_s_result_12) | _a_'yı _s_ ile böler. |
| [divide(s, a)](#divide_s_a_13) | _a_'yı _s_ ile böler. |
| [divide(s, a, result)](#divide_s_a_result_14) | _s_'yı _a_ ile böler. |
| [exp(a)](#exp_a_15) | e'yi _a_ kadar yükseltir. |
| [log(a)](#log_a_16) | _a_'nın logaritmasını alır. |
| [multiply(a, b)](#multiply_a_b_17) | _a_'yı _b_ ile çarpar. |
| [multiply(a, b, result)](#multiply_a_b_result_18) | _a_'yı _b_ ile çarpar. |
| [multiply(a, s)](#multiply_a_s_19) | _a_'yı _s_ ile çarpar. |
| [multiply(a, s, result)](#multiply_a_s_result_20) | _a_'yı _s_ ile çarpar. |
| [negate(a)](#negate_a_21) | _a_'yı negatife çevirir. |
| [parse(s)](#parse_s_22) | Belirtilen _s_'yi bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) içine ayrıştırır. |
| [sin(a)](#sin_a_23) | _a_'nın Sin'ini alır. |
| [sqrt(a)](#sqrt_a_24) | _a_'nın karekökünü alır. |
| [subtract(a, b)](#subtract_a_b_25) | _a_'dan _b_'yi çıkarır. |
| [subtract(a, b, result)](#subtract_a_b_result_26) | _a_'dan _b_'yi çıkarır. |
| [subtract(a, s)](#subtract_a_s_27) | _a_'dan _s_'yi çıkarır. |
| [subtract(a, s, result)](#subtract_a_s_result_28) | _a_'dan _s_'yi çıkarır. |
| [subtract(s, a)](#subtract_s_a_29) | _a_'dan _s_'yi çıkarır. |
| [subtract(s, a, result)](#subtract_s_a_result_30) | _s_'dan _a_'yi çıkarır. |
| [tan(a)](#tan_a_31) | _a_'nın Tan'ını alır. |
| [try_parse(s, result)](#try_parse_s_result_32) | Belirtilen _s_'yi bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) içine ayrıştırmayı dener. |


### Constructor: Complex() {#Complex__1}


```
 Complex() 
```

Complex sınıfının yeni bir örneğini başlatır.

### Constructor: Complex(c) {#Complex_c_2}


```
 Complex(c) 
```

Yeni bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) yapısının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| c | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Karmaşık sayı. |

### Constructor: Complex(real, imaginary) {#Complex_real_imaginary_3}


```
 Complex(real, imaginary) 
```

Yeni bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) yapısının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| gerçek | float | Gerçek kısım. |
| imajiner | float | İmajiner kısım. |

### Method: add(a, b)  [static] {#add_a_b_1}


```
 add(a, b) 
```

_a_ ve _b_'yi toplar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | toplam karmaşık. |


### Method: add(a, b, result)  [static] {#add_a_b_result_2}


```
 add(a, b, result) 
```

_a_ ve _b_'yi toplar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: add(a, s)  [static] {#add_a_s_3}


```
 add(a, s) 
```

_a_ ve _s_'yi toplar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Re'si _s_ artırılmış karmaşık sayı. |


### Method: add(a, s, result)  [static] {#add_a_s_result_4}


```
 add(a, s, result) 
```

_a_ ve _s_'yi toplar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: approx_equal(a, b)  [static] {#approx_equal_a_b_5}


```
 approx_equal(a, b) 
```

Yaklaşık eşitliği kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Yaklaşık eşitlik sonucu. |


### Method: approx_equal(a, b, tolerance)  [static] {#approx_equal_a_b_tolerance_6}


```
 approx_equal(a, b, tolerance) 
```

Yaklaşık eşitliği kontrol eder.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |
| tolerans | float | Tolerans. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Yaklaşık eşitlik sonucu. |


### Method: clone() {#clone__7}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Bu karmaşık sayının bir kopyası. |


### Method: cos(a)  [static] {#cos_a_8}


```
 cos(a) 
```

_a_'nın Cos değerini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Cos _a_'nın. |


### Method: divide(a, b)  [static] {#divide_a_b_9}


```
 divide(a, b) 
```

_a_'yı _b_'ye böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Bölme sonucu. |


### Method: divide(a, b, result)  [static] {#divide_a_b_result_10}


```
 divide(a, b, result) 
```

_a_'yı _b_'ye böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: divide(a, s)  [static] {#divide_a_s_11}


```
 divide(a, s) 
```

_a_'yı _s_ ile böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Bölme sonucu. |


### Method: divide(a, s, result)  [static] {#divide_a_s_result_12}


```
 divide(a, s, result) 
```

_a_'yı _s_ ile böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: divide(s, a)  [static] {#divide_s_a_13}


```
 divide(s, a) 
```

_a_'yı _s_ ile böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | float | s değeri. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Bölme sonucu. |


### Method: divide(s, a, result)  [static] {#divide_s_a_result_14}


```
 divide(s, a, result) 
```

_s_'yı _a_ ile böler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | float | s değeri. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: exp(a)  [static] {#exp_a_15}


```
 exp(a) 
```

e'yi _a_ kadar yükseltir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | e _a_ kadar yükseltilmiş. |


### Method: log(a)  [static] {#log_a_16}


```
 log(a) 
```

_a_'nın logaritmasını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Log _a_'ın. |


### Method: multiply(a, b)  [static] {#multiply_a_b_17}


```
 multiply(a, b) 
```

_a_'yı _b_ ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Çarpma sonucu. |


### Method: multiply(a, b, result)  [static] {#multiply_a_b_result_18}


```
 multiply(a, b, result) 
```

_a_'yı _b_ ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: multiply(a, s)  [static] {#multiply_a_s_19}


```
 multiply(a, s) 
```

_a_'yı _s_ ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Çarpma sonucu. |


### Method: multiply(a, s, result)  [static] {#multiply_a_s_result_20}


```
 multiply(a, s, result) 
```

_a_'yı _s_ ile çarpar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: negate(a)  [static] {#negate_a_21}


```
 negate(a) 
```

_a_'yı negatife çevirir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Negatifleme sonucu. |


### Method: parse(s)  [static] {#parse_s_22}


```
 parse(s) 
```

Belirtilen _s_'yi bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) içine ayrıştırır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | s değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Karmaşık sayı. |


### Method: sin(a)  [static] {#sin_a_23}


```
 sin(a) 
```

_a_'nın Sin'ini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sin _a_'nın. |


### Method: sqrt(a)  [static] {#sqrt_a_24}


```
 sqrt(a) 
```

_a_'nın karekökünü alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Karekök. |


### Method: subtract(a, b)  [static] {#subtract_a_b_25}


```
 subtract(a, b) 
```

_a_'dan _b_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Çıkarma sonucu. |


### Method: subtract(a, b, result)  [static] {#subtract_a_b_result_26}


```
 subtract(a, b, result) 
```

_a_'dan _b_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| b | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | b karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: subtract(a, s)  [static] {#subtract_a_s_27}


```
 subtract(a, s) 
```

_a_'dan _s_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Çıkarma sonucu. |


### Method: subtract(a, s, result)  [static] {#subtract_a_s_result_28}


```
 subtract(a, s, result) 
```

_a_'dan _s_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| s | float | s değeri. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: subtract(s, a)  [static] {#subtract_s_a_29}


```
 subtract(s, a) 
```

_a_'dan _s_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | float | s değeri. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Çıkarma sonucu. |


### Method: subtract(s, a, result)  [static] {#subtract_s_a_result_30}


```
 subtract(s, a, result) 
```

_s_'dan _a_'yi çıkarır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | float | s değeri. |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

### Method: tan(a)  [static] {#tan_a_31}


```
 tan(a) 
```

_a_'nın Tan'ını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| a | [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | a karmaşık. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Tan _a_'nın. |


### Method: try_parse(s, result)  [static] {#try_parse_s_result_32}


```
 try_parse(s, result) 
```

Belirtilen _s_'yi bir [Complex](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) içine ayrıştırmayı dener.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| s | string | s değeri. |
| result | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | Sonuç. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Doğru, eğer karmaşık sayı ayrıştırıldıysa. |


