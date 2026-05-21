---
title: "الفئة EmfPlgBlt"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPlgBlt class. سجل EMR_PLGBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى متوازي أضلاع الوجهة مع تطبيق صورة قناع لوني."
type: docs
weight: 4050
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

سجل EMR_PLGBLT يحدد نقل كتلة من البكسلات من صورة مصدر إلى متوازي أضلاع هدف، مع تطبيق صورة قناع لوني.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfPlgBlt](emfplgblt/)(EmfRecord) | يقوم بتهيئة نسخة جديدة من الفئة `EmfPlgBlt`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest/) { get; set; } | يحصل أو يعيّن مصفوفة من ثلاثة كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد ثلاثة زوايا لمنطقة متوازي أضلاع الوجهة لنقل الكتلة. الزاوية العلوية اليسرى لمستطيل المصدر تُطابق النقطة الأولى في هذه المصفوفة، والزاوية العلوية اليمنى تُطابق النقطة الثانية، والزاوية السفلية اليسرى تُطابق النقطة الثالثة. الزاوية السفلية اليمنى لمستطيل المصدر تُطابق النقطة الرابعة الضمنية في متوازي الأضلاع، والتي تُحسب من الثلاث نقاط الأولى (A, B, و C) باعتبارها متجهات. D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color/) { get; set; } | يحصل أو يعيّن كائن WMF ColorRef ([MS-WMF] القسم 2.2.2.8) الذي يحدد لون خلفية صورة المصدر. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds/) { get; set; } | يحصل أو يعيّن كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز، للإخراج إلى الوجهة. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد العرض المنطقي للمستطيل المصدر. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الارتفاع المنطقي للمستطيل المصدر. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صورة القناع، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صورة المصدر، والتي لا يُشترط أن تكون متجاورة مع الجزء الثابت من سجل EMR_PLGBLT أو مع بعضها البعض. وبالتالي، الحقول في هذا المخزن التي تحمل تسمية "UndefinedSpace" هي اختيارية ويجب تجاهلها. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد طريقة تفسير القيم في جدول الألوان في رأس صورة القناع. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد كيفية تفسير القيم في جدول الألوان في رأس صورة المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors. |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc/) { get; set; } | يحصل أو يضبط كائن XForm (القسم 2.2.28) الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة لتطبيقه على البت ماب المصدر. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي x المنطقي للزاوية العليا اليسرى لصورة القناع. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32‑بت يحدد الإحداثي y المنطقي للزاوية العليا اليسرى لصورة القناع. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل المصدر. |

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


