---
title: "الفئة EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathGradientBrushData. كائن EmfPlusPathGradientBrushData يحدد تدرج مسار لفرشاة رسومية"
type: docs
weight: 5740
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
## EmfPlusPathGradientBrushData class

كائن EmfPlusPathGradientBrushData يحدد تدرج مسار لفرشاة رسومية.

```csharp
public sealed class EmfPlusPathGradientBrushData : EmfPlusBaseBrushData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusPathGradientBrushData](emfpluspathgradientbrushdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BoundaryData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/boundarydata/) { get; set; } | يحصل أو يعيّن حد فرشاة تدرج المسار، الذي يُحدَّد إما بمسار أو بمنحنى كاردينال مغلق. إذا تم تعيين علم BrushDataPath في حقل BrushDataFlags، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPathData (القسم 2.2.2.6)؛ وإلا، يجب أن يحتوي هذا الحقل على كائن EmfPlusBoundaryPointData (القسم 2.2.2.7). |
| [BrushDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/brushdataflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد البيانات في حقل OptionalData. يجب أن يتكون هذا القيمة من أعلام BrushData (القسم 2.1.2.1). العلامات التالية ذات صلة بفرشاة تدرج المسار: |
| [CenterArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerargb32color/) { get; set; } | يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد اللون المركزي لفرشاة تدرج المسار، وهو اللون الذي يظهر عند النقطة المركزية للفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى اللون المركزي كلما انتقل من الحد إلى النقطة المركزية. |
| [CenterPointF](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/centerpointf/) { get; set; } | يحصل أو يعيّن كائن EmfPlusARGB (القسم 2.2.2.1) الذي يحدد اللون المركزي لفرشاة تدرج المسار، وهو اللون الذي يظهر عند النقطة المركزية للفرشاة. يتغير لون الفرشاة تدريجيًا من لون الحد إلى اللون المركزي كلما انتقل من الحد إلى النقطة المركزية. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/optionaldata/) { get; set; } | يحصل أو يعيّن كائن EmfPlusPathGradientBrushOptionalData اختياري (القسم 2.2.2.30) يحدد بيانات إضافية لفرشاة تدرج المسار. يتم تحديد المحتويات المحددة لهذا الحقل بقيمة حقل BrushDataFlags. |
| [SurroundingArgb32Colors](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/surroundingargb32colors/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات SurroundingColorCount EmfPlusARGB التي تحدد الألوان للنقاط المنفصلة على حد الفرشاة. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/wrapmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت من تعداد WrapMode (القسم 2.1.1.34) يحدد ما إذا كان سيتم رسم المنطقة خارج حد الفرشاة. عند الرسم خارج الحد، يحدد وضع الالتفاف كيفية تكرار تدرج اللون. |

### انظر أيضًا

* class [EmfPlusBaseBrushData](../emfplusbasebrushdata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


