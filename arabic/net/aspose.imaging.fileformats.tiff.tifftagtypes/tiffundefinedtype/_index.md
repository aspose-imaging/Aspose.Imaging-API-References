---
title: "الفئة TiffUndefinedType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffUndefinedType الفئة. نوع tiff غير معرف"
type: docs
weight: 8220
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
## TiffUndefinedType class

نوع tiff undefined.

```csharp
public class TiffUndefinedType : TiffDataType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffUndefinedType](tiffundefinedtype/#constructor)(TiffTags) | ينشئ مثيلاً جديداً من الفئة `TiffUndefinedType`. |
| [TiffUndefinedType](tiffundefinedtype/#constructor_1)(ushort) | ينشئ مثيلاً جديداً من الفئة `TiffUndefinedType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/count/) { get; } | يحصل على عدد العناصر. |
| [Data](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/data/) { get; set; } | يسترجع أو يعيّن البيانات. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/tagtype/) { get; } | يحصل على نوع الوسم. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

### انظر أيضًا

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


