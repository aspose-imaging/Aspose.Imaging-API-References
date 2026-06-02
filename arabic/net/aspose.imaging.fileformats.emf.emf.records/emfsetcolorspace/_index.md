---
title: "فئة EmfSetColorSpace"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetColorSpace فئة. سجل EMR_SETCOLORSPACE يحدد كائن مساحة اللون المنطقية الحالية لعمليات الرسومات"
type: docs
weight: 4440
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/
---
## EmfSetColorSpace class

سجل EMR_SETCOLORSPACE يعرّف كائن مساحة اللون المنطقية الحالية لعمليات الرسومات.

```csharp
public sealed class EmfSetColorSpace : EmfObjectManipulationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetColorSpace](emfsetcolorspace/)(EmfRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfSetColorSpace`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IhCS](../../aspose.imaging.fileformats.emf.emf.records/emfsetcolorspace/ihcs/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد فهرس كائن مساحة لون منطقية في جدول كائنات EMF (القسم 3.1.1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يجب استخدام كائن مساحة اللون المنطقية المحدد بهذا السجل في عمليات الرسم التي تحددها سجلات EMF اللاحقة، حتى يتم تحديد كائن مساحة لون منطقية مختلف بواسطة سجل EMR_SETCOLORSPACE آخر، أو يتم إزالة الكائن بواسطة سجل EMR_DELETECOLORSPACE.

### انظر أيضًا

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


