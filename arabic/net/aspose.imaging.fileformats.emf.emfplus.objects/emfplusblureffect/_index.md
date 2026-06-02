---
title: "الفئة EmfPlusBlurEffect"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBlurEffect الفئة. كائن BlurEffect يحدد انخفاضًا في الفرق في الشدة بين بكسلات الصورة."
type: docs
weight: 5340
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---
## EmfPlusBlurEffect class

يحدد كائن BlurEffect انخفاضًا في الفرق في الشدة بين البكسلات في الصورة.

```csharp
public sealed class EmfPlusBlurEffect : EmfPlusImageEffectsObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusBlurEffect](emfplusblureffect/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlurRadius](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/blurradius/) { get; set; } | يحصل أو يضبط عددًا عائمًا 32-بت يحدد نصف قطر الضبابية بالبكسل، والذي يحدد عدد البكسلات المشاركة في حساب القيمة الجديدة لبكسل معين. يجب أن تكون هذه القيمة في النطاق من 0.0 إلى 255.0. |
| [ExpandEdge](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/expandedge/) { get; set; } | يحصل أو يضبط قيمة منطقية 32-بت تحدد ما إذا كانت الصورة النقطية تتوسع بمقدار يساوي قيمة BlurRadius لإنتاج حواف ناعمة. يجب أن تكون هذه القيمة واحدة من التالي: FALSE 0x00000000 يجب ألا يتغير حجم الصورة النقطية، ويجب قص الحواف الناعمة لتتناسب مع حجم BlurRadius. TRUE 0x00000001 يجب أن يتوسع حجم الصورة النقطية بمقدار يساوي BlurRadius لإنتاج حواف ناعمة. |

### انظر أيضًا

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


