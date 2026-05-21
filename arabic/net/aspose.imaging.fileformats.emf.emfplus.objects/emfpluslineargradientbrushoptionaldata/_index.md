---
title: "الفئة EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLinearGradientBrushOptionalData. يحدد كائن EmfPlusLinearGradientBrushOptionalData بيانات اختيارية لفرشاة تدرج خطي."
type: docs
weight: 5690
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
## EmfPlusLinearGradientBrushOptionalData class

كائن EmfPlusLinearGradientBrushOptionalData يحدد البيانات الاختيارية لفرشاة تدرج خطية.

```csharp
public sealed class EmfPlusLinearGradientBrushOptionalData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData](emfpluslineargradientbrushoptionaldata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpattern/) { get; set; } | يحصل أو يعيّن نمط دمج اختياري لفرشاة التدرج الخطي. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4)، أو على كائن أو كائنين EmfPlusBlendFactors (القسم 2.2.2.5)، ولكن لا يجب أن يحتوي على كليهما. يوضح الجدول أدناه التركيبات الصالحة لأعلام BrushData في EmfPlusLinearGradientBrushData وأنماط الدمج المقابلة: EmfPlusBlendFactors. |
| [BlendPatternAsBlendFactorsH](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsh/) { get; } | يحصل على نمط الدمج كعوامل دمج أفقية h. |
| [BlendPatternAsBlendFactorsV](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternasblendfactorsv/) { get; } | يحصل على نمط الدمج كعوامل دمج عمودية v. |
| [BlendPatternAsPresetColors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/blendpatternaspresetcolors/) { get; } | يحصل على نمط الدمج كلون مسبق. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/transformmatrix/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من مساحة العالم إلى مساحة الجهاز لفرشاة التدرج الخطي. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusLinearGradientBrushData. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


