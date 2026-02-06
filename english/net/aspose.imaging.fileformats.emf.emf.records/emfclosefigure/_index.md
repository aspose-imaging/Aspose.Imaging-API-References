---
title: Class EmfCloseFigure
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCloseFigure class. This record closes an open figure in a path. Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure and then it MUST connect the lines by using the line join style.If a figure is closed by processing the EMR_LINETO record instead of the EMR_CLOSEFIGURE record end caps are used to create the corner instead of a join.EMR_LINETO is specified in section 2.3.5.13. The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record
type: docs
weight: 3410
url: /net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
## EmfCloseFigure class

This record closes an open figure in a path. Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure, and then it MUST connect the lines by using the line join style.If a figure is closed by processing the EMR_LINETO record instead of the EMR_CLOSEFIGURE record, end caps are used to create the corner instead of a join.EMR_LINETO is specified in section 2.3.5.13. The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record.

```csharp
public sealed class EmfCloseFigure : EmfPathBracketRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCloseFigure](emfclosefigure/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Note: A figure can be open even if the current point and the starting point of the figure are the same. After processing the EMR_CLOSEFIGURE record, adding a line or curve to the path MUST start a new figure.

### See Also

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


