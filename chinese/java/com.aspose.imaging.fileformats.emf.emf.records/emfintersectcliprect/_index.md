---
title: "EmfIntersectClipRect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_INTERSECTCLIPRECT 记录指定一个新的剪裁区域，该区域由当前剪裁区域与指定矩形的交集构成。"
type: docs
weight: 66
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

EMR\_INTERSECTCLIPRECT 记录指定一个新的剪裁区域，该区域由当前剪裁区域与指定矩形的交集构成。注意，本节未描述的字段在第 2.3.2 节中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfIntersectClipRect` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getClip()](#getClip--) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定矩形。 |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定矩形。 |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


初始化 `EmfIntersectClipRect` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），该对象以逻辑单位指定矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

