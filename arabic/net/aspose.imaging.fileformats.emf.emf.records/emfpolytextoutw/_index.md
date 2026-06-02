---
title: "الفئة EmfPolyTextOutW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutW. سجل EMR_POLYTEXTOUTW يرسم سلسلة أو أكثر من سلاسل النص Unicode باستخدام الخط الحالي وألوان النص."
type: docs
weight: 4190
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
## EmfPolyTextOutW class

سجل EMR_POLYTEXTOUTW يرسم سلسلة نصية واحدة أو أكثر من نوع Unicode باستخدام الخط الحالي وألوان النص.

```csharp
public sealed class EmfPolyTextOutW : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `EmfPolyTextOutW`. |
| [EmfPolyTextOutW](emfpolytextoutw/#constructor_1)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfPolyTextOutW`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/exscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/eyscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/igraphicsmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/wemrtext/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج بترميز Unicode 16‑بت UTF16-LE، مع سمات النص وقيم التباعد. يتم تحديد عدد كائنات EmrText بواسطة cStrings. |

## ملاحظات

يتم تحديد الخط وألوان النص المستخدمة للإخراج عبر الخصائص في الحالة الحالية لسياق جهاز التشغيل. يجب محاكاة EMR_POLYTEXTOUTW بسلسلة من سجلات EMR_EXTTEXTOUTW (القسم 2.3.5.7)، سجل واحد لكل سلسلة.

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


