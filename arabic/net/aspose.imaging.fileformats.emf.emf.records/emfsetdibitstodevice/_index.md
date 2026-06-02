---
title: "الفئة EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetDiBitsToDevice. السجل EMR_SETDIBITSTODEVICE يحدد نقلًا كتليًا للبكسلات من خطوط المسح المحددة لصورة البت المصدر إلى مستطيل الوجهة"
type: docs
weight: 4450
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
## EmfSetDiBitsToDevice class

سجل EMR_SETDIBITSTODEVICE يحدد نقل كتلة من البكسلات من خطوط المسح المحددة لصورة البت المصدر إلى المستطيل الوجهة.

```csharp
public sealed class EmfSetDiBitsToDevice : EmfBitmapRecordType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfSetDiBitsToDevice](emfsetdibitstodevice/)(EmfRecord) | ينشئ مثيلًا جديدًا للفئة `EmfSetDiBitsToDevice`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/bounds/) { get; set; } | يحصل أو يضبط كائن WMF RectL ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدودي للوجهة بوحدات الجهاز. |
| [CScans](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cscans/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد خطوط المسح. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cxsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد العرض بالبكسل للمستطيل المصدر. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت يحدد الارتفاع بالبكسل للمستطيل المصدر |
| [IStartScan](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/istartscan/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقّع 32-بت يحدد أول سطر مسح في المصفوفة. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | يحصل أو يعيّن حجم السجل |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/sourcebitmap/) { get; set; } | يحصل أو يعيّن مخزنًا يحتوي على صورة البت المصدر، والتي لا يلزم أن تكون متصلة بالجزء الثابت من سجل EMR_SETDIBITSTODEVICE. وبالتالي، الحقول في هذا المخزن التي تم تسمية "UndefinedSpace" اختيارية ويجب أن تُهمل. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | يحصل أو يعيّن النوع. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/usagesrc/) { get; set; } | يحصل أو يضبط عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير القيم في جدول الألوان في رأس البت ماب المصدر. يجب أن تكون هذه القيمة ضمن تعداد DIBColors (القسم 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xdest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي السيني المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xsrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت يحدد إحداثي x بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ydest/) { get; set; } | يحصل أو يضبط عدد صحيح موقع 32‑بت يحدد الإحداثي الصادي المنطقي للزاوية العليا اليسرى للمستطيل الوجهة. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ysrc/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا موقّعًا 32-بت يحدد إحداثي y بالبكسل للزاوية السفلية اليسرى للمستطيل المصدر. |

## ملاحظات

يدعم هذا السجل الصور المصدرية بصيغة JPEG و PNG. حقل Compression في رأس صورة البت المصدر يحدد صيغة الصورة.

### انظر أيضًا

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


