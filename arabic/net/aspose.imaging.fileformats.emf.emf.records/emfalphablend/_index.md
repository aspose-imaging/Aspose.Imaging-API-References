---
title: "الفئة EmfAlphaBlend"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAlphaBlend. يسجل EMR_ALPHABLEND يحدد نقلًا كتلًا من البكسلات من صورة مصدر إلى مستطيل هدف بما في ذلك بيانات الشفافية ألفا وفقًا لعملية دمج محددة"
type: docs
weight: 3290
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

يسجل EMR_ALPHABLEND عملية نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، بما في ذلك بيانات الشفافية ألفا، وفقًا لعملية دمج محددة.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfAlphaBlend](emfalphablend/)(EmfRecord) | يُهيئ نسخة جديدة من الفئة `EmfAlphaBlend`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color/) { get; set; } | يحصل أو يضبط كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون الخلفية للبت ماب المصدر. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction/) { get; set; } | يحصل أو يضبط بنية تحدد عمليات المزج للبت ماب المصدر والوجهة. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد العرض المنطقي للمستطيل الوجهة. يجب أن تكون هذه القيمة أكبر من الصفر. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد العرض المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الارتفاع المنطقي للمستطيل الوجهة. يجب أن تكون هذه القيمة أكبر من الصفر. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. يجب أن تكون هذه القيمة أكبر من الصفر. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap/) { get; set; } | يحصل أو يضبط مخزنًا يحتوي على البت ماب المصدر، ولا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR_ALPHABLEND. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية \"UndefinedSpace\" هي اختيارية ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


