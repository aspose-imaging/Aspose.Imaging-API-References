---
title: "CustomLineCap"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "封装自定义用户定义的线帽。"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

封装自定义用户定义的线帽。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | 使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | 从指定的现有 `LineCap` 枚举并使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | 从指定的现有 `LineCap` 枚举并使用指定的轮廓、填充和内嵌初始化 `CustomLineCap` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillPath()](#getFillPath--) | 获取定义 custom cap 填充的对象。 |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | 设置定义自定义帽填充的对象。 |
| [getStrokePath()](#getStrokePath--) | 获取定义自定义帽轮廓的对象。 |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | 设置定义自定义帽轮廓的对象。 |
| [getStrokeJoin()](#getStrokeJoin--) | 获取 `LineJoin` 枚举，它决定组成此 `CustomLineCap` 对象的线段如何连接。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | 设置 `LineJoin` 枚举，它决定组成此 `CustomLineCap` 对象的线段如何连接。 |
| [getBaseCap()](#getBaseCap--) | 获取此 `CustomLineCap` 所基于的 `LineCap` 枚举。 |
| [setBaseCap(int value)](#setBaseCap-int-) | 设置此 `CustomLineCap` 所基于的 `LineCap` 枚举。 |
| [getBaseInset()](#getBaseInset--) | 获取帽子与线之间的距离。 |
| [setBaseInset(float value)](#setBaseInset-float-) | 设置帽子与线之间的距离。 |
| [getWidthScale()](#getWidthScale--) | 获取相对于 `System.Drawing.Pen` 对象宽度，对此 `CustomLineCap` 类对象的缩放量。 |
| [setWidthScale(float value)](#setWidthScale-float-) | 设置相对于 `System.Drawing.Pen` 对象宽度，对此 `CustomLineCap` 类对象的缩放量。 |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | 设置用于开始和结束组成此自定义帽的线段的帽子。 |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | 获取用于开始和结束组成此自定义帽的线段的帽子。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的填充。 |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的轮廓。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


从指定的现有 `LineCap` 枚举并使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的填充。 |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的轮廓。 |
| baseCap | int | 用于创建自定义帽的线帽。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


从指定的现有 `LineCap` 枚举并使用指定的轮廓、填充和内嵌初始化 `CustomLineCap` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的填充。 |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `GraphicsPath` 对象，定义自定义帽的轮廓。 |
| baseCap | int | 用于创建自定义帽的线帽。 |
| baseInset | float | 帽子与线之间的距离。 |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


获取定义 custom cap 填充的对象。

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


设置定义自定义帽填充的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 定义自定义帽填充的对象。 |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


获取定义自定义帽轮廓的对象。

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


设置定义自定义帽轮廓的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 定义自定义帽轮廓的对象。 |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


获取 `LineJoin` 枚举，它决定组成此 `CustomLineCap` 对象的线段如何连接。

**Returns:**
int - 此 `CustomLineCap` 对象用于连接线段的 `LineJoin` 枚举。
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


设置 `LineJoin` 枚举，它决定组成此 `CustomLineCap` 对象的线段如何连接。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | `LineJoin` 枚举，此 `CustomLineCap` 对象用于连接线段。 |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


获取此 `CustomLineCap` 所基于的 `LineCap` 枚举。

**Returns:**
int - 此 `CustomLineCap` 所基于的 `LineCap` 枚举。
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


设置此 `CustomLineCap` 所基于的 `LineCap` 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | `LineCap` 枚举，此 `CustomLineCap` 所基于的。 |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


获取帽子与线之间的距离。

**Returns:**
float - 圆帽起始点与线段结束点之间的距离。
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


设置帽子与线之间的距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 圆帽起始点与线段结束点之间的距离。 |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


获取相对于 `System.Drawing.Pen` 对象宽度，对此 `CustomLineCap` 类对象的缩放量。

**Returns:**
float - 缩放圆帽的量。
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


设置相对于 `System.Drawing.Pen` 对象宽度，对此 `CustomLineCap` 类对象的缩放量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 缩放圆帽的量。 |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


设置用于开始和结束组成此自定义帽的线段的帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int | 此圆帽中用于线段起始处的 `LineCap` 枚举。 |
| endCap | int | 此圆帽中用于线段结束处的 `LineCap` 枚举。 |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


获取用于开始和结束组成此自定义帽的线段的帽子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startCap | int[] | 此圆帽中用于线段起始处的 `LineCap` 枚举。 |
| endCap | int[] | 此圆帽中用于线段结束处的 `LineCap` 枚举。 |

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
