---
title: "الفئة EmfPolyTextOutA"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyTextOutA. سجل EMR_POLYTEXTOUTA يرسم سلسلة نصية ASCII واحدة أو أكثر باستخدام الخط الحالي وألوان النص."
type: docs
weight: 4180
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
## EmfPolyTextOutA class

سجل EMR_POLYTEXTOUTA يرسم سلسلة نصية واحدة أو أكثر من نوع ASCII باستخدام الخط الحالي وألوان النص.

```csharp
public sealed class EmfPolyTextOutA : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPolyTextOutA](emfpolytextouta/#constructor)() | ينشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutA`. |
| [EmfPolyTextOutA](emfpolytextouta/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا من الفئة `EmfPolyTextOutA`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/aemrtext/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات EmrText (القسم 2.2.5) التي تحدد سلاسل الإخراج ببتات ASCII 8، مع سمات النص وقيم التباعد. عدد كائنات EmrText يُحدّد بواسطة cStrings. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19)، الذي يحدد المستطيل المحيط بوحدات الجهاز. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/exscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس X من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/eyscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد مقياس Y من وحدات الصفحة إلى وحدات .01 مم إذا كان وضع الرسومات هو GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/igraphicsmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الرسومات الحالي، من تعداد GraphicsMode (القسم 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

## ملاحظات

يتم تحديد الخط وألوان النص المستخدمة للإخراج بواسطة الخصائص في الحالة الحالية لسياق جهاز التشغيل. يجب محاكاة EMR_POLYTEXTOUTA بسلسلة من سجلات EMR_EXTTEXTOUTW (القسم 2.3.5.7)، سجل واحد لكل سلسلة. يتطلب ذلك تحويل سلسلة النص ASCII في كل كائن EmrText إلى ترميز Unicode UTF16-LE.

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


