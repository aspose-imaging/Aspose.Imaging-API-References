---
title: "EmfSetWindowExtEx"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETWINDOWEXTEX 记录定义了窗口范围。"
type: docs
weight: 144
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetWindowExtEx extends EmfStateRecordType
```

该 EMR\_SETWINDOWEXTEX 记录定义窗口范围。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetWindowExtEx(EmfRecord source)](#EmfSetWindowExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetWindowExtEx` 类的新实例。 |
| [EmfSetWindowExtEx()](#EmfSetWindowExtEx--) | 初始化 `EmfSetWindowExtEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExtent()](#getExtent--) | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定逻辑单位中的水平和垂直范围。 |
| [setExtent(Size value)](#setExtent-com.aspose.imaging.Size-) | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定逻辑单位中的水平和垂直范围。 |
### EmfSetWindowExtEx(EmfRecord source) {#EmfSetWindowExtEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetWindowExtEx(EmfRecord source)
```


初始化 `EmfSetWindowExtEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetWindowExtEx() {#EmfSetWindowExtEx--}
```
public EmfSetWindowExtEx()
```


初始化 `EmfSetWindowExtEx` 类的新实例。

### getExtent() {#getExtent--}
```
public Size getExtent()
```


获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定逻辑单位中的水平和垂直范围。

**Returns:**
[Size](../../com.aspose.imaging/size)
### setExtent(Size value) {#setExtent-com.aspose.imaging.Size-}
```
public void setExtent(Size value)
```


获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定逻辑单位中的水平和垂直范围。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

