---
title: WmfStretchBlt
second_title: Aspose.Imaging for Java API Reference
description: The META_STRETCHBLT record specifies the transfer of a block of pixels     according to a raster operation with possible expansion or contraction.
type: docs
weight: 93
url: /com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

The META\_STRETCHBLT record specifies the transfer of a block of pixels according to a raster operation, with possible expansion or contraction.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Gets or sets the raster operation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Gets or sets the raster operation. |
| [getSrcHeight()](#getSrcHeight--) | Gets or sets the height of the source. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Gets or sets the height of the source. |
| [getSrcWidth()](#getSrcWidth--) | Gets or sets the width of the source. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Gets or sets the width of the source. |
| [getSrcPosition()](#getSrcPosition--) | Gets or sets the source position. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Gets or sets the source position. |
| [getDestHeight()](#getDestHeight--) | Gets or sets the height of the dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Gets or sets the height of the dest. |
| [getDestWidth()](#getDestWidth--) | Gets or sets the width of the dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Gets or sets the width of the dest. |
| [getDstPosition()](#getDstPosition--) | Gets or sets the DST position. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Gets or sets the DST position. |
| [getReserved()](#getReserved--) | Gets or sets the reserved. |
| [setReserved(short value)](#setReserved-short-) | Gets or sets the reserved. |
| [getBitmap()](#getBitmap--) | Gets or sets the bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Gets or sets the bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Gets or sets the raster operation.

Value: The source pixels, the current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Gets or sets the raster operation.

Value: The source pixels, the current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Gets or sets the height of the source.

Value: The height, in logical units, of the source rectangle.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Gets or sets the height of the source.

Value: The height, in logical units, of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Gets or sets the width of the source.

Value: The width, in logical units, of the source rectangle.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Gets or sets the width of the source.

Value: The width, in logical units, of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Gets or sets the source position.

Value: The source position.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Gets or sets the source position.

Value: The source position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Gets or sets the height of the dest.

Value: The height, in logical units, of the destination rectangle.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Gets or sets the height of the dest.

Value: The height, in logical units, of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Gets or sets the width of the dest.

Value: The width, in logical units, of the destination rectangle.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Gets or sets the width of the dest.

Value: The width, in logical units, of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Gets or sets the DST position.

Value: The DST position.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Gets or sets the DST position.

Value: The DST position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Gets or sets the reserved.

Value: The reserved.This field MUST be ignored.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Gets or sets the reserved.

Value: The reserved.This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Gets or sets the bitmap.

Value: The bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Gets or sets the bitmap.

Value: The bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

