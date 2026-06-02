---
title: "EmfSetPixelV"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETPIXELV 记录定义了在指定逻辑坐标处像素的颜色。"
type: docs
weight: 135
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

EMR\_SETPIXELV 记录定义指定逻辑坐标处像素的颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetPixelV` 类的新实例。 |
| [EmfSetPixelV()](#EmfSetPixelV--) | 初始化 [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPixel()](#getPixel--) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定像素的逻辑坐标。 |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定像素的逻辑坐标。 |
| [getArgb32Color()](#getArgb32Color--) | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定像素颜色。 |
| [setArgb32Color(int value)](#setArgb32Color-int-) | 获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定像素颜色。 |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


初始化 `EmfSetPixelV` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


初始化 [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv) 类的新实例。

### getPixel() {#getPixel--}
```
public Point getPixel()
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定像素的逻辑坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定像素的逻辑坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定像素颜色。

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


获取或设置一个 32 位 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定像素颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

