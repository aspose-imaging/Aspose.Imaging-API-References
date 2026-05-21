---
title: "الفئة EmfExtTextOutW"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtTextOutW. السجل EMR_EXTTEXTOUTW يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص"
type: docs
weight: 3780
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/
---
## EmfExtTextOutW class

سجل EMR_EXTTEXTOUTW يرسم سلسلة نصية ASCII باستخدام الخط الحالي وألوان النص.

```csharp
public sealed class EmfExtTextOutW : EmfDrawingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfExtTextOutW](emfexttextoutw/#constructor)() | ينشئ مثيلًا جديدًا للفئة `EmfExtTextOutW`. |
| [EmfExtTextOutW](emfexttextoutw/#constructor_1)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfExtTextOutW`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19). لا يُستخدم ويجب تجاهله عند الاستلام. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/exscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على المحور X لتحويل الوحدات من مساحة الصفحة إلى وحدات .01 مم. يجب استخدام ذلك فقط إذا كان وضع الرسوميات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/eyscale/) { get; set; } | يحصل أو يعيّن قيمة عائمة 32‑بت تحدد معامل التحجيم لتطبيقه على المحور Y لتحويل الوحدات من مساحة الصفحة إلى وحدات .01 مم. يجب استخدام ذلك فقط إذا كان وضع الرسوميات المحدد بواسطة iGraphicsMode هو GM_COMPATIBLE. |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/igraphicsmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد وضع الرسوميات من تعداد GraphicsMode (القسم 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [WEmrText](../../aspose.imaging.fileformats.emf.emf.records/emfexttextoutw/wemrtext/) { get; set; } | يحصل أو يعيّن كائن EmrText (القسم 2.2.5) الذي يحدد سلسلة الإخراج في أحرف Unicode UTF16-LE 16‑بت، مع سمات النص وقيم التباعد. |

### انظر أيضًا

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


