---
title: Class EmfGradientFill
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfGradientFill class. The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color
type: docs
weight: 3860
url: /net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
## EmfGradientFill class

The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

```csharp
public sealed class EmfGradientFill : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfGradientFill](emfgradientfill/)(EmfRecord) | Initializes a new instance of the `EmfGradientFill` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies a bounding rectangle, in inclusive-inclusive device units. |
| [NTri](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ntri/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of rectangles or triangles to fill. |
| [NVer](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/nver/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of vertexes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UlMode](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/ulmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the gradient fill mode. The value MUST be in the GradientFill enumeration (section 2.1.15). |
| [VertexData](../../aspose.imaging.fileformats.emf.emf.records/emfgradientfill/vertexdata/) { get; set; } | Gets or sets objects that specify the vertexes of either rectangles or triangles and the colors that correspond to them. |

## Remarks

An EMR_GRADIENTFILL record that specifies that the three vertexes of a triangle SHOULD fill the figure with smooth gradients of colors.[85] An EMR_GRADIENTFILL record that specifies that the upper-left and lower-right vertexes of a rectangle SHOULD fill the figure with smooth gradients of color. There are two gradient fill modes in the GradientFill enumeration that can be used when drawing a rectangle. In GRADIENT_FILL_RECT_H mode, the rectangle is filled from left to right. In GRADIENT_FILL_RECT_V mode, the rectangle is filled from top to bottom. Note An EMR_GRADIENTFILL record MUST ignore the Alpha fields in the TriVertex objects. An EMR_ALPHABLEND record (section 2.3.1.1) that immediately follows the EMR_GRADIENTFILL record can be used to apply an alpha transparency gradient to the filled area.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


