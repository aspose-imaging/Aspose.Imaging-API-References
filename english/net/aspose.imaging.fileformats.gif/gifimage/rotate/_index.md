---
title: GifImage.Rotate
second_title: Aspose.Imaging for .NET API Reference
description: GifImage method. This method rotates the image around its center point. By specifying the rotation angle you can rotate the image clockwise or counterclockwise to achieve the desired orientation. This rotation helps adjust the images presentation or alignment without distorting its content
type: docs
weight: 390
url: /net/aspose.imaging.fileformats.gif/gifimage/rotate/
---
## GifImage.Rotate method

This method rotates the image around its center point. By specifying the rotation angle, you can rotate the image clockwise or counterclockwise to achieve the desired orientation. This rotation helps adjust the image's presentation or alignment without distorting its content.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| angle | Single | The rotate angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only `internal` image contents are rotated. |
| backgroundColor | Color | Color of the background. |

### See Also

* struct [Color](../../../aspose.imaging/color/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


