---
title: "EmfPlusBeginContainerNoParams"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusBeginContainerNoParams 记录打开一个新的图形状态容器。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

EmfPlusBeginContainerNoParams 记录打开一个新的图形状态容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusBeginContainerNoParams` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | 获取或设置一个 32 位无符号整数，指定与图形状态容器关联的索引。 |
| [setStackIndex(int value)](#setStackIndex-int-) | 获取或设置一个 32 位无符号整数，指定与图形状态容器关联的索引。 |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


初始化 `EmfPlusBeginContainerNoParams` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


获取或设置一个 32 位无符号整数，指定与图形状态容器关联的索引。该索引必须在后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。

值：堆栈的索引。

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


获取或设置一个 32 位无符号整数，指定与图形状态容器关联的索引。该索引必须在后续的 EmfPlusEndContainer 记录（第 2.3.7.3 节）中被引用，以关闭图形状态容器。

值：堆栈的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

