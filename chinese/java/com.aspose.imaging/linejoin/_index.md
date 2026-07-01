---
title: "LineJoin"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定如何在 GraphicsPath 对象中包含的图形子路径的连续直线或曲线段之间进行连接。"
type: docs
weight: 69
url: /zh/java/com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

指定如何在 `GraphicsPath` 对象包含的图形（子路径）中连接连续的直线或曲线段。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Miter](#Miter) | 指定斜接连接。 |
| [Bevel](#Bevel) | 指定斜角连接。 |
| [Round](#Round) | 指定圆形连接。 |
| [MiterClipped](#MiterClipped) | 指定斜接连接。 |
### Miter {#Miter}
```
public static final int Miter
```


指定斜接连接。这会产生锐角或被截断的角，取决于斜接长度是否超过斜接限制。

### Bevel {#Bevel}
```
public static final int Bevel
```


指定斜角连接。这会产生对角角。

### Round {#Round}
```
public static final int Round
```


指定圆形连接。这会在直线之间产生平滑的圆弧。

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


指定斜接连接。这会产生锐角或斜角，取决于斜接长度是否超过斜接限制。

