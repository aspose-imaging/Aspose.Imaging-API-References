---
title: "EmfRoundRect"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_ROUNDRECT 记录指定一个带圆角的矩形。"
type: docs
weight: 111
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

EMR\_ROUNDRECT 记录指定一个带圆角的矩形。该矩形使用当前笔描边并使用当前画刷填充。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfRoundRect` 类的新实例。 |
| [EmfRoundRect()](#EmfRoundRect--) | 初始化 [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。 |
| [getCorner()](#getCorner--) | 获取或设置一个 64 位 WMF SizeL 对象（在 [MS-WMF] 第 2.2.2.22 节中指定），该对象以逻辑坐标指定用于绘制圆角的椭圆的宽度和高度。 |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | 获取或设置一个 64 位 WMF SizeL 对象（在 [MS-WMF] 第 2.2.2.22 节中指定），该对象以逻辑坐标指定用于绘制圆角的椭圆的宽度和高度。 |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


初始化 `EmfRoundRect` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


初始化 [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) 类的新实例。

### getBox() {#getBox--}
```
public Rectangle getBox()
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


获取或设置一个 64 位 WMF SizeL 对象（在 [MS-WMF] 第 2.2.2.22 节中指定），该对象以逻辑坐标指定用于绘制圆角的椭圆的宽度和高度。

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


获取或设置一个 64 位 WMF SizeL 对象（在 [MS-WMF] 第 2.2.2.22 节中指定），该对象以逻辑坐标指定用于绘制圆角的椭圆的宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

