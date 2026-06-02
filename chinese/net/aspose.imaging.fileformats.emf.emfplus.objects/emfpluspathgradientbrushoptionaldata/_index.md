---
title: "类 EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushOptionalData 类。EmfPlusPathGradientBrushOptionalData 对象指定路径渐变画笔的可选数据"
type: docs
weight: 5750
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
## EmfPlusPathGradientBrushOptionalData class

该 EmfPlusPathGradientBrushOptionalData 对象指定路径渐变画刷的可选数据。

```csharp
public sealed class EmfPlusPathGradientBrushOptionalData : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData](emfpluspathgradientbrushoptionaldata/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/blendpattern/) { get; set; } | 获取或设置路径渐变画笔的可选混合模式。如果此字段存在，则必须包含 EmfPlusBlendColors 对象（第 2.2.2.4 节）或 EmfPlusBlendFactors 对象（第 2.2.2.5 节），但不得同时包含两者。下表显示了 EmfPlusPathGradientBrushData BrushData 标志与相应混合模式的有效组合： |
| [FocusScaleData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/focusscaledata/) { get; set; } | 获取或设置一个可选的 EmfPlusFocusScaleData 对象（第 2.2.2.18 节），该对象指定路径渐变画笔的焦点比例。如果 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataFocusScales 标志，则此字段必须存在。 |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/transformmatrix/) { get; set; } | 获取或设置一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象指定路径渐变画笔的世界坐标到设备坐标的变换。如果 EmfPlusPathGradientBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


