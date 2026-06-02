---
title: "الفئة EmfExtCreatePen"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtCreatePen فئة. السجل EMR_EXTCREATEPEN يعرّف قلمًا منطقيًا ممتدًا لعمليات الرسومات. يمكن تحديد DIB اختياري لاستخدامه كنمط للخط."
type: docs
weight: 3730
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
## EmfExtCreatePen class

سجل EMR_EXTCREATEPEN يعرّف قلمًا منطقيًا ممتدًا لعمليات الرسومات. يمكن تحديد DIB اختياري لاستخدامه كنمط للخط.

```csharp
public sealed class EmfExtCreatePen : EmfObjectCreationRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfExtCreatePen](emfextcreatepen/#constructor)() | ينشئ مثيلاً جديداً من الفئة `EmfExtCreatePen`. |
| [EmfExtCreatePen](emfextcreatepen/#constructor_1)(EmfRecord) | ينشئ مثيلاً جديداً من الفئة `EmfExtCreatePen`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/bitmapbuffer/) { get; set; } | يحصل أو يضبط مخزنًا اختياريًا يحتوي على DIB مضغوط على شكل كائن WMF DeviceIndependentBitmap ([MS-WMF] القسم 2.2.2.9). لا يلزم أن يكون متجاورًا مع الجزء الثابت من سجل EMR_EXTCREATEPEN. |
| [Elp](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/elp/) { get; set; } | يحصل أو يضبط كائن LogPenEx (القسم 2.2.20) الذي يحدد قلمًا منطقيًا ممتدًا بسمات تشمل مصفوفة نمط خط اختيارية. |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/ihpen/) { get; set; } | يحصل أو يضبط عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن القلم المنطقي الممتد في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن أو تعديله. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


