---
title: RasterImage.GetModifyDate
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Gets the DateTime value the image was last modified
type: docs
weight: 360
url: /net/aspose.imaging/rasterimage/getmodifydate/
---
## RasterImage.GetModifyDate method

Gets the DateTime value the image was last modified.

```csharp
public virtual DateTime GetModifyDate(bool useDefault)
```

| Parameter | Type | Description |
| --- | --- | --- |
| useDefault | Boolean | If value is to `true`, it returns LastWriteTimeUtc of the image source file. Otherwise, it tries to parse it from [`XmpData`](../../image/xmpdata/) or [`ExifData`](../../image/exifdata/). |

### Return Value

DateTime or MinValue in case the value is absent or a parsing error occured.

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


