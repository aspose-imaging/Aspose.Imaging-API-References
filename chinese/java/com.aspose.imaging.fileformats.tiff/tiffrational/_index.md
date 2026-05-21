---
title: "TiffRational"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "tiff 有理数类型。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.tiff/tiffrational/
---
**Inheritance:**
java.lang.Object
```
public class TiffRational
```

tiff 有理数类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffRational()](#TiffRational--) | 初始化 `TiffRational` 类的新实例。 |
| [TiffRational(long value)](#TiffRational-long-) | 初始化 `TiffRational` 类的新实例。 |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | 初始化 `TiffRational` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EPSILON](#EPSILON) | 用于分数计算的 epsilon |
## 方法

| 方法 | 描述 |
| --- | --- |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | 将提供的值近似为分数。 |
| [approximateFraction(double value)](#approximateFraction-double-) | 将提供的值近似为分数。 |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | 将提供的值近似为分数。 |
| [approximateFraction(float value)](#approximateFraction-float-) | 将提供的值近似为分数。 |
| [getDenominator()](#getDenominator--) | 获取分母。 |
| [getNominator()](#getNominator--) | 获取分子。 |
| [getValue()](#getValue--) | 获取 float 值。 |
| [getValueD()](#getValueD--) | 获取 double 值。 |
| [toString()](#toString--) | 转换为字符串。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


初始化 `TiffRational` 类的新实例。

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


初始化 `TiffRational` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | long | 分子值。 |

分子将用作指定的值，且分母将等于 1。 |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


初始化 `TiffRational` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 分子 | long | 分子。 |
| 分母 | long | 分母。 |

### EPSILON {#EPSILON}
```
public static final double EPSILON
```


用于分数计算的 epsilon

### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


将提供的值近似为分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 值。 |
| epsilon | double | 允许的误差。 |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


将提供的值近似为分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 值。 |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


将提供的值近似为分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 值。 |
| epsilon | double | 允许的误差。 |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `epsilon`.
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


将提供的值近似为分数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 值。 |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - A rational number having error less than `Epsilon`.
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


获取分母。

值：分母。

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


获取分子。

值：分子。

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


获取 float 值。

值：float 值。

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


获取 double 值。

值：双精度值。

**Returns:**
double
### toString() {#toString--}
```
public String toString()
```


转换为字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 `Object`。 |

**Returns:**
布尔值 - 如果指定的 `Object` 等于此实例则为 `true`；否则为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
