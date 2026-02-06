---
title: Class WmfBitmapCoreHeader
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Objects.WmfBitmapCoreHeader class. The BitmapCoreHeader Object contains information about the dimensions and color format of a deviceindependent bitmapDIB
type: docs
weight: 8640
url: /net/aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/
---
## WmfBitmapCoreHeader class

The BitmapCoreHeader Object contains information about the dimensions and color format of a device-independent bitmap(DIB).

```csharp
public class WmfBitmapCoreHeader : WmfBitmapBaseHeader
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfBitmapCoreHeader](wmfbitmapcoreheader/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. This value MUST be in the [`BitCount`](../wmfbitmapbaseheader/bitcount/) Enumeration (section 2.1.1.3). |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/height/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the height of the DIB, in pixels |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the number of planes for the target device. This value MUST be 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapcoreheader/width/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the width of the DIB, in pixels |

### See Also

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


