---
title: XmpGuid
second_title: Aspose.Imaging for Java API Reference
description: Represents XMP global unique identifier.
type: docs
weight: 14
url: /com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

Represents XMP global unique identifier.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Initializes a new instance of the `XmpGuid` class. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | Initializes a new instance of the `XmpGuid` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPrefix()](#getPrefix--) | Gets or sets the prefix like uuid. |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | Gets or sets the prefix like uuid. |
| [getValue()](#getValue--) | Gets or sets the value. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | Gets or sets the value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Initializes a new instance of the `XmpGuid` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


Initializes a new instance of the `XmpGuid` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| guid | java.util.UUID | The unique identifier. |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets or sets the prefix like uuid.

Value: The prefix like uuid.

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


Gets or sets the prefix like uuid.

Value: The prefix like uuid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


Gets or sets the value.

Value: The value.

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


Gets or sets the value.

Value: The value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
