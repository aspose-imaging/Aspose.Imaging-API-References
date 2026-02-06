---
title: Class EmfPlusCustomLineCapOptionalData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusCustomLineCapOptionalData class. The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap
type: docs
weight: 5520
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
## EmfPlusCustomLineCapOptionalData class

The EmfPlusCustomLineCapOptionalData object specifies optional fill and outline data for a custom line cap.

```csharp
public sealed class EmfPlusCustomLineCapOptionalData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData](emfpluscustomlinecapoptionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [FillData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/filldata/) { get; set; } | Gets or sets optional EmfPlusFillPath object (section 2.2.2.17) that specifies the path for filling a custom graphics line cap. This field MUST be present if the CustomLineCapDataFillPath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object. |
| [OutlineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/outlinedata/) { get; set; } | Gets or sets optional EmfPlusLinePath object (section 2.2.2.26) that specifies the path for outlining a custom graphics line cap. This field MUST be present if the CustomLineCapDataLinePath flag is set in the CustomLineCapDataFlags field of the EmfPlusCustomLineCapData object. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


