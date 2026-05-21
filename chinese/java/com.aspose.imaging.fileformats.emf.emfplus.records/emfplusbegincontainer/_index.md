---
title: "EmfPlusBeginContainer"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定变换。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

EmfPlusBeginContainer 记录打开一个新的图形状态容器并为其指定变换。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusBeginContainer` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | 获取页面单位。 |
| [getDestRect()](#getDestRect--) | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定容器的变换。 |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定容器的变换。 |
| [getSrcRect()](#getSrcRect--) | 获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起指定容器的变换。 |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | 获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起指定容器的变换。 |
| [getStackIndex()](#getStackIndex--) | 获取或设置一个 32 位无符号整数，该整数指定与图形状态容器关联的索引。 |
| [setStackIndex(int value)](#setStackIndex-int-) | 获取或设置一个 32 位无符号整数，该整数指定与图形状态容器关联的索引。 |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


初始化 `EmfPlusBeginContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


获取页面单位。

值：页面单位。

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定容器的变换。当该变换应用于 DestRect 时，会得到 SrcRect。

值：目标矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象与 SrcRect 一起指定容器的变换。当该变换应用于 DestRect 时，会得到 SrcRect。

值：目标矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起指定容器的变换。当该变换应用于 DestRect 时，会得到 SrcRect。

值：源矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


获取或设置一个 EmfPlusRectF 矩形，该矩形与 DestRect 一起指定容器的变换。当该变换应用于 DestRect 时，会得到 SrcRect。

值：源矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


获取或设置一个 32 位无符号整数，该整数指定与图形状态容器关联的索引。该索引必须在后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。

值：堆栈的索引。

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


获取或设置一个 32 位无符号整数，该整数指定与图形状态容器关联的索引。该索引必须在后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。

值：堆栈的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

