---
title: "الفئة EmfSetIcmMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmMode class. السجل EMR_SETICMMODE يحدد وضع إدارة ألوان الصورة ICM لعمليات الرسومات"
type: docs
weight: 4460
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
## EmfSetIcmMode class

سجل EMR_SETICMMODE يحدد وضع إدارة ألوان الصورة (ICM) لعمليات الرسومات.

```csharp
public sealed class EmfSetIcmMode : EmfStateRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetIcmMode](emfseticmmode/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfSetIcmMode`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IcmMode](../../aspose.imaging.fileformats.emf.emf.records/emfseticmmode/icmmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد ما إذا كان يجب تمكين أو تعطيل ICM، من تعداد ICMMode (القسم 2.1.18). هذه القيمة جزء من حالة سياق جهاز التشغيل. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

عند تمكين وضع ICM، يجب أن يتم مطابقة الألوان المحددة في سجلات EMF، بينما يجب استخدام ملف تعريف اللون الافتراضي في سياق جهاز التشغيل عند إجراء نقل بت-بلوك. إذا لم يكن ملف تعريف اللون الافتراضي مطلوبًا، يجب إيقاف وضع ICM قبل إجراء نقل بت-بلوك.

### انظر أيضًا

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


