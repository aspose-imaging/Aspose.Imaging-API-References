---
title: "الفئة EmfSetTextJustification"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetTextJustification الفئة. سجل EMR_SETTEXTJUSTIFICATION يحدد مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لتبرير النص."
type: docs
weight: 4630
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
## EmfSetTextJustification class

سجل EMR_SETTEXTJUSTIFICATION يحدد مقدار المسافة الإضافية التي تُضاف إلى أحرف الفاصل لتبرير النص.

```csharp
public sealed class EmfSetTextJustification : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetTextJustification](emfsettextjustification/)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfSetTextJustification`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [NBreakCount](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakcount/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت يحدد عدد أحرف الفاصل. |
| [NBreakExtra](../../aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/nbreakextra/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت يحدد إجمالي مقدار المسافة الإضافية، بوحدات منطقية، التي تُضاف. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

بدلاً من استخدام سجل EMR_SETTEXTJUSTIFICATION، يجب على التنفيذ أن يستخدم سجل EMR_EXTTEXTOUTW (القسم 2.3.5.8) لتنفيذ هذه الوظيفة.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


