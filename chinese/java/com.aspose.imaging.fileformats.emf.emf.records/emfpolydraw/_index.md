---
title: "EmfPolyDraw"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_POLYDRAW 记录指定一组线段和贝塞尔曲线。"
type: docs
weight: 89
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

EMR\_POLYDRAW 记录指定一组线段和贝塞尔曲线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPolyDraw` 类的新实例。 |
| [EmfPolyDraw()](#EmfPolyDraw--) | 初始化 [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | 获取一个长度为 Count 的字节值数组，指定如何使用 Gets or sets aPoints 数组中的每个点。 |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | 设置一个长度为 Count 的字节值数组，指定如何使用 Gets or sets aPoints 数组中的每个点。 |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


初始化 `EmfPolyDraw` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


初始化 [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw) 类的新实例。

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


获取一个长度为 Count 的字节值数组，用于指定在获取或设置 aPoints 数组时每个点的使用方式。此值必须属于 Point（第 2.1.26 节）枚举。

**Returns:**
byte[] - 一个长度为 Count 的字节值数组，用于指定在获取或设置 aPoints 数组时每个点的使用方式。
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


设置一个长度为 Count 的字节值数组，用于指定在获取或设置 aPoints 数组时每个点的使用方式。此值必须属于 Point（第 2.1.26 节）枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] | 一个长度为 Count 的字节值数组，用于指定在获取或设置 aPoints 数组时每个点的使用方式。 |

