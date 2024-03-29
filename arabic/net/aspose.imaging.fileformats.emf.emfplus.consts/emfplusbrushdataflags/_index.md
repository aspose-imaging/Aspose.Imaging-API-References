---
title: EmfPlusBrushDataFlags
second_title: Aspose.Imaging لمرجع NET API
description: تحدد علامات BrushData خصائص فرش الرسومات  بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه العلامات لتحديد خيارات متعددة.
type: docs
weight: 4690
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

تحدد علامات BrushData خصائص فرش الرسومات ، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه العلامات لتحديد خيارات متعددة.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| BrushDataPath | `1` | هذه العلامة لها معنى في[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) كائنات (القسم 2.2.2.29) . إذا تم تعيينها ، فسيتم تعيين ملف[`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) كائن (القسم 2.2.2.6) يجب تحديده في حقل BoundaryData لكائن بيانات الفرشاة. إذا كان مسحًا ،[`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) يجب تحديد الكائن (القسم 2.2.2.7) في حقل BoundaryData الخاص بكائن بيانات الفرشاة. |
| BrushDataTransform | `2` | هذه العلامة لها معنى في[`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) كائنات (القسم 2.2.2.24) ،[`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) الأشياء و[`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata) كائنات (القسم 2.2.2.45) . في حالة الضبط ، يجب تحديد مساحة 2x3 لمصفوفة تحويل مساحة الجهاز في حقل OptionalData الخاص بكائن بيانات الفرشاة. |
| BrushDataPresetColors | `4` | هذه العلامة ذات مغزى في EmfPlusLinearGradientBrushData وكائنات EmfPlusPathGradientBrushData.[`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) يجب تحديد الكائن (القسم 2.2.2.4) في حقل OptionalData الخاص بكائن بيانات الفرشاة. |
| BrushDataBlendFactorsH | `8` | هذه العلامة ذات مغزى في EmfPlusLinearGradientBrushData وكائنات EmfPlusPathGradientBrushData.[`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) يجب تحديد كائن (القسم 2.2.2.5) الذي يحدد نمط مزج على طول تدرج أفقي في حقل OptionalData من كائن بيانات الفرشاة. |
| BrushDataBlendFactorsV | `10` | هذه العلامة ذات مغزى في كائنات EmfPlusLinearGradientBrushData . إذا تم تعيينها ، يجب تحديد كائن EmfPlusBlendFactors الذي يحدد نمط مزج على طول التدرج العمودي في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataFocusScales | `40` | هذه العلامة لها معنى في كائنات EmfPlusPathGradientBrushData . إذا تم تعيينها ،[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) الكائن (القسم 2.2.2.18) يجب تحديده في حقل OptionalData الخاص بكائن بيانات الفرشاة. |
| BrushDataIsGammaCorrected | `80` | هذه العلامة ذات مغزى في EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData وكائنات EmfPlusTextureBrushData . إذا تم تعيينها ، يجب أن تكون الفرشاة مصححة بالفعل ؛ وهذا يعني أنه تم تصحيح سطوع المخرجات وشدتها لتتناسب مع صورة الإدخال. |
| BrushDataDoNotTransform | `100` | هذه العلامة ذات مغزى في كائنات EmfPlusTextureBrushData . في حالة الضبط ، يجب عدم تطبيق تحويل مساحة العالم إلى مساحة الجهاز على فرشاة النسيج . |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
