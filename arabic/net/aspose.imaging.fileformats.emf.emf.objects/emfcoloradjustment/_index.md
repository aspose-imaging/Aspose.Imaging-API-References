---
title: "Class EmfColorAdjustment"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfColorAdjustment class. كائن ColorAdjustment يحدد القيم لضبط الألوان في خرائط البت المصدرية في عمليات نقل البت بلوك."
type: docs
weight: 3020
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

كائن ColorAdjustment يحدد القيم لتعديل الألوان في صور البت المصدرية أثناء عمليات نقل الكتل.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأزرق للألوان المصدرية. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار السطوع الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجب إجراء تعديل السطوع. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار الحيوية اللونية التي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجب إجراء تعديل الحيوية اللونية. |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار التباين الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. قيمة الصفر تعني أنه لا يجب إجراء تعديل التباين. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأخضر للألوان المصدرية. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد نوع مصدر الضوء القياسي الذي يُعرض تحتّه الصورة، من تعداد Illuminant (القسم 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد قيمة تصحيح غاما للقوة n للون الأساسي الأحمر للألوان المصدرية. يجب أن تكون هذه القيمة في النطاق من 2,500 إلى 65,000. قيمة 10,000 تعني أنه لا يجب إجراء تصحيح غاما. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 16‑بت يحدد مقدار تعديل الصبغة الأحمر أو الأخضر الذي سيُطبق على الكائن المصدر. يجب أن تكون هذه القيمة في النطاق من –100 إلى 100. الأعداد الموجبة تعدل نحو الأحمر والأعداد السالبة نحو الأخضر. قيمة الصفر تعني أنه لا يجب إجراء تعديل الصبغة. |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأسود للألوان المصدرية. أي ألوان أغمق من هذا تُعامل كأنها سوداء. يجب أن تكون هذه القيمة في النطاق من صفر إلى 4,000. |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد المرجع الأبيض للألوان المصدرية. أي ألوان أفتح من هذا تُعامل كأنها بيضاء. يجب أن تكون هذه القيمة في النطاق من 6,000 إلى 10,000. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد الحجم بالبايت لهذا الكائن. يجب أن تكون هذه القيمة 0x0018. |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد كيفية إعداد صورة الإخراج. يمكن تعيين هذا الحقل إلى NULL أو إلى أي تركيبة من القيم في تعداد ColorAdjustment (القسم 2.1.5). |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


