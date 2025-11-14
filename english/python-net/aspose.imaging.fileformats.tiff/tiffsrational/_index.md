---
title: TiffSRational Class
type: docs
weight: 280
url: /python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(value)](#TiffSRational_value_3) | Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | float | r | The epsilon for fraction calculation |
| denominator | int | r | Gets the denominator. |
| nominator | int | r | Gets the nominator. |
| value | float | r | Gets the float value. |
| value_d | float | r | Gets the double value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | Approximates the provided value to a fraction. |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | Approximates the provided value to a fraction. |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | Approximates the provided value to a fraction. |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | Approximates the provided value to a fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_5) | Approximates the provided value to a fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_6) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | Approximates the provided value to a fraction. |


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

Initializes a new instance of the [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | int | The value. |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | float | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than _epsilon_. |


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
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | float | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than _epsilon_. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | float | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than _epsilon_. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | float | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | A rational number having error less than _epsilon_. |


