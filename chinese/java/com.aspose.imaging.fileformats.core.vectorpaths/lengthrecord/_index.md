---
title: "LengthRecord"
second_title: "Aspose.Imaging for Java API 参考"
description: "子路径长度记录类"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object，[com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

子路径长度记录类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | 初始化 [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) 类的新实例。 |
| [LengthRecord()](#LengthRecord--) | 初始化 [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isClosed()](#isClosed--) | 获取指示此实例是否已关闭的值。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 设置指示此实例是否已关闭的值。 |
| [isOpen()](#isOpen--) | 获取指示此实例是否已打开的值。 |
| [setOpen(boolean value)](#setOpen-boolean-) | 设置指示此实例是否已打开的值。 |
| [getRecordCount()](#getRecordCount--) | 获取记录计数。 |
| [setRecordCount(int value)](#setRecordCount-int-) | 设置记录计数。 |
| [getType()](#getType--) | 获取类型。 |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | 获取贝塞尔结点记录计数。 |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | 设置贝塞尔结点记录计数。 |
| [getPathOperations()](#getPathOperations--) | 获取路径操作。 |
| [setPathOperations(int value)](#setPathOperations-int-) | 设置路径操作。 |
| [getShapeIndex()](#getShapeIndex--) | 获取当前层中路径形状的索引。 |
| [setShapeIndex(int value)](#setShapeIndex-int-) | 设置当前层中路径形状的索引。 |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


初始化 [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 记录数据。 |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


初始化 [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) 类的新实例。

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


获取指示此实例是否已关闭的值。

值：`true` 如果此实例已关闭；否则为 `false`。

**Returns:**
boolean - 指示此实例是否已关闭的值。
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


设置指示此实例是否已关闭的值。

值：`true` 如果此实例已关闭；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示此实例是否已关闭的值。 |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


获取指示此实例是否已打开的值。

值：如果此实例已打开，则为 `true`；否则为 `false`。

**Returns:**
boolean - 表示此实例是否打开的值。
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


设置指示此实例是否已打开的值。

值：如果此实例已打开，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 表示此实例是否打开的值。 |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


获取记录计数。

值：记录计数。

**Returns:**
int - 记录计数。
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


设置记录计数。

值：记录计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 记录计数。 |

### getType() {#getType--}
```
public short getType()
```


获取类型。

值：类型。

**Returns:**
short - 类型。
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


获取贝塞尔结点记录计数。

**Returns:**
int - 贝塞尔结点记录计数。
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


设置贝塞尔结点记录计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 贝塞尔结点记录计数。 |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


获取路径操作。

**Returns:**
int - 路径操作。
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


设置路径操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 路径操作。 |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


获取当前层中路径形状的索引。

**Returns:**
int - 当前层中路径形状的索引。
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


设置当前层中路径形状的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 当前层中路径形状的索引。 |

