---
title: "الفئة TiffDataType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tiff.TiffDataType فئة. نوع بيانات TIFF"
type: docs
weight: 8000
url: /ar/net/aspose.imaging.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

نوع بيانات TIFF.

```csharp
public abstract class TiffDataType : IComparable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Count](../../aspose.imaging.fileformats.tiff/tiffdatatype/count/) { get; } | يحصل على عدد العناصر. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| abstract [TagType](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagtype/) { get; } | يحصل على نوع الوسم. |
| abstract [Value](../../aspose.imaging.fileformats.tiff/tiffdatatype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ReadTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | يقرأ بيانات الوسم. |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| abstract [WriteAdditionalData](../../aspose.imaging.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff/)
* assembly [Aspose.Imaging](../../)


