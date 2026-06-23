---
title: "EmfPlusPenOptionalData"
second_title: "Aspose.Imaging for Java API 参考"
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
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（section 2.2.2.47），它指定笔的世界空间到设备空间的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（section 2.2.2.47），它指定笔的世界空间到设备空间的变换。 |
| [getStartCap()](#getStartCap--) | 获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。 |
| [setStartCap(int value)](#setStartCap-int-) | 获取或设置一个可选的 32 位有符号整数，指定 CustomStartCapData 字段中线段起始端的形状。 |
| [getEndCap()](#getEndCap--) | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。 |
| [setEndCap(int value)](#setEndCap-int-) | 获取或设置可选的 32 位有符号整数，指定 CustomEndCapData 字段中线段结束端的形状。 |
| [getJoin()](#getJoin--) | 获取或设置一个可选的 32 位有符号整数，指定如何连接由同一支笔绘制且端点相接的两条线。 |
| [setJoin(int value)](#setJoin-int-) | 获取或设置一个可选的 32 位有符号整数，指定如何连接由同一支笔绘制且端点相接的两条线。 |
| [getMiterLimit()](#getMiterLimit--) | 获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 获取或设置可选的 32 位浮点值，指定斜接限制，即斜接长度与线宽的最大允许比例。 |
| [getLineStyle()](#getLineStyle--) | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。 |
| [setLineStyle(int value)](#setLineStyle-int-) | 获取或设置可选的 32 位有符号整数，指定使用此笔对象绘制的线条样式。 |
| [getDashedLineCapType()](#getDashedLineCapType--) | 获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。 |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | 获取或设置可选的 32 位有符号整数，指定虚线中每段短划线两端的形状。 |
| [getDashOffset()](#getDashOffset--) | 获取或设置可选的 32 位浮点值，指定从线段起点到虚线模式中第一个空格起点的距离。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 获取或设置可选的 32 位浮点值，指定从线段起点到虚线模式中第一个空格起点的距离。 |
| [getDashedLineData()](#getDashedLineData--) | 获取或设置可选的 EmfPlusDashedLineData 对象（章节 2.2.2.16），该对象指定自定义虚线中破折号和空格的长度。 |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | 获取或设置可选的 EmfPlusDashedLineData 对象（章节 2.2.2.16），该对象指定自定义虚线中破折号和空格的长度。 |
| [getPenAlignment()](#getPenAlignment--) | 获取或设置可选的 32 位有符号整数，用于指定相对于所绘制线条坐标的笔宽分布。 |
| [setPenAlignment(int value)](#setPenAlignment-int-) | 获取或设置可选的 32 位有符号整数，用于指定相对于所绘制线条坐标的笔宽分布。 |
| [getCompoundLineData()](#getCompoundLineData--) | 获取或设置可选的 EmfPlusCompoundLineData 对象（章节 2.2.2.9），该对象指定一组浮点值，用于定义笔的复合线——由平行线和间隔组成。 |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | 获取或设置可选的 EmfPlusCompoundLineData 对象（章节 2.2.2.9），该对象指定一组浮点值，用于定义笔的复合线——由平行线和间隔组成。 |
| [getCustomStartCapData()](#getCustomStartCapData--) | 获取或设置可选的 EmfPlusCustomStartCapData 对象（章节 2.2.2.15），该对象定义自定义起始帽形状，即使用此笔绘制的线条起点所使用的形状。 |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | 获取或设置可选的 EmfPlusCustomStartCapData 对象（章节 2.2.2.15），该对象定义自定义起始帽形状，即使用此笔绘制的线条起点所使用的形状。 |
| [getCustomEndCapData()](#getCustomEndCapData--) | 获取或设置可选的 EmfPlusCustomEndCapData 对象（章节 2.2.2.11），该对象定义自定义结束帽形状，即使用此笔绘制的线条终点所使用的形状。 |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | 获取或设置可选的 EmfPlusCustomEndCapData 对象（章节 2.2.2.11），该对象定义自定义结束帽形状，即使用此笔绘制的线条终点所使用的形状。 |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取或设置可选的 EmfPlusTransformMatrix 对象（章节 2.2.2.47），该对象指定笔的世界坐标到设备坐标的变换。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataTransform 标志，则此字段必须存在。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


获取或设置可选的 EmfPlusTransformMatrix 对象（章节 2.2.2.47），该对象指定笔的世界坐标到设备坐标的变换。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataTransform 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


获取或设置可选的 32 位有符号整数，用于指定 CustomStartCapData 字段中线段起始端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataStartCap 标志，则此字段必须存在，且其值必须在 LineCapType 枚举中定义（章节 2.1.1.18）。

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


获取或设置可选的 32 位有符号整数，用于指定 CustomStartCapData 字段中线段起始端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataStartCap 标志，则此字段必须存在，且其值必须在 LineCapType 枚举中定义（章节 2.1.1.18）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


获取或设置可选的 32 位有符号整数，用于指定 CustomEndCapData 字段中线段结束端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且其值必须在 LineCapType 枚举中定义。

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


获取或设置可选的 32 位有符号整数，用于指定 CustomEndCapData 字段中线段结束端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataEndCap 标志，则此字段必须存在，且其值必须在 LineCapType 枚举中定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


获取或设置可选的 32 位有符号整数，用于指定由同一支笔绘制且端点相接的两条线的连接方式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且其值必须在 LineJoinType 枚举中定义（章节 2.1.1.19）。

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


获取或设置可选的 32 位有符号整数，用于指定由同一支笔绘制且端点相接的两条线的连接方式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataJoin 标志，则此字段必须存在，且其值必须在 LineJoinType 枚举中定义（章节 2.1.1.19）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


获取或设置可选的 32 位浮点值，用于指定斜接限制，即斜接长度与线宽的最大允许比例。斜接长度是指连接内部线壁交点到外部线壁交点的距离。当两条线的夹角较小时，斜接长度可能很大。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataMiterLimit 标志，则此字段必须存在。

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


获取或设置可选的 32 位浮点值，用于指定斜接限制，即斜接长度与线宽的最大允许比例。斜接长度是指连接内部线壁交点到外部线壁交点的距离。当两条线的夹角较小时，斜接长度可能很大。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataMiterLimit 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


获取或设置可选的 32 位有符号整数，用于指定使用此笔对象绘制的线条样式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且其值必须在 LineStyle 枚举中定义（章节 2.1.1.20）。

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


获取或设置可选的 32 位有符号整数，用于指定使用此笔对象绘制的线条样式。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataLineStyle 标志，则此字段必须存在，且其值必须在 LineStyle 枚举中定义（章节 2.1.1.20）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


获取或设置可选的 32 位有符号整数，用于指定虚线中每段破折号两端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且其值必须在 DashedLineCapType 枚举中定义（章节 2.1.1.10）。

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


获取或设置可选的 32 位有符号整数，用于指定虚线中每段破折号两端的形状。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineCap 标志，则此字段必须存在，且其值必须在 DashedLineCapType 枚举中定义（章节 2.1.1.10）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


获取或设置可选的 32 位浮点值，用于指定从线段起点到虚线模式中第一个空格起点的距离。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


获取或设置可选的 32 位浮点值，用于指定从线段起点到虚线模式中第一个空格起点的距离。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLineOffset 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


获取或设置可选的 EmfPlusDashedLineData 对象（章节 2.2.2.16），该对象指定自定义虚线中破折号和空格的长度。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


获取或设置可选的 EmfPlusDashedLineData 对象（章节 2.2.2.16），该对象指定自定义虚线中破折号和空格的长度。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataDashedLine 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


获取或设置可选的 32 位有符号整数，用于指定相对于所绘制线条坐标的笔宽分布。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataNonCenter 标志，则此字段必须存在，且其值必须在 PenAlignment 枚举中定义（章节 2.1.1.24）。

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


获取或设置可选的 32 位有符号整数，用于指定相对于所绘制线条坐标的笔宽分布。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataNonCenter 标志，则此字段必须存在，且其值必须在 PenAlignment 枚举中定义（章节 2.1.1.24）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


获取或设置可选的 EmfPlusCompoundLineData 对象（章节 2.2.2.9），该对象指定一组浮点值，用于定义笔的复合线——由平行线和间隔组成。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


获取或设置可选的 EmfPlusCompoundLineData 对象（章节 2.2.2.9），该对象指定一组浮点值，用于定义笔的复合线——由平行线和间隔组成。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCompoundLine 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


获取或设置可选的 EmfPlusCustomStartCapData 对象（章节 2.2.2.15），该对象定义自定义起始帽形状，即使用此笔绘制的线条起点所使用的形状。它可以是多种形状之一，例如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


获取或设置可选的 EmfPlusCustomStartCapData 对象（章节 2.2.2.15），该对象定义自定义起始帽形状，即使用此笔绘制的线条起点所使用的形状。它可以是多种形状之一，例如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomStartCap 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


获取或设置可选的 EmfPlusCustomEndCapData 对象（章节 2.2.2.11），该对象定义自定义结束帽形状，即使用此笔绘制的线条终点所使用的形状。它可以是多种形状之一，例如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


获取或设置可选的 EmfPlusCustomEndCapData 对象（章节 2.2.2.11），该对象定义自定义结束帽形状，即使用此笔绘制的线条终点所使用的形状。它可以是多种形状之一，例如方形、圆形或菱形。如果在 EmfPlusPenData 对象的 PenDataFlags 字段中设置了 PenDataCustomEndCap 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

