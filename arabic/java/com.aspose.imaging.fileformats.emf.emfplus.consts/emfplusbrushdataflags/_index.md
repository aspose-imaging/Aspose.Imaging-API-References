---
title: "EmfPlusBrushDataFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد علامات BrushData خصائص فراشي الرسومات بما في ذلك وجود حقول بيانات اختيارية."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

تحدد علامات BrushData خصائص فراشي الرسومات، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه العلامات لتحديد خيارات متعددة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | هذه العلامة ذات معنى في كائنات [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (القسم 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | هذه العلامة ذات معنى في كائنات [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (القسم 2.2.2.24)، وكائنات [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)، وكائنات `EmfPlusTextureBrushData` (القسم 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | هذه العلامة ذات معنى في كائنات EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData، EmfPlusPathGradientBrushData، و EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | هذه العلامة ذات معنى في كائنات EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


هذه العلامة ذات معنى في كائنات [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (القسم 2.2.2.29). إذا تم التعيين، يجب تحديد كائن [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (القسم 2.2.2.6) في حقل BoundaryData لكائن بيانات الفرشاة. إذا لم يتم التعيين، يجب تحديد كائن [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (القسم 2.2.2.7) في حقل BoundaryData لكائن بيانات الفرشاة.

--------------------

يتم تحديد فراشي الرسومات بواسطة كائنات [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush).

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


هذه العلامة ذات معنى في كائنات [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (القسم 2.2.2.24)، وكائنات [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata)، وكائنات `EmfPlusTextureBrushData` (القسم 2.2.2.45). إذا تم التعيين، يجب تحديد مصفوفة تحويل من الفضاء العالمي إلى الفضاء الجهاز 2x3 في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم التعيين، يجب تحديد كائن [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (القسم 2.2.2.4) في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم التعيين، يجب تحديد كائن [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (القسم 2.2.2.5) الذي يحدد نمط مزج على طول تدرج أفقي في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData. إذا تم التعيين، يجب تحديد كائن EmfPlusBlendFactors الذي يحدد نمط مزج على طول تدرج عمودي في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


هذه العلامة ذات معنى في كائنات EmfPlusPathGradientBrushData. إذا تم التعيين، يجب تحديد كائن [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (القسم 2.2.2.18) في حقل OptionalData لكائن بيانات الفرشاة.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


هذه العلامة ذات معنى في كائنات EmfPlusLinearGradientBrushData، EmfPlusPathGradientBrushData، و EmfPlusTextureBrushData. إذا تم التعيين، يجب أن تكون الفرشاة قد تم تصحيحها بالفعل للجاما؛ أي أن سطوع الإخراج وشدته تم تصحيحهما لتطابق الصورة المدخلة.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


هذه العلامة ذات معنى في كائنات EmfPlusTextureBrushData. إذا تم التعيين، يجب عدم تطبيق تحويل من الفضاء العالمي إلى الفضاء الجهاز على فرشاة النسيج.

