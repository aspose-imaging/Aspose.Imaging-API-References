---
title: "الفئة EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushOptionalData class. يحدد كائن EmfPlusPathGradientBrushOptionalData البيانات الاختيارية لفرشاة تدرج المسار."
type: docs
weight: 5750
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
## EmfPlusPathGradientBrushOptionalData class

كائن EmfPlusPathGradientBrushOptionalData يحدد البيانات الاختيارية لفرشاة تدرج المسار.

```csharp
public sealed class EmfPlusPathGradientBrushOptionalData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData](emfpluspathgradientbrushoptionaldata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendPattern](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/blendpattern/) { get; set; } | الحصول أو تعيين نمط مزج اختياري لفرشاة تدرج المسار. إذا كان هذا الحقل موجودًا، يجب أن يحتوي إما على كائن EmfPlusBlendColors (القسم 2.2.2.4) أو كائن EmfPlusBlendFactors (القسم 2.2.2.5)، ولا يجب أن يحتوي على كليهما. يوضح الجدول أدناه التركيبات الصالحة لأعلام BrushData في EmfPlusPathGradientBrushData وأنماط المزج المقابلة. |
| [FocusScaleData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/focusscaledata/) { get; set; } | الحصول أو تعيين كائن EmfPlusFocusScaleData اختياري (القسم 2.2.2.18) يحدد مقاييس التركيز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataFocusScales في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/transformmatrix/) { get; set; } | الحصول أو تعيين كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز لفرشاة تدرج المسار. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusPathGradientBrushData. |

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


