---
title: "EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusPathPointTypeRle 对象指定使用 RLE 压缩的图形路径上点的类型值。"
type: docs
weight: 62
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

EmfPlusPathPointTypeRle 对象使用 RLE 压缩指定与图形路径上的点关联的类型值。0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B（1 位）：如果设置，则路径点位于贝塞尔曲线上；如果清除，则路径点位于普通直线。RunCount（6 位）：运行计数，即在 PointType 字段中关联的路径点数量。PointType（1 字节）：一个 EmfPlusPathPointType 对象（章节 2.2.2.31），指定要与路径点关联的类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getData()](#getData--) | 获取或设置数据。 |
| [setData(int value)](#setData-int-) | 获取或设置数据。 |
| [getBezier()](#getBezier--) | 获取或设置一个值，指示此 `EmfPlusPathPointTypeRle` 是否为贝塞尔曲线。 |
| [setBezier(boolean value)](#setBezier-boolean-) | 获取或设置一个值，指示此 `EmfPlusPathPointTypeRle` 是否为贝塞尔曲线。 |
| [getRunCount()](#getRunCount--) | 获取或设置运行计数。 |
| [setRunCount(byte value)](#setRunCount-byte-) | 获取或设置运行计数。 |
| [getPointType()](#getPointType--) | 获取或设置点的类型。 |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | 获取或设置点的类型。 |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


获取或设置数据。

值：数据。

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


获取或设置数据。

值：数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


获取或设置一个值，指示此 `EmfPlusPathPointTypeRle` 是否为贝塞尔曲线。如果设置，则路径点位于贝塞尔曲线上；如果清除，则路径点位于普通直线。

值：如果为贝塞尔曲线则为 `true`；否则为 `false`。

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


获取或设置一个值，指示此 `EmfPlusPathPointTypeRle` 是否为贝塞尔曲线。如果设置，则路径点位于贝塞尔曲线上；如果清除，则路径点位于普通直线。

值：如果为贝塞尔曲线则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


获取或设置运行计数。RunCount（6 位）：运行计数，即在 PointType 字段中关联的路径点数量。

值：运行计数。

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


获取或设置运行计数。RunCount（6 位）：运行计数，即在 PointType 字段中关联的路径点数量。

值：运行计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


获取或设置点的类型。PointType（1 字节）：一个 EmfPlusPathPointType 对象（章节 2.2.2.31），指定要与路径点关联的类型。

值：点的类型。

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


获取或设置点的类型。PointType（1 字节）：一个 EmfPlusPathPointType 对象（章节 2.2.2.31），指定要与路径点关联的类型。

值：点的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

