---
title: ReadSLongArray
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 140
url: /net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
## TiffStreamReader.ReadSLongArray method

Reads an array of signed integer values from the stream.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| position | Int64 | The position to read from. |
| count | Int64 | The elements count. |

### Return Value

The array of signed integer values.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | count;Total bytes count is negative. + count + x4= + totalBytes |

### See Also

* class [TiffStreamReader](../../tiffstreamreader)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamreader)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
