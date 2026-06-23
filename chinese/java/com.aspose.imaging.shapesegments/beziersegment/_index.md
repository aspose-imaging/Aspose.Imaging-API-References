---
title: "BezierSegment"
second_title: "Aspose.Imaging for Java API 参考"
description: "从一个点到下一个点并使用两个控制点的贝塞尔段。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

从一个点到下一个点并使用两个控制点的贝塞尔段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 初始化 `BezierSegment` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | 获取贝塞尔样条的第一个控制点。 |
| [getSecondControlPoint()](#getSecondControlPoint--) | 获取贝塞尔样条的第二个控制点。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


初始化 `BezierSegment` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | 起始点。 |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | 第一个控制点。 |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | 第二个控制点。 |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | 结束点。 |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


获取贝塞尔样条的第一个控制点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


获取贝塞尔样条的第二个控制点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
