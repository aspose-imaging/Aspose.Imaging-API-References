---
title: Timecode
second_title: Aspose.Imaging for Java API Reference
description: Represents timecode value in video.
type: docs
weight: 16
url: /com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Represents timecode value in video.
## Constructors

| Constructor | Description |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Initializes a new instance of the `Timecode` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Gets or sets the format used in the `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | Gets or sets the format used in the `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | Gets or sets the time value in the specified format. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Gets or sets the time value in the specified format. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns the string contained value in XMP format. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified `System.Object`, is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Initializes a new instance of the `Timecode` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | The time format. |
| timeValue | java.lang.String | The time value. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Gets or sets the format used in the `TimeValue`.

Value: The format used in the `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Gets or sets the format used in the `TimeValue`.

Value: The format used in the `TimeValue`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Gets or sets the time value in the specified format.

Value: The time value in the specified format.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Gets or sets the time value in the specified format.

Value: The time value in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string containing xmp representation.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the `other` parameter; otherwise, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified `System.Object`, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The `System.Object` to compare with this instance. |

**Returns:**
boolean - `true` if the specified `System.Object` is equal to this instance; otherwise, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
