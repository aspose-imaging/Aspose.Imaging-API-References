---
title: "EmfPlusPathGradientBrushOptionalData 类"
type: docs
weight: 510
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | 初始化 EmfPlusPathGradientBrushOptionalData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | 获取或设置路径渐变画刷的可选混合模式。如果此字段存在，必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节），<br/>或 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不能同时包含两者。<br/>下表显示了 EmfPlusPathGradientBrushData<br/>BrushData 标志与相应混合模式的有效组合： |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | 获取或设置可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），指定路径渐变画刷的焦点比例。<br/>如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataFocusScales 标志，则此字段必须存在。 |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），指定路径渐变画刷的世界空间到设备空间的变换。<br/>如果在 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

初始化 EmfPlusPathGradientBrushOptionalData 类的新实例

