---
title: "EmfPlusRestore"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusRestore 记录从已保存图形状态的堆栈中恢复由指定索引标识的图形状态。"
type: docs
weight: 49
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

EmfPlusRestore 记录从已保存的图形状态栈中恢复由指定索引标识的图形状态。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusRestore` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | 获取或设置一个 32 位无符号整数，指定与图形状态关联的级别。 |
| [setStackIndex(int value)](#setStackIndex-int-) | 获取或设置一个 32 位无符号整数，指定与图形状态关联的级别。 |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


初始化 `EmfPlusRestore` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


获取或设置一个 32 位无符号整数，指定与图形状态关联的级别。该级别值由先前的 EmfPlusSave 记录（第 2.3.7.5 节）分配给图形状态。

值：堆栈的索引。

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


获取或设置一个 32 位无符号整数，指定与图形状态关联的级别。该级别值由先前的 EmfPlusSave 记录（第 2.3.7.5 节）分配给图形状态。

值：堆栈的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

