---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画刷的可选数据。"
type: docs
weight: 54
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画刷的可选数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定线性渐变画笔的世界空间到设备空间的变换。 |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定线性渐变画笔的世界空间到设备空间的变换。 |
| [getBlendPattern()](#getBlendPattern--) | 获取或设置线性渐变画笔的可选混合模式。 |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | 获取或设置线性渐变画笔的可选混合模式。 |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | 获取混合模式的预设颜色。 |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | 获取混合模式的水平混合因子。 |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | 获取混合模式的垂直混合因子。 |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定线性渐变画笔的世界空间到设备空间的变换。如果在 EmfPlusLinearGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定线性渐变画笔的世界空间到设备空间的变换。如果在 EmfPlusLinearGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


获取或设置线性渐变画笔的可选混合模式。如果此字段存在，它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节），或一个或两个 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不能同时包含两者。下表显示了 EmfPlusLinearGradientBrushData BrushData 标志与相应混合模式的有效组合：EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


获取或设置线性渐变画笔的可选混合模式。如果此字段存在，它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节），或一个或两个 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不能同时包含两者。下表显示了 EmfPlusLinearGradientBrushData BrushData 标志与相应混合模式的有效组合：EmfPlusBlendFactors

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


获取混合模式的预设颜色。

值：混合模式为预设颜色。

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


获取混合模式的水平混合因子。

值：混合模式为水平混合因子。

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


获取混合模式的垂直混合因子。

值：混合模式为垂直混合因子。

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
