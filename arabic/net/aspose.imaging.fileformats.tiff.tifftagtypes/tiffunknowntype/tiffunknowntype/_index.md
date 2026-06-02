---
title: "TiffUnknownType.TiffUnknownType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ TiffUnknownType. يهيئ مثيلاً جديداً من فئة TiffUnknownType"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tiffunknowntype/
---
## TiffUnknownType constructor

ينشئ مثيلاً جديداً من الفئة [`TiffUnknownType`](../).

```csharp
public TiffUnknownType(TiffStreamReader stream, ushort tagType, ushort tagId, ulong count, 
    ulong offsetOrValue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | TiffStreamReader | الدفق للقراءة منه. |
| tagType | UInt16 | نوع العلامة. |
| tagId | UInt16 | معرف العلامة. |
| count | UInt64 | قيمة العد. |
| offsetOrValue | UInt64 | الإزاحة أو القيمة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| InvalidDataException | قيمة علامة Tiff تتجاوز طول البيانات. |

### انظر أيضًا

* class [TiffStreamReader](../../../aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/)
* class [TiffUnknownType](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../tiffunknowntype/)
* assembly [Aspose.Imaging](../../../)


