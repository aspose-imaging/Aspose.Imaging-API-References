---
title: "الفئة EmfExtTextOutA"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutA. سجل EMR_EXTTEXTOUTA يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص."
type: docs
weight: 3770
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfexttextouta/
---
## EmfExtTextOutA class

سجل EMR_EXTTEXTOUTA يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص.

```csharp
public sealed class EmfExtTextOutA : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfExtTextOutA](emfexttextouta/#constructor)() | يُهيّئ مثيلًا جديدًا من الفئة `EmfExtTextOutA`. |
| [EmfExtTextOutA](emfexttextouta/#constructor_1)(EmfRecord) | يُهيّئ مثيلًا جديدًا من الفئة `EmfExtTextOutA`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/aemrtext/) { get; set; } | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) يحدد سلسلة الإخراج بأحرف ASCII 8‑بت، وسمات النص، وقيم التباعد. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19). لا يُستخدم ويجب تجاهله عند الاستلام. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/exscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على المحور X لتحويل الوحدات من مساحة الصفحة إلى وحدات .01 مم. يجب استخدام ذلك فقط إذا كان وضع الرسوميات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/eyscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على المحور Y لتحويل الوحدات من مساحة الصفحة إلى وحدات .01 مم. يجب استخدام ذلك فقط إذا كان وضع الرسوميات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextouta/igraphicsmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسوميات من تعداد GraphicsMode (القسم 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


