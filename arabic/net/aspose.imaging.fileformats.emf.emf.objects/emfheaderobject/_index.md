---
title: "الفئة EmfHeaderObject"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfHeaderObject. يعرّف كائن Header رأس ملف EMF. يحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل ملف التعريف."
type: docs
weight: 3100
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
## EmfHeaderObject class

كائن Header يحدد رأس ملف EMF. يحدد خصائص الجهاز الذي تم إنشاء الصورة فيه داخل ملف الميتا.

```csharp
public class EmfHeaderObject : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfHeaderObject](emfheaderobject/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد الحدود المستطيلة شاملة-شاملة بوحدات الجهاز لأصغر مستطيل يمكن رسمه حول الصورة المخزنة في ملف التعريف. |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم ملف التعريف، بالبايت. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device/) { get; set; } | يحصل أو يعيّن كائن WMF SizeL ([MS-WMF] القسم 2.2.2.22) الذي يحدد حجم الجهاز المرجعي، بالبكسل. |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame/) { get; set; } | يحصل أو يعيّن كائن WMF RectL الذي يحدد أبعاد المستطيل شاملة-شاملة، بوحدات .01 مليمتر، لمستطيل يحيط بالصورة المخزنة في ملف التعريف. |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحدد عدد كائنات الرسومات التي ستُستخدم أثناء معالجة ملف التعريف. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters/) { get; set; } | يحصل أو يعيّن كائن WMF SizeL الذي يحدد حجم الجهاز المرجعي، بالمليمتر. |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الأحرف في المصفوفة التي تحتوي على وصف محتويات ملف التعريف. يكون صفرًا إذا لم يكن هناك سلسلة وصف. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد الإدخالات في لوحة ألوان ملف التعريف. تقع اللوحة في سجل EMR_EOF. |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الإزاحة من بداية هذا السجل إلى المصفوفة التي تحتوي على وصف محتويات ملف التعريف. |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد السجلات في ملف التعريف. |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد توقيع السجل. يجب أن يكون هذا ENHMETA_SIGNATURE، من تعداد FormatSignature (القسم 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16 بت يجب أن يكون 0x0000 ويجب تجاهله. |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `EmfHeaderObject` صالحًا. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version/) { get; set; } | يحصل أو يعيّن الإصدار (4 بايت): عدد صحيح غير موقع 32 بت يحدد قابلية التبادل لملف EMF. يجب أن يكون هذا 0x00010000. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


