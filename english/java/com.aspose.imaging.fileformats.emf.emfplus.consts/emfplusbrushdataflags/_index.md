---
title: EmfPlusBrushDataFlags
second_title: Aspose.Imaging for Java API Reference
description: The BrushData flags specify properties of graphics brushes including the presence of optional data fields.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

The BrushData flags specify properties of graphics brushes, including the presence of optional data fields. These flags can be combined to specify multiple options.
## Fields

| Field | Description |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | This flag is meaningful in [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objects (section 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | This flag is meaningful in [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) objects (section 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objects, and `EmfPlusTextureBrushData` objects (section 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | This flag is meaningful in EmfPlusLinearGradientBrushData objects. |
| [BrushDataFocusScales](#BrushDataFocusScales) | This flag is meaningful in EmfPlusPathGradientBrushData objects. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | This flag is meaningful in EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData, and EmfPlusTextureBrushData objects. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | This flag is meaningful in EmfPlusTextureBrushData objects. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


This flag is meaningful in [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objects (section 2.2.2.29). If set, an [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) object (section 2.2.2.6) MUST be specified in the BoundaryData field of the brush data object. If clear, an [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) object (section 2.2.2.7) MUST be specified in the BoundaryData field of the brush data object.

--------------------

Graphics brushes are specified by [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) objects

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


This flag is meaningful in [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) objects (section 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) objects, and `EmfPlusTextureBrushData` objects (section 2.2.2.45). If set, a 2x3 world space to device space transform matrix MUST be specified in the OptionalData field of the brush data object.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. If set, an [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) object (section 2.2.2.4) MUST be specified in the OptionalData field of the brush data object.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


This flag is meaningful in EmfPlusLinearGradientBrushData and EmfPlusPathGradientBrushData objects. If set, an [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) object (section 2.2.2.5) that specifies a blend pattern along a horizontal gradient MUST be specified in the OptionalData field of the brush data object.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


This flag is meaningful in EmfPlusLinearGradientBrushData objects. If set, an EmfPlusBlendFactors object that specifies a blend pattern along a vertical gradient MUST be specified in the OptionalData field of the brush data object.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


This flag is meaningful in EmfPlusPathGradientBrushData objects. If set, an[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) object (section 2.2.2.18) MUST be specified in the OptionalData field of the brush data object.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


This flag is meaningful in EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData, and EmfPlusTextureBrushData objects. If set, the brush MUST already be gamma corrected; that is, output brightness and intensity have been corrected to match the input image.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


This flag is meaningful in EmfPlusTextureBrushData objects. If set, a world space to device space transform SHOULD NOT be applied to the texture brush.

