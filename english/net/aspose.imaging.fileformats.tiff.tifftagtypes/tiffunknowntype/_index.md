---
title: Class TiffUnknownType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffUnknownType class. The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated
type: docs
weight: 8230
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffUnknownType](tiffunknowntype/)(TiffStreamReader, ushort, ushort, ulong, ulong) | Initializes a new instance of the `TiffUnknownType` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count/) { get; } | Gets the count of elements. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | Gets the tag value size. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | Gets the element size in bytes. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | Gets tag id as number. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue/) { get; } | Gets the offset value for an additional data or value itself in case count is 1. |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream/) { get; } | Gets the stream to read additional data from. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | Gets the tag id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype/) { get; } | Gets the tag type. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value/) { get; set; } | Gets or sets the value this data type contains. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | Performs a deep clone of this instance. |
| override [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/getadditionaldatasize/)(byte) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring/)() | Returns a String that represents this instance. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata/)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Writes the tag data. |

## Remarks

Note the `TiffUnknownType` is not serialized back to stream.

### See Also

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


