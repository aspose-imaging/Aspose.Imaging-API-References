---
title: "فئة EmfPlusSetTsClip"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsClip فئة. يحدد سجل EmfPlusSetTSClip مناطق القص في سياق جهاز الرسومات لخادم طرفية."
type: docs
weight: 6520
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
## EmfPlusSetTsClip class

سجل EmfPlusSetTSClip يحدد مناطق القص في سياق جهاز الرسومات لخادم الطرفية.

```csharp
public sealed class EmfPlusSetTsClip : EmfPlusTerminalServerRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlusSetTsClip](emfplussettsclip/)(EmfPlusRecord) | يُهيئ نسخة جديدة من الفئة `EmfPlusSetTsClip`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/compressed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `EmfPlusSetTsClip` مضغوطًا. يحدد هذا البت تنسيق بيانات المستطيلات في حقل rects. إذا تم تعيينه، يُعرّف كل مستطيل بـ 4 بايت. إذا لم يُحدد، يُعرّف كل مستطيل بـ 8 بايت. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يجب أن يحدد عدد البايتات المتراصة على 32‑بت في حقل RecordData التالي. هذا العدد لا يشمل رأس السجل الذي يبلغ 12 بايت. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 16‑بت يحتوي على معلومات لبعض السجلات حول كيفية تنفيذ العملية وعلى بنية السجل. |
| [NumRects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/numrects/) { get; } | يحصل على عدد المستطيلات. يحدد هذا الحقل عدد المستطيلات المعرفة في حقل rect. |
| [Rects](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/rects/) { get; set; } | يحصل أو يعيّن مصفوفة من المستطيلات NumRects التي تحدد مناطق القص. يتم تحديد تنسيق هذه البيانات بواسطة بت C في حقل Flags. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد عدد البايتات المتراصة على 32‑بت في السجل بالكامل، بما في ذلك رأس السجل الذي يبلغ 12 بايت والبيانات الخاصة بالسجل. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | يحصل على عدد صحيح غير موقع 16‑بت يحدد نوع السجل. |

## ملاحظات

مخطط الضغط للبيانات في هذا السجل يستخدم الخوارزمية التالية. يتم ترميز كل نقطة من كل مستطيل إما بايتًا واحدًا أو بايتين. إذا تم ترميز النقطة بايتًا واحدًا، يجب أن يكون بت العَلَية (0x80) للبايت MUST مُحددًا، والقيمة هي عدد موقع مُمَثل بالبتات السبع الأقل. إذا لم يتم تحديد بت العَلَية، فإن القيمة تُرمَّز ببايتين، حيث يتم ترميز البايت الأعلى في الـ 7 بتات الأقل للبايت الأول، ويتم ترميز قيمة البايت الأقل في البايت الثاني. يتم ترميز كل نقطة كفرق بين النقطة في المستطيل الحالي والنقطة في المستطيل السابق. يتم ترميز النقطة السفلية للمستطيل كفرق بين الإحداثي السفلي والإحداثي العلوي في المستطيل الحالي.

### انظر أيضًا

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


