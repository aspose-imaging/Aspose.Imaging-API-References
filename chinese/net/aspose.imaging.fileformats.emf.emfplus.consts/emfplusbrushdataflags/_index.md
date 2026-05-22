---
title: "枚举 EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusBrushDataFlags 枚举。BrushData 标志指定图形画刷的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。"
type: docs
weight: 4810
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

BrushData 标志指定图形画刷的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| BrushDataPath | `1` | 此标志在[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/)对象（第 2.2.2.29 节）中有意义。如果设置，则必须在画刷数据对象的 BoundaryData 字段中指定一个[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/)对象（第 2.2.2.6 节）。如果清除，则必须在画刷数据对象的 BoundaryData 字段中指定一个[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/)对象（第 2.2.2.7 节）。 |
| BrushDataTransform | `2` | 此标志在 [`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) 对象（第 2.2.2.24 节）、[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) 对象和 [`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) 对象（第 2.2.2.45 节）中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 2x3 的世界空间到设备空间的变换矩阵。 |
| BrushDataPresetColors | `4` | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) 对象（第 2.2.2.4 节）。 |
| BrushDataBlendFactorsH | `8` | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) 对象（第 2.2.2.5 节），该对象指定沿水平渐变的混合模式。 |
| BrushDataBlendFactorsV | `10` | 此标志在 EmfPlusLinearGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 EmfPlusBlendFactors 对象，该对象指定沿垂直渐变的混合模式。 |
| BrushDataFocusScales | `40` | 此标志在 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) 对象（第 2.2.2.18 节）。 |
| BrushDataIsGammaCorrected | `80` | 此标志在 EmfPlusLinearGradientBrushData、EmfPlusPathGradientBrushData 和 EmfPlusTextureBrushData 对象中有意义。如果设置，则画笔必须已经进行伽马校正；即输出的亮度和强度已被校正以匹配输入图像。 |
| BrushDataDoNotTransform | `100` | 此标志在 EmfPlusTextureBrushData 对象中有意义。如果设置，则不应对纹理画笔应用世界空间到设备空间的变换。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


