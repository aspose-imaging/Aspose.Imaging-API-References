---
title: Class EmfPlusPath
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPath class. The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The order for Bezier data points is the start point control point 1 control point 2 and end point.For more information seeMSDN  DrawBeziers
type: docs
weight: 5730
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
## EmfPlusPath class

The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The order for Bezier data points is the start point, control point 1, control point 2, and end point.For more information see[MSDN - DrawBeziers].

```csharp
public sealed class EmfPlusPath : EmfPlusGraphicsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPath](emfpluspath/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [PathPointFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointflags/) { get; set; } | Gets or sets Path points count A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object |
| [PathPoints](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints/) { get; set; } | Gets or sets array of path points An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field, as follows: If the P flag is set, the points are relative locations that are specified by EmfPlusPointR objects (section 2.2.2.37). If the P flag is clear and the C flag is set, the points are absolute locations that are specified by EmfPlusPoint objects (section 2.2.2.35). If the P flag is clear and the C flag is clear, the points are absolute locations that are specified by EmfPlusPointF objects (section 2.2.2.36). |
| [PathPointTypes](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpointtypes/) { get; set; } | Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. The type of objects in this array is specified by the R flag in the PathPointFlags field |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version/) { get; set; } | Gets or sets the version. |

### See Also

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


