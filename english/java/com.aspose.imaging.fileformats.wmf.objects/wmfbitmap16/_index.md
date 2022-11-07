---
title: WmfBitmap16
second_title: Aspose.Imaging for Java API Reference
description: The Bitmap16 Object specifies information about the dimensions and color format of a bitmap.
type: docs
weight: 13
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfBitmap16 extends MetaObject
```

The Bitmap16 Object specifies information about the dimensions and color format of a bitmap.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfBitmap16()](#WmfBitmap16--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets or sets the type. |
| [setType(short value)](#setType-short-) | Gets or sets the type. |
| [getWidth()](#getWidth--) | Gets or sets the width. |
| [setWidth(short value)](#setWidth-short-) | Gets or sets the width. |
| [getHeight()](#getHeight--) | Gets or sets the height. |
| [setHeight(short value)](#setHeight-short-) | Gets or sets the height. |
| [getWidthBytes()](#getWidthBytes--) | Gets or sets the width bytes. |
| [setWidthBytes(short value)](#setWidthBytes-short-) | Gets or sets the width bytes. |
| [getPlanes()](#getPlanes--) | Gets or sets the planes. |
| [setPlanes(byte value)](#setPlanes-byte-) | Gets or sets the planes. |
| [getBitsPixel()](#getBitsPixel--) | Gets or sets the bits pixel. |
| [setBitsPixel(byte value)](#setBitsPixel-byte-) | Gets or sets the bits pixel. |
| [getBits()](#getBits--) | Gets or sets the bits. |
| [setBits(byte[] value)](#setBits-byte---) | Gets or sets the bits. |
### WmfBitmap16() {#WmfBitmap16--}
```
public WmfBitmap16()
```


### getType() {#getType--}
```
public short getType()
```


Gets or sets the type.

Value: The bitmap type.

**Returns:**
short
### setType(short value) {#setType-short-}
```
public void setType(short value)
```


Gets or sets the type.

Value: The bitmap type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Gets or sets the width.

Value: The width of the bitmap in pixels

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Gets or sets the width.

Value: The width of the bitmap in pixels

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Gets or sets the height.

Value: The height of the bitmap in scan lines.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Gets or sets the height.

Value: The height of the bitmap in scan lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getWidthBytes() {#getWidthBytes--}
```
public short getWidthBytes()
```


Gets or sets the width bytes.

Value: The number of bytes per scan line.

**Returns:**
short
### setWidthBytes(short value) {#setWidthBytes-short-}
```
public void setWidthBytes(short value)
```


Gets or sets the width bytes.

Value: The number of bytes per scan line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getPlanes() {#getPlanes--}
```
public byte getPlanes()
```


Gets or sets the planes.

Value: The value of this field MUST be 0x01.

**Returns:**
byte
### setPlanes(byte value) {#setPlanes-byte-}
```
public void setPlanes(byte value)
```


Gets or sets the planes.

Value: The value of this field MUST be 0x01.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBitsPixel() {#getBitsPixel--}
```
public byte getBitsPixel()
```


Gets or sets the bits pixel.

Value: The number of adjacent color bits on each plane.

**Returns:**
byte
### setBitsPixel(byte value) {#setBitsPixel-byte-}
```
public void setBitsPixel(byte value)
```


Gets or sets the bits pixel.

Value: The number of adjacent color bits on each plane.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBits() {#getBits--}
```
public byte[] getBits()
```


Gets or sets the bits.

Value: The bitmap pixel data. The length of this field in bytes can be computed as follows.

**Returns:**
byte[]
### setBits(byte[] value) {#setBits-byte---}
```
public void setBits(byte[] value)
```


Gets or sets the bits.

Value: The bitmap pixel data. The length of this field in bytes can be computed as follows.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

