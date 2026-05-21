---
title: "TiffStreamReader.ReadUIntArray"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffStreamReader. تقرأ مصفوفة من القيم الصحيحة غير الموقعة من الدفق"
type: docs
weight: 220
url: /ar/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readuintarray/
---
## TiffStreamReader.ReadUIntArray method

يقرأ مصفوفة من قيم unsigned integer من الدفق.

```csharp
public uint[] ReadUIntArray(long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع | Int64 | الموضع للقراءة منه. |
| count | Int64 | عدد العناصر. |

### قيمة الإرجاع

المصفوفة التي تحتوي على قيم صحيحة غير موقعة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | count;عدد البايتات الكلي سالب. + count + x4= + totalBytes |

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


