---
title: "EmfCommentMultiFormats"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_COMMENT_MULTIFORMATS 记录指定以多种图形格式表示的图像。"
type: docs
weight: 30
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

该 EMR\_COMMENT\_MULTIFORMATS 记录指定以多种图形格式呈现的图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfCommentMultiFormats` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑坐标指定输出矩形。 |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑坐标指定输出矩形。 |
| [getAFormats()](#getAFormats--) | 获取或设置一个长度为 CountFormats 的图形格式数组，由 EmrFormat 对象（第 2.2.4 节）指定，按优先顺序排列。 |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | 获取或设置一个长度为 CountFormats 的图形格式数组，由 EmrFormat 对象（第 2.2.4 节）指定，按优先顺序排列。 |
| [getFormatData()](#getFormatData--) | 获取或设置一个可变长度的字节数组，包含此记录中所有图形格式的图像数据。 |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | 获取或设置一个可变长度的字节数组，包含此记录中所有图形格式的图像数据。 |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


初始化 `EmfCommentMultiFormats` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑坐标指定输出矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑坐标指定输出矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


获取或设置一个长度为 CountFormats 的图形格式数组，由 EmrFormat 对象（第 2.2.4 节）指定，按优先顺序排列。

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


获取或设置一个长度为 CountFormats 的图形格式数组，由 EmrFormat 对象（第 2.2.4 节）指定，按优先顺序排列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


获取或设置一个可变长度的字节数组，包含此记录中所有图形格式的图像数据。每个图像的数据大小由相应 EmrFormat 对象中的 DataSize 字段提供。因此，此字段的总大小等于所有 EmrFormat 对象中 DataSize 值的总和。每个图像的数据的图形格式由相应 EmrFormat 对象中的 Signature 字段指定。

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


获取或设置一个可变长度的字节数组，包含此记录中所有图形格式的图像数据。每个图像的数据大小由相应 EmrFormat 对象中的 DataSize 字段提供。因此，此字段的总大小等于所有 EmrFormat 对象中 DataSize 值的总和。每个图像的数据的图形格式由相应 EmrFormat 对象中的 Signature 字段指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[][] |  |

