---
title: "EmfSetBrushOrgEx"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETBRUSHORGEX 记录指定当前画笔的原点。"
type: docs
weight: 121
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBrushOrgEx extends EmfStateRecordType
```

EMR\_SETBRUSHORGEX 记录指定当前画刷的原点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetBrushOrgEx(EmfRecord source)](#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetBrushOrgEx` 类的新实例。 |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx--) | 初始化 `EmfSetBrushOrgEx` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOrigin()](#getOrigin--) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定画笔在设备单位中的水平和垂直原点。 |
| [setOrigin(Point value)](#setOrigin-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定画笔在设备单位中的水平和垂直原点。 |
### EmfSetBrushOrgEx(EmfRecord source) {#EmfSetBrushOrgEx-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBrushOrgEx(EmfRecord source)
```


初始化 `EmfSetBrushOrgEx` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSetBrushOrgEx() {#EmfSetBrushOrgEx--}
```
public EmfSetBrushOrgEx()
```


初始化 `EmfSetBrushOrgEx` 类的新实例。

### getOrigin() {#getOrigin--}
```
public Point getOrigin()
```


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定画笔在设备单位中的水平和垂直原点。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOrigin(Point value) {#setOrigin-com.aspose.imaging.Point-}
```
public void setOrigin(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（在 [MS-WMF] 第 2.2.2.15 节中指定），该对象指定画笔在设备单位中的水平和垂直原点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

