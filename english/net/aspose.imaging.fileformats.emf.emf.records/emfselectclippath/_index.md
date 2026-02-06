---
title: Class EmfSelectClipPath
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectClipPath class. The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback device context combining the new region with any existing clipping region using the specified mode
type: docs
weight: 4360
url: /net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
## EmfSelectClipPath class

The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback device context, combining the new region with any existing clipping region using the specified mode.

```csharp
public sealed class EmfSelectClipPath : EmfClippingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSelectClipPath](emfselectclippath/#constructor)() | Initializes a new instance of the `EmfSelectClipPath` class. |
| [EmfSelectClipPath](emfselectclippath/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSelectClipPath` class. |

## Properties

| Name | Description |
| --- | --- |
| [RegionMode](../../aspose.imaging.fileformats.emf.emf.records/emfselectclippath/regionmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the way to use the path. The value MUST be in the RegionMode enumeration (section 2.1.29). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfClippingRecordType](../emfclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


