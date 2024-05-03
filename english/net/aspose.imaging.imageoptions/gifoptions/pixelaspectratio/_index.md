---
title: GifOptions.PixelAspectRatio
second_title: Aspose.Imaging for .NET API Reference
description: GifOptions property. Gets or sets the GIF pixel aspect ratio
type: docs
weight: 120
url: /net/aspose.imaging.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Gets or sets the GIF pixel aspect ratio.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

The GIF pixel aspect ratio.

## Remarks

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

### See Also

* class [GifOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../gifoptions/)
* assembly [Aspose.Imaging](../../../)


