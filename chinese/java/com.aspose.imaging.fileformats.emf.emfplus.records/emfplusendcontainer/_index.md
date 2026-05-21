---
title: "EmfPlusEndContainer"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusEndContainer 记录关闭先前由开始容器操作打开的图形状态容器。"
type: docs
weight: 30
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

EmfPlusEndContainer 记录关闭先前由开始容器操作打开的图形状态容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusEndContainer` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | 获取或设置一个 32 位无符号整数，指定图形状态容器的索引。 |
| [setStackIndex(int value)](#setStackIndex-int-) | 获取或设置一个 32 位无符号整数，指定图形状态容器的索引。 |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


初始化 `EmfPlusEndContainer` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


获取或设置一个 32 位无符号整数，指定图形状态容器的索引。该索引 MUST 必须匹配先前的 EmfPlusBeginContainer（第 2.3.7.1 节）或 EmfPlusBeginContainerNoParams 记录（第 2.3.7.2 节）打开的图形状态容器所关联的值。

值：堆栈的索引。

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


获取或设置一个 32 位无符号整数，指定图形状态容器的索引。该索引 MUST 必须匹配先前的 EmfPlusBeginContainer（第 2.3.7.1 节）或 EmfPlusBeginContainerNoParams 记录（第 2.3.7.2 节）打开的图形状态容器所关联的值。

值：堆栈的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

