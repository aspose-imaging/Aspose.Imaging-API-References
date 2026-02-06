---
title: Class WmfDeviceIndependentBitmap
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeviceIndependentBitmap class. The DeviceIndependentBitmap Object defines an image in deviceindependent bitmap DIB format
type: docs
weight: 8760
url: /net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
## WmfDeviceIndependentBitmap class

The DeviceIndependentBitmap Object defines an image in device-independent bitmap (DIB) format

```csharp
public class WmfDeviceIndependentBitmap : MetaObject
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfDeviceIndependentBitmap](wmfdeviceindependentbitmap/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/adata/) { get; set; } | Gets or sets an array of bytes that define the image. The size and format of this data is determined by information in the DIBHeaderInfo field. |
| [CachedImage](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/cachedimage/) { get; set; } | Gets or sets the cached raster image. |
| [ColorsData](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/colorsdata/) { get; set; } | Gets or sets an optional array of either RGBQuad Objects (section 2.2.2.20) or 16-bit unsigned integers that define a color table. The size and contents of this field SHOULD be determined from the metafile record or object that contains this DeviceIndependentBitmap and from information in the DIBHeaderInfo field. See ColorUsage Enumeration (section 2.1.1.6) and BitCount Enumeration (section 2.1.1.3) for additional details |
| [Header](../../aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/header/) { get; set; } | Gets or sets either a BitmapCoreHeader Object (section 2.2.2.2) or a BitmapInfoHeader Object (section 2.2.2.3) that specifies information about the image |

### See Also

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


