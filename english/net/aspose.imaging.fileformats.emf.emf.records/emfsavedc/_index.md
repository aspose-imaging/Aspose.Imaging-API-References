---
title: Class EmfSaveDc
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSaveDc class. Saves the current state of playback device context on a stack of states saved by preceding EMR_SAVEDC records if any. The state consists of graphics properties and objects including the currently selected bitmap brush palette font pen and region. An EMR_RESTOREDC record is used to restore the state. This EMF record specifies no parameters
type: docs
weight: 4330
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
## EmfSaveDc class

Saves the current state of playback device context on a stack of states saved by preceding EMR_SAVEDC records, if any. The state consists of graphics properties and objects, including the currently selected bitmap, brush, palette, font, pen, and region. An EMR_RESTOREDC record is used to restore the state. This EMF record specifies no parameters.

```csharp
public sealed class EmfSaveDc : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSaveDc](emfsavedc/#constructor)() | Initializes a new instance of the `EmfSaveDc` class. |
| [EmfSaveDc](emfsavedc/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfSaveDc` class. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The stack can contain state information for multiple instances of the playback device context. When a state is restored, all state instances that were saved more recently MUST be discarded.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


