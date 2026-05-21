---
title: "تعداد EmfPlusBrushDataFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusBrushDataFlags. تحدد أعلام BrushData خصائص فراشي الرسومات بما في ذلك وجود حقول البيانات الاختيارية. يمكن دمج هذه الأعلام لتحديد خيارات متعددة."
type: docs
weight: 4810
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
## EmfPlusBrushDataFlags enumeration

تحدد أعلام BrushData خصائص فرش الرسومات، بما في ذلك وجود حقول بيانات اختيارية. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

```csharp
[Flags]
public enum EmfPlusBrushDataFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| BrushDataPath | `1` | هذه العلامة ذات معنى في كائنات [`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (section 2.2.2.29). إذا تم ضبطه، يجب تحديد كائن [`EmfPlusBoundaryPathData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (section 2.2.2.6) في حقل BoundaryData لكائن بيانات الفرشاة. إذا لم يُضبط، يجب تحديد كائن [`EmfPlusBoundaryPointData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (section 2.2.2.7) في حقل BoundaryData لكائن بيانات الفرشاة. |
| BrushDataTransform | `2` | This العلامة لها معنى في كائنات [`EmfPlusLinearGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (القسم 2.2.2.24)، وكائنات [`EmfPlusPathGradientBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) ، وكائنات [`EmfPlusTextureBrushData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (القسم 2.2.2.45). إذا تم تعيينها، يجب تحديد مصفوفة تحويل مساحة العالم إلى مساحة الجهاز 2x3 في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataPresetColors | `4` | هذه العلامة لها معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن [`EmfPlusBlendColors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (القسم 2.2.2.4) في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataBlendFactorsH | `8` | هذه العلامة لها معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن [`EmfPlusBlendFactors`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (القسم 2.2.2.5) الذي يحدد نمط المزج على طول تدرج أفقي في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataBlendFactorsV | `10` | هذه العلامة لها معنى في كائنات EmfPlusLinearGradientBrushData. إذا تم تعيينها، يجب تحديد كائن EmfPlusBlendFactors الذي يحدد نمط المزج على طول تدرج عمودي في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataFocusScales | `40` | هذه العلامة لها معنى في كائنات EmfPlusPathGradientBrushData. إذا تم تعيينها، يجب تحديد كائن[`EmfPlusFocusScaleData`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (القسم 2.2.2.18) في حقل OptionalData لكائن بيانات الفرشاة. |
| BrushDataIsGammaCorrected | `80` | هذه العلامة لها معنى في كائنات EmfPlusLinearGradientBrushData و EmfPlusPathGradientBrushData و EmfPlusTextureBrushData. إذا تم تعيينها، يجب أن تكون الفرشاة قد تم تصحيحها غاما مسبقًا؛ أي أن سطوع الإخراج وشدته تم تصحيحهما لتطابق الصورة المدخلة. |
| BrushDataDoNotTransform | `100` | هذه العلامة لها معنى في كائنات EmfPlusTextureBrushData. إذا تم تعيينها، يجب عدم تطبيق تحويل مساحة العالم إلى مساحة الجهاز على فرشاة النسيج. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


