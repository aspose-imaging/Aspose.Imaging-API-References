---
title: TiffRational Class
type: docs
weight: 230
url: /python-net/aspose.imaging.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffRational

**Aspose.Imaging Version:** 23.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class. |
| [TiffRational(value)](#TiffRational_value_3) | Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | The epsilon for fraction calculation |
| denominator | uint | r | Gets the denominator. |
| nominator | uint | r | Gets the nominator. |
| value | float | r | Gets the float value. |
| value_d | double | r | Gets the double value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Approximates the provided value to a fraction. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Approximates the provided value to a fraction. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Approximates the provided value to a fraction. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Approximates the provided value to a fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_5) |    |
| [approximate_fraction(value)](#approximate_fraction_value_6) |    |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) |    |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) |    |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| nominator | uint | The nominator. |
| denominator | uint | The denominator. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | uint | The nominator value. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | A rational number having error less than [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double | The value. |
| epsilon | double | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | A rational number having error less than <paramref name="epsilon" />. |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | A rational number having error less than [TiffRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | double | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) | A rational number having error less than <paramref name="epsilon" />. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double |  |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) |  |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float |  |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) |  |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double |  |
| epsilon | double |  |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) |  |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float |  |
| epsilon | double |  |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational) |  |


