---
title: "EmfPlusPenOptionalData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusPenOptionalData 对象指定图形笔的可选数据。"
type: docs
weight: 65
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPenOptionalData 对象指定图形笔的可选数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定笔的世界空间到设备空间的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定笔的世界空间到设备空间的变换。 |
| [getStartCap()](#getStartCap--) | 获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。 |
| [setStartCap(int value)](#setStartCap-int-) | 获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。 |
| [getEndCap()](#getEndCap--) | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。 |
| [setEndCap(int value)](#setEndCap-int-) | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。 |
| [getJoin()](#getJoin--) | 获取或设置一个可选的 32 位有符号整数，指定如何连接同一支笔绘制且端点相接的两条线。 |
| [setJoin(int value)](#setJoin-int-) | 获取或设置一个可选的 32 位有符号整数，指定如何连接同一支笔绘制且端点相接的两条线。 |
| [getMiterLimit()](#getMiterLimit--) | 获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。 |
| [getLineStyle()](#getLineStyle--) | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。 |
| [setLineStyle(int value)](#setLineStyle-int-) | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。 |
| [getDashedLineCapType()](#getDashedLineCapType--) | 获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。 |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | 获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。 |
| [getDashOffset()](#getDashOffset--) | 获取或设置可选的 32 位浮点值，指定从线段起点到虚线模式中第一个空格起点的距离。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 获取或设置可选的 32 位浮点值，指定从线段起点到虚线模式中第一个空格起点的距离。 |
| [getDashedLineData()](#getDashedLineData--) | 获取或设置可选的 EmfPlusDashedLineData 对象（第 2.2.2.16 节），该对象指定自定义虚线中短划线和空格的长度。 |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | 获取或设置可选的 EmfPlusDashedLineData 对象（第 2.2.2.16 节），该对象指定自定义虚线中短划线和空格的长度。 |
| [getPenAlignment()](#getPenAlignment--) | 获取或设置可选的 32 位有符号整数，指定笔宽相对于被绘制线条坐标的分布方式。 |
| [setPenAlignment(int value)](#setPenAlignment-int-) | 获取或设置可选的 32 位有符号整数，指定笔宽相对于被绘制线条坐标的分布方式。 |
| [getCompoundLineData()](#getCompoundLineData--) | 获取或设置可选的 EmfPlusCompoundLineData 对象（第 2.2.2.9 节），该对象指定一组浮点值，用于定义笔的复合线——由平行线段和空格组成。 |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | 获取或设置可选的 EmfPlusCompoundLineData 对象（第 2.2.2.9 节），该对象指定一组浮点值，用于定义笔的复合线——由平行线段和空格组成。 |
| [getCustomStartCapData()](#getCustomStartCapData--) | 获取或设置可选的 EmfPlusCustomStartCapData 对象（第 2.2.2.15 节），该对象定义自定义起始帽形状，即在使用此笔绘制的线段起点使用的形状。 |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | 获取或设置可选的 EmfPlusCustomStartCapData 对象（第 2.2.2.15 节），该对象定义自定义起始帽形状，即在使用此笔绘制的线段起点使用的形状。 |
| [getCustomEndCapData()](#getCustomEndCapData--) | 获取或设置可选的 EmfPlusCustomEndCapData 对象（第 2.2.2.11 节），该对象定义自定义结束帽形状，即在使用此笔绘制的线段终点使用的形状。 |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | 获取或设置可选的 EmfPlusCustomEndCapData 对象（第 2.2.2.11 节），该对象定义自定义结束帽形状，即在使用此笔绘制的线段终点使用的形状。 |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定笔的世界空间到设备空间的变换。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataTransform 标志，则此字段必须存在。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定笔的世界空间到设备空间的变换。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataTransform 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataStartCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举（第 2.1.1.18 节）中定义。

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataStartCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举（第 2.1.1.18 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举中定义。

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且该值必须在 LineCapType 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


获取或设置一个可选的 32 位有符号整数，指定如何连接由同一支笔绘制且端点相接的两条线。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且该值必须在 LineJoinType 枚举（第 2.1.1.19 节）中定义。

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


获取或设置一个可选的 32 位有符号整数，指定如何连接由同一支笔绘制且端点相接的两条线。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且该值必须在 LineJoinType 枚举（第 2.1.1.19 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。斜接长度是从连接内部的线壁交点到连接外部的线壁交点的距离。当两条线之间的角度较小时，斜接长度可能很大。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataMiterLimit 标志，则此字段必须存在。

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。斜接长度是从连接内部的线壁交点到连接外部的线壁交点的距离。当两条线之间的角度较小时，斜接长度可能很大。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataMiterLimit 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


获取或设置可选的 32 位有符号整数，指定此笔对象绘制的线条使用的样式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且该值必须在 LineStyle 枚举（第 2.1.1.20 节）中定义。

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


获取或设置可选的 32 位有符号整数，指定此笔对象绘制的线条使用的样式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且该值必须在 LineStyle 枚举（第 2.1.1.20 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且该值必须在 DashedLineCapType 枚举（第 2.1.1.10 节）中定义。

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且该值必须在 DashedLineCapType 枚举（第 2.1.1.10 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


获取或设置可选的 32 位浮点值，指定从线条起点到虚线模式中第一个空格起点的距离。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


获取或设置可选的 32 位浮点值，指定从线条起点到虚线模式中第一个空格起点的距离。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


获取或设置可选的 EmfPlusDashedLineData 对象（第 2.2.2.16 节），指定自定义虚线中短划线和空格的长度。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


获取或设置可选的 EmfPlusDashedLineData 对象（第 2.2.2.16 节），指定自定义虚线中短划线和空格的长度。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


获取或设置可选的 32 位有符号整数，指定相对于所绘线条坐标的笔宽分布。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataNonCenter 标志，则此字段必须存在，且该值必须在 PenAlignment 枚举（第 2.1.1.24 节）中定义。

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


获取或设置可选的 32 位有符号整数，指定相对于所绘线条坐标的笔宽分布。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataNonCenter 标志，则此字段必须存在，且该值必须在 PenAlignment 枚举（第 2.1.1.24 节）中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


获取或设置可选的 EmfPlusCompoundLineData 对象（第 2.2.2.9 节），指定一组浮点值，用于定义笔的复合线，由平行线和间隔组成。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


获取或设置可选的 EmfPlusCompoundLineData 对象（第 2.2.2.9 节），指定一组浮点值，用于定义笔的复合线，由平行线和间隔组成。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


获取或设置可选的 EmfPlusCustomStartCapData 对象（第 2.2.2.15 节），定义自定义起始帽形状，即在使用此笔绘制的线条起点使用的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


获取或设置可选的 EmfPlusCustomStartCapData 对象（第 2.2.2.15 节），定义自定义起始帽形状，即在使用此笔绘制的线条起点使用的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


获取或设置可选的 EmfPlusCustomEndCapData 对象（第 2.2.2.11 节），定义自定义结束帽形状，即在使用此笔绘制的线条终点使用的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


获取或设置可选的 EmfPlusCustomEndCapData 对象（第 2.2.2.11 节），定义自定义结束帽形状，即在使用此笔绘制的线条终点使用的形状。它可以是各种形状，如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

