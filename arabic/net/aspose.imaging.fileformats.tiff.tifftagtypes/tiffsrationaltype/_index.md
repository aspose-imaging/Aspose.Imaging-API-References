---
title: "الفئة TiffSRationalType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffSRationalType. نوع Tiff كسر موقع"
type: docs
weight: 8190
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
## TiffSRationalType class

نوع tiff signed rational.

```csharp
public sealed class TiffSRationalType : TiffCommonArrayType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffSRationalType](tiffsrationaltype/#constructor)(TiffTags) | يقوم بتهيئة نسخة جديدة من الفئة `TiffSRationalType`. |
| [TiffSRationalType](tiffsrationaltype/#constructor_1)(ushort) | يقوم بتهيئة نسخة جديدة من الفئة `TiffSRationalType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count/) { get; } | يحصل على عدد العناصر. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/tagtype/) { get; } | يحصل على نوع الوسم. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/values/) { get; set; } | يحصل أو يعيّن القيم. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/valuescontainer/) { get; } | يحصل على حاوية القيم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

### انظر أيضًا

* class [TiffCommonArrayType](../tiffcommonarraytype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


