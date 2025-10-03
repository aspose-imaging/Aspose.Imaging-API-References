---
title: WebPImage.Rotate
second_title: Aspose.Imaging for .NET API Reference
description: WebPImage method. Rotate the image around its center by a specified angle while proportionally resizing it and applying specified background color parameters. Incorporate this method into your image processing workflow to achieve precise transformations with customizable background colors ensuring optimal visual presentation within your application
type: docs
weight: 260
url: /net/aspose.imaging.fileformats.webp/webpimage/rotate/
---
## WebPImage.Rotate method

Rotate the image around its center by a specified angle, while proportionally resizing it and applying specified background color parameters. Incorporate this method into your image processing workflow to achieve precise transformations with customizable background colors, ensuring optimal visual presentation within your application.

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
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


