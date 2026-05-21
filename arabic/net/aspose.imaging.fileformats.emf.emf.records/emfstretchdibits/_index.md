---
title: "الفئة EmfStretchDiBits"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchDiBits class. السجل EMR_STRETCHDIBITS يحدد نقل كتلة من البكسلات من بت ماب المصدر إلى مستطيل الوجهة اختياريًا مع نمط فرشاة وفق عملية رستر محددة مع تمديد أو ضغط المخرجات لتتناسب مع أبعاد الوجهة إذا لزم الأمر"
type: docs
weight: 4720
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

سجل EMR_STRETCHDIBITS يحدد نقل كتلة من البكسلات من صورة نقطية مصدر إلى مستطيل هدف، اختياريًا مع نمط فرشاة، وفق عملية نقطية محددة، مع تمديد أو ضغط المخرجات لتناسب أبعاد الهدف إذا لزم الأمر.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits/)(EmfRecord) | يُنشئ مثيلاً جديدًا للفئة `EmfStretchDiBits`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد رمز عملية الرستر. تُعرّف هذه الرموز كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الوجهة واختياريًا نمط الفرشاة، لتحقيق اللون النهائي. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل الوجهة. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض بالبكسل للمستطيل المصدر. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل الوجهة. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الارتفاع بالبكسل للمستطيل المصدر. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على بت ماب المصدر، والذي لا يُشترط أن يكون متجاورًا مع الجزء الثابت من سجل EMR_STRETCHDIBITS. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" اختيارية ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد إحداثي x بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد إحداثي y بالبكسل للزاوية العلوية اليسرى للمستطيل المصدر. |

## ملاحظات

يدعم هذا السجل صور المصدر بصيغ JPEG و PNG. حقل Compression في رأس بت ماب المصدر يحدد صيغة الصورة. إذا اختلفت إشارات حقول الارتفاع والعرض للمصدر والوجهة، يحدد هذا السجل نسخة مرآة من بت ماب المصدر إلى الوجهة. أي أنه إذا كان لـ cxSrc و cxDest إشارات مختلفة، يتم تحديد نسخة مرآة من بت ماب المصدر على محور x. وإذا كان لـ cySrc و cyDest إشارات مختلفة، يتم تحديد نسخة مرآة من بت ماب المصدر على محور y.

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


