---
title: "EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusPathGradientBrushData 对象指定图形画刷的路径渐变。"
type: docs
weight: 59
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusPathGradientBrushData 对象指定图形画刷的路径渐变。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定是否绘制画笔边界之外的区域。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定是否绘制画笔边界之外的区域。 |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。 |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。 |
| [getCenterPointF()](#getCenterPointF--) | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。 |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | 获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。 |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | 获取或设置 SurroundingColorCount 个 EmfPlusARGB 对象的数组，用于指定画笔边界上离散点的颜色。 |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | 获取或设置 SurroundingColorCount 个 EmfPlusARGB 对象的数组，用于指定画笔边界上离散点的颜色。 |
| [getBoundaryData()](#getBoundaryData--) | 获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条曲线指定。 |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | 获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条曲线指定。 |
| [getOptionalData()](#getOptionalData--) | 获取或设置可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），用于指定路径渐变画笔的附加数据。 |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | 获取或设置可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），用于指定路径渐变画笔的附加数据。 |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


获取或设置 32 位无符号整数，指定 OptionalData 字段中的数据。此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与路径渐变画笔相关：

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


获取或设置 32 位无符号整数，指定 OptionalData 字段中的数据。此值必须由 BrushData 标志（第 2.1.2.1 节）组成。以下标志与路径渐变画笔相关：

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定是否绘制画笔边界之外的区域。在绘制边界之外时，包装模式指定颜色渐变的重复方式

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，用于指定是否绘制画笔边界之外的区域。在绘制边界之外时，包装模式指定颜色渐变的重复方式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点的移动而变化。

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点的移动而变化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点的移动而变化。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


获取或设置 EmfPlusARGB 对象（第 2.2.2.1 节），该对象指定路径渐变画笔的中心颜色，即画笔中心点出现的颜色。画笔的颜色会从边界颜色逐渐过渡到中心颜色，随着从边界向中心点的移动而变化。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


获取或设置 SurroundingColorCount 个 EmfPlusARGB 对象的数组，用于指定画笔边界上离散点的颜色。

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


获取或设置 SurroundingColorCount 个 EmfPlusARGB 对象的数组，用于指定画笔边界上离散点的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条曲线指定。如果在 BrushDataFlags 字段中设置了 BrushDataPath 标志，则此字段必须包含 EmfPlusBoundaryPathData 对象（第 2.2.2.6 节）；否则，此字段必须包含 EmfPlusBoundaryPointData 对象（第 2.2.2.7 节）。

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


获取或设置路径渐变画笔的边界，该边界可以由路径或闭合的基数样条曲线指定。如果在 BrushDataFlags 字段中设置了 BrushDataPath 标志，则此字段必须包含 EmfPlusBoundaryPathData 对象（第 2.2.2.6 节）；否则，此字段必须包含 EmfPlusBoundaryPointData 对象（第 2.2.2.7 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


获取或设置可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），用于指定路径渐变画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


获取或设置可选的 EmfPlusPathGradientBrushOptionalData 对象（第 2.2.2.30 节），用于指定路径渐变画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

