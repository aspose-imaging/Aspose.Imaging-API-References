---
title: "EmfOffsetClipRgn"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_OFFSETCLIPRGN 记录通过指定的偏移量移动回放设备上下文中的当前裁剪区域。"
type: docs
weight: 78
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfOffsetClipRgn extends EmfClippingRecordType
```

EMR\_OFFSETCLIPRGN 记录通过指定的偏移量移动回放设备上下文中的当前剪裁区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfOffsetClipRgn(EmfRecord source)](#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfOffsetClipRgn` 类的新实例。 |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn--) | 初始化 `EmfOffsetClipRgn` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOffset()](#getOffset--) | 获取一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定逻辑单位中的水平和垂直偏移量。 |
| [setOffset(Point value)](#setOffset-com.aspose.imaging.Point-) | 设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定逻辑单位中的水平和垂直偏移量。 |
### EmfOffsetClipRgn(EmfRecord source) {#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfOffsetClipRgn(EmfRecord source)
```


初始化 `EmfOffsetClipRgn` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn--}
```
public EmfOffsetClipRgn()
```


初始化 `EmfOffsetClipRgn` 类的新实例。

### getOffset() {#getOffset--}
```
public Point getOffset()
```


获取一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定逻辑单位中的水平和垂直偏移量。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOffset(Point value) {#setOffset-com.aspose.imaging.Point-}
```
public void setOffset(Point value)
```


设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定逻辑单位中的水平和垂直偏移量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

