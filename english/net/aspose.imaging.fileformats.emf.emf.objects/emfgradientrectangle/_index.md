---
title: Class EmfGradientRectangle
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfGradientRectangle class. The GradientRectangle object defines a rectangle using TriVertex objects section 2.2.26 in an EMR_GRADIENTFILL record section 2.3.5.12
type: docs
weight: 3060
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
## EmfGradientRectangle class

The GradientRectangle object defines a rectangle using TriVertex objects (section 2.2.26) in an EMR_GRADIENTFILL record (section 2.3.5.12).

```csharp
public sealed class EmfGradientRectangle : EmfObject
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfGradientRectangle](emfgradientrectangle/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [LowerRight](../../aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/lowerright/) { get; set; } | Gets or sets an index into an array of TriVertex objects that specifies the lower-right vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR_GRADIENTFILL record. |
| [UpperLeft](../../aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/upperleft/) { get; set; } | Gets or sets an index into an array of TriVertex objects that specifies the upper-left vertex of a rectangle. The index MUST be smaller than the size of the array, as defined by the nVer field of the EMR_GRADIENTFILL record. |

### See Also

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


