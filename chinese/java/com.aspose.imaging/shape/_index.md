---
title: "形状"
second_title: "Aspose.Imaging for Java API 参考"
description: "形状。"
type: docs
weight: 102
url: /zh/java/com.aspose.imaging/shape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

形状。使用特定规则连接的一组连续点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Shape()](#Shape--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCenter()](#getCenter--) | 获取形状的中心。 |
| [getSegments()](#getSegments--) | 获取形状段。 |
| [hasSegments()](#hasSegments--) | 获取一个值，指示形状是否有段。 |
### Shape() {#Shape--}
```
public Shape()
```


### getCenter() {#getCenter--}
```
public abstract PointF getCenter()
```


获取形状的中心。

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The shape's center.
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


获取形状段。

**Returns:**
com.aspose.imaging.ShapeSegment[] - 形状段。
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


获取一个值，指示形状是否有段。

**Returns:**
boolean - 如果形状有段则为 `True`；否则为 `false`。
