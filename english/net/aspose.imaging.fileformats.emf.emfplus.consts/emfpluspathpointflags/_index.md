---
title: Enum EmfPlusPathPointFlags
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPathPointFlags enum. A 32bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object. C 1 bit If set the PathPoints array specifies absolute locations in the coordinate space with 16bit integer coordinates. If clear the PathPoints array specifies absolute locations in the coordinate space with 32bit floatingpoint coordinates. Note If the P flag below is set this flag MAY be clear and MUST be ignored. R 1 bit If set the point types in the PathPointTypes array are specified by EmfPlusPathPointTypeRle objects section 2.2.2.32 which use runlength encoding RLE compression and/or EmfPlusPathPointType objects section 2.2.2.31. See MSWMF section 3.1.6 for more information on RLE compression. If clear the point types in the PathPointTypes array are specified by EmfPlusPathPointType objects. P 1 bit If set each element in the PathPoints array specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PathPoints a previous location at coordinates 00 is assumed. If clear each element in the PathPoints array specifies an absolute location
type: docs
weight: 5080
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object. C (1 bit): If set, the PathPoints array specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, the PathPoints array specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag MAY be clear and MUST be ignored. R (1 bit): If set, the point types in the PathPointTypes array are specified by EmfPlusPathPointTypeRle objects (section 2.2.2.32), which use run-length encoding (RLE) compression, and/or EmfPlusPathPointType objects (section 2.2.2.31). See [MS-WMF] section 3.1.6 for more information on RLE compression. If clear, the point types in the PathPointTypes array are specified by EmfPlusPathPointType objects. P (1 bit): If set, each element in the PathPoints array specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PathPoints, a previous location at coordinates (0,0) is assumed. If clear, each element in the PathPoints array specifies an absolute location.

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| C | `4000` | The c flag |
| R | `1000` | The r flag |
| P | `800` | The p flag |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


