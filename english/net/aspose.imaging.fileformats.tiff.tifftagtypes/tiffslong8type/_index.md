---
title: Class TiffSLong8Type
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffSLong8Type class. The Tiff unsigned 64bit type
type: docs
weight: 8170
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
## TiffSLong8Type class

The Tiff unsigned 64-bit type.

```csharp
public class TiffSLong8Type : TiffCommonArrayType
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffSLong8Type](tiffslong8type/#constructor)(TiffTags) | Initializes a new instance of the `TiffSLong8Type` class. |
| [TiffSLong8Type](tiffslong8type/#constructor_1)(ushort) | Initializes a new instance of the `TiffSLong8Type` class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count/) { get; } | Gets the count of elements. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | Gets the tag value size. |
| override [ElementSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/elementsize/) { get; } | Gets size of element. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | Gets tag id as number. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | Gets the tag id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/tagtype/) { get; } | Gets the tag type. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/value/) { get; set; } | Gets or sets the value this data type contains. |
| [Values](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/values/) { get; set; } | Gets or sets the values. |
| override [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/valuescontainer/) { get; } | Gets the values container. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | Performs a deep clone of this instance. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | Returns a String that represents this instance. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/writeadditionaldata/)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* class [TiffCommonArrayType](../tiffcommonarraytype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


