---
title: EmfRecord
second_title: Aspose.Imaging for Java API Reference
description: Base class for EMF records All EMF records MUST have a length that is a multiple of 4 bytes.
type: docs
weight: 103
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Base class for EMF records All EMF records MUST have a length that is a multiple of 4 bytes. This is depicted in the generic structures of the preceding EMF record types by including AlignmentPadding fields where appropriate at the ends of these structures. The contents of AlignmentPadding fields MUST always be ignored. For brevity, these fields are not shown in every individual EMF record definition.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Initializes a new instance of the `EmfRecord` class. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfRecord` class. |
| [EmfRecord(int type)](#EmfRecord-int-) | Initializes a new instance of the `EmfRecord` class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets the type. |
| [setType(int value)](#setType-int-) | Sets the type. |
| [getSize()](#getSize--) | Gets the size of the record |
| [setSize(int value)](#setSize-int-) | Sets the size of the record |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Initializes a new instance of the `EmfRecord` class.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Initializes a new instance of the `EmfRecord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Initializes a new instance of the `EmfRecord` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The record type. |

### getType() {#getType--}
```
public int getType()
```


Gets the type.

**Returns:**
int - The type.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Sets the type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The type. |

### getSize() {#getSize--}
```
public int getSize()
```


Gets the size of the record

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Sets the size of the record

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

