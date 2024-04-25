---
title: EmfPlusGetDc
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.
type: docs
weight: 39
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusControlRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscontrolrecordtype)
```
public final class EmfPlusGetDc extends EmfPlusControlRecordType
```

The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusGetDc(EmfPlusRecord source)](#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusGetDc` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Gets or sets a 16-bit unsigned integer that is not used. |
| [setFlags(short value)](#setFlags-short-) | Gets or sets a 16-bit unsigned integer that is not used. |
### EmfPlusGetDc(EmfPlusRecord source) {#EmfPlusGetDc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusGetDc(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusGetDc` class.

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

