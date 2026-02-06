---
title: Class EmfExtFloodFill
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtFloodFill class. The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush
type: docs
weight: 3750
url: /net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---
## EmfExtFloodFill class

The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

```csharp
public sealed class EmfExtFloodFill : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfExtFloodFill](emfextfloodfill/)(EmfRecord) | Initializes a new instance of the `EmfExtFloodFill` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/argb32color/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8), which is used with the FloodFillMode to determine the area to fill. |
| [FloodFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/floodfillmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to use the Color value to determine the area for the flood fill operation. The value MUST be in the FloodFill enumeration (section 2.1.13). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/start/) { get; set; } | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15), which specifies the coordinates, in logical units, where filling begins. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


