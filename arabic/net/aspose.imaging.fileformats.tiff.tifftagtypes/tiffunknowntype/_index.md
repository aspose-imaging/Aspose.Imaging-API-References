---
title: TiffUnknownType
second_title: Aspose.Imaging لمرجع NET API
description: نوع tiff غير معروف. في حالة تعذر التعرف على علامة tiff  يتم إنشاء هذا النوع.
type: docs
weight: 8050
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

نوع tiff غير معروف. في حالة تعذر التعرف على علامة tiff ، يتم إنشاء هذا النوع.

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TiffUnknownType](tiffunknowntype)(TiffStreamReader, ushort, ushort, uint, uint) | يقوم بتهيئة مثيل جديد لملف[`TiffUnknownType`](../tiffunknowntype) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة) . |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count) { get; } | يحصل على عدد العناصر . |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/datasize) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة) . |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | يحصل على تمثيل صحيح لمعرف العلامة . |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. تحتوي العلامة الصالحة على بيانات يمكن الاحتفاظ بها. لا يمكن تخزين العلامة غير الصالحة. |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue) { get; } | الحصول على قيمة الإزاحة لبيانات إضافية أو القيمة نفسها في حالة كان عدد الحالات 1. |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream) { get; } | الحصول على الدفق لقراءة البيانات الإضافية منه . |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | يحصل على معرف العلامة . |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype) { get; } | يحصل على نوع العلامة . |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value) { get; set; } | الحصول على القيمة التي يحتوي عليها نوع البيانات هذا أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | يقارن المثيل الحالي بكائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يحدث في نفس الموضع في ترتيب الفرز مثل الكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | يقوم بعمل نسخة عميقة من هذا المثيل. |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata)(TiffStreamWriter) | يكتب بيانات العلامة الإضافية . |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | يكتب بيانات العلامة . |

### ملاحظات

لاحظ ال[`TiffUnknownType`](../tiffunknowntype) لم يتم تسلسلها مرة أخرى إلى البث.

### أنظر أيضا

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
