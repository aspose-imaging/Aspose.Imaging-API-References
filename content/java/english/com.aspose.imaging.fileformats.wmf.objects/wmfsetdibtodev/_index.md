---
title: WmfSetDibToDev
second_title: Aspose.Imaging for Java API Reference
description: The META_SETDIBTODEV record sets a block of pixels in the playback     device context using device-independent color data.
type: docs
weight: 75
url: /com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

The META\_SETDIBTODEV record sets a block of pixels in the playback device context using device-independent color data. The source of the color data is a DIB.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Gets or sets the color usage. |
| [setColorUsage(int value)](#setColorUsage-int-) | Gets or sets the color usage. |
| [getScanCount()](#getScanCount--) | Gets or sets the scan count. |
| [setScanCount(int value)](#setScanCount-int-) | Gets or sets the scan count. |
| [getStartScan()](#getStartScan--) | Gets or sets the start scan. |
| [setStartScan(int value)](#setStartScan-int-) | Gets or sets the start scan. |
| [getDibPos()](#getDibPos--) | Gets or sets the dib position. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Gets or sets the dib position. |
| [getHeight()](#getHeight--) | Gets or sets the height. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets the height. |
| [getWidth()](#getWidth--) | Gets or sets the width. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets the width. |
| [getDestPos()](#getDestPos--) | Gets or sets the dest position. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Gets or sets the dest position. |
| [getDib()](#getDib--) | Gets or sets the dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets the dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Gets or sets the color usage.

Value: The Colors field of the DIB contains explicit RGB values or indexes into a palette. This MUST be one of the values in the `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` Enumeration (section 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Gets or sets the color usage.

Value: The Colors field of the DIB contains explicit RGB values or indexes into a palette. This MUST be one of the values in the `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` Enumeration (section 2.1.1.6).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Gets or sets the scan count.

Value: The the number of scan lines in the source.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Gets or sets the scan count.

Value: The the number of scan lines in the source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Gets or sets the start scan.

Value: The starting scan line in the source.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Gets or sets the start scan.

Value: The starting scan line in the source.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Gets or sets the dib position.

Value: The coordinates, in logical units, of the source rectangle.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Gets or sets the dib position.

Value: The coordinates, in logical units, of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the height.

Value: The height, in logical units, of the source and destination rectangles.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets the height.

Value: The height, in logical units, of the source and destination rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets the width.

Value: The width, in logical units, of the source and destination rectangles.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets the width.

Value: The width, in logical units, of the source and destination rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Gets or sets the dest position.

Value: The coordinates, in logical units, of the upper-left corner of the destination rectangle.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Gets or sets the dest position.

Value: The coordinates, in logical units, of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Gets or sets the dib.

Value: y-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Gets or sets the dib.

Value: y-coordinate, in logical units, of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

