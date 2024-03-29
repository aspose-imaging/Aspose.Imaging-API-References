---
title: EmfColorAdjustment
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن ColorAdjustment قيمًا لضبط الألوان في الصور النقطية المصدر في عمليات نقل كتلة البت.
type: docs
weight: 2930
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

يحدد كائن ColorAdjustment قيمًا لضبط الألوان في الصور النقطية المصدر في عمليات نقل كتلة البت.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة يبلغ 16 بت يحدد قيمة تصحيح غاما للطاقة n لـ الأزرق الأساسي للألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2500 إلى 65000. تعني القيمة 10000 أنه يجب عدم إجراء تصحيح جاما. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت يحدد مقدار السطوع الذي سيتم تطبيقه على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100. القيمة الصفرية تعني أنه يجب عدم إجراء تعديل السطوع . |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت يحدد مقدار اللون الذي سيتم تطبيقه على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100. تعني القيمة الصفرية أنه يجب عدم إجراء تعديل الألوان |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت يحدد مقدار التباين الذي سيتم تطبيقه على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100. وتعني القيمة الصفرية أنه يجب عدم إجراء تعديل التباين. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد قيمة تصحيح غاما للطاقة n للأخضر الأساسي للألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2500 إلى 65000. تعني القيمة 10000 أنه يجب عدم إجراء تصحيح جاما. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد نوع مصدر الضوء القياسي الذي بموجبه يتم عرض الصورة ، من التعداد المضيء (القسم 2.1.19) . |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد قيمة تصحيح غاما للطاقة n للأحمر الأساسي للألوان المصدر. يجب أن تكون هذه القيمة في النطاق من 2500 إلى 65000. القيمة 10000 تعني أنه يجب عدم إجراء تصحيح جاما. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 16 بت يحدد مقدار ضبط اللون الأحمر أو الأخضر ليتم تطبيقه على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من -100 إلى 100. يتم ضبط الأرقام الموجبة باتجاه الأحمر والأرقام السالبة على اللون الأخضر. تعني القيمة الصفرية أنه يجب عدم إجراء تعديل الصبغة |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد المرجع الأسود للألوان المصدر. يتم التعامل مع أي ألوان أغمق من ذلك على أنها سوداء. يجب أن تكون هذه القيمة في النطاق من صفر إلى 4000 |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد المرجع الأبيض للألوان المصدر. يتم التعامل مع أي ألوان أفتح من هذه على أنها بيضاء. يجب أن تكون هذه القيمة في النطاق من 6000 إلى 10000 . |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد الحجم بالبايت لهذا الكائن. يجب أن يكون هذا 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد كيفية تحضير صورة الإخراج. يمكن تعيين هذا الحقل إلى NULL أو على أي مجموعة من القيم في تعداد ColorAdjustment (القسم 2.1.5) . |

### أنظر أيضا

* class [EmfObject](../emfobject)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
