---
title: "الفئة TiffUnknownType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffUnknownType الفئة. نوع tiff غير معروف. في حال عدم إمكانية التعرف على علامة tiff يتم إنشاء هذا النوع"
type: docs
weight: 8230
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

نوع tiff غير معروف. في حال عدم إمكانية التعرف على علامة tiff يتم إنشاء هذا النوع.

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffUnknownType](tiffunknowntype/)(TiffStreamReader, ushort, ushort, ulong, ulong) | ينشئ مثيلاً جديداً من الفئة `TiffUnknownType`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count/) { get; } | يحصل على عدد العناصر. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | يحصل على حجم قيمة الوسم. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | يحصل على حجم العنصر بالبايت. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | يحصل على معرف الوسم كرقم. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الوسم صالحة. الوسم الصالح يحتوي على بيانات يمكن حفظها. الوسم غير الصالح لا يمكن تخزينه. |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue/) { get; } | يحصل على قيمة الإزاحة لبيانات إضافية أو للقيمة نفسها في حال كان العدد 1. |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream/) { get; } | يحصل على الدفق لقراءة البيانات الإضافية منه. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | يحصل على معرف الوسم. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype/) { get; } | يحصل على نوع الوسم. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value/) { get; set; } | يحصل أو يعيّن القيمة التي يحتويها هذا النوع من البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | ينفّذ استنساخًا عميقًا لهذا المثيل. |
| override [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/getadditionaldatasize/)(byte) | يحصل على حجم قيمة الوسم الإضافية بالبايت (في حال عدم قدرة الوسم على احتواء القيمة الكاملة للوسم). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring/)() | يرجع سلسلة تمثل هذه الحالة. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata/)(TiffStreamWriter) | يكتب بيانات الوسم الإضافية. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | يكتب بيانات الوسم. |

## ملاحظات

ملاحظة أن `TiffUnknownType` لا يتم تسلسله مرة أخرى إلى الدفق.

### انظر أيضًا

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


