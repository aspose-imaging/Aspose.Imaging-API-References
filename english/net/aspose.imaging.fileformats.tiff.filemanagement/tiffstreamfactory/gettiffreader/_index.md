---
title: TiffStreamFactory.GetTiffReader
second_title: Aspose.Imaging for .NET API Reference
description: TiffStreamFactory method. Gets the tiff stream reader
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamfactory/gettiffreader/
---
## GetTiffReader(StreamContainer, TiffByteOrder, bool) {#gettiffreader}

Gets the tiff stream reader.

```csharp
public static TiffStreamReader GetTiffReader(StreamContainer stream, TiffByteOrder byteOrder, 
    bool isBigTiff = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | StreamContainer | The stream container. |
| byteOrder | TiffByteOrder | The byte order. |
| isBigTiff | Boolean | Indicates TIFF type. |

### Return Value

Tiff stream suitable for reading.

### See Also

* class [TiffStreamReader](../../tiffstreamreader/)
* class [StreamContainer](../../../aspose.imaging/streamcontainer/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)

---

## GetTiffReader(byte[], int, int, TiffByteOrder, bool) {#gettiffreader_1}

Gets the tiff stream reader.

```csharp
public static TiffStreamReader GetTiffReader(byte[] bytes, int bytesOffset, int dataLength, 
    TiffByteOrder byteOrder, bool isBigTiff = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | Byte[] | The bytes. |
| bytesOffset | Int32 | The bytes offset. |
| dataLength | Int32 | Length of the data. |
| byteOrder | TiffByteOrder | The byte order. |
| isBigTiff | Boolean | Indicates Tiff type: original or big. |

### Return Value

Tiff stream suitable for reading.

### See Also

* class [TiffStreamReader](../../tiffstreamreader/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffStreamFactory](../)
* namespace [Aspose.Imaging.FileFormats.Tiff.FileManagement](../../tiffstreamfactory/)
* assembly [Aspose.Imaging](../../../)


