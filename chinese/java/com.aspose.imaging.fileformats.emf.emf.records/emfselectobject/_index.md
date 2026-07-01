---
title: "EmfSelectObject"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SELECTOBJECT 记录向当前元文件回放设备上下文添加一个图形对象。"
type: docs
weight: 116
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

EMR\_SELECTOBJECT 记录向当前元文件回放设备上下文添加一个图形对象。该对象可以通过其在 EMF Object Table（第 3.1.1.1 节）中的索引，或通过其在 StockObject 枚举（第 2.1.31 节）中的值来指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSelectObject` 类的新实例。 |
| [EmfSelectObject()](#EmfSelectObject--) | 初始化 `EmfSelectObject` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | 获取或设置 32 位无符号整数，用于指定 EMF Object Table 中图形对象的索引或 `Consts.EmfStockObject` 枚举中库存对象的索引。 |
| [setObjectHandle(int value)](#setObjectHandle-int-) | 获取或设置 32 位无符号整数，用于指定 EMF Object Table 中图形对象的索引或 `Consts.EmfStockObject` 枚举中库存对象的索引。 |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


初始化 `EmfSelectObject` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


初始化 `EmfSelectObject` 类的新实例。

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


获取或设置 32 位无符号整数，用于指定 EMF Object Table 中图形对象的索引或 `Consts.EmfStockObject` 枚举中库存对象的索引。

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


获取或设置 32 位无符号整数，用于指定 EMF Object Table 中图形对象的索引或 `Consts.EmfStockObject` 枚举中库存对象的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

