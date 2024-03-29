---
title: EmfExtSelectClipRgn
second_title: Aspose.Imaging لمرجع NET API
description: يدمج سجل EMR_EXTSELECTCLIPRGN المنطقة المحددة مع منطقة القصاصة الحالية باستخدام الوضع المحدد. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.
type: docs
weight: 3660
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
## EmfExtSelectClipRgn class

يدمج سجل EMR_EXTSELECTCLIPRGN المنطقة المحددة مع منطقة القصاصة الحالية باستخدام الوضع المحدد. ملاحظة الحقول التي لم يتم وصفها في هذا القسم محددة في القسم 2.3.2.

```csharp
public sealed class EmfExtSelectClipRgn : EmfClippingRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfExtSelectClipRgn](emfextselectcliprgn#constructor)() | يقوم بتهيئة مثيل جديد لملف[`EmfExtSelectClipRgn`](../emfextselectcliprgn) فئة . |
| [EmfExtSelectClipRgn](emfextselectcliprgn#constructor_1)(EmfRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfExtSelectClipRgn`](../emfextselectcliprgn) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/regionmode) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد طريقة استخدام المنطقة. يجب أن تكون قيمة في تعداد RegionMode (القسم 2.1.29). |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndata) { get; set; } | الحصول على أو تعيين صفيف طول RgnDataSize من البايت الذي يحدد كائن RegionData بوحدات منطقية. إذا كان RegionMode هو RGN_COPY ، فيمكن حذف هذه البيانات وتعيين منطقة المقطع إلى منطقة المقطع الافتراضية (NULL). |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/rgndatasize) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد حجم بيانات المنطقة بالبايت. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |

### أنظر أيضا

* class [EmfClippingRecordType](../emfclippingrecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
