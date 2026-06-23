---
title: "ColorBlend"
second_title: "Aspose.Imaging for Java API 参考"
description: "定义用于在多色渐变中插值颜色混合的颜色和位置数组。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging/colorblend/
---
**Inheritance:**
java.lang.Object
```
public final class ColorBlend
```

定义用于在多色渐变中插值颜色混合的颜色和位置数组。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorBlend()](#ColorBlend--) | 初始化 `com.aspose.imaging.ColorBlend` 类的新实例。 |
| [ColorBlend(int count)](#ColorBlend-int-) | 使用指定的颜色数量和位置初始化 `com.aspose.imaging.ColorBlend` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColors()](#getColors--) | 获取或设置表示在渐变对应位置使用的颜色的颜色数组。 |
| [setColors(Color[] value)](#setColors-com.aspose.imaging.Color---) |  |
| [getPositions()](#getPositions--) | 获取或设置沿渐变线的位置。 |
| [setPositions(float[] value)](#setPositions-float---) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 测试指定的对象是否为 `com.aspose.imaging.ColorBlend` 类且等价于此 `com.aspose.imaging.ColorBlend` 类。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### ColorBlend() {#ColorBlend--}
```
public ColorBlend()
```


初始化 `com.aspose.imaging.ColorBlend` 类的新实例。

### ColorBlend(int count) {#ColorBlend-int-}
```
public ColorBlend(int count)
```


使用指定的颜色数量和位置初始化 `com.aspose.imaging.ColorBlend` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 计数 | int | 此 `com.aspose.imaging.ColorBlend` 中的颜色和位置数量。 |

### getColors() {#getColors--}
```
public Color[] getColors()
```


获取或设置表示在渐变对应位置使用的颜色的颜色数组。

**Returns:**
com.aspose.imaging.Color[] - 表示在渐变对应位置使用的颜色的 `com.aspose.imaging.Color` 结构数组。
### setColors(Color[] value) {#setColors-com.aspose.imaging.Color---}
```
public void setColors(Color[] value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) |  |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


获取或设置沿渐变线的位置。

**Returns:**
float[] - 指定沿渐变线距离百分比的值数组。
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float[] |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


测试指定的对象是否为 `com.aspose.imaging.ColorBlend` 类且等价于此 `com.aspose.imaging.ColorBlend` 类。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 `obj` 是等价于此 `com.aspose.imaging.ColorBlend` 类的 `com.aspose.imaging.ColorBlend` 类，则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
