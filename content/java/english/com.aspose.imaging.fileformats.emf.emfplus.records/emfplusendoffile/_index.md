---
title: EmfPlusEndOfFile
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusEndOfFile record specifies the end of EMF data in the metafile.
type: docs
weight: 31
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendoffile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusEndOfFile extends EmfPlusControlRecordType
```

The EmfPlusEndOfFile record specifies the end of EMF+ data in the metafile.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusEndOfFile(EmfPlusRecord source)](#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusEndOfFile` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Gets or sets a 16-bit unsigned integer that is not used. |
| [setFlags(short value)](#setFlags-short-) | Gets or sets a 16-bit unsigned integer that is not used. |
### EmfPlusEndOfFile(EmfPlusRecord source) {#EmfPlusEndOfFile-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndOfFile(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusEndOfFile` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

