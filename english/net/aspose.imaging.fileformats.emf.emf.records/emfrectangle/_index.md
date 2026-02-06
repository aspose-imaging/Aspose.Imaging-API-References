---
title: Class EmfRectangle
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle class. The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush
type: docs
weight: 4280
url: /net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
## EmfRectangle class

The EMR_RECTANGLE record draws a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush.

```csharp
public sealed class EmfRectangle : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfRectangle](emfrectangle/#constructor)() | Initializes a new instance of the `EmfRectangle` class. |
| [EmfRectangle](emfrectangle/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfRectangle` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfrectangle/box/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive rectangle to draw. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The current position is neither used nor updated by Rectangle. If a PS_NULL pen is used, the dimensions of the rectangle are 1 pixel less in height and 1 pixel less in width.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


