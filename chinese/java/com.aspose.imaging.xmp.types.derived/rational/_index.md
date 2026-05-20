---
title: "Rational"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP Rational。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.derived/rational/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public class Rational extends XmpTypeBase
```

表示 XMP Rational。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rational(int numerator, int denominator)](#Rational-int-int-) | 初始化 `Rational` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumerator()](#getNumerator--) | 获取分子。 |
| [getDenominator()](#getDenominator--) | 获取或设置分母。 |
| [setDenominator(int value)](#setDenominator-int-) | 获取或设置分母。 |
| [getFloatValue()](#getFloatValue--) | 获取 float 值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式中包含的字符串值。 |
### Rational(int numerator, int denominator) {#Rational-int-int-}
```
public Rational(int numerator, int denominator)
```


初始化 `Rational` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 分子 | int | 分子。 |
| 分母 | int | 分母。 |

### getNumerator() {#getNumerator--}
```
public int getNumerator()
```


获取分子。

值：分子。

**Returns:**
int
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


获取或设置分母。

**Returns:**
int - 分母。
### setDenominator(int value) {#setDenominator-int-}
```
public void setDenominator(int value)
```


获取或设置分母。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 分母。 |

### getFloatValue() {#getFloatValue--}
```
public float getFloatValue()
```


获取 float 值。

**Returns:**
float - 浮点值。
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
