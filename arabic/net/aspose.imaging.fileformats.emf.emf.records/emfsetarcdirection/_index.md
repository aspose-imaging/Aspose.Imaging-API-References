---
title: "الفئة EmfSetArcDirection"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetArcDirection. يحدد سجل EMR_SETARCDIRECTION اتجاه الرسم الذي سيُستخدم لإخراج الأقواس والمستطيلات."
type: docs
weight: 4390
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
## EmfSetArcDirection class

سجل EMR_SETARCDIRECTION يحدد اتجاه الرسم المستخدم لإخراج الأقواس والمستطيلات.

```csharp
public sealed class EmfSetArcDirection : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetArcDirection](emfsetarcdirection/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfSetArcDirection`. |
| [EmfSetArcDirection](emfsetarcdirection/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfSetArcDirection`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArcDirection](../../aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/arcdirection/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع بحجم 32 بت يحدد اتجاه القوس. يجب أن تكون القيمة ضمن تعداد ArcDirection (القسم 2.1.2). الاتجاه الافتراضي هو عكس اتجاه عقارب الساعة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يؤثر سجل EMR_SETARCDIRECTION على الاتجاه الذي تُرسم به السجلات التالية: - EMR_ARC (القسم 2.3.5.2) - EMR_ARCTO (القسم 2.3.5.3) - EMR_CHORD (القسم 2.3.5.4) - EMR_ELLIPSE (القسم 2.3.5.5) - EMR_PIE (القسم 2.3.5.15) - EMR_RECTANGLE (القسم 2.3.5.34) - EMR_ROUNDRECT (القسم 2.3.5.35)

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


