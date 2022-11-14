---
title: EmfCloseFigure
second_title: Aspose.Imaging for Java API Reference
description: This record closes an open figure in a path.
type: docs
weight: 21
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

This record closes an open figure in a path. Processing the EMR\_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure, and then it MUST connect the lines by using the line join style.If a figure is closed by processing the EMR\_LINETO record instead of the EMR\_CLOSEFIGURE record, end caps are used to create the corner instead of a join.EMR\_LINETO is specified in section 2.3.5.13. The EMR\_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record.

Note: A figure can be open even if the current point and the starting point of the figure are the same. After processing the EMR\_CLOSEFIGURE record, adding a line or curve to the path MUST start a new figure.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Initializes a new instance of the `EmfCloseFigure` class. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Initializes a new instance of the `EmfCloseFigure` class.

