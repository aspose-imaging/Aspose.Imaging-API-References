---
title: "EmfExcludeClipRect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_EXCLUDECLIPRECT 记录指定一个新的剪裁区域，该区域由现有剪裁区域减去指定的矩形组成。"
type: docs
weight: 50
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

EMR\_EXCLUDECLIPRECT 记录指定一个新的剪裁区域，该区域由现有剪裁区域减去指定的矩形组成。注意，本节未描述的字段在第 2.3.2 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfExcludeClipRect` 类的新实例。 |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | 初始化 `EmfExcludeClipRect` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getClip()](#getClip--) | 获取一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定剪裁矩形。 |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | 设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定剪裁矩形。 |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


初始化 `EmfExcludeClipRect` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


初始化 `EmfExcludeClipRect` 类的新实例。

### getClip() {#getClip--}
```
public Rectangle getClip()
```


获取一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定剪裁矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定剪裁矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

