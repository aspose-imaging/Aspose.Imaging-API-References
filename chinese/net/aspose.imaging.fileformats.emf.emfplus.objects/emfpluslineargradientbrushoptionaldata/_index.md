---
title: EmfPlusLinearGradientBrushOptionalData
second_title: Aspose.Imaging for .NET API 参考
description: EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画笔的可选数据
type: docs
weight: 5570
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
## EmfPlusLinearGradientBrushOptionalData class

EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画笔的可选数据。

```csharp
public sealed class EmfPlusLinearGradientBrushOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData](emfpluslineargradientbrushoptionaldata)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpattern) { get; set; } | 获取或设置线性渐变画笔的可选混合模式。如果该字段存在， 它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节）、 或一个或两个 EmfPlusBlendFactors 对象（第 2.2.2.5 节）、 但它不能同时包含两者。下表显示 EmfPlusLinearGradientBrushData BrushData 标志和相应混合模式的有效组合: EmfPlusBlendFactors |
| [BlendPatternAsBlendFactorsH](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsh) { get; } | 获取混合模式作为混合因子 h。 |
| [BlendPatternAsBlendFactorsV](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsv) { get; } | 获取混合模式作为混合因子 v. |
| [BlendPatternAsPresetColors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternaspresetcolors) { get; } | 获取混合图案作为预设颜色。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/transformmatrix) { get; set; } | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象为线性渐变画笔指定 世界空间到设备空间的变换。 如果在 EmfPlusLinearGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则该字段必须存在。 |

### 也可以看看

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->