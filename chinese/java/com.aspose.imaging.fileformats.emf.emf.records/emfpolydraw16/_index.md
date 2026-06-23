---
title: "EmfPolyDraw16"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_POLYDRAW16 记录指定一组线段和贝塞尔曲线。"
type: docs
weight: 90
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

EMR\_POLYDRAW16 记录指定一组线段和贝塞尔曲线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPolyDraw16` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | 获取或设置一个长度为 Count 的字节数组，用于指定点类型。 |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | 设置一个长度为 Count 的字节数组，用于指定点类型。 |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


初始化 `EmfPolyDraw16` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


获取或设置一个长度为 Count 的字节数组，用于指定点类型。此值必须属于 Point（第 2.1.26 节）枚举。

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


设置一个长度为 Count 的字节数组，用于指定点类型。此值必须属于 Point（第 2.1.26 节）枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] | 一个长度为 Count 的字节数组，用于指定点类型。 |

