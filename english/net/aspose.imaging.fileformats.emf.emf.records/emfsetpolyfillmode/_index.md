---
title: Class EmfSetPolyFillMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetPolyFillMode class. The EMR_SETPOLYFILLMODE record defines polygon fill mode
type: docs
weight: 4580
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
## EmfSetPolyFillMode class

The EMR_SETPOLYFILLMODE record defines polygon fill mode.

```csharp
public sealed class EmfSetPolyFillMode : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor)() | Initializes a new instance of the `EmfSetPolyFillMode` class. |
| [EmfSetPolyFillMode](emfsetpolyfillmode/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSetPolyFillMode` class. |

## Properties

| Name | Description |
| --- | --- |
| [PolygonFillMode](../../aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/polygonfillmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and MUST be in the PolygonFillMode (section 2.1.27) enumeration. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

In general, the modes differ only in cases where a complex, overlapping polygon MUST be filled; for example, a five-sided polygon that forms a five-pointed star with a pentagon in the center. In such cases, ALTERNATE mode SHOULD fill every other enclosed region within the polygon (the points of the star), but WINDING mode SHOULD fill all regions (the points of the star and the pentagon). When the fill mode is ALTERNATE, the area between odd-numbered and even-numbered polygon sides on each scan line SHOULD be filled. That is, the area between the first and second side SHOULD be filled, and between the third and fourth side, and so on. When the fill mode is WINDING, any region that has a nonzero winding value SHOULD be filled. The winding value is the number of times a pen used to draw the polygon would go around the region. The direction of each edge of the polygon is significant.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


