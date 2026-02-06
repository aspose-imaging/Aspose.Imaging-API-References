---
title: Class EmfRegionDataHeader
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfRegionDataHeader class. The RegionDataHeader object describes the properties of a RegionData object
type: docs
weight: 3240
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
## EmfRegionDataHeader class

The RegionDataHeader object describes the properties of a RegionData object.

```csharp
public sealed class EmfRegionDataHeader : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfRegionDataHeader](emfregiondataheader/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19), which specifies the bounds of the region. |
| [CountRects](../../aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/countrects/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of rectangles in this region. |
| [RgnSize](../../aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/rgnsize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of the buffer of rectangles in bytes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of this object in bytes. This MUST be 0x00000020. |
| [Type](../../aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/type/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the region type. This SHOULD be RDH_RECTANGLES (0x00000001). |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


