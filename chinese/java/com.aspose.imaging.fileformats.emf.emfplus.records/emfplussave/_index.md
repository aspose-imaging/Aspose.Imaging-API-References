---
title: "EmfPlusSave"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusSave 记录将图形状态保存到已保存图形状态堆栈中，由指定的索引标识。"
type: docs
weight: 51
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

EmfPlusSave 记录将由指定索引标识的图形状态保存在已保存的图形状态栈上。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSave` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | 获取或设置一个 32 位无符号整数，指定要与图形状态关联的级别。 |
| [setStackIndex(int value)](#setStackIndex-int-) | 获取或设置一个 32 位无符号整数，指定要与图形状态关联的级别。 |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


初始化 `EmfPlusSave` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


获取或设置一个 32 位无符号整数，指定要与图形状态关联的级别。该级别值可被后续的 EmfPlusRestore 记录（第 2.3.7.4 节）操作用于检索图形状态。

值：堆栈的索引。

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


获取或设置一个 32 位无符号整数，指定要与图形状态关联的级别。该级别值可被后续的 EmfPlusRestore 记录（第 2.3.7.4 节）操作用于检索图形状态。

值：堆栈的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

