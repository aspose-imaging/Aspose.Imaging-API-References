---
title: Class EmfRestoreDc
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRestoreDc class. The EMR_RESTOREDC record restores the playback device context to the specified state. The playback device context is restored by popping state information off a stack that was created by prior EMR_SAVEDC records section 2.3.11
type: docs
weight: 4300
url: /net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
## EmfRestoreDc class

The EMR_RESTOREDC record restores the playback device context to the specified state. The playback device context is restored by popping state information off a stack that was created by prior EMR_SAVEDC records (section 2.3.11).

```csharp
public sealed class EmfRestoreDc : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfRestoreDc](emfrestoredc/#constructor)() | Initializes a new instance of the `EmfRestoreDc` class. |
| [EmfRestoreDc](emfrestoredc/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfRestoreDc` class. |

## Properties

| Name | Description |
| --- | --- |
| [SavedDc](../../aspose.imaging.fileformats.emf.emf.records/emfrestoredc/saveddc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the saved state to restore relative to the current state. This value MUST be negative; –1 represents the state that was most recently saved on the stack, –2 the one before that, etc. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The stack can contain state information for multiple instances of the playback device context. When a state is restored, all state instances that were saved more recently MUST be discarded.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


