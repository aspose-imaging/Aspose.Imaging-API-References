---
title: Class EmfPlusPenData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenData class. The EmfPlusPenData object specifies properties of a graphics pen
type: docs
weight: 5790
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
## EmfPlusPenData class

The EmfPlusPenData object specifies properties of a graphics pen.

```csharp
public sealed class EmfPlusPenData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPenData](emfpluspendata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/optionaldata/) { get; set; } | Gets or sets optional EmfPlusPenOptionalData object (section 2.2.2.34) that specifies additional data for the pen object. The specific contents of this field are determined by the value of the PenDataFlags field. |
| [PenDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/pendataflags/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of PenData flags (section 2.1.2.7). |
| [PenUnit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penunit/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the measuring units for the pen. The value MUST be from the UnitType enumeration (section 2.1.1.33). |
| [PenWidth](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/penwidth/) { get; set; } | Gets or sets 32-bit floating-point value that specifies the width of the line drawn by the pen in the units specified by the PenUnit field. If a zero width is specified, a minimum value is used, which is determined by the units |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


