---
title: "EmfPlusLinearGradientBrushData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusLinearGradientBrushData 对象指定图形画刷的线性渐变。"
type: docs
weight: 53
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusLinearGradientBrushData 对象指定图形画刷的线性渐变。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | 获取或设置刷子数据标志。 |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | 获取或设置刷子数据标志。 |
| [getEndArgb32Color()](#getEndArgb32Color--) | 获取或设置结束颜色。 |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | 获取或设置结束颜色。 |
| [getOptionalData()](#getOptionalData--) | 获取或设置可选数据。 |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | 获取或设置可选数据。 |
| [getRectF()](#getRectF--) | 获取或设置 rect f。 |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | 获取或设置 rect f。 |
| [getStartArgb32Color()](#getStartArgb32Color--) | 获取或设置起始颜色。 |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | 获取或设置起始颜色。 |
| [getWrapMode()](#getWrapMode--) | 获取或设置包装模式。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 获取或设置包装模式。 |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


获取或设置刷子数据标志。

值：BrushDataFlags（4 字节）：一个指定 OptionalData 字段中数据的 32 位无符号整数。此值必须由 `EmfPlusBrushDataFlags`（第 2.1.2.1 节）组成。

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


获取或设置刷子数据标志。

值：BrushDataFlags（4 字节）：一个指定 OptionalData 字段中数据的 32 位无符号整数。此值必须由 `EmfPlusBrushDataFlags`（第 2.1.2.1 节）组成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


获取或设置结束颜色。

值：一个 EmfPlusARGB 对象，指定线性渐变画笔结束边界点的颜色。

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


获取或设置结束颜色。

值：一个 EmfPlusARGB 对象，指定线性渐变画笔结束边界点的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


获取或设置可选数据。

值：一个可选的 `EmfPlusLinearGradientBrushOptionalData` 对象（第 2.2.2.25 节），指定线性渐变画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


获取或设置可选数据。

值：一个可选的 `EmfPlusLinearGradientBrushOptionalData` 对象（第 2.2.2.25 节），指定线性渐变画笔的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


获取或设置 rect f。

值：一个 EmfPlusRectF 对象（第 2.2.2.39 节），指定渐变线的起点和终点。矩形的左上角为起点，右下角为终点。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


获取或设置 rect f。

值：一个 EmfPlusRectF 对象（第 2.2.2.39 节），指定渐变线的起点和终点。矩形的左上角为起点，右下角为终点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


获取或设置起始颜色。

值：一个 EmfPlusARGB 对象（第 2.2.2.1 节），指定线性渐变画笔起始边界点的颜色。

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


获取或设置起始颜色。

值：一个 EmfPlusARGB 对象（第 2.2.2.1 节），指定线性渐变画笔起始边界点的颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取或设置包装模式。

值：来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，指定是否在画笔边界之外绘制区域。在边界之外绘制时，包装模式指定颜色渐变的重复方式。

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


获取或设置包装模式。

值：来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，指定是否在画笔边界之外绘制区域。在边界之外绘制时，包装模式指定颜色渐变的重复方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

