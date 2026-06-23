---
title: "EmfSetViewportExtEx"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETVIEWPORTEXTEX 记录定义了视口范围。"
type: docs
weight: 142
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetViewportExtEx extends EmfStateRecordType
```

该 EMR\_SETVIEWPORTEXTEX 记录定义视口范围。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetViewportExtEx(EmfRecord source)](#EmfSetViewportExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetViewportExtEx` 类的新实例。 |
| [EmfSetViewportExtEx()](#EmfSetViewportExtEx--) | 初始化 `EmfSetViewportExtEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExtent()](#getExtent--) | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定设备单位中的水平和垂直范围。 |
| [setExtent(Size value)](#setExtent-com.aspose.imaging.Size-) | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定设备单位中的水平和垂直范围。 |
### EmfSetViewportExtEx(EmfRecord source) {#EmfSetViewportExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetViewportExtEx(EmfRecord source)
```


初始化 `EmfSetViewportExtEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetViewportExtEx() {#EmfSetViewportExtEx--}
```
public EmfSetViewportExtEx()
```


初始化 `EmfSetViewportExtEx` 类的新实例。

### getExtent() {#getExtent--}
```
public Size getExtent()
```


获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定设备单位中的水平和垂直范围。

**Returns:**
[Size](../../com.aspose.imaging/size)
### setExtent(Size value) {#setExtent-com.aspose.imaging.Size-}
```
public void setExtent(Size value)
```


获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定设备单位中的水平和垂直范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

