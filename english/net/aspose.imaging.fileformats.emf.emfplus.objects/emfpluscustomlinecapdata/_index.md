---
title: Class EmfPlusCustomLineCapData
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusCustomLineCapData class. The EmfPlusCustomLineCapData object specifies default data for a custom line cap
type: docs
weight: 5510
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
## EmfPlusCustomLineCapData class

The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

```csharp
public sealed class EmfPlusCustomLineCapData : EmfPlusCustomBaseLineCap
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusCustomLineCapData](emfpluscustomlinecapdata/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BaseCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/basecap/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) on which the custom line cap is based. |
| [BaseInset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/baseinset/) { get; set; } | Gets or sets 32-bit floating-point value that specifies the distance between the beginning of the line cap and the end of the line. |
| [CustomLineCapDataFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/customlinecapdataflags/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field |
| [FillHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/fillhotspot/) { get; set; } | Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| [OptionalData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/optionaldata/) { get; set; } | Gets or sets optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14) that specifies additional data for the custom graphics line cap. T he specific contents of this field are determined by the value of the CustomLineCapDataFlags field. |
| [StrokeEndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokeendcap/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what line cap is to be used at the end of the line to be drawn. |
| [StrokeHotSpot](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokehotspot/) { get; set; } | Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to {0.0, 0.0}. |
| [StrokeJoin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokejoin/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration (section 2.1.1.19), which specifies how to join two lines that are drawn by the same pen and whose ends meet. At the intersection of the two line ends, a line join makes the connection look more continuous. |
| [StrokeMiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokemiterlimit/) { get; set; } | Gets or sets 32-bit floating-point value that contains the limit of the thickness of the join on a mitered corner by setting the maximum allowed ratio of miter length to line width. |
| [StrokeStartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/strokestartcap/) { get; set; } | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap used at the start of the line to be drawn |
| [WidthScale](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/widthscale/) { get; set; } | Gets or sets 32-bit floating-point value that specifies the amount by which to scale the custom line cap with respect to the width of the EmfPlusPen object (section 2.2.1.7) that is used to draw the lines. |

### See Also

* class [EmfPlusCustomBaseLineCap](../emfpluscustombaselinecap/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


