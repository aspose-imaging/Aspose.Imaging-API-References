---
title: "TiffStreamReader.ReadUShortArray"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffStreamReader. تقرأ مصفوفة من القيم الصحيحة غير الموقعة من الدفق"
type: docs
weight: 260
url: /ar/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
## TiffStreamReader.ReadUShortArray method

يقرأ مصفوفة من قيم unsigned integer من الدفق.

```csharp
public ushort[] ReadUShortArray(long position, long count)
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
| ArgumentOutOfRangeException | count;عدد البايتات الإجمالي سالب. + count + x2= + totalBytes |

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


