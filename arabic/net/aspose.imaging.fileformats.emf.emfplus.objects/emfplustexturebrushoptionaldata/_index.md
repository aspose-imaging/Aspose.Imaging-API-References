---
title: "الفئة EmfPlusTextureBrushOptionalData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusTextureBrushOptionalData. كائن EmfPlusTextureBrushOptionalData يحدد بيانات اختيارية لفرشاة نسيج"
type: docs
weight: 5940
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
## EmfPlusTextureBrushOptionalData class

كائن EmfPlusTextureBrushOptionalData يحدد البيانات الاختيارية لفرشاة نسيج.

```csharp
public sealed class EmfPlusTextureBrushOptionalData : EmfPlusStructureObjectType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusTextureBrushOptionalData](emfplustexturebrushoptionaldata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ImageObject](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/imageobject/) { get; set; } | يحصل أو يعيّن كائن EmfPlusImage اختياري (القسم 2.2.1.4) يحدد نسيج الفرشاة. يجب أن يكون هذا الحقل موجودًا إذا كان حجم سجل EmfPlusObject (القسم 2.3.5.1) الذي يعرّف هذه الفرشاة النسيجية كبيرًا بما يكفي لاستيعاب كائن EmfPlusImage بالإضافة إلى الحقول المطلوبة لكائن EmfPlusTextureBrushData وربما كائن EmfPlusTransformMatrix. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/transformmatrix/) { get; set; } | يحصل أو يعيّن كائن EmfPlusTransformMatrix اختياري (القسم 2.2.2.47) يحدد تحويل من الفضاء العالمي إلى فضاء الجهاز للفرشاة النسيجية. يجب أن يكون هذا الحقل موجودًا إذا تم تعيين علم BrushDataTransform في حقل BrushDataFlags لكائن EmfPlusTextureBrushData. |

## ملاحظات

ملاحظة: كل حقل من هذا الكائن اختياري وقد لا يكون موجودًا في حقل OptionalData لكائن EmfPlusTextureBrushData (القسم 2.2.2.45)، اعتمادًا على أعلام BrushData (القسم 2.1.2.1) المحددة في حقل BrushDataFlags الخاص به. على الرغم من أنه غير عملي تمثيل كل تركيبة ممكنة من الحقول الموجودة أو الغائبة، يحدد هذا القسم ترتيبها النسبي في الكائن. المسؤولية على المنفذ لتحديد أي الحقول موجودة فعليًا في سجل الميتافايل المعطى، ولتحليل البيانات لكل حقل على حدة وبالطريقة المناسبة.

### انظر أيضًا

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


