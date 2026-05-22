---
title: "EmfPlusBrushDataFlags 枚举"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

BrushData 标志指定图形画刷的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有效。<br/>            如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) 对象（第 2.2.2.5 节），该对象指定水平渐变的混合模式。 |
| BRUSH_DATA_BLEND_FACTORS_V | 此标志在 EmfPlusLinearGradientBrushData 对象中有效。<br/>            如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 EmfPlusBlendFactors 对象，该对象指定垂直渐变的混合模式。 |
| BRUSH_DATA_DO_NOT_TRANSFORM | 此标志在 EmfPlusTextureBrushData 对象中有效。<br/>            如果设置，则不应对纹理画笔应用世界坐标到设备坐标的变换。 |
| BRUSH_DATA_FOCUS_SCALES | 此标志在 EmfPlusPathGradientBrushData 对象中有效。<br/>            如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个[EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) 对象（第 2.2.2.18 节）。 |
| BRUSH_DATA_IS_GAMMA_CORRECTED | 此标志在 EmfPlusLinearGradientBrushData、EmfPlusPathGradientBrushData 和 EmfPlusTextureBrushData 对象中有效。<br/>            如果设置，则画笔必须已经进行伽马校正；即输出的亮度和强度已被校正以匹配输入图像。 |
| BRUSH_DATA_PATH | 此标志在 [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) 对象（第 2.2.2.29 节）中有效。<br/>            如果设置，则必须在画笔数据对象的 BoundaryData 字段中指定一个 [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) 对象（第 2.2.2.6 节）。<br/>            如果未设置，则必须在 BoundaryData 字段中指定一个 [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) 对象（第 2.2.2.7 节）。 |
| BRUSH_DATA_PRESET_COLORS | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有效。<br/>            如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) 对象（第 2.2.2.4 节）。 |
| BRUSH_DATA_TRANSFORM | 此标志在 [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) 对象（第 2.2.2.24 节）、[EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) 对象以及 [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) 对象（第 2.2.2.45 节）中有效。<br/>            如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 2x3 的世界坐标到设备坐标的变换矩阵。 |
