---
title: "TiffSRational 类"
type: docs
weight: 280
url: /zh/python-net/aspose.imaging.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffSRational

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | 初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。 |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | 初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。 |
| [TiffSRational(value)](#TiffSRational_value_3) | 初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| EPSILON [静态] | float | r | 用于分数计算的 epsilon |
| 分母 | int | r | 获取分母。 |
| 分子 | int | r | 获取分子。 |
| value | float | r | 获取浮点值。 |
| value_d | float | r | 获取双精度值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [approximate_double_fraction(value)](#approximate_double_fraction_value_1) | 将提供的值近似为分数。 |
| [approximate_double_fraction_eps(value, epsilon)](#approximate_double_fraction_eps_value_epsilon_2) | 将提供的值近似为分数。 |
| [approximate_float_fraction(value)](#approximate_float_fraction_value_3) | 将提供的值近似为分数。 |
| [approximate_float_fraction_eps(value, epsilon)](#approximate_float_fraction_eps_value_epsilon_4) | 将提供的值近似为分数。 |
| [approximate_fraction(value)](#approximate_fraction_value_5) | 将提供的值近似为分数。 |
| [approximate_fraction(value)](#approximate_fraction_value_6) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_7) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_8) | 将提供的值近似为分数。 |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 分子 | int | 分子。 |
| 分母 | int | 分母。 |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

初始化 [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | int | 值。 |

### Method: approximate_double_fraction(value)  [static] {#approximate_double_fraction_value_1}


```
 approximate_double_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_double_fraction_eps(value, epsilon)  [static] {#approximate_double_fraction_eps_value_epsilon_2}


```
 approximate_double_fraction_eps(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |
| epsilon | float | 允许的误差。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 _epsilon_ 的有理数。 |


### Method: approximate_float_fraction(value)  [static] {#approximate_float_fraction_value_3}


```
 approximate_float_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_float_fraction_eps(value, epsilon)  [static] {#approximate_float_fraction_eps_value_epsilon_4}


```
 approximate_float_fraction_eps(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |
| epsilon | float | 允许的误差。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 _epsilon_ 的有理数。 |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_5}


```
 approximate_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_6}


```
 approximate_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 [TiffSRational.EPSILON](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_7}


```
 approximate_fraction(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |
| epsilon | float | 允许的误差。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 _epsilon_ 的有理数。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_8}


```
 approximate_fraction(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | float | 值。 |
| epsilon | float | 允许的误差。 |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffsrational/) | 误差小于 _epsilon_ 的有理数。 |


