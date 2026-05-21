---
title: "الفئة EmfTransparentBlt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfTransparentBlt. سجل EMR_TRANSPARENTBLT يحدد نقلًا كتليًا للبكسلات من بت ماب المصدر إلى مستطيل الوجهة مع معالجة لون محدد كشفاف، وتمتد أو تضغط الإخراج لتناسب أبعاد الوجهة إذا لزم الأمر."
type: docs
weight: 4760
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

سجل EMR_TRANSPARENTBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى مستطيل هدف، مع معالجة لون محدد كشفاف، وتمديد أو ضغط الناتج ليتناسب مع أبعاد الهدف إذا لزم الأمر.

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt/)(EmfRecord) | يُنشئ مثيلًا جديدًا للفئة `EmfTransparentBlt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الوجهة. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على بت ماب المصدر، والذي لا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR_TRANSPARENTBLT. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" اختيارية ويجب تجاهلها. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color/) { get; set; } | يحصل أو يعيّن كائن WMF ColorRef يحدد لون الخلفية لبت ماب المصدر. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color/) { get; set; } | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) يحدد اللون في بت ماب المصدر الذي يُعامل كشفاف. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة البت المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


