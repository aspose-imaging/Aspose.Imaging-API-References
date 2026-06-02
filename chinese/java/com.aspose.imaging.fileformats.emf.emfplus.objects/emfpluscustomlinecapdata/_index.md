---
title: "EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusCustomLineCapData 对象指定自定义线帽的默认数据。"
type: docs
weight: 36
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

EmfPlusCustomLineCapData 对象指定自定义线帽的默认数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 |
| [getBaseCap()](#getBaseCap--) | 获取或设置一个 32 位无符号整数，指定自定义线帽所基于的 LineCap 枚举值（第 2.1.1.18 节）。 |
| [setBaseCap(int value)](#setBaseCap-int-) | 获取或设置一个 32 位无符号整数，指定自定义线帽所基于的 LineCap 枚举值（第 2.1.1.18 节）。 |
| [getBaseInset()](#getBaseInset--) | 获取或设置一个 32 位浮点值，指定线帽起点与线段终点之间的距离。 |
| [setBaseInset(float value)](#setBaseInset-float-) | 获取或设置一个 32 位浮点值，指定线帽起点与线段终点之间的距离。 |
| [getStrokeStartCap()](#getStrokeStartCap--) | 获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段起始处使用的线帽。 |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | 获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段起始处使用的线帽。 |
| [getStrokeEndCap()](#getStrokeEndCap--) | 获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段末端使用的线帽。 |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | 获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段末端使用的线帽。 |
| [getStrokeJoin()](#getStrokeJoin--) | 获取或设置一个 32 位无符号整数，指定 LineJoin 枚举中的值（第 2.1.1.19 节），用于指定如何连接同一画笔绘制且端点相接的两条线。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | 获取或设置一个 32 位无符号整数，指定 LineJoin 枚举中的值（第 2.1.1.19 节），用于指定如何连接同一画笔绘制且端点相接的两条线。 |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | 获取或设置一个 32 位浮点值，包含通过设置斜接角的斜接长度与线宽的最大允许比例来限制连接处厚度的上限。 |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | 获取或设置一个 32 位浮点值，包含通过设置斜接角的斜接长度与线宽的最大允许比例来限制连接处厚度的上限。 |
| [getWidthScale()](#getWidthScale--) | 获取或设置 32 位浮点值，指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度的自定义线帽的缩放量。 |
| [setWidthScale(float value)](#setWidthScale-float-) | 获取或设置 32 位浮点值，指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度的自定义线帽的缩放量。 |
| [getFillHotSpot()](#getFillHotSpot--) | 获取或设置未被当前使用的 EmfPlusPointF 对象。 |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | 获取或设置未被当前使用的 EmfPlusPointF 对象。 |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | 获取或设置未被当前使用的 EmfPlusPointF 对象。 |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | 获取或设置未被当前使用的 EmfPlusPointF 对象。 |
| [getOptionalData()](#getOptionalData--) | 获取或设置可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节），该对象指定自定义图形线帽的附加数据。 |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | 获取或设置可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节），该对象指定自定义图形线帽的附加数据。 |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


获取或设置一个 32 位无符号整数，指定自定义线帽所基于的 LineCap 枚举值（第 2.1.1.18 节）。

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


获取或设置一个 32 位无符号整数，指定自定义线帽所基于的 LineCap 枚举值（第 2.1.1.18 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


获取或设置一个 32 位浮点值，指定线帽起点与线段终点之间的距离。

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


获取或设置一个 32 位浮点值，指定线帽起点与线段终点之间的距离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段起始处使用的线帽。

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段起始处使用的线帽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段末端使用的线帽。

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


获取或设置一个 32 位无符号整数，指定 LineCap 枚举中的值，指示绘制线段末端使用的线帽。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


获取或设置 32 位无符号整数，指定 LineJoin 枚举（第 2.1.1.19 节）中的值，该枚举定义如何连接由同一画笔绘制且端点相接的两条线。在两条线端点的交叉处，线段连接使连接看起来更连续。

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


获取或设置 32 位无符号整数，指定 LineJoin 枚举（第 2.1.1.19 节）中的值，该枚举定义如何连接由同一画笔绘制且端点相接的两条线。在两条线端点的交叉处，线段连接使连接看起来更连续。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


获取或设置一个 32 位浮点值，包含通过设置斜接角的斜接长度与线宽的最大允许比例来限制连接处厚度的上限。

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


获取或设置一个 32 位浮点值，包含通过设置斜接角的斜接长度与线宽的最大允许比例来限制连接处厚度的上限。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


获取或设置 32 位浮点值，指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度的自定义线帽的缩放量。

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


获取或设置 32 位浮点值，指定相对于用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）宽度的自定义线帽的缩放量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


获取或设置未被当前使用的 EmfPlusPointF 对象。它必须设置为 \{0.0, 0.0\}。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


获取或设置未被当前使用的 EmfPlusPointF 对象。它必须设置为 \{0.0, 0.0\}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


获取或设置未被当前使用的 EmfPlusPointF 对象。它必须设置为 \{0.0, 0.0\}。

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


获取或设置未被当前使用的 EmfPlusPointF 对象。它必须设置为 \{0.0, 0.0\}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


获取或设置可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节），该对象指定自定义图形线帽的附加数据。此字段的具体内容由 CustomLineCapDataFlags 字段的值决定。

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


获取或设置可选的 EmfPlusCustomLineCapOptionalData 对象（第 2.2.2.14 节），该对象指定自定义图形线帽的附加数据。此字段的具体内容由 CustomLineCapDataFlags 字段的值决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

