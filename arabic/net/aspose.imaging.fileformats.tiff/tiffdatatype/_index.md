---
title: TiffDataType
second_title: Aspose.Imaging لمرجع NET API
description: نوع بيانات tiff .
type: docs
weight: 7850
url: /ar/net/aspose.imaging.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

نوع بيانات tiff .

```csharp
public abstract class TiffDataType : IComparable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة) . |
| abstract [Count](../../aspose.imaging.fileformats.tiff/tiffdatatype/count) { get; } | يحصل على عدد العناصر . |
| abstract [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize) { get; } | الحصول على حجم البيانات الإضافي بالبايت (في حالة عدم كفاية 12 بايت لملاءمة بيانات العلامة) . |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | يحصل على تمثيل صحيح لمعرف العلامة . |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. تحتوي العلامة الصالحة على بيانات يمكن الاحتفاظ بها. لا يمكن تخزين العلامة غير الصالحة. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | يحصل على معرف العلامة . |
| abstract [TagType](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagtype) { get; } | يحصل على نوع العلامة . |
| abstract [Value](../../aspose.imaging.fileformats.tiff/tiffdatatype/value) { get; set; } | الحصول على القيمة التي يحتوي عليها نوع البيانات هذا أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ReadTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/readtag)(TiffStreamReader, long) | يقرأ بيانات العلامة . |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | يقارن المثيل الحالي بكائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يحدث في نفس الموضع في ترتيب الفرز مثل الكائن الآخر. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | يقوم بعمل نسخة عميقة من هذا المثيل. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| abstract [WriteAdditionalData](../../aspose.imaging.fileformats.tiff/tiffdatatype/writeadditionaldata)(TiffStreamWriter) | يكتب بيانات العلامة الإضافية . |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | يكتب بيانات العلامة . |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
