---
title: "الفئة TiffFloatType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffFloatType الفئة. نوع tiff العائم"
type: docs
weight: 8100
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
## TiffFloatType class

نوع tiff float.

```csharp
public sealed class TiffFloatType : TiffCommonArrayType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffFloatType](tifffloattype/#constructor)(TiffTags) | ينشئ مثيلاً جديداً من الفئة `TiffFloatType`. |
| [TiffFloatType](tifffloattype/#constructor_1)(ushort) | ينشئ مثيلاً جديداً من الفئة `TiffFloatType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count/) { get; } | يحصل على عدد العناصر. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/tagtype/) { get; } | يحصل على نوع الوسم. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/values/) { get; set; } | يحصل أو يعيّن القيم. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/valuescontainer/) { get; } | يحصل على حاوية القيم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

### انظر أيضًا

* class [TiffCommonArrayType](../tiffcommonarraytype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


