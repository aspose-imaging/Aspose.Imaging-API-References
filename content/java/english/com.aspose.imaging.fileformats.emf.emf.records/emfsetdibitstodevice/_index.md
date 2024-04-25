---
title: EmfSetDiBitsToDevice
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle.
type: docs
weight: 121
url: /com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

The EMR\_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle.

This record supports source images in JPEG and PNG format. The Compression field in the source bitmap header specifies the image format.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfSetDiBitsToDevice` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [getXDest()](#getXDest--) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [setXDest(int value)](#setXDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [getYDest()](#getYDest--) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [setYDest(int value)](#setYDest-int-) | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [getXSrc()](#getXSrc--) | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left corner of the source rectangle. |
| [setXSrc(int value)](#setXSrc-int-) | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left corner of the source rectangle. |
| [getYSrc()](#getYSrc--) | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left corner of the source rectangle. |
| [setYSrc(int value)](#setYSrc-int-) | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left corner of the source rectangle. |
| [getCxSrc()](#getCxSrc--) | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [setCxSrc(int value)](#setCxSrc-int-) | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [getCySrc()](#getCySrc--) | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle |
| [setCySrc(int value)](#setCySrc-int-) | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle |
| [getUsageSrc()](#getUsageSrc--) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. |
| [getIStartScan()](#getIStartScan--) | Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array. |
| [setIStartScan(int value)](#setIStartScan-int-) | Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array. |
| [getCScans()](#getCScans--) | Gets or sets a 32-bit unsigned integer that specifies the number of scan lines. |
| [setCScans(int value)](#setCScans-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of scan lines. |
| [getSourceBitmap()](#getSourceBitmap--) | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_SETDIBITSTODEVICE record. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_SETDIBITSTODEVICE record. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Initializes a new instance of the `EmfSetDiBitsToDevice` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left corner of the source rectangle.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left corner of the source rectangle.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left corner of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Gets or sets a 32-bit unsigned integer that specifies the number of scan lines.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of scan lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_SETDIBITSTODEVICE record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR\_SETDIBITSTODEVICE record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

