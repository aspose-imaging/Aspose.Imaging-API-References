---
title: TiffUnknownType.TiffUnknownType
second_title: Aspose.Imaging for .NET API Reference
description: TiffUnknownType constructor. Initializes a new instance of the TiffUnknownType class
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tiffunknowntype/
---
## TiffUnknownType constructor

Initializes a new instance of the [`TiffUnknownType`](../) class.

```csharp
public TiffUnknownType(TiffStreamReader stream, ushort tagType, ushort tagId, ulong count, 
    ulong offsetOrValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | TiffStreamReader | The stream to read from. |
| tagType | UInt16 | Type of the tag. |
| tagId | UInt16 | The tag id. |
| count | UInt64 | The count value. |
| offsetOrValue | UInt64 | The offset or value. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidDataException | Tiff tag value exceeds data length. |

### See Also

* class [TiffStreamReader](../../../aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/)
* class [TiffUnknownType](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../tiffunknowntype/)
* assembly [Aspose.Imaging](../../../)


