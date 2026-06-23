---
title: "EmfRectangle"
second_title: "Aspose.Imaging for Java API 参考"
description: "该 EMR_RECTANGLE 记录绘制一个矩形。"
type: docs
weight: 107
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

该 EMR\_RECTANGLE 记录绘制一个矩形。该矩形使用当前笔描边，并使用当前画刷填充。

Rectangle 不会使用也不会更新当前坐标。如果使用 PS\_NULL 笔，则矩形的高度和宽度各减少 1 像素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfRectangle` 类的新实例。 |
| [EmfRectangle()](#EmfRectangle--) | 初始化 `EmfRectangle` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置一个 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定要绘制的包含-包含矩形。 |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


初始化 `EmfRectangle` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


初始化 `EmfRectangle` 类的新实例。

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

