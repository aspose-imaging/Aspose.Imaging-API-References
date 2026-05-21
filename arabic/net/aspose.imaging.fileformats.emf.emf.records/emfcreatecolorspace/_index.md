---
title: "الفئة EmfCreateColorSpace"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateColorSpace. سجل EMR_CREATECOLORSPACE ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII."
type: docs
weight: 3570
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
## EmfCreateColorSpace class

سجل EMR_CREATECOLORSPACE ينشئ كائن مساحة لون منطقية من ملف تعريف لون يحمل اسمًا مكوّنًا من أحرف ASCII.

```csharp
public sealed class EmfCreateColorSpace : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreateColorSpace](emfcreatecolorspace/)(EmfRecord) | يُهيئ نسخة جديدة من الفئة `EmfCreateColorSpace`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/ihcs/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد فهرس كائن مساحة اللون المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديلّه. |
| [Lcs](../../aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/lcs/) { get; set; } | يحصل أو يضبط كائن WMF LogColorSpace ([MS-WMF] القسم 2.2.2.11)، الذي يمكنه تحديد اسم ملف تعريف اللون بأحرف ASCII. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يمكن اختيار كائن مساحة اللون المنطقية المحدد بواسطة هذا السجل إلى سياق جهاز التشغيل عبر سجل EMR_SETCOLORSPACE (القسم 2.3.8.7)، الذي يحدد مساحة اللون المنطقية المستخدمة في عمليات الرسومات اللاحقة.

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


