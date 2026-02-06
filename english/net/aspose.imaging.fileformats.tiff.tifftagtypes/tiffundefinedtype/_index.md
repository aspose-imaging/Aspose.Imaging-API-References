---
title: Class TiffUndefinedType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffUndefinedType class. The tiff undefined type
type: docs
weight: 8220
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/
---
## TiffUndefinedType class

The tiff undefined type.

```csharp
public class TiffUndefinedType : TiffDataType
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffUndefinedType](tiffundefinedtype/#constructor)(TiffTags) | Initializes a new instance of the `TiffUndefinedType` class. |
| [TiffUndefinedType](tiffundefinedtype/#constructor_1)(ushort) | Initializes a new instance of the `TiffUndefinedType` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/count/) { get; } | Gets the count of elements. |
| [Data](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/data/) { get; set; } | Gets or sets the data. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | Gets the tag value size. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | Gets the element size in bytes. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | Gets tag id as number. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | Gets the tag id. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/tagtype/) { get; } | Gets the tag type. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/value/) { get; set; } | Gets or sets the value this data type contains. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | Performs a deep clone of this instance. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | Returns a String that represents this instance. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffundefinedtype/writeadditionaldata/)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


