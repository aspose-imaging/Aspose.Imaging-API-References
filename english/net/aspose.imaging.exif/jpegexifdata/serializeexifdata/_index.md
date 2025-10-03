---
title: JpegExifData.SerializeExifData
second_title: Aspose.Imaging for .NET API Reference
description: JpegExifData method. Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents
type: docs
weight: 240
url: /net/aspose.imaging.exif/jpegexifdata/serializeexifdata/
---
## JpegExifData.SerializeExifData method

Serializes the EXIF data. Writes the tags values and contents. The most influencing size tag is Thumbnail tag contents.

```csharp
public byte[] SerializeExifData()
```

### Return Value

The serialized EXIF data.

## Remarks

The overall segment size must be less than or equal to MaxExifSegmentSize bytes in order to produce correct jpeg image. Hint: try to reduce the thumbnail size or change its compression in case you have too big EXIF section size.

### See Also

* class [JpegExifData](../)
* namespace [Aspose.Imaging.Exif](../../jpegexifdata/)
* assembly [Aspose.Imaging](../../../)


