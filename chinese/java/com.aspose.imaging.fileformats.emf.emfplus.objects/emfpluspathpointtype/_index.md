---
title: "EmfPlusPathPointType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusPathPointType 对象指定与图形上点关联的类型值。"
type: docs
weight: 61
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointType extends EmfPlusBasePointType
```

EmfPlusPathPointType 对象指定与图形上点关联的类型值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPathPointType()](#EmfPlusPathPointType--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getData()](#getData--) | 获取或设置数据。 |
| [setData(int value)](#setData-int-) | 获取或设置数据。 |
| [getType()](#getType--) | 获取或设置 4 位无符号整数路径点类型。 |
| [setType(int value)](#setType-int-) | 获取或设置 4 位无符号整数路径点类型。 |
| [getFlags()](#getFlags--) | 获取或设置 4 位标志字段，指定路径点的属性。 |
| [setFlags(int value)](#setFlags-int-) | 获取或设置 4 位标志字段，指定路径点的属性。 |
### EmfPlusPathPointType() {#EmfPlusPathPointType--}
```
public EmfPlusPathPointType()
```


### getData() {#getData--}
```
public int getData()
```


获取或设置数据。

值：数据。

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


获取或设置数据。

值：数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public int getType()
```


获取或设置 4 位无符号整数路径点类型。此值必须在 PathPointType 枚举中定义（第 2.1.1.23 节）。

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取或设置 4 位无符号整数路径点类型。此值必须在 PathPointType 枚举中定义（第 2.1.1.23 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


获取或设置 4 位标志字段，指定路径点的属性。此值必须是一个或多个 PathPointType 标志（第 2.1.2.6 节）。

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


获取或设置 4 位标志字段，指定路径点的属性。此值必须是一个或多个 PathPointType 标志（第 2.1.2.6 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

