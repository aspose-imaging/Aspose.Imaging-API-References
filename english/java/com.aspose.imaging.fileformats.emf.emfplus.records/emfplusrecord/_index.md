---
title: EmfPlusRecord
second_title: Aspose.Imaging for Java API Reference
description: The Emf base record type.
type: docs
weight: 46
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

The Emf+ base record type.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Initializes a new instance of the `EmfPlusRecord` class. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusRecord` class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets a 16-bit unsigned integer that identifies the record type. |
| [getFlags()](#getFlags--) | Gets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [setFlags(short value)](#setFlags-short-) | Sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [getSize()](#getSize--) | Gets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [setSize(int value)](#setSize-int-) | Sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [getDataSize()](#getDataSize--) | Gets a 32-bit unsigned integer that MUST define the 32-bit\\u2013aligned number of bytes of data in the RecordData field that follows. |
| [setDataSize(int value)](#setDataSize-int-) | Sets a 32-bit unsigned integer that MUST define the 32-bit\\u2013aligned number of bytes of data in the RecordData field that follows. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Initializes a new instance of the `EmfPlusRecord` class.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusRecord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getType() {#getType--}
```
public short getType()
```


Gets a 16-bit unsigned integer that identifies the record type.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Gets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record.

**Returns:**
short - The flags.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | The flags. |

### getSize() {#getSize--}
```
public int getSize()
```


Gets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data.

**Returns:**
int - The size.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The size. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Gets a 32-bit unsigned integer that MUST define the 32-bit\\u2013aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header.

**Returns:**
int - The size of the data.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Sets a 32-bit unsigned integer that MUST define the 32-bit\\u2013aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The size of the data. |

