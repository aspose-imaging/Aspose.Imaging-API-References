---
title: CieCoordinates
second_title: Aspose.Imaging for Java API Reference
description: The class contains the xy and z coordinates of a specific color in a specified color space.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.bmp.structures/ciecoordinates/
---
**Inheritance:**
java.lang.Object
```
public class CieCoordinates
```

The class contains the x,y, and z coordinates of a specific color in a specified color space.
## Constructors

| Constructor | Description |
| --- | --- |
| [CieCoordinates(byte[] bytes)](#CieCoordinates-byte---) | Initializes a new instance of the `CieCoordinates` class. |
| [CieCoordinates(byte[] bytes, int offset)](#CieCoordinates-byte---int-) | Initializes a new instance of the [CieCoordinates](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinates) class from a byte array. |
## Methods

| Method | Description |
| --- | --- |
| [getCieCoordinatesX()](#getCieCoordinatesX--) | Gets or sets the coordinates x. |
| [setCieCoordinatesX(long value)](#setCieCoordinatesX-long-) | Gets or sets the coordinates x. |
| [getCieCoordinatesY()](#getCieCoordinatesY--) | Gets or sets the coordinates y. |
| [setCieCoordinatesY(long value)](#setCieCoordinatesY-long-) | Gets or sets the coordinates y. |
| [getCieCoordinatesZ()](#getCieCoordinatesZ--) | Gets or sets the coordinates z. |
| [setCieCoordinatesZ(long value)](#setCieCoordinatesZ-long-) | Gets or sets the coordinates z. |
### CieCoordinates(byte[] bytes) {#CieCoordinates-byte---}
```
public CieCoordinates(byte[] bytes)
```


Initializes a new instance of the `CieCoordinates` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The byte array containing the serialized CIE coordinates data. |

### CieCoordinates(byte[] bytes, int offset) {#CieCoordinates-byte---int-}
```
public CieCoordinates(byte[] bytes, int offset)
```


Initializes a new instance of the [CieCoordinates](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinates) class from a byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The byte array containing the serialized CIE coordinates data. |
| offset | int | The zero-based byte offset in `bytes` at which to begin reading the coordinates. The coordinates are expected to be stored as three consecutive 32-bit unsigned integers (x, y, z) in big-endian order, each representing a fixed-point (2.30) value. |

### getCieCoordinatesX() {#getCieCoordinatesX--}
```
public long getCieCoordinatesX()
```


Gets or sets the coordinates x.

Value: The coordinates x.

**Returns:**
long
### setCieCoordinatesX(long value) {#setCieCoordinatesX-long-}
```
public void setCieCoordinatesX(long value)
```


Gets or sets the coordinates x.

Value: The coordinates x.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCieCoordinatesY() {#getCieCoordinatesY--}
```
public long getCieCoordinatesY()
```


Gets or sets the coordinates y.

Value: The coordinates y.

**Returns:**
long
### setCieCoordinatesY(long value) {#setCieCoordinatesY-long-}
```
public void setCieCoordinatesY(long value)
```


Gets or sets the coordinates y.

Value: The coordinates y.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCieCoordinatesZ() {#getCieCoordinatesZ--}
```
public long getCieCoordinatesZ()
```


Gets or sets the coordinates z.

Value: The coordinates z.

**Returns:**
long
### setCieCoordinatesZ(long value) {#setCieCoordinatesZ-long-}
```
public void setCieCoordinatesZ(long value)
```


Gets or sets the coordinates z.

Value: The coordinates z.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

