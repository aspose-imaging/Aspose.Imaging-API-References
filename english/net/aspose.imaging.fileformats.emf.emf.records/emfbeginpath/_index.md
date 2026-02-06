---
title: Class EmfBeginPath
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBeginPath class. This record opens a path bracket in the current playback device context. After a path bracket is open an application can begin processing records to define the points that lie in the path.An application MUST close an open path bracket by processing the EMR_ENDPATH record. When an application processes the EMR_BEGINPATH record all previous paths MUST be discarded from the playback device context
type: docs
weight: 3330
url: /net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
## EmfBeginPath class

This record opens a path bracket in the current playback device context. After a path bracket is open, an application can begin processing records to define the points that lie in the path.An application MUST close an open path bracket by processing the EMR_ENDPATH record. When an application processes the EMR_BEGINPATH record, all previous paths MUST be discarded from the playback device context.

```csharp
public sealed class EmfBeginPath : EmfPathBracketRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfBeginPath](emfbeginpath/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


