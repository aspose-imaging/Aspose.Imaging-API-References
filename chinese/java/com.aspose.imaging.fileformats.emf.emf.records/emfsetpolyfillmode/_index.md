---
title: "EmfSetPolyFillMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_SETPOLYFILLMODE 记录定义多边形填充模式。"
type: docs
weight: 136
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

EMR\_SETPOLYFILLMODE 记录定义多边形填充模式。

一般而言，这些模式仅在需要填充复杂的、重叠的多边形时才有所区别；例如，一个由五条边组成的多边形形成一个中心带有五边形的五角星。在这种情况下，ALTERNATE 模式应填充多边形内部的每隔一个封闭区域（星形的各点），而 WINDING 模式应填充所有区域（星形的各点以及中心的五边形）。当填充模式为 ALTERNATE 时，每条扫描线在奇数边和偶数边之间的区域应被填充。也就是说，第一条边与第二条边之间的区域应被填充，第三条边与第四条边之间的区域亦如此，依此类推。当填充模式为 WINDING 时，任何具有非零 winding 值的区域都应被填充。winding 值是指用于绘制多边形的笔绕该区域的次数。多边形每条边的方向都是重要的。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetPolyFillMode` 类的新实例。 |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | 初始化 `EmfSetPolyFillMode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | 获取或设置一个 32 位无符号整数，指定多边形填充模式，且必须属于 PolygonFillMode（第 2.1.27 节）枚举。 |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | 获取或设置一个 32 位无符号整数，指定多边形填充模式，且必须属于 PolygonFillMode（第 2.1.27 节）枚举。 |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


初始化 `EmfSetPolyFillMode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


初始化 `EmfSetPolyFillMode` 类的新实例。

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


获取或设置一个 32 位无符号整数，指定多边形填充模式，且必须属于 PolygonFillMode（第 2.1.27 节）枚举。

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


获取或设置一个 32 位无符号整数，指定多边形填充模式，且必须属于 PolygonFillMode（第 2.1.27 节）枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

