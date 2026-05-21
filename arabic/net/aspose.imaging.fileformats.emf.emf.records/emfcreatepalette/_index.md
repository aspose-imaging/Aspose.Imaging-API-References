---
title: "الفئة EmfCreatePalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreatePalette. سجل EMR_CREATEPALETTE يحدد لوحة ألوان منطقية لعمليات الرسومات"
type: docs
weight: 3610
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
## EmfCreatePalette class

سجل EMR_CREATEPALETTE يعرف لوحة ألوان منطقية لعمليات الرسوم.

```csharp
public sealed class EmfCreatePalette : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfCreatePalette](emfcreatepalette/)(EmfRecord) | يُهيئ مثيلاً جديداً من الفئة `EmfCreatePalette`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/ihpal/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن لوحة الألوان المنطقية في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله. |
| [LogPalette](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/logpalette/) { get; set; } | يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). يجب ضبط حقل Version لهذا الكائن إلى 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن تفشل معالجة هذا السجل. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


