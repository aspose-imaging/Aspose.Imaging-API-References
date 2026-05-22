---
title: "EmfPlusLinearGradientBrushOptionalData 类"
type: docs
weight: 450
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | 初始化 EmfPlusLinearGradientBrushOptionalData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | 获取或设置线性渐变画刷的可选混合模式。如果此字段存在，<br/>            必须包含 EmfPlusBlendColors 对象（第 2.2.4 节），<br/>            或一个或两个 EmfPlusBlendFactors 对象（第 2.2.5 节），<br/>            但不能同时包含两者。下表显示了 EmfPlusLinearGradientBrushData BrushData 标志与相应混合模式的有效组合：<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | 获取水平混合因子 h 的混合模式。 |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | 获取垂直混合因子 v 的混合模式。 |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | 获取混合模式作为预设颜色。 |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定线性渐变画笔的<br/>世界空间到设备空间的变换。<br/>如果在 EmfPlusLinearGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

初始化 EmfPlusLinearGradientBrushOptionalData 类的新实例

