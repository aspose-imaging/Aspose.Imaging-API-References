---
title: TiffOptions.ColorMap
second_title: Aspose.Imaging for .NET API Reference
description: TiffOptions property. Gets or sets the color map
type: docs
weight: 70
url: /net/aspose.imaging.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Gets or sets the color map.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

The color map.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | value |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | The color map may be defined for samples per pixel equal to 1 only. or The bits per sample are not defined. |
| ArgumentOutOfRangeException | value;The array length must correspond to the followign formula: 3 * (2**BitsPerSample). |

### See Also

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


