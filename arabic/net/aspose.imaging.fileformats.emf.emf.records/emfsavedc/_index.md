---
title: "الفئة EmfSaveDc"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSaveDc الفئة. يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس من الحالات التي تم حفظها بواسطة سجلات EMR_SAVEDC السابقة إن وجدت. تتكون الحالة من خصائص ورسومات كائنات تشمل الفرشاة النقطية، لوحة الألوان، الخط، القلم والمنطقة المحددة حاليًا. يُستخدم سجل EMR_RESTOREDC لاستعادة الحالة. هذا السجل EMF لا يحدد أي معلمات."
type: docs
weight: 4330
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
## EmfSaveDc class

يحفظ الحالة الحالية لسياق جهاز التشغيل على مكدس الحالات التي حفظتها سجلات EMR_SAVEDDC السابقة، إن وجدت. تتكون الحالة من خصائص ورسومات كائنات، بما في ذلك صورة البت، الفرشاة، لوحة الألوان، الخط، القلم، والمنطقة المحددة حاليًا. يُستخدم سجل EMR_RESTOREDC لاستعادة الحالة. لا يحدد هذا السجل EMF أي معلمات.

```csharp
public sealed class EmfSaveDc : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSaveDc](emfsavedc/#constructor)() | يُنشئ مثلاً جديدًا من الفئة `EmfSaveDc`. |
| [EmfSaveDc](emfsavedc/#constructor_1)(EmfRecord) | يُنشئ مثلاً جديدًا من الفئة `EmfSaveDc`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يمكن للمكدس أن يحتوي على معلومات حالة لعدة مثيلات من سياق جهاز التشغيل. عند استعادة حالة، يجب التخلص من جميع مثيلات الحالة التي تم حفظها مؤخرًا.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


