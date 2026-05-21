---
title: "الفئة EmfPlusHeader"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusHeader. سجل EmfPlusHeader يحدد بداية بيانات EMF في ملف التعريف. يجب أن يكون سجل EmfPlusHeader مضمّنًا في سجل EMF EMR_COMMENT_EMFPLUS الذي يجب أن يكون السجل التالي مباشرةً بعد رأس EMF في ملف التعريف. يتم تحديد سجل EMR_COMMENT_EMFPLUS في قسم MSEMF 2.3.3.2."
type: docs
weight: 6260
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

السجل EmfPlusHeader يحدد بداية بيانات EMF+ في ملف التعريف. يجب أن يكون السجل EmfPlusHeader مضمنًا في سجل EMF EMR_COMMENT_EMFPLUS، والذي يجب أن يكون السجل التالي مباشرةً بعد رأس EMF في ملف التعريف. يتم تحديد سجل EMR_COMMENT_EMFPLUS في القسم 2.3.3.2 من [MS-EMF].

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusHeader](emfplusheader/)(EmfPlusRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPlusHeader`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [dual mode]. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف هذا هو \"dual-mode\", مما يعني أنه يحتوي على مجموعتين من السجلات، كل واحدة تحدد محتوى الرسومات بالكامل. إذا لم تُحدد، يتم تحديد محتوى الرسومات بواسطة سجلات EMF+, وربما سجلات EMF التي تسبقها سجل EmfPlusGetDC. إذا تم تعيين هذه العلامة، يجب أن تكون سجلات EMF وحدها كافية لتعريف محتوى الرسومات. لاحظ أنه سواء تم تعيين علامة \"dual-mode\" أم لا، فإن بعض سجلات EMF تكون موجودة دائمًا، وهي سجلات التحكم في EMF والسجلات التي تحتوي على سجلات EMF+. سجلات التحكم في EMF محددة في [MS-EMF] القسم 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags/) { get; set; } | يحصل أو يعيّن أعلام EMF plus. عدد صحيح غير موقع 32‑بت يحتوي على معلومات حول كيفية تسجيل ملف التعريف هذا. إذا تم تعيين البت الـ31 من الحقل، فإن هذه العلامة تشير إلى أن ملف التعريف سُجل باستخدام سياق جهاز مرجعي لشاشة فيديو. إذا لم تُحدد، سُجل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل صالحًا. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix/) { get; set; } | يحصل أو يعيّن قيمة DPI المنطقية للمحور x. عدد صحيح غير موقع 32‑بت يحدد الدقة الأفقية التي سُجل بها ملف التعريف، بوحدة بكسل لكل بوصة. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy/) { get; set; } | يحصل أو يعيّن قيمة DPI المنطقية للمحور y. عدد صحيح غير موقع 32‑بت يحدد الدقة العمودية التي سُجل بها ملف التعريف، بوحدة خطوط لكل بوصة. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version/) { get; set; } | يحصل أو يعيّن الإصدار. كائن EmfPlusGraphicsVersion (القسم 2.2.2.19) يحدد نسخة رسومات نظام التشغيل التي استُخدمت لإنشاء ملف التعريف هذا. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان عرض فيديو. إذا تم تعيينها، فإن هذه العلامة تشير إلى أن ملف التعريف سُجل باستخدام سياق جهاز مرجعي لشاشة فيديو. إذا لم تُحدد، سُجل ملف التعريف باستخدام سياق جهاز مرجعي لطابعة. |

### انظر أيضًا

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


