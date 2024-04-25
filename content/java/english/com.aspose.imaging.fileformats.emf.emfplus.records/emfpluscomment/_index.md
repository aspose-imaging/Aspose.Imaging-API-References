---
title: EmfPlusComment
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusComment record specifies arbitrary private data.
type: docs
weight: 14
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

The EmfPlusComment record specifies arbitrary private data.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusComment` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Gets or sets a DataSize-length byte array of private data. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Gets or sets a DataSize-length byte array of private data. |
| [getFlags()](#getFlags--) | Gets or sets a 16-bit unsigned integer that is not used. |
| [setFlags(short value)](#setFlags-short-) | Gets or sets a 16-bit unsigned integer that is not used. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusComment` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Gets or sets a DataSize-length byte array of private data. bytes of record-specific data that follows.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Gets or sets a DataSize-length byte array of private data. bytes of record-specific data that follows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

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

