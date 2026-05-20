---
title: "EmfSetWindowOrgEx"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETWINDOWORGEX 记录定义窗口原点。"
type: docs
weight: 145
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetWindowOrgEx extends EmfStateRecordType
```

EMR\_SETWINDOWORGEX 记录定义窗口原点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetWindowOrgEx(EmfRecord source)](#EmfSetWindowOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetWindowOrgEx` 类的新实例。 |
| [EmfSetWindowOrgEx()](#EmfSetWindowOrgEx--) | 初始化 `EmfSetWindowOrgEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrigin()](#getOrigin--) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定窗口的水平和垂直原点，单位为逻辑单位。 |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定窗口的水平和垂直原点，单位为逻辑单位。 |
### EmfSetWindowOrgEx(EmfRecord source) {#EmfSetWindowOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetWindowOrgEx(EmfRecord source)
```


初始化 `EmfSetWindowOrgEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSetWindowOrgEx() {#EmfSetWindowOrgEx--}
```
public EmfSetWindowOrgEx()
```


初始化 `EmfSetWindowOrgEx` 类的新实例。

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定窗口的水平和垂直原点，单位为逻辑单位。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），指定窗口的水平和垂直原点，单位为逻辑单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

