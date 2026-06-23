---
title: "CmxEllipseSpec"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示为椭圆指定的几何信息。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

表示为椭圆指定的几何信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAngle1()](#getAngle1--) | 获取用于定义饼图扇形的第一个角度。 |
| [setAngle1(float value)](#setAngle1-float-) | 设置用于定义饼图扇形的第一个角度。 |
| [getAngle2()](#getAngle2--) | 获取用于定义饼图扇形的第二个角度。 |
| [setAngle2(float value)](#setAngle2-float-) | 设置用于定义饼图扇形的第二个角度。 |
| [getRotation()](#getRotation--) | 获取椭圆的旋转角度。 |
| [setRotation(float value)](#setRotation-float-) | 设置椭圆的旋转角度。 |
| [getPie()](#getPie--) | 获取一个值，指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图。 |
| [setPie(boolean value)](#setPie-boolean-) | 设置一个值，指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图。 |
| [getCenterX()](#getCenterX--) | 获取矩形中心的 X 坐标。 |
| [setCenterX(float value)](#setCenterX-float-) | 设置矩形中心的 X 坐标。 |
| [getCenterY()](#getCenterY--) | 获取矩形中心的 Y 坐标。 |
| [setCenterY(float value)](#setCenterY-float-) | 设置矩形中心的 Y 坐标。 |
| [getDiameterX()](#getDiameterX--) | 获取矩形 X 维度的直径。 |
| [setDiameterX(float value)](#setDiameterX-float-) | 设置矩形的 X 维度直径。 |
| [getDiameterY()](#getDiameterY--) | 获取矩形的 Y 维度直径。 |
| [setDiameterY(float value)](#setDiameterY-float-) | 设置矩形的 Y 维度直径。 |
| [getBoundingBox()](#getBoundingBox--) | 获取边界框。 |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | 设置边界框。 |
| [toString()](#toString--) | 返回表示此实例的字符串。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查对象是否相等。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


获取用于定义饼图扇区的第一个角度。如果 `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) 为 `false`，则不受影响。以弧度为单位。

**Returns:**
float - 用于定义饼图扇区的第一个角度。
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


设置用于定义饼图扇区的第一个角度。如果 `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) 为 `false`，则不受影响。以弧度为单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 用于定义饼图扇区的第一个角度。 |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


获取用于定义饼图扇区的第二个角度。如果 `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) 为 `false`，则不受影响。以弧度为单位。

**Returns:**
float - 用于定义饼图扇区的第二个角度。
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


设置用于定义饼图扇区的第二个角度。如果 `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) 为 `false`，则不受影响。以弧度为单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 用于定义饼图扇区的第二个角度。 |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


获取椭圆的旋转角度。以弧度为单位。

**Returns:**
float - 椭圆的旋转角度。
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


设置椭圆的旋转角度。以弧度为单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 椭圆的旋转角度。 |

### getPie() {#getPie--}
```
public final boolean getPie()
```


获取一个值，指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图。

**Returns:**
boolean - 指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图的值。
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


设置一个值，指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示此 [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) 是否为饼图的值。 |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


获取矩形中心的 X 坐标。以常用文档距离单位计量。

**Returns:**
float - 矩形中心的 X 坐标。
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


设置矩形中心的 X 坐标。以常用文档距离单位计量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 矩形中心的 X 坐标。 |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


获取矩形中心的 Y 坐标。以常用文档距离单位计量。

**Returns:**
float - 矩形中心的 Y 坐标。
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


设置矩形中心的 Y 坐标。以常用文档距离单位计量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 矩形中心的 Y 坐标。 |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


获取矩形的 X 维度直径。以常用文档距离单位计量。

**Returns:**
float - 矩形的 X 维度直径。
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


设置矩形的 X 维度直径。以常用文档距离单位计量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 矩形的 X 维度直径。 |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


获取矩形的 Y 维度直径。以常用文档距离单位计量。

**Returns:**
float - 矩形的 Y 维度直径。
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


设置矩形的 Y 维度直径。以常用文档距离单位进行测量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 矩形的 Y 维度直径。 |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


获取边界框。

值：边界框。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


设置边界框。

值：边界框。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 边界框。 |

### toString() {#toString--}
```
public String toString()
```


返回表示此实例的字符串。

**Returns:**
java.lang.String - 表示此实例的字符串。
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
