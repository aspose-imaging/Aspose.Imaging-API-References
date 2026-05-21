---
title: "الهيكل EmfBlendFunction"
second_title: "Aspose.Imaging for .NET API Reference"
description: "هيكل Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBlendFunction. بنية تحدد عمليات المزج للصور النقطية المصدر والوجهة"
type: docs
weight: 3360
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
## EmfBlendFunction structure

هيكل يحدد عمليات المزج لصور المصدر والوجهة.

```csharp
public struct EmfBlendFunction
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfBlendFunction](emfblendfunction/)(int) | يُهيئ مثيلاً جديداً من الفئة `EmfBlendFunction`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlphaFormat](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/alphaformat/) { get; } | يحصل على بنية تحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة للشفافية ألفا. |
| [BlendFlags](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendflags/) { get; } | يحصل على أعلام المزج. يجب أن تكون هذه القيمة 0x00 ويجب تجاهلها. |
| [BlendOperation](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/blendoperation/) { get; } | يحصل على رمز عملية المزج. عملية المزج الوحيدة للمصدر والوجهة التي تم تعريفها هي 0x00، والتي تحدد أنه يجب دمج صورة المصدر مع صورة الوجهة بناءً على قيم الشفافية ألفا لبكسلات المصدر. راجع المعادلات التالية للتفاصيل. |
| [SrcConstantAlpha](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/srcconstantalpha/) { get; } | يحصل على عدد صحيح غير موقع 8‑بت يحدد الشفافية ألفا، التي تحدد مزج صور المصدر والوجهة. يجب استخدام هذه القيمة على كامل صورة المصدر. القيمة الدنيا للشفافية ألفا، الصفر، تمثل شفافية تامة، والقيمة القصوى، 0xFF، تمثل تعتمماً تاماً. في الواقع، قيمة 0xFF تحدد أن قيم الشفافية ألفا لكل بكسل هي التي تحدد مزج صور المصدر والوجهة. راجع المعادلات لاحقًا في هذا القسم للتفاصيل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ToInt](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction/toint/)() | يحوّل تمثيل النص للعدد إلى عدد صحيح. |

## الأعضاء الآخرون

| الاسم | الوصف |
| --- | --- |
| enum [AlphaFormatEnum](../../aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum) | هيكل يحدد كيفية تفسير بكسلات المصدر والوجهة بالنسبة للشفافية ألفا. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


