---
title: "الفئة EmfBitBlt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBitBlt class. سجل EMR_BITBLT يحدد نقل كتلة من البكسلات من صورة المصدر إلى مستطيل الوجهة اختياريًا مع نمط فرشاة وفق عملية رستر محددة"
type: docs
weight: 3340
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
## EmfBitBlt class

يسجل EMR_BITBLT عملية نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفقًا لعملية نقطية محددة.

```csharp
public sealed class EmfBitBlt : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfBitBlt](emfbitblt/)(EmfRecord) | يُنشئ مثيلًا جديدًا من الفئة `EmfBitBlt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bitbltrasteroperation/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رمز عملية الرستر. يحدد هذا الرمز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة واختياريًا نمط الفرشاة، لتحقيق اللون النهائي. |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bksrcargb32color/) { get; set; } | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للبت ماب المصدر. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cxdest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض المنطقي للمستطيلات المصدر والوجهة. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cydest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع المنطقي للمستطيلات المصدر والوجهة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والذي لا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR_BITBLT. وبالتالي، الحقول في هذا المخزن التي تم تسميةها "UndefinedSpace" هي اختيارية ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xformsrc/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


