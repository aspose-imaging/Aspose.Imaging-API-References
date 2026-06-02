---
title: "EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "BrushData 标志指定图形画刷的属性，包括可选数据字段的存在。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

BrushData 标志指定图形画刷的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。
## 字段

| 字段 | 描述 |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | 此标志在 [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) 对象中有意义（第 2.2.2.29 节）。 |
| [BrushDataTransform](#BrushDataTransform) | 此标志在 [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) 对象（第 2.2.2.24 节）、[EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) 对象以及 `EmfPlusTextureBrushData` 对象（第 2.2.2.45 节）中有意义。 |
| [BrushDataPresetColors](#BrushDataPresetColors) | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。 |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | 此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。 |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | 此标志在 EmfPlusLinearGradientBrushData 对象中有意义。 |
| [BrushDataFocusScales](#BrushDataFocusScales) | 此标志在 EmfPlusPathGradientBrushData 对象中有意义。 |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | 此标志在 EmfPlusLinearGradientBrushData、EmfPlusPathGradientBrushData 和 EmfPlusTextureBrushData 对象中有意义。 |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | 此标志在 EmfPlusTextureBrushData 对象中有意义。 |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


此标志在 [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) 对象（第 2.2.2.29 节）中有意义。如果设置，则必须在画笔数据对象的 BoundaryData 字段中指定一个 [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) 对象（第 2.2.2.6 节）。如果未设置，则必须在画笔数据对象的 BoundaryData 字段中指定一个 [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) 对象（第 2.2.2.7 节）。

--------------------

图形画刷由 [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) 对象指定。

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


此标志在 [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) 对象（第 2.2.2.24 节）、[EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) 对象以及 `EmfPlusTextureBrushData` 对象（第 2.2.2.45 节）中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 2x3 世界空间到设备空间的变换矩阵。

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) 对象（第 2.2.2.4 节）。

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


此标志在 EmfPlusLinearGradientBrushData 和 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) 对象（第 2.2.2.5 节），该对象指定沿水平渐变的混合模式。

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


此标志在 EmfPlusLinearGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 EmfPlusBlendFactors 对象，该对象指定沿垂直渐变的混合模式。

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


此标志在 EmfPlusPathGradientBrushData 对象中有意义。如果设置，则必须在画笔数据对象的 OptionalData 字段中指定一个 [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) 对象（第 2.2.2.18 节）。

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


此标志在 EmfPlusLinearGradientBrushData、EmfPlusPathGradientBrushData 和 EmfPlusTextureBrushData 对象中有意义。如果设置，则画刷必须已经进行伽马校正；即输出的亮度和强度已被校正以匹配输入图像。

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


此标志在 EmfPlusTextureBrushData 对象中有意义。如果设置，则不应对纹理画刷应用世界空间到设备空间的变换。

