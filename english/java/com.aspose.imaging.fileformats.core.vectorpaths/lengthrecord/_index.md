---
title: LengthRecord
second_title: Aspose.Imaging for Java API Reference
description: Subpath Length Record Class
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Subpath Length Record Class
## Constructors

| Constructor | Description |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Initializes a new instance of the [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) class. |
| [LengthRecord()](#LengthRecord--) | Initializes a new instance of the [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) class. |
## Methods

| Method | Description |
| --- | --- |
| [isClosed()](#isClosed--) | Gets a value indicating whether this instance is closed. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sets a value indicating whether this instance is closed. |
| [isOpen()](#isOpen--) | Gets a value indicating whether this instance is open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a value indicating whether this instance is open. |
| [getRecordCount()](#getRecordCount--) | Gets the record count. |
| [setRecordCount(int value)](#setRecordCount-int-) | Sets the record count. |
| [getType()](#getType--) | Gets the type. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Gets the bezier knot records count. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Sets the bezier knot records count. |
| [getPathOperations()](#getPathOperations--) | Gets the path operations. |
| [setPathOperations(int value)](#setPathOperations-int-) | Sets the path operations. |
| [getShapeIndex()](#getShapeIndex--) | Gets the index of current path shape in layer. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Sets the index of current path shape in layer. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Initializes a new instance of the [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The record data. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Initializes a new instance of the [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord) class.

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Gets a value indicating whether this instance is closed.

Value: `true` if this instance is closed; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is closed.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Sets a value indicating whether this instance is closed.

Value: `true` if this instance is closed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this instance is closed. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Gets a value indicating whether this instance is open.

Value: `true` if this instance is open; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this instance is open.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Sets a value indicating whether this instance is open.

Value: `true` if this instance is open; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this instance is open. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Gets the record count.

Value: The record count.

**Returns:**
int - the record count.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Sets the record count.

Value: The record count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the record count. |

### getType() {#getType--}
```
public short getType()
```


Gets the type.

Value: The type.

**Returns:**
short - the type.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Gets the bezier knot records count.

**Returns:**
int - the bezier knot records count.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Sets the bezier knot records count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the bezier knot records count. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Gets the path operations.

**Returns:**
int - the path operations.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Sets the path operations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the path operations. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Gets the index of current path shape in layer.

**Returns:**
int - the index of current path shape in layer.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Sets the index of current path shape in layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the index of current path shape in layer. |

