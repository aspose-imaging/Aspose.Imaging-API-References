---
title: TgaImage.Rotate
second_title: Aspose.Imaging for .NET API Reference
description: TgaImage method. Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation ensuring that the rotation maintains visual balance and consistency with the specified background color. Its ideal for tasks where accurate rotation around the center is necessary such as orientation correction or artistic adjustments
type: docs
weight: 350
url: /net/aspose.imaging.fileformats.tga/tgaimage/rotate/
---
## TgaImage.Rotate method

Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation, ensuring that the rotation maintains visual balance and consistency with the specified background color. It's ideal for tasks where accurate rotation around the center is necessary, such as orientation correction or artistic adjustments.

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
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


