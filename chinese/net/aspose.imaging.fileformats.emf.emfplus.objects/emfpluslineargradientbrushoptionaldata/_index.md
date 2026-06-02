---
title: "类 EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLinearGradientBrushOptionalData 类。EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画刷的可选数据。"
type: docs
weight: 5690
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
## EmfPlusLinearGradientBrushOptionalData class

该 EmfPlusLinearGradientBrushOptionalData 对象指定线性渐变画刷的可选数据。

```csharp
public sealed class EmfPlusLinearGradientBrushOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData](emfpluslineargradientbrushoptionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpattern/) { get; set; } | 获取或设置线性渐变画刷的可选混合模式。如果此字段存在，它必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节），或一个或两个 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不得同时包含两者。下表显示了 EmfPlusLinearGradientBrushData BrushData 标志与相应混合模式的有效组合：EmfPlusBlendFactors。 |
| [BlendPatternAsBlendFactorsH](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsh/) { get; } | 获取水平混合因子的混合模式。 |
| [BlendPatternAsBlendFactorsV](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsv/) { get; } | 获取垂直混合因子的混合模式。 |
| [BlendPatternAsPresetColors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternaspresetcolors/) { get; } | 获取预设颜色的混合模式。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/transformmatrix/) { get; set; } | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），用于指定线性渐变画刷的世界空间到设备空间的变换。如果 EmfPlusLinearGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


