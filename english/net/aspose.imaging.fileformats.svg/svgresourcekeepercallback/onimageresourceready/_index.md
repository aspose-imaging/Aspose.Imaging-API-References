---
title: SvgResourceKeeperCallback.OnImageResourceReady
second_title: Aspose.Imaging for .NET API Reference
description: SvgResourceKeeperCallback method. Called when the image resource is ready for export
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.svg/svgresourcekeepercallback/onimageresourceready/
---
## SvgResourceKeeperCallback.OnImageResourceReady method

Called when the image resource is ready for export.

```csharp
public virtual string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
    string suggestedFileName, ref bool useEmbeddedImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageData | Byte[] | The resource data. |
| imageType | SvgImageType | Type of the image. |
| suggestedFileName | String | Name of the suggested file. |
| useEmbeddedImage | Boolean& | if set to `true` the embedded image must be used. |

### Return Value

Returns the path to the saved resource. Path should be relative to target SVG document.

### See Also

* enum [SvgImageType](../../svgimagetype/)
* class [SvgResourceKeeperCallback](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgresourcekeepercallback/)
* assembly [Aspose.Imaging](../../../)


