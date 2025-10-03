---
title: TiffImage.NormalizeAngle
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans ensuring accurate alignment. Seamlessly integrate this functionality into your text processing workflows to enhance document readability and quality improving overall efficiency in text recognition and analysis tasks. This method uses GetSkewAngle and Rotate methods
type: docs
weight: 290
url: /net/aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/
---
## TiffImage.NormalizeAngle method

Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans, ensuring accurate alignment. Seamlessly integrate this functionality into your text processing workflows to enhance document readability and quality, improving overall efficiency in text recognition and analysis tasks. This method uses [`GetSkewAngle`](../../../aspose.imaging/rasterimage/getskewangle/) and [`Rotate`](../rotate/) methods.

```csharp
public override void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | Color | Color of the background. |

### See Also

* struct [Color](../../../aspose.imaging/color/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


