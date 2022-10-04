---
title: EmfHeaderObject
second_title: Aspose.Imaging لمرجع NET API
description: يحدد كائن الرأس رأس ملف تعريف EMF. تحدد خصائص الجهاز الذي تم إنشاء الصورة في ملف التعريف عليه.
type: docs
weight: 3010
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
## EmfHeaderObject class

يحدد كائن الرأس رأس ملف تعريف EMF. تحدد خصائص الجهاز الذي تم إنشاء الصورة في ملف التعريف عليه.

```csharp
public class EmfHeaderObject : EmfObject
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfHeaderObject](emfheaderobject)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | الحصول على أو تعيين كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة الشاملة الشاملة في وحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد حجم ملف التعريف ، بالبايت. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | الحصول على كائن WMF SizeL أو تعيينه (القسم [MS-WMF] 2.2.2.22) الذي يحدد حجم الجهاز المرجعي بالبكسل |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | الحصول على أو تعيين كائن WMF RectL الذي يحدد أبعاد مستطيلة شاملة وشاملة ، بوحدات .01 ملليمتر ، لمستطيل يحيط بالصورة المخزنة في ملف التعريف |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يحدد عدد كائنات الرسومات التي سيتم استخدامها أثناء معالجة ملف التعريف |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | الحصول على أو تعيين كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي ، بالمليمترات |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف التعريف. هذا هو صفر إذا لم يكن هناك سلسلة وصف . |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد الإدخالات في لوحة ملف التعريف . توجد اللوحة في السجل EMR_EOF |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد الإزاحة من بداية سجل هذا إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد عدد السجلات في ملف التعريف |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد توقيع السجل. يجب أن يكون هذا ENHMETA_SIGNATURE ، من تعداد FormatSignature (القسم 2.1.14) . |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 16 بت يجب أن يكون 0x0000 ويجب تجاهله |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا[`EmfHeaderObject`](../emfheaderobject)صالح . |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | الحصول على الإصدار (4 بايت) أو تعيينه: عدد صحيح بدون إشارة يبلغ 32 بت يحدد إمكانية التشغيل التفاعلي لملف تعريف EMF. يجب أن يكون هذا 0x00010000 |

### أنظر أيضا

* class [EmfObject](../emfobject)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->