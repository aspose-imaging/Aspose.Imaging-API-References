---
title: "EmfPie"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_PIE 记录指定由椭圆与两条径线的交点限定的扇形楔形。"
type: docs
weight: 82
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPie extends EmfDrawingRecordType
```

EMR\_PIE 记录指定由椭圆与两条径线的交点限定的扇形楔形。该扇形使用当前笔描边，并使用当前画刷填充。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPie(EmfRecord source)](#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfPie` 类的新实例。 |
| [EmfPie()](#EmfPie--) | 初始化 `EmfPie` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBox()](#getBox--) | 获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定闭区间的边界矩形。 |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | 获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定闭区间的边界矩形。 |
| [getStart()](#getStart--) | 获取或设置 64 位 WMF PointL 对象，定义于 [MS-WMF] section 2.2.2.15，指定第一条径线终点的逻辑单位坐标。 |
| [setStart(Point value)](#setStart-com.aspose.imaging.Point-) | 获取或设置 64 位 WMF PointL 对象，定义于 [MS-WMF] section 2.2.2.15，指定第一条径线终点的逻辑单位坐标。 |
| [getEnd()](#getEnd--) | 获取或设置 64 位 PointL 对象，指定第二条径线终点的逻辑单位坐标。 |
| [setEnd(Point value)](#setEnd-com.aspose.imaging.Point-) | 获取或设置 64 位 PointL 对象，指定第二条径线终点的逻辑单位坐标。 |
### EmfPie(EmfRecord source) {#EmfPie-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPie(EmfRecord source)
```


初始化 `EmfPie` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfPie() {#EmfPie--}
```
public EmfPie()
```


初始化 `EmfPie` 类的新实例。

### getBox() {#getBox--}
```
public Rectangle getBox()
```


获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定闭区间的边界矩形。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


获取或设置 128 位 WMF RectL 对象（在 [MS-WMF] 第 2.2.2.19 节中指定），该对象指定闭区间的边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStart() {#getStart--}
```
public Point getStart()
```


获取或设置 64 位 WMF PointL 对象，定义于 [MS-WMF] section 2.2.2.15，指定第一条径线终点的逻辑单位坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setStart(Point value) {#setStart-com.aspose.imaging.Point-}
```
public void setStart(Point value)
```


获取或设置 64 位 WMF PointL 对象，定义于 [MS-WMF] section 2.2.2.15，指定第一条径线终点的逻辑单位坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getEnd() {#getEnd--}
```
public Point getEnd()
```


获取或设置 64 位 PointL 对象，指定第二条径线终点的逻辑单位坐标。

**Returns:**
[Point](../../com.aspose.imaging/point)
### setEnd(Point value) {#setEnd-com.aspose.imaging.Point-}
```
public void setEnd(Point value)
```


获取或设置 64 位 PointL 对象，指定第二条径线终点的逻辑单位坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

