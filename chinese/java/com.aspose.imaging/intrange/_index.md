---
title: "IntRange"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于表示元素序列的类"
type: docs
weight: 64
url: /zh/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

用于表示元素序列的类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | 初始化 `IntRange` 类的新实例。 |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | 初始化 `IntRange` 类的新实例。 |
| [IntRange(int[] range)](#IntRange-int---) | 初始化 `IntRange` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRange()](#getRange--) | 获取范围。 |
| [setRange(int[] value)](#setRange-int---) | 设置范围。 |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | 返回指定索引处的单项数组 |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | 获取从 start 开始的 int 元素计数范围 |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


初始化 `IntRange` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


初始化 `IntRange` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |
| 增量 | int | 增量。 |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


初始化 `IntRange` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | int[] | 范围。 |

### getRange() {#getRange--}
```
public int[] getRange()
```


获取范围。

**Returns:**
int[] - 范围。
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


设置范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 范围。 |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


返回指定索引处的单项数组

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 范围索引。 |

**Returns:**
int[] - `System.Int32` 的数组
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


获取从 start 开始的 int 元素计数范围

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |
| 增量 | int | 增量。 |

**Returns:**
int[] - 项目数组
