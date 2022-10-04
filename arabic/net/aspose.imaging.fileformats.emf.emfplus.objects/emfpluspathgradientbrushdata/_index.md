---
title: EmfPlusPathGradientBrushData
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن EmfPlusPathGradientBrushData تدرج مسار لفرشاة رسومات.
type: docs
weight: 5620
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
## EmfPlusPathGradientBrushData class

يحدد كائن EmfPlusPathGradientBrushData تدرج مسار لفرشاة رسومات.

```csharp
public sealed class EmfPlusPathGradientBrushData : EmfPlusBaseBrushData
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfPlusPathGradientBrushData](emfpluspathgradientbrushdata)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BoundaryData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/boundarydata) { get; set; } | الحصول على أو تعيين حدود فرشاة التدرج اللوني للمسار ، والتي يتم تحديدها إما بواسطة مسار أو بشق أساسي مغلق. إذا تم تعيين علامة BrushDataPath في حقل BrushDataFlags ، فيجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6) ؛ وإلا ، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7). |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/brushdataflags) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد البيانات في حقل OptionalData . يجب أن تتكون هذه القيمة من علامات BrushData (القسم 2.1.2.1). العلامات التالية ذات صلة بفرشاة تدرج المسار: |
| [CenterArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerargb32color) { get; set; } | الحصول على كائن EmfPlusARGB أو تعيينه (القسم 2.2.2.1) الذي يحدد اللون المركزي لـ فرشاة تدرج المسار ، وهو اللون الذي يظهر في النقطة المركزية للفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحدود إلى لون المركز أثناء انتقاله من الحد إلى نقطة المركز . |
| [CenterPointF](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerpointf) { get; set; } | الحصول على كائن EmfPlusARGB أو تعيينه (القسم 2.2.2.1) الذي يحدد اللون المركزي لفرشاة تدرج المسار ، وهو اللون الذي يظهر في النقطة المركزية للفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحدود إلى لون المركز أثناء تحركه من الحدود إلى نقطة المركز. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/optionaldata) { get; set; } | الحصول على أو تعيين كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) والذي يحدد بيانات إضافية لفرشاة تدرج المسار. يتم تحديد المحتويات المحددة لهذا الحقل بواسطة قيمة الحقل BrushDataFlags. |
| [SurroundingArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/surroundingargb32colors) { get; set; } | الحصول على أو تعيين مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حدود الفرشاة. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/wrapmode) { get; set; } | الحصول على أو تعيين عدد صحيح موقعة 32 بت من تعداد WrapMode (القسم 2.1.1.34) الذي يحدد ما إذا كان سيتم رسم المنطقة خارج حدود الفرشاة. عند رسم خارج الحدود ، يحدد وضع الالتفاف كيفية تكرار التدرج اللوني |

### أنظر أيضا

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->