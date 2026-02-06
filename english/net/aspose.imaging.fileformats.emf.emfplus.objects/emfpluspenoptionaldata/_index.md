---
title: Class EmfPlusPenOptionalData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPenOptionalData class. The EmfPlusPenOptionalData object specifies optional data for a graphics pen
type: docs
weight: 5800
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

The EmfPlusPenOptionalData object specifies optional data for a graphics pen

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata/) { get; set; } | Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) that specifies an array of floating-point values that define the compound line of a pen, which is made up of parallel lines and spaces. This field MUST be present if the PenDataCompoundLine flag is set in the PenDataFlags field of the EmfPlusPenData object |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata/) { get; set; } | Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) that defines the custom end-cap shape, which is the shape to use at the end of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata/) { get; set; } | Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) that defines the custom start-cap shape, which is the shape to use at the start of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype/) { get; set; } | Gets or sets optional 32-bit signed integer that specifies the shape for both ends of each dash in a dashed line. This field MUST be present if the PenDataDashedLineCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the DashedLineCapType enumeration (section 2.1.1.10). |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata/) { get; set; } | Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) that specifies the lengths of dashes and spaces in a custom dashed line. This field MUST be present if the PenDataDashedLine flag is set in the PenDataFlags field of the EmfPlusPenData object. |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset/) { get; set; } | Gets or sets optional 32-bit floating-point value that specifies the distance from the start of a line to the start of the first space in a dashed line pattern. This field MUST be present if the PenDataDashedLineOffset flag is set in the PenDataFlags field of the EmfPlusPenData object. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap/) { get; set; } | Gets or sets optional 32-bit signed integer that specifies the shape for the end of a line in the CustomEndCapData field. This field MUST be present if the PenDataEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join/) { get; set; } | Gets or sets an optional 32-bit signed integer that specifies how to join two lines that are drawn by the same pen and whose ends meet. This field MUST be present if the PenDataJoin flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineJoinType enumeration (section 2.1.1.19). |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle/) { get; set; } | Gets or sets optional 32-bit signed integer that specifies the style used for lines drawn with this pen object. This field MUST be present if the PenDataLineStyle flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineStyle enumeration (section 2.1.1.20). |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit/) { get; set; } | Gets or sets optional 32-bit floating-point value that specifies the miter limit, which is the maximum allowed ratio of miter length to line width. The miter length is the distance from the intersection of the line walls on the inside the join to the intersection of the line walls outside the join. The miter length can be large when the angle between two lines is small. This field MUST be present if the PenDataMiterLimit flag is set in the PenDataFlags field of the EmfPlusPenData object. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment/) { get; set; } | Gets or sets optional 32-bit signed integer that specifies the distribution of the pen width with respect to the coordinates of the line being drawn. This field MUST be present if the PenDataNonCenter flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the PenAlignment enumeration (section 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap/) { get; set; } | Gets or sets an optional 32-bit signed integer that specifies the shape for the start of a line in the CustomStartCapData field. This field MUST be present if the PenDataStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration (section 2.1.1.18). |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix/) { get; set; } | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the pen. This field MUST be present if the PenDataTransform flag is set in the PenDataFlags field of the EmfPlusPenData object. |

### See Also

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


