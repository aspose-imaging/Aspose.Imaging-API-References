---
title: "الفئة EmfExtSelectClipRgn"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtSelectClipRgn. سجل EMR_EXTSELECTCLIPRGN يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2."
type: docs
weight: 3760
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
## EmfExtSelectClipRgn class

سجل EMR_EXTSELECTCLIPRGN يجمع المنطقة المحددة مع منطقة القص الحالية باستخدام الوضع المحدد. ملاحظة: الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.

```csharp
public sealed class EmfExtSelectClipRgn : EmfClippingRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor)() | ينشئ مثلاً جديداً من الفئة `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn](emfextselectcliprgn/#constructor_1)(EmfRecord) | ينشئ مثلاً جديداً من الفئة `EmfExtSelectClipRgn`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/regionmode/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة استخدام المنطقة. يجب أن تكون القيمة ضمن تعداد RegionMode (القسم 2.1.29). |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndata/) { get; set; } | يحصل أو يعيّن مصفوفة بطول RgnDataSize من البايتات تحدد كائن RegionData بوحدات منطقية. إذا كان RegionMode هو RGN_COPY، يمكن حذف هذه البيانات ويجب أن تُضبط منطقة القص إلى المنطقة الافتراضية (NULL). |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndatasize/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد حجم بيانات المنطقة بالبايت. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |

### انظر أيضًا

* class [EmfClippingRecordType](../emfclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


