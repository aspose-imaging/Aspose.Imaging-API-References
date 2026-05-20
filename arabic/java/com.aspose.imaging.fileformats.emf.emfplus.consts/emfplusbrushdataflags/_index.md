---
title: "EmfPlusBrushDataFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد أعلام BrushData خصائص فراشي الرسوم بما في ذلك وجود حقول بيانات اختيارية."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

تحدد أعلام BrushData خصائص فراشي الرسوم، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | هذا العلم ذو معنى في كائنات [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (القسم 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | هذه العلامة ذات معنى في [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) كائنات (القسم 2.2.2.24)، [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) كائنات، و `EmfPlusTextureBrushData` كائنات (القسم 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | هذه العلامة ذات معنى في كائنات EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData و EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | هذه العلامة ذات معنى في كائنات EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


هذه العلامة ذات معنى في [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) كائنات (القسم 2.2.2.29). إذا تم تعيينها، يجب تحديد كائن [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (القسم 2.2.2.6) في حقل BoundaryData لكائن بيانات الفرشاة. إذا تم إلغاء تعيينها، يجب تحديد كائن [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (القسم 2.2.2.7) في حقل BoundaryData لكائن بيانات الفرشاة.

--------------------

فرش الرسومات محددة بواسطة كائنات [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) كائنات

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


هذه العلامة ذات معنى في [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) كائنات (القسم 2.2.2.24)، [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) كائنات، و `EmfPlusTextureBrushData` كائنات (القسم 2.2.2.45). إذا تم تعيينها، يجب تحديد مصفوفة تحويل مساحة العالم إلى مساحة الجهاز 2x3 في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (القسم 2.2.2.4) في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (القسم 2.2.2.5) الذي يحدد نمط المزج على طول تدرج أفقي في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData. إذا تم تعيينها، يجب تحديد كائن EmfPlusBlendFactors الذي يحدد نمط المزج على طول تدرج عمودي في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


هذه العلامة ذات معنى في كائنات EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (القسم 2.2.2.18) في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData و EmfPlusTextureBrushData. إذا تم تعيينها، يجب أن تكون الفرشاة قد تم تصحيحها غاما مسبقًا؛ أي أن سطوع الإخراج وشدته تم تصحيحهما لتطابق صورة الإدخال.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


هذه العلامة ذات معنى في كائنات EmfPlusTextureBrushData. إذا تم تعيينها، يجب عدم تطبيق تحويل مساحة العالم إلى مساحة الجهاز على فرشاة النسيج.

