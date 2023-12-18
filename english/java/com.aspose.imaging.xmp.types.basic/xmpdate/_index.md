---
title: XmpDate
second_title: Aspose.Imaging for Java API Reference
description: Represents Date in XMP packet.
type: docs
weight: 11
url: /java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Represents Date in XMP packet.

A date-time value is represented using a subset of the formats as defined in Date and Time Formats: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initializes a new instance of the `XmpDate` class. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initializes a new instance of the `XmpDate` class. |
## Fields

| Field | Description |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | The ISO 8601 (roundtrip) format string. |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the date value. |
| [setValue(Date value)](#setValue-java.util.Date-) | Gets or sets the date value. |
| [getFormat()](#getFormat--) | Gets the format string for current value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initializes a new instance of the `XmpDate` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | A date-time value which is represented using a subset of ISO RFC 8601 formatting. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initializes a new instance of the `XmpDate` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateString | java.lang.String | The string representation of date. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


The ISO 8601 (roundtrip) format string.

See more: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


Gets or sets the date value.

Value: The date value.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Gets or sets the date value.

Value: The date value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


Gets the format string for current value.

Value: The format string for current value.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String - Returns string containing xmp representation
