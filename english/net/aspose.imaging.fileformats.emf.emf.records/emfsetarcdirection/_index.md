---
title: Class EmfSetArcDirection
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetArcDirection class. The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output
type: docs
weight: 4390
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
## EmfSetArcDirection class

The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

```csharp
public sealed class EmfSetArcDirection : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetArcDirection](emfsetarcdirection/#constructor)() | Initializes a new instance of the `EmfSetArcDirection` class. |
| [EmfSetArcDirection](emfsetarcdirection/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSetArcDirection` class. |

## Properties

| Name | Description |
| --- | --- |
| [ArcDirection](../../aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/arcdirection/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the arc direction. The value MUST be in the ArcDirection enumeration (section 2.1.2). The default direction is counterclockwise. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The EMR_SETARCDIRECTION record affects the direction in which the following records draw: - EMR_ARC (section 2.3.5.2) - EMR_ARCTO (section 2.3.5.3) - EMR_CHORD (section 2.3.5.4) - EMR_ELLIPSE (section 2.3.5.5) - EMR_PIE (section 2.3.5.15) - EMR_RECTANGLE (section 2.3.5.34) - EMR_ROUNDRECT (section 2.3.5.35)

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


