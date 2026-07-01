---
title: "EmfSetViewportOrgEx"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETVIEWPORTORGEX 记录定义视口原点。"
type: docs
weight: 143
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetViewportOrgEx extends EmfStateRecordType
```

该 EMR\_SETVIEWPORTORGEX 记录定义视口原点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetViewportOrgEx(EmfRecord source)](#EmfSetViewportOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetViewportOrgEx` 类的新实例。 |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx--) | 初始化 `EmfSetViewportOrgEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrigin()](#getOrigin--) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），用于指定窗口在设备单位下的水平和垂直原点。 |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），用于指定窗口在设备单位下的水平和垂直原点。 |
### EmfSetViewportOrgEx(EmfRecord source) {#EmfSetViewportOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetViewportOrgEx(EmfRecord source)
```


初始化 `EmfSetViewportOrgEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetViewportOrgEx() {#EmfSetViewportOrgEx--}
```
public EmfSetViewportOrgEx()
```


初始化 `EmfSetViewportOrgEx` 类的新实例。

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），用于指定窗口在设备单位下的水平和垂直原点。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），用于指定窗口在设备单位下的水平和垂直原点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

