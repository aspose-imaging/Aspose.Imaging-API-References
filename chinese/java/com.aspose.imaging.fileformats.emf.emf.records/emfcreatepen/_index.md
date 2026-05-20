---
title: "EmfCreatePen"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_CREATEPEN 记录定义了用于图形操作的逻辑笔。"
type: docs
weight: 41
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

该 EMR\_CREATEPEN 记录定义用于图形操作的逻辑钢笔。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreatePen` 类的新实例。 |
| [EmfCreatePen()](#EmfCreatePen--) | 初始化 `EmfCreatePen` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPen()](#getIhPen--) | 获取或设置一个 32 位无符号整数，指定逻辑笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [setIhPen(int value)](#setIhPen-int-) | 获取或设置一个 32 位无符号整数，指定逻辑笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [getLogPen()](#getLogPen--) | 获取或设置一个 LogPen 对象（第 2.2.19 节），该对象指定逻辑笔的样式、宽度和颜色。 |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | 获取或设置一个 LogPen 对象（第 2.2.19 节），该对象指定逻辑笔的样式、宽度和颜色。 |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


初始化 `EmfCreatePen` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


初始化 `EmfCreatePen` 类的新实例。

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


获取或设置一个 32 位无符号整数，指定逻辑笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便可以重新使用或修改该对象。

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


获取或设置一个 32 位无符号整数，指定逻辑笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便可以重新使用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


获取或设置一个 LogPen 对象（第 2.2.19 节），该对象指定逻辑笔的样式、宽度和颜色。

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


获取或设置一个 LogPen 对象（第 2.2.19 节），该对象指定逻辑笔的样式、宽度和颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

