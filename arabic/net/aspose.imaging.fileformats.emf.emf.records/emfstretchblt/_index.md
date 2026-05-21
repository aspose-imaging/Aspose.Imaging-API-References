---
title: "الفئة EmfStretchBlt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchBlt فئة. السجل EMR_STRETCHBLT يحدد نقلًا كتليًا للبكسلات من صورة مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة وفق عملية نقطية محددة، مع تمديد أو ضغط الإخراج ليتناسب مع أبعاد الهدف إذا لزم الأمر."
type: docs
weight: 4710
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

سجل EMR_STRETCHBLT يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفق عملية نقطية محددة، مع تمديد أو ضغط المخرجات لتناسب أبعاد الهدف إذا لزم الأمر.

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfStretchBlt](emfstretchblt/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `EmfStretchBlt`. |
| [EmfStretchBlt](emfstretchblt/#constructor_1)(EmfRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfStretchBlt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc/) { get; set; } | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للبت ماب المصدر. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد رمز عملية الرستر. يحدد هذا الرمز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة وربما نمط الفرشاة، لتحقيق اللون النهائي. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الوجهة. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect/) { get; set; } | يحصل أو يعيّن مستطيل الوجهة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR_STRETCHBLT. وبالتالي، الحقول في هذا المخزن التي تحمل التسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect/) { get; set; } | يحصل أو يعيّن مستطيل المصدر. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


