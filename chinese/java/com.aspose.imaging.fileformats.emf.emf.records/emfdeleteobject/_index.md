---
title: "EmfDeleteObject"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EMR_DELETEOBJECT 记录删除一个图形对象，该对象由其在 EMF Object Table 中的索引指定，参见第 3.1.1.1 节。"
type: docs
weight: 43
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

该 EMR\_DELETEOBJECT 记录删除图形对象，该对象通过其在 EMF 对象表（第 3.1.1.1 节）中的索引指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfDeleteObject` 类的新实例。 |
| [EmfDeleteObject()](#EmfDeleteObject--) | 初始化 `EmfDeleteObject` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | 获取或设置 32 位无符号整数，该整数指定 EMF Object Table 中图形对象的索引或 StockObject 枚举中库存对象的索引。 |
| [setObjectHandle(int value)](#setObjectHandle-int-) | 获取或设置 32 位无符号整数，该整数指定 EMF Object Table 中图形对象的索引或 StockObject 枚举中库存对象的索引。 |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


初始化 `EmfDeleteObject` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 记录。 |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


初始化 `EmfDeleteObject` 类的新实例。

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


获取或设置 32 位无符号整数，该整数指定 EMF Object Table 中图形对象的索引或 StockObject 枚举中库存对象的索引。

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


获取或设置 32 位无符号整数，该整数指定 EMF Object Table 中图形对象的索引或 StockObject 枚举中库存对象的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

