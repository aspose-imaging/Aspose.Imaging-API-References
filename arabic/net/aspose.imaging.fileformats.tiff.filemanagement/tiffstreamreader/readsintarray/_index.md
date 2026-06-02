---
title: "TiffStreamReader.ReadSIntArray"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffStreamReader. تقرأ مصفوفة من قيم العدد الصحيح الموقعة من الدفق"
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readsintarray/
---
## TiffStreamReader.ReadSIntArray method

يقرأ مصفوفة من قيم signed integer من الدفق.

```csharp
public int[] ReadSIntArray(long position, long count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الموضع | Int64 | الموضع للقراءة منه. |
| count | Int64 | عدد العناصر. |

### قيمة الإرجاع

مصفوفة قيم العدد الصحيح الموقعة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | count;عدد البايتات الكلي سالب. + count + x4= + totalBytes |

### انظر أيضًا

* class [TiffStreamReader](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* assembly [Aspose.Imaging](../../../)


