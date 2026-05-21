---
title: "الفئة EmfCreateColorSpaceW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateColorSpaceW class. السجل EMR_CREATECOLORSPACEW ينشئ كائن مساحة ألوان منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode"
type: docs
weight: 3580
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
## EmfCreateColorSpaceW class

سجل EMR_CREATECOLORSPACEW ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف Unicode.

```csharp
public sealed class EmfCreateColorSpaceW : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreateColorSpaceW](emfcreatecolorspacew/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfCreateColorSpaceW`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/cbdata/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد الحجم، بالبايت، لحقل Data. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/data/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/dwflags/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يوفر معلومات حول البيانات في هذا السجل. |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/ihcs/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديلّه. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/lcs/) { get; set; } | يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) يمكنه تحديد اسم ملف تعريف اللون بأحرف Unicode UTF16-LE. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يمكن اختيار كائن مساحة اللون المنطقية المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل عبر سجل EMR_SETCOLORSPACE (القسم 2.3.8.7)، الذي يحدد مساحة اللون المنطقية المستخدمة في عمليات الرسومات اللاحقة.

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


