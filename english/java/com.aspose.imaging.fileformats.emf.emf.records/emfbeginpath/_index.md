---
title: EmfBeginPath
second_title: Aspose.Imaging for Java API Reference
description: This record opens a path bracket in the current playback device context.
type: docs
weight: 15
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfBeginPath extends EmfPathBracketRecordType
```

This record opens a path bracket in the current playback device context. After a path bracket is open, an application can begin processing records to define the points that lie in the path.An application MUST close an open path bracket by processing the EMR\_ENDPATH record. When an application processes the EMR\_BEGINPATH record, all previous paths MUST be discarded from the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfBeginPath()](#EmfBeginPath--) | Initializes a new instance of the `EmfBeginPath` class. |
### EmfBeginPath() {#EmfBeginPath--}
```
public EmfBeginPath()
```


Initializes a new instance of the `EmfBeginPath` class.

