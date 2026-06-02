---
title: "الفئة EmfMaskBlt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMaskBlt. سجل EMR_MASKBLT يحدد نقلًا كتلًا من البكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لوني وفقًا لعمليات نقطية محددة للواجهة والخلفية."
type: docs
weight: 3900
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

سجل EMR_MASKBLT يحدد نقلًا كتليًا للبكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة وتطبيق صورة قناع لون، وفقًا لعمليات الراستر المحددة للأمام والخلف.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfMaskBlt](emfmaskblt/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfMaskBlt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc/) { get; set; } | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للبت ماب المصدر. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الوجهة. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صور القناع، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" اختيارية ويجب تجاهلها. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4/) { get; set; } | يحصل أو يعيّن عملية نقطية رباعية، التي تحدد عمليات نقطية ثلاثية للألوان الأمامية والخلفية لصورة نقطية. هذه القيم تُعرّف كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صور المصدر، والتي لا يلزم أن تكون متجاورة مع الجزء الثابت من سجل EMR_MASKBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" اختيارية ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى لصورة القناع. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى لصورة القناع. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


