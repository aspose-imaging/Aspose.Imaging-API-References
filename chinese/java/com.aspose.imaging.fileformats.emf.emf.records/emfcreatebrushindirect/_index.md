---
title: "EmfCreateBrushIndirect"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_CREATEBRUSHINDIRECT 记录定义了用于图形操作的逻辑画笔。"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

该 EMR\_CREATEBRUSHINDIRECT 记录定义用于图形操作的逻辑画刷。

此记录定义的逻辑画笔对象可以通过 EMR\_SELECTOBJECT 记录（第 2.3.8.5 节）选择到回放设备上下文中，该记录指定在后续图形操作中使用的逻辑画笔。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCreateBrushIndirect` 类的新实例。 |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | 初始化 `EmfCreateBrushIndirect` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | 获取或设置一个 32 位无符号整数，指定逻辑画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [setIhBrush(int value)](#setIhBrush-int-) | 获取或设置一个 32 位无符号整数，指定逻辑画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。 |
| [getLogBrush()](#getLogBrush--) | 获取或设置一个 LogBrushEx 对象（第 2.2.12 节），该对象指定逻辑画笔的样式、颜色和图案。 |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | 获取或设置一个 LogBrushEx 对象（第 2.2.12 节），该对象指定逻辑画笔的样式、颜色和图案。 |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


初始化 `EmfCreateBrushIndirect` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


初始化 `EmfCreateBrushIndirect` 类的新实例。

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


获取或设置一个 32 位无符号整数，指定逻辑画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便可以重新使用或修改该对象。

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


获取或设置一个 32 位无符号整数，指定逻辑画笔对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便可以重新使用或修改该对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


获取或设置一个 LogBrushEx 对象（第 2.2.12 节），该对象指定逻辑画笔的样式、颜色和图案。此对象中的 BrushStyle 字段必须为 BS\_SOLID、BS\_HATCHED 或 BS\_NULL。

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


获取或设置一个 LogBrushEx 对象（第 2.2.12 节），该对象指定逻辑画笔的样式、颜色和图案。此对象中的 BrushStyle 字段必须为 BS\_SOLID、BS\_HATCHED 或 BS\_NULL。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

