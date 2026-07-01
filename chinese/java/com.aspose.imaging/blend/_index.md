---
title: "混合"
second_title: "Aspose.Imaging for Java API 参考"
description: "定义混合模式。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

定义混合模式。此类不可被继承。

典型的 blend 类用法是为 brush 定义一个 blend 模式。因此应仔细初始化 blend 属性。不允许空数组。如果 blend 因子或 positions 数组为空或长度不一致，brush 将抛出相应的异常。如果 positions 数组中有两个或更多元素，则第一个元素应为 0，最后一个应为 1。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Blend()](#Blend--) | 初始化 `Blend` 类的新实例。 |
| [Blend(int count)](#Blend-int-) | 使用指定数量的因子和位置初始化 `Blend` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFactors()](#getFactors--) | 获取渐变的 blend 因子数组。 |
| [setFactors(float[] value)](#setFactors-float---) | 设置渐变的 blend 因子数组。 |
| [getPositions()](#getPositions--) | 获取渐变的 blend 位置数组。 |
| [setPositions(float[] value)](#setPositions-float---) | 设置渐变的混合位置数组。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为 `com.aspose.imaging.Blend` 类且等价于此 `com.aspose.imaging.Blend` 类。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### Blend() {#Blend--}
```
public Blend()
```


初始化 `Blend` 类的新实例。因子数组和混合数组的元素数量将等于 1。

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


使用指定数量的因子和位置初始化 `Blend` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 计数 | int | 因子数组和位置数组中的元素数量。 |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


获取渐变的 blend 因子数组。

**Returns:**
float[] - 指定在相应位置使用的起始颜色和结束颜色百分比的混合因子数组。
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


设置渐变的 blend 因子数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] | 指定在相应位置使用的起始颜色和结束颜色百分比的混合因子数组。 |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


获取渐变的 blend 位置数组。

**Returns:**
float[] - 指定沿渐变线距离百分比的混合位置数组。
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


设置渐变的混合位置数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] | 指定沿渐变线距离百分比的混合位置数组。 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为 `com.aspose.imaging.Blend` 类且等价于此 `com.aspose.imaging.Blend` 类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 `obj` 是等价于此 `com.aspose.imaging.Blend` 类的 `com.aspose.imaging.Blend` 类，则为 True；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
