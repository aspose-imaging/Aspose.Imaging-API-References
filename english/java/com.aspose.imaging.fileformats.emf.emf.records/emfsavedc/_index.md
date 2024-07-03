---
title: EmfSaveDc
second_title: Aspose.Imaging for Java API Reference
description: Saves the current state of playback device context on a stack of states saved by preceding EMR_SAVEDC records if any.
type: docs
weight: 112
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Saves the current state of playback device context on a stack of states saved by preceding EMR\_SAVEDC records, if any. The state consists of graphics properties and objects, including the currently selected bitmap, brush, palette, font, pen, and region. An EMR\_RESTOREDC record is used to restore the state. This EMF record specifies no parameters.

The stack can contain state information for multiple instances of the playback device context. When a state is restored, all state instances that were saved more recently MUST be discarded.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSaveDc` class. |
| [EmfSaveDc()](#EmfSaveDc--) | Initializes a new instance of the `EmfSaveDc` class. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Initializes a new instance of the `EmfSaveDc` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Initializes a new instance of the `EmfSaveDc` class.

