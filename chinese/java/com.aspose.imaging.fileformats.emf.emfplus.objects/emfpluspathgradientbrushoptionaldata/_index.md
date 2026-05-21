---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusPathGradientBrushOptionalData 对象指定路径渐变画刷的可选数据。"
type: docs
weight: 60
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPathGradientBrushOptionalData 对象指定路径渐变画刷的可选数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），用于指定路径渐变画刷的世界空间到设备空间的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），用于指定路径渐变画刷的世界空间到设备空间的变换。 |
| [getBlendPattern()](#getBlendPattern--) | 获取或设置路径渐变画笔的可选混合模式。 |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | 获取或设置路径渐变画笔的可选混合模式。 |
| [getFocusScaleData()](#getFocusScaleData--) | 获取或设置可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），该对象指定路径渐变画笔的焦点比例。 |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | 获取或设置可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），该对象指定路径渐变画笔的焦点比例。 |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定路径渐变画笔的世界坐标到设备坐标的变换。如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定路径渐变画笔的世界坐标到设备坐标的变换。如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


获取或设置路径渐变画笔的可选混合模式。如果此字段存在，它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节）或 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不能同时包含两者。下表显示了 EmfPlusPathGradientBrushData BrushData 标志与相应混合模式的有效组合：

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


获取或设置路径渐变画笔的可选混合模式。如果此字段存在，它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节）或 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不能同时包含两者。下表显示了 EmfPlusPathGradientBrushData BrushData 标志与相应混合模式的有效组合：

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


获取或设置可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），该对象指定路径渐变画笔的焦点比例。如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataFocusScales 标志，则此字段必须存在。

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


获取或设置可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），该对象指定路径渐变画笔的焦点比例。如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataFocusScales 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

