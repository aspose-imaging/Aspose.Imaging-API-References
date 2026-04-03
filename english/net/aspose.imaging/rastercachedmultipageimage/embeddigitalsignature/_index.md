---
title: RasterCachedMultipageImage.EmbedDigitalSignature
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage method. Embed digital sign based on provided password into each page of the image
type: docs
weight: 240
url: /net/aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/
---
## RasterCachedMultipageImage.EmbedDigitalSignature method

Embed digital sign based on provided password into each page of the image.

```csharp
public override void EmbedDigitalSignature(string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | The password used for generate digital sign data |

### Exceptions

| exception | condition |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Thrown in any processing issues. |

## Examples

The example shows how to embed digital signature based on provided password into image pixel data.

```csharp
[C#]

var imageFilePath = "ball.png";
var password = "veryStr0ngPassword";
using (var image = Image.Load(imageFilePath))
{
    image.EmbedDigitalSignature(password);
    image.Save(outputPath);
}
```

### See Also

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


