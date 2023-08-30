---
title: TiffSRational Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

**Aspose.Imaging Version:** 23.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(value)](#TiffSRational_value_3) | Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | The epsilon for fraction calculation |
| denominator | int | r | Gets the denominator. |
| nominator | int | r | Gets the nominator. |
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


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| nominator | int | The nominator. |
| denominator | int | The denominator. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initializes a new instance of the [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | int | The nominator value. |

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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | A rational number having error less than <paramref name="epsilon" />. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) | A rational number having error less than <paramref name="epsilon" />. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) |  |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) |  |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) |  |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational) |  |


