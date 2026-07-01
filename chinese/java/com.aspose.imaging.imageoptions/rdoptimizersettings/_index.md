---
title: "RdOptimizerSettings"
second_title: "Aspose.Imaging for Java API 参考"
description: "RD 优化器设置类"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.imageoptions/rdoptimizersettings/
---
**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

RD 优化器设置类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | 初始化 `RdOptimizerSettings` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBppScale()](#getBppScale--) | 获取 BPP（每像素位数）缩放因子。 |
| [setBppScale(int value)](#setBppScale-int-) | 设置 BPP（每像素位数）缩放因子。 |
| [getBppMax()](#getBppMax--) | 获取在每像素位数中考虑的最大 R 值 |
| [setBppMax(double value)](#setBppMax-double-) | 设置在每像素位数中考虑的最大 R 值 |
| [getMaxQ()](#getMaxQ--) | 获取最大量化值。 |
| [setMaxQ(int value)](#setMaxQ-int-) | 设置最大量化值。 |
| [getMinQ()](#getMinQ--) | 获取允许的最小量化值。 |
| [getMaxPixelValue()](#getMaxPixelValue--) | 获取最大像素值。 |
| [getPsnrMax()](#getPsnrMax--) | 获取 PSNR 最大预期值。 |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | 获取用于考虑的最大 R 值。 |
| [create()](#create--) | 创建此实例。 |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


初始化 `RdOptimizerSettings` 类的新实例。

### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


获取 BPP（每像素位数）缩放因子。

**Returns:**
int - BPP 比例。
### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


设置 BPP（每像素位数）缩放因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | BPP 比例。 |

### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


获取在每像素位数中考虑的最大 R 值

**Returns:**
double - 每像素位数中用于考虑的最大 R 值。
### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


设置在每像素位数中考虑的最大 R 值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 每像素位数中用于考虑的最大 R 值。 |

### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


获取最大量化值。

**Returns:**
int - 最大量化值。
### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


设置最大量化值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 最大量化值。 |

### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


获取允许的最小量化值。

**Returns:**
int - 最小允许的量化值。
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


获取最大像素值。

**Returns:**
int - 最大像素值。
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


获取 PSNR 最大预期值。

**Returns:**
int - 最大像素值。
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


获取用于考虑的最大 R 值。

**Returns:**
int - 用于考虑的最大 R 值。
### create() {#create--}
```
public static RdOptimizerSettings create()
```


创建此实例。

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
