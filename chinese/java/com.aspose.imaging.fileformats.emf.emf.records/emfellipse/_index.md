---
title: "EmfEllipse"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_ELLIPSE 记录指定一个椭圆。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfEllipse extends EmfDrawingRecordType
```

EMR\_ELLIPSE 记录指定一个椭圆。椭圆的中心是指定的边界矩形的中心。椭圆使用当前画笔描边，并使用当前画刷填充。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfEllipse(EmfRecord source)](#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfEllipse` 类的新实例。 |
| [EmfEllipse()](#EmfEllipse--) | 初始化 `EmfEllipse` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置一个 128 位（WMF）RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于指定包含边界的包围矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位（WMF）RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于指定包含边界的包围矩形。 |
### EmfEllipse(EmfRecord source) {#EmfEllipse-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEllipse(EmfRecord source)
```


初始化 `EmfEllipse` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfEllipse() {#EmfEllipse--}
```
public EmfEllipse()
```


初始化 `EmfEllipse` 类的新实例。

### getBox() {#getBox--}
```
public Rectangle getBox()
```


获取或设置一个 128 位（WMF）RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于指定包含边界的包围矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


获取或设置一个 128 位（WMF）RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于指定包含边界的包围矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

