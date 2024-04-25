---
title: WmfDibStrechBlt
second_title: Aspose.Imaging for Java API Reference
description: The META_DIBSTRETCHBLT record specifies the transfer of a block of     pixels in device-independent format according to a raster operation     with possible expansion or contraction.
type: docs
weight: 30
url: /com.aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfDibStrechBlt extends WmfObject
```

The META\_DIBSTRETCHBLT record specifies the transfer of a block of pixels in device-independent format according to a raster operation, with possible expansion or contraction.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfDibStrechBlt()](#WmfDibStrechBlt--) | WMFs the record. |
## Methods

| Method | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Gets or sets the raster operation. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Gets or sets the raster operation. |
| [getSrcHeight()](#getSrcHeight--) | Gets or sets the height of the source. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Gets or sets the height of the source. |
| [getSrcWidth()](#getSrcWidth--) | Gets or sets the width of the source. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Gets or sets the width of the source. |
| [getYSrc()](#getYSrc--) | Gets or sets the y source. |
| [setYSrc(short value)](#setYSrc-short-) | Gets or sets the y source. |
| [getXSrc()](#getXSrc--) | Gets or sets the x source. |
| [setXSrc(short value)](#setXSrc-short-) | Gets or sets the x source. |
| [getDestHeight()](#getDestHeight--) | Gets or sets the height of the dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Gets or sets the height of the dest. |
| [getDestWidth()](#getDestWidth--) | Gets or sets the width of the dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Gets or sets the width of the dest. |
| [getYDest()](#getYDest--) | Gets or sets the y dest. |
| [setYDest(short value)](#setYDest-short-) | Gets or sets the y dest. |
| [getXDest()](#getXDest--) | Gets or sets the x dest. |
| [setXDest(short value)](#setXDest-short-) | Gets or sets the x dest. |
| [getSourceBitmap()](#getSourceBitmap--) | Gets or sets the source bitmap. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets the source bitmap. |
### WmfDibStrechBlt() {#WmfDibStrechBlt--}
```
public WmfDibStrechBlt()
```


WMFs the record.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Gets or sets the raster operation.

Value: The current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Gets or sets the raster operation.

Value: The current brush in the playback device context, and the destination pixels are to be combined to form the new image. This code MUST be one of the values in the Ternary Raster Operation Enumeration (section 2.1.1.31).

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

Value: The width, in logical units, of the source rectangle

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Gets or sets the width of the source.

Value: The width, in logical units, of the source rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Gets or sets the y source.

Value: The y-coordinate, in logical units, of the upper-left corner of the source rectangle.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Gets or sets the y source.

Value: The y-coordinate, in logical units, of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Gets or sets the x source.

Value: The x-coordinate, in logical units, of the upper-left corner of the source rectangle.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Gets or sets the x source.

Value: The x-coordinate, in logical units, of the upper-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

### getYDest() {#getYDest--}
```
public short getYDest()
```


Gets or sets the y dest.

Value: The y-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Gets or sets the y dest.

Value: The y-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Gets or sets the x dest.

Value: The x-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Gets or sets the x dest.

Value: The x-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Gets or sets the source bitmap.

Value: The source bitmap.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets the source bitmap.

Value: The source bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

