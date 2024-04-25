---
title: WmfDibBitBlt
second_title: Aspose.Imaging for Java API Reference
description: The META_DIBBITBLT record specifies the transfer of a block of pixels in     device-independent format according to a raster operation.
type: docs
weight: 28
url: /com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

The META\_DIBBITBLT record specifies the transfer of a block of pixels in device-independent format according to a raster operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Gets or sets the raster operation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Gets or sets the raster operation. |
| [getSrcPos()](#getSrcPos--) | Gets or sets the source position. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Gets or sets the source position. |
| [getHeight()](#getHeight--) | Gets or sets the height. |
| [setHeight(short value)](#setHeight-short-) | Gets or sets the height. |
| [getWidth()](#getWidth--) | Gets or sets the width. |
| [setWidth(short value)](#setWidth-short-) | Gets or sets the width. |
| [getDstPos()](#getDstPos--) | Gets or sets the DST position. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Gets or sets the DST position. |
| [getReserved()](#getReserved--) | Gets or sets the reserved. |
| [setReserved(int value)](#setReserved-int-) | Gets or sets the reserved. |
| [getSource()](#getSource--) | Gets or sets the source. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets the source. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Gets or sets the raster operation.

Value: The source pixels, the current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Gets or sets the raster operation.

Value: The source pixels, the current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration (section 2.1.1.31).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Gets or sets the source position.

Value: The coordinates, in logical units, of the source rectangle.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Gets or sets the source position.

Value: The coordinates, in logical units, of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Gets or sets the height.

Value: The height, in logical units, of the source and destination rectangles.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Gets or sets the height.

Value: The height, in logical units, of the source and destination rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Gets or sets the width.

Value: The width, in logical units, of the source and destination rectangles.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Gets or sets the width.

Value: The width, in logical units, of the source and destination rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Gets or sets the DST position.

Value: The coordinates, in logical units, of the upper-left corner of the destination rectangle.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Gets or sets the DST position.

Value: The coordinates, in logical units, of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Gets or sets the reserved.

Value: The reserved.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Gets or sets the reserved.

Value: The reserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Gets or sets the source.

Value: A variable-sized DeviceIndependentBitmap Object (section 2.2.2.9) that defines image content. This object MUST be specified, even if the raster operation does not require a source.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Gets or sets the source.

Value: A variable-sized DeviceIndependentBitmap Object (section 2.2.2.9) that defines image content. This object MUST be specified, even if the raster operation does not require a source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

