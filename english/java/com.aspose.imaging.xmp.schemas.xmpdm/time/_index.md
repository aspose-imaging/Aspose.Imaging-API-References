---
title: Time
second_title: Aspose.Imaging for Java API Reference
description: Representation of a time value in seconds.
type: docs
weight: 14
url: /java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representation of a time value in seconds.
## Constructors

| Constructor | Description |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Initializes a new instance of the `Time` class. |
## Methods

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Gets or sets scale for the time value. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Gets or sets scale for the time value. |
| [getValue()](#getValue--) | Gets or sets time value in the specified scale. |
| [setValue(int value)](#setValue-int-) | Gets or sets time value in the specified scale. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initializes a new instance of the `Time` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | The scale. |
| value | int | The value. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Gets or sets scale for the time value.

For NTSC, use 1001/30000, or the less accurate 100/2997. For PAL, use 1/25. Value: The scale for the time value.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Gets or sets scale for the time value.

For NTSC, use 1001/30000, or the less accurate 100/2997. For PAL, use 1/25. Value: The scale for the time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Gets or sets time value in the specified scale.

Value: The time value in the specified scale.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Gets or sets time value in the specified scale.

Value: The time value in the specified scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
