---
title: Class TiffCommonArrayType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.TiffTagTypes.TiffCommonArrayType class. The tiff common array type
type: docs
weight: 8080
url: /net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/
---
## TiffCommonArrayType class

The tiff common array type.

```csharp
public abstract class TiffCommonArrayType : TiffDataType
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/count/) { get; } | Gets the count of elements. |
| virtual [DataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/datasize/) { get; } | Gets the tag value size. |
| virtual [ElementSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/elementsize/) { get; } | Gets the element size in bytes. |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id/) { get; } | Gets tag id as number. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Gets a value indicating whether tag data is valid. The valid tag contains data which may be preserved. The invalid tag cannot be stored. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid/) { get; } | Gets the tag id. |
| abstract [TagType](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Gets the tag type. |
| abstract [Value](../../aspose.imaging.fileformats.tiff/tiffdatatype/value/) { get; set; } | Gets or sets the value this data type contains. |
| abstract [ValuesContainer](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/valuescontainer/) { get; } | Gets the values container. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto/)(object) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone/)() | Performs a deep clone of this instance. |
| virtual [GetAdditionalDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getadditionaldatasize/)(byte) | Gets the additional tag value size in bytes (in case the tag can not fit the whole tag value). |
| [GetAlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/getaligneddatasize/)(byte) | Gets the data size aligned in 4-byte (int) or 8-byte (long) boundary. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring/)() | Returns a String that represents this instance. |
| abstract [WriteAdditionalData](../../aspose.imaging.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Writes the additional tag data. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Writes the tag data. |

### See Also

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* namespace [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes/)
* assembly [Aspose.Imaging](../../)


