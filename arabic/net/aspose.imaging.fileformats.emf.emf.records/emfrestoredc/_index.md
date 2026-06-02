---
title: "الفئة EmfRestoreDc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRestoreDc class. سجل EMR_RESTOREDC يعيد سياق جهاز التشغيل إلى الحالة المحددة. يتم استعادة سياق جهاز التشغيل عن طريق إزالة معلومات الحالة من مكدس تم إنشاؤه بواسطة سجلات EMR_SAVEDC السابقة (القسم 2.3.11)."
type: docs
weight: 4300
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
## EmfRestoreDc class

سجل EMR_RESTOREDC يعيد سياق جهاز التشغيل إلى الحالة المحددة. يتم استعادة سياق جهاز التشغيل عن طريق إلغاء معلومات الحالة من المكدس الذي تم إنشاؤه بواسطة سجلات EMR_SAVEDC السابقة (القسم 2.3.11).

```csharp
public sealed class EmfRestoreDc : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfRestoreDc](emfrestoredc/#constructor)() | يُنشئ مثيلًا جديدًا للفئة `EmfRestoreDc`. |
| [EmfRestoreDc](emfrestoredc/#constructor_1)(EmfRecord) | يُنشئ مثيلًا جديدًا للفئة `EmfRestoreDc`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [SavedDc](../../aspose.imaging.fileformats.emf.emf.records/emfrestoredc/saveddc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32 بت يحدد الحالة المحفوظة لاستعادتها بالنسبة إلى الحالة الحالية. يجب أن تكون هذه القيمة سلبية؛ –1 تمثل الحالة التي تم حفظها مؤخرًا على المكدس، –2 تمثل الحالة التي قبلها، إلخ. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يمكن للمكدس أن يحتوي على معلومات حالة لعدة مثيلات من سياق جهاز التشغيل. عند استعادة حالة، يجب التخلص من جميع مثيلات الحالة التي تم حفظها مؤخرًا.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


