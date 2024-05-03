---
title: ISvgResourceKeeperCallback.OnImageResourceReady
second_title: Aspose.Imaging for .NET API Reference
description: ISvgResourceKeeperCallback method. Called when the image resource is ready for export
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/onimageresourceready/
---
## ISvgResourceKeeperCallback.OnImageResourceReady method

Called when the image resource is ready for export.

```csharp
public string OnImageResourceReady(byte[] imageData, SvgImageType imageType, 
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
* interface [ISvgResourceKeeperCallback](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../isvgresourcekeepercallback/)
* assembly [Aspose.Imaging](../../../)


