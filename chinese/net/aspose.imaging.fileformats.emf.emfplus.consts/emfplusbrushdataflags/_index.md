---
title: EmfPlusBrushDataFlags
second_title: Aspose.Imaging for .NET API 参考
description: BrushData 标志指定图形画笔的属性包括可选数据字段的存在这些标志可以组合起来指定多个选项
type: docs
weight: 4690
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

BrushData 标志指定图形画笔的属性，包括可选数据字段的存在。这些标志可以组合起来指定多个选项。

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| BrushDataPath | `1` | 此标志在[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)对象中有意义（第 2.2.2.29 节） . 如果设置，一个[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata)对象（第 2.2.2.6 节）必须在刷数据对象。 如果清除，则必须在 BoundaryData 字段中指定[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata)对象（第 2.2.2.7 节）刷数据对象。 |
| BrushDataTransform | `2` | 此标志在[`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata)对象中有意义（第 2.2.2.24 节） ,[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)对象和[`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata)对象（第 2.2.2.45 节）。 如果设置，则必须在画笔数据对象的 OptionalData 字段中指定 2x3 世界空间到设备空间的变换矩阵。 |
| BrushDataPresetColors | `4` | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中是有意义的。 如果设置，则[`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)对象（第 2.2.2.4 节）必须在刷数据对象。 |
| BrushDataBlendFactorsH | `8` | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中是有意义的。 如果设置，则[`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)对象（第 2.2.2.5 节）指定沿水平渐变的混合模式必须在画笔数据对象的 OptionalData 字段中指定。 |
| BrushDataBlendFactorsV | `10` | 这个标志在 EmfPlusLinearGradientBrushData 对象中是有意义的。 如果设置，则必须在画笔数据对象的 OptionalData 字段中指定沿垂直渐变指定混合模式的 EmfPlusBlendFactors 对象。 |
| BrushDataFocusScales | `40` | 这个标志在 EmfPlusPathGradientBrushData 对象中是有意义的。 如果设置，则[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)对象（第 2.2.2.18 节）必须在刷数据对象。 |
| BrushDataIsGammaCorrected | `80` | 此标志在 EmfPlusLinearGradientBrushData、EmfPlusPathGradientBrushData 和 EmfPlusTextureBrushData 对象中是有意义的。 如果设置，画笔必须已经经过伽玛校正；也就是说，输出亮度和强度已被校正以匹配输入图像。 |
| BrushDataDoNotTransform | `100` | 这个标志在 EmfPlusTextureBrushData 对象中是有意义的。 如果设置，世界空间到设备空间的变换不应该应用于纹理画笔。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
