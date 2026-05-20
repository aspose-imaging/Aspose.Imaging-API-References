---
title: "LineSegment"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示直接从特定点到下一个点的段。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.shapesegments/linesegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment)
```
public class LineSegment extends ShapeSegment
```

表示直接从特定点到下一个点的段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LineSegment(PointF startPoint, PointF endPoint)](#LineSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 初始化 `LineSegment` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartPoint()](#getStartPoint--) | 获取起始点。 |
| [getEndPoint()](#getEndPoint--) | 获取结束点。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### LineSegment(PointF startPoint, PointF endPoint) {#LineSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public LineSegment(PointF startPoint, PointF endPoint)
```


初始化 `LineSegment` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | 起始点。 |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | 结束点。 |

### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


获取起始点。

值：起始点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


获取结束点。

值：结束点。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查对象是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 其他对象。 |

**Returns:**
boolean - 相等比较结果。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
