---
title: "الفئة TiffASCIIType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffASCIIType. نوع Tiff ASCII"
type: docs
weight: 8060
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
## TiffASCIIType class

نوع tiff ascii.

```csharp
public sealed class TiffASCIIType : TiffDataType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffASCIIType](tiffasciitype/#constructor)(TiffTags) | يقوم بتهيئة نسخة جديدة من الفئة `TiffASCIIType`. |
| [TiffASCIIType](tiffasciitype/#constructor_1)(ushort) | يقوم بتهيئة نسخة جديدة من الفئة `TiffASCIIType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/count/) { get; } | يحصل على عدد العناصر. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/tagtype/) { get; } | يحصل على نوع الوسم. |
| [Text](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/text/) { get; set; } | يحصل أو يضبط النص. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

### انظر أيضًا

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


