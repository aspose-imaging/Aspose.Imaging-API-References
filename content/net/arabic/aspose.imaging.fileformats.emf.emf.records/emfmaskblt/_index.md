---
title: EmfMaskBlt
second_title: Aspose.Imaging لمرجع NET API
description: يحدد سجل EMR_MASKBLT نقل كتلة وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة  اختياريًا بالاقتران مع نمط الفرشاة وتطبيق قناع اللون الصورة النقطية  وفقًا لعمليات المسح النقطية الأمامية والخلفية المحددة.
type: docs
weight: 3800
url: /ar/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

يحدد سجل EMR_MASKBLT نقل كتلة وحدات البكسل من الصورة النقطية المصدر إلى مستطيل الوجهة ، اختياريًا بالاقتران مع نمط الفرشاة وتطبيق قناع اللون الصورة النقطية ، وفقًا لعمليات المسح النقطية الأمامية والخلفية المحددة.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfMaskBlt](emfmaskblt)(EmfRecord) | يقوم بتهيئة مثيل جديد لملف[`EmfMaskBlt`](../emfmaskblt) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc) { get; set; } | الحصول على كائن WMF ColorRef أو تعيينه ([MS-WMF] القسم 2.2.2.8 الذي يحدد لون الخلفية للصورة النقطية المصدر. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds) { get; set; } | الحصول على أو تعيين كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل المحيط للوجهة في وحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد العرض المنطقي لمستطيل الوجهة. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد الارتفاع المنطقي لمستطيل الوجهة. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap) { get; set; } | الحصول على أو تعيين مخزن مؤقت يحتوي على الصور النقطية للقناع ، والتي ليست مطلوبة لتكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع كل أخرى. وفقًا لذلك ، الحقول الموجودة في هذا المخزن المؤقت والتي تسمى "UndefinedSpace" اختيارية ويجب تجاهل . |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4) { get; set; } | الحصول على أو تعيين عملية نقطية رباعية ، والتي تحدد العمليات النقطية الثلاثية لـ ألوان المقدمة والخلفية للصورة النقطية. تحدد هذه القيم كيفية دمج بيانات اللون الخاصة بالمستطيل المصدر مع بيانات لون المستطيل الوجهة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | الحصول على أو تحديد حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap) { get; set; } | الحصول على أو تعيين مخزن مؤقت يحتوي على الصور النقطية المصدر ، والتي ليست مطلوبة لتكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع كل أخرى. وفقًا لذلك ، الحقول الموجودة في هذا المخزن المؤقت والتي تسمى "UndefinedSpace" اختيارية ويجب تجاهل . |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | الحصول على النوع أو تحديده. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس الصورة النقطية للقناع. يجب أن تكون هذه القيمة في تعداد ألوان DIBC. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc) { get; set; } | الحصول على أو تعيين عدد صحيح بدون إشارة 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس الصورة النقطية المصدر. يجب أن تكون هذه القيمة في تعداد ألوان DIBC (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي x المنطقي للزاوية العلوية اليسرى من المستطيل الوجهة. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc) { get; set; } | الحصول على كائن XForm أو تعيينه (القسم 2.2.28) الذي يحدد تحويل مساحة العالم إلى مساحة الصفحة لتطبيقه على الصورة النقطية المصدر. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي x المنطقي للركن الأيسر العلوي من الصورة النقطية للقناع. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي x المنطقي للزاوية العلوية اليسرى من المستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي y المنطقي للزاوية العلوية اليسرى من المستطيل الوجهة. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي y المنطقي للركن الأيسر العلوي من الصورة النقطية للقناع. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc) { get; set; } | الحصول على أو تعيين عدد صحيح ذي إشارة 32 بت يحدد إحداثي y المنطقي للزاوية العلوية اليسرى من المستطيل المصدر. |

### أنظر أيضا

* class [EmfBitmapRecordType](../emfbitmaprecordtype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
